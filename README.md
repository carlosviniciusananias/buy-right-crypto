# Buyright Crypto

Este repositório foi criado para estudar websockets e monitoramento de preços em binance.

## Configuração

1. Clone o repositório:

```bash
git clone https://github.com/carlosviniciusananias/buyright-crypto.git
```

2. Instale as dependências:

```bash
cd buyright-crypto
yarn install
```

3. Configure as variáveis de ambiente:

Crie um arquivo .env na raiz do projeto e defina as seguintes variáveis.

```bash
BINANCE_API_KEY=YOUR_KEY
BINANCE_API_SECRET=YOUR_SECRET_KEY
```

Substitua `YOUR_KEY` e `YOUR_SECRET_KEY` pelas suas credenciais da API da binance.

4. Inicie o servidor:

```bash
yarn start
```

O servidor será iniciado em http://localhost:3000.

## Rotas

O servidor expõe as seguintes rotas:

- `/`
- `/monitoring`
- `trade`

## Dependências

- Node.js
- TypeScript
- Express
- WebSocket
- Binance API
- Nodemon

## Contribuindo

Sinta-se à vontade para enviar pull requests e relatar problemas.