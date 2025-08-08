$ git config --global user.email "romalopes@yahoo.com.br"
$ git config --global user.name "Anderson A Lopes"
$ source /Users/romalopes/.zshenv  
$ curl -L https://foundry.paradigm.xyz | bash
$ foundryup
$ forge init --forge .
$ forge compile
$ forge build
$ forge create SimpleStorage --interactive. // It will ask for the private key.
$ forge create SimpleStorage --rpc-url http://localhost:8545 --interactive
$ anvil
$ cast wallet import defaultKey --interactive
`defaultKey` keystore was saved successfully. Address: 0xf39fd6e51aad88f6f4ce6ab8827279cfffb92266
$ cast wallet list
$ forge script script/DeployFundMe.s.sol:DeployFundMe --rpc-url http://localhost:8545 --account defaultKey --sender 0xf39fd6e51aad88f6f4ce6ab8827279cfffb92266 --broadcast -vvvv

forge script script/Counter.s.sol --rpc-url http://localhost:8545 --account defaultKey --sender 0xf39fd6e51aad88f6f4ce6ab8827279cfffb92266 --broadcast -vvvv

$ forge create SimpleStorage --rpc-url http://localhost:8545 --interactive

$ cd
$ cd .foundry/keystores

$ forge script script/DeploySimpleStorage.s.sol --rpc-url http://localhost:8545

This will deploy on the blockchain.
$ forge script script/DeploySimpleStorage.s.sol --rpc-url http://localhost:8545 --broadcast --private-key 0xac0974bec39a17e36ba4a6b4d238ff944bacb478cbed5efcae784d7bf4f2ff80

$ forge script script/DeploySimpleStorage.s.sol --rpc-url $RPC_URL --broadcast --private-key $PRIVATE_KEY

$ forge script script/DeploySimpleStorage.s.sol --rpc-url http://localhost:8545 --account defaultKey --sender 0xf39fd6e51aad88f6f4ce6ab8827279cfffb92266 --broadcast -vvvv

$ source .env
$ cast --to-base 0x11111 dec

$ cast send 0x59c6995e998f97a5a0044966f0945389dc9e86dae88c7a8412f4603b6b78690d "store(uint256)" 123 --rpc-url $RPC_URL --private-key $PRIVATE_KEY
