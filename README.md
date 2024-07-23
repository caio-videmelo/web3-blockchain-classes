# DIOToken (DIO Coin)
## Overview

DIOToken é um token ERC-20 implementado em Solidity, projetado para ser interoperável com contratos inteligentes e aplicações descentralizadas (dApps) na blockchain Ethereum. Este contrato implementa as funcionalidades básicas de um token ERC-20, além de práticas de segurança aprimoradas com o uso de SafeMath.

## Token Details

1. Token Name: DIO Coin

2. Token Symbol: DIO

3. Decimals: 2

4. Total Supply: 1,000,000 DIO

## Contract Features

SafeMath Integration:

Para garantir operações matemáticas seguras, o contrato utiliza a biblioteca SafeMath, que previne overflow e underflow em operações aritméticas.

## ERC-20 Interface

O contrato implementa a interface ERC-20 padrão, que inclui as seguintes funções:

1. totalSupply(): Retorna o fornecimento total de tokens.

2. balanceOf(address tokenOwner): Retorna o saldo de um endereço específico.

3. allowance(address tokenOwner, address spender): Verifica a quantidade de tokens que um proprietário permite a um gastador.

4. transfer(address to, uint tokens): Transfere tokens de uma conta para outra.

5. approve(address spender, uint tokens): Aprova que um gastador gaste um número específico de tokens da conta do proprietário.

6. transferFrom(address from, address to, uint tokens): Transfere tokens de uma conta para outra usando a permissão concedida.

## Callback Function

O contrato suporta a funcionalidade approveAndCall, que permite a aprovação de tokens e execução de uma função em um único chamado. A função receiveApproval é definida no contrato ApproveAndCallFallBack.

## Payable Fallback Function

O contrato inclui uma função receive() que permite receber Ether. Além disso, há uma função fallback() para lidar com transferências inesperadas de Ether.

## Contract Code

<img src="https://github.com/user-attachments/assets/80395f12-08df-409f-8d4e-3942f029ddc9" alt="Carbon"/>

## Usage

### Deployment

### Deploy the Contract:

Utilize uma ferramenta de desenvolvimento Ethereum como Remix, Truffle ou Hardhat para implantar o contrato DIOToken.

### Interacting with the Contract:

Utilize a interface de usuário (UI) do Remix ou ferramentas de integração como Web3.js ou Ethers.js para interagir com o contrato.

### Key Functions

Transfer Tokens:

<img src="https://github.com/user-attachments/assets/0038b5bc-2943-4984-9cd3-d26c00e772d2" alt="Carbon1"/>

Approve Spender:

<img src="https://github.com/user-attachments/assets/165c2775-c97b-4352-9680-72a5e3c6a707" alt="Carbon2"/>

Transfer From:

<img src="https://github.com/user-attachments/assets/92d3e7af-1c2e-4313-97f2-d9c7d80cf081" alt="Carbon3"/>

Approve and Call:

<img src="https://github.com/user-attachments/assets/e74e5fba-e27a-4648-8c83-25b412eb3368" alt="Carbon4"/>

## Testing

Testando o código no Remix - Ethereum IDE e fazendo o "compiling".

<img src="https://github.com/user-attachments/assets/db65542f-9c6c-42e4-b5b1-bb65dce8431d" alt="Remix"/>

## License

Este projeto está licenciado sob a GPL-3.0 License.
