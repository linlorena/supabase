# Node.js API com Supabase e Express

Este projeto é uma API construída usando Node.js, Express e Supabase. A API permite operações CRUD (Create, Read, Update, Delete) em uma tabela de produtos.

## Instalação

1. Clone este repositório para a sua máquina local:

    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    ```

2. Navegue até o diretório do projeto:

    ```bash
    cd seu-repositorio
    ```

3. Instale as dependências:

    ```bash
    npm install
    ```

## Configuração

Antes de iniciar o servidor, você deve configurar suas credenciais do Supabase.

1. Crie uma conta no [Supabase](https://supabase.io/).
2. Crie um novo projeto no Supabase.
3. Obtenha a URL e a chave API do seu projeto.
4. Atualize as seguintes linhas no arquivo principal do projeto (`index.js`, por exemplo) com suas próprias credenciais do Supabase:

    ```javascript
    const supabase = 
        supabaseClient.createClient('https://sua-url-supabase.supabase.co', 
            'sua-chave-api-supabase')
    ```

## Uso

1. Inicie o servidor:

    ```bash
    npm start
    ```

2. Acesse a API em `http://localhost:3000`.

## Endpoints

### Listar todos os produtos

