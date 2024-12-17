# Buscador de CEP

Este projeto é um aplicativo simples criado com **React** que permite buscar informações de endereços a partir de um **CEP** (Código de Endereçamento Postal). 

## Funcionalidades
- Busca automática de endereço através de um **CEP válido**.
- Exibição de informações como **logradouro**, **bairro**, **cidade** e **estado**.
- Mensagens de erro caso o CEP não seja encontrado ou seja inválido.

---

## Tecnologias Utilizadas

- **React**: Framework principal para criação da interface.
- **Axios**: Biblioteca para realizar chamadas HTTP.
- **ViaCEP API**: Serviço público utilizado para buscar os dados de CEP.
- **CSS**: Estilização da interface.

## Instalação

Para rodar o projeto localmente, siga os passos abaixo:

1. **Clone** o repositório:
   ```bash
   git clone https://github.com/seu-usuario/buscadorCEP.git
   ```

2. Acesse o diretório do projeto:
   ```bash
   cd buscadorCEP
   ```

3. Instale as dependências:
   ```bash
   npm install
   ```

4. Execute o projeto:
   ```bash
   npm start
   ```

O aplicativo será aberto em [http://localhost:3000](http://localhost:3000) no navegador.

---

## Como Usar

1. Digite um **CEP** no campo de busca.
2. Clique no botão de **Buscar**.
3. Aguarde as informações de endereço serem carregadas.
4. Caso o CEP não seja encontrado, uma mensagem de erro será exibida.
