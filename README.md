# Introduzindo-React

## Instalando o Node.js
1. Visite o site oficial do Node.js
2. Baixe o Node.js

Para verificar se instalou com sucesso, abra o terminal e digite:
```sh
node --version
npm --version
```

## Criando o primeiro projeto com o React
Crie sua pasta utilizando o comando:
```sh
mkdir nomeDoProjeto
```
Após a criação, entre em seu diretório utilizando:
```sh
cd nomeDoProjeto
```

Para a criação do projeto com React usaremos o Vite
Use o seguinte comando:
```sh
npm create vite@latest
```

Este comando irá iniciar o processo de criação do projeto. Você será guiado por algumas perguntas:

1. **Nome do projeto**: Digite o nome desejado para seu projeto, por exemplo, "introducao-react"
2. **Framework**: Selecione "React" na lista de opções
3. **Variante**: Escolha "JavaScript"

Agora, entre em seu diretório usando:
```sh
cd introducao-react
```

## Instalando as Dependências
Agora, precisamos instalar as dependências do projeto. Execute:
```sh
npm install
```
Este comando lê o arquivo `package.json` e instala todas as dependências listadas.

### Estrutura do Projeto
```
meu-primeiro-react/
├── node_modules/       # Contém todas as dependências instaladas
├── public/             # Arquivos estáticos que serão servidos diretamente
│   └── vite.svg
├── src/                # Contém o código-fonte da sua aplicação
│   ├── assets/
│   │   └── react.svg
│   ├── App.css
│   ├── App.jsx         # O componente principal da sua aplicação
│   ├── index.css
│   └── main.jsx        # O ponto de entrada da sua aplicação
├── .eslintrc.cjs
├── .gitignore
├── index.html          # Arquivo HTML principal
├── package.json        # Lista as dependências e scripts do projeto
├── package-lock.json
└── vite.config.js      # Configurações do Vite
```

## Executando o Projeto
Para iniciar o servidor, execute o comando:
```sh
npm run dev
```
