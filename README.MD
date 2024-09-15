
# App de Controle de Metas

Bem-vindo ao App de Controle de Metas! Este é um aplicativo simples em Node.js que permite criar, listar, marcar como concluídas e deletar metas, tudo diretamente no terminal.

## Funcionalidades

- **Cadastrar Metas**: Adicione novas metas ao sistema.
- **Listar Metas**: Visualize todas as metas cadastradas.
- **Metas Realizadas**: Visualize metas que foram concluídas.
- **Metas Abertas**: Veja metas que ainda estão pendentes.
- **Deletar Metas**: Exclua metas do sistema.

## Tecnologias Utilizadas

- **Node.js**: Plataforma de desenvolvimento JavaScript no servidor.
- **JavaScript**: Linguagem de programação utilizada para a lógica do app.
- **Inquirer.js**: Biblioteca utilizada para interagir com o terminal, com prompts e seleção de opções.

## Instalação

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/app-metas.git
   ```
2. **Navegue até o diretório do projeto**:
   ```bash
   cd app-metas
   ```
3. **Instale as dependências**:
   ```bash
   npm install
   ```

## Uso

1. **Execute o app**:
   ```bash
   node index.js
   ```

   Após executar o comando, você verá o menu interativo no terminal:

   ```
   ? Menu > (Use as setas para navegar)
   ❯ Cadastrar meta
     Listar metas
     Metas realizadas
     Metas abertas
     Deletar metas
     Sair
   ```

   - **Cadastrar meta**: Adicione uma nova meta.
   - **Listar metas**: Exibe todas as metas cadastradas.
   - **Metas realizadas**: Visualiza as metas concluídas.
   - **Metas abertas**: Lista as metas que ainda estão pendentes.
   - **Deletar metas**: Remove metas selecionadas.
   - **Sair**: Encerra o aplicativo.

## Estrutura do Projeto

- **index.js**: Arquivo principal que contém a lógica do aplicativo.
- **metas.json**: Arquivo onde as metas são salvas em formato JSON.

## Contribuições

Sinta-se à vontade para abrir issues ou enviar pull requests para novas funcionalidades ou correções.

