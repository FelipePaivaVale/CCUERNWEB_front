Após clonar o projeto, abra o terminal na pasta raiz do projeto (onde está o arquivo `package.json`) e execute:

```bash
npm install
```

Isso instalará todas as dependências necessárias para rodar o projeto.

### 3. Configurar a porta (opcional)
Se você deseja rodar o projeto em uma porta diferente da padrão (3000), siga estas etapas:

1. Crie um arquivo chamado `.env` na raiz do projeto.
2. Adicione a seguinte linha ao arquivo `.env`:

```env
PORT=3001
```

Isso fará com que o projeto rode na porta 3001.

### 4. Rodar o projeto
Para iniciar o servidor de desenvolvimento, execute:

```bash
npm start
```

O projeto será iniciado e estará disponível no navegador em:

[http://localhost:3001](http://localhost:3001) (ou na porta configurada no `.env`, como 3001).

### 5. Estrutura básica do projeto
- `src`: Contém o código-fonte do projeto.
- `public`: Contém arquivos públicos, como o `index.html`.
- `package.json`: Lista as dependências e scripts do projeto.

### 6. Parar o servidor
Para parar o servidor de desenvolvimento, pressione `Ctrl + C` no terminal.
