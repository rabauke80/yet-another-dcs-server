**To run this repo:**

- make an empty mission (any map)
- modify your dcs to run [dcs-grpc](https://github.com/DCS-gRPC/rust-server)
- clone this repo
- install deps with `npm install`
- create generated code with `npm run codegen`
- start the server with a grpc address `GRPC_ADDRESS=localhost:50051 npm start`

**vscode extensions you should have:**

- [eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) for code standards enforcement
- [prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) for code formatting
- [lua](https://marketplace.visualstudio.com/items?itemName=sumneko.lua) for lua. Only needed if you plan to work on the lua bits. (You probably don't need this)
