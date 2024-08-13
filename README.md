REMIX DEFAULT WORKSPACE

Remix default workspace is present when:
i. Remix loads for the very first time 
ii. A new workspace is created with 'Default' template
iii. There are no files existing in the File Explorer

This workspace contains 3 directories:

1. 'contracts': Holds three contracts with increasing levels of complexity.
2. 'scripts': Contains four typescript files to deploy a contract. It is explained below.
3. 'tests': Contains one Solidity test file for 'Ballot' contract & one JS test file for 'Storage' contract.

SCRIPTS

The 'scripts' folder has four typescript files which help to deploy the 'Storage' contract using 'web3.js' and 'ethers.js' libraries.

For the deployment of any other contract, just update the contract's name from 'Storage' to the desired contract and provide constructor arguments accordingly 
in the file `deploy_with_ethers.ts` or  `deploy_with_web3.ts`

In the 'tests' folder there is a script containing Mocha-Chai unit tests for 'Storage' contract.

To run a script, right click on file name in the file explorer and click 'Run'. Remember, Solidity file must already be compiled.
Output from script will appear in remix terminal.

Please note, require/import is supported in a limited manner for Remix supported modules.
For now, modules supported by Remix are ethers, web3, swarmgw, chai, multihashes, remix and hardhat only for hardhat.ethers object/plugin.
For unsupported modules, an error like this will be thrown: '<module_name> module require is not supported by Remix IDE' will be shown.


# Criando a Sua Primeira Criptomoeda da Rede Ethereum

Projeto com o objetivo de gerar um contrato na rede Ethereum

## 💻 Tecnologias utilizadas no projeto

- [Ganache](https://archive.trufflesuite.com/ganache/) 
- [IDE Remix](https://remix.ethereum.org/) 
- [MetaMask](https://metamask.io/)
- [Truffle](https://archive.trufflesuite.com/)
- [Solidity](https://soliditylang.org/)

## ✨ Como foi feito ?

- Criamos um ambiente no Ganache para visualizar o envios do bloco e transações
- Usamos a IDE Remix para executar o codigo solidity do contrato
- Com o MetaMask criamos uma rede em ambiente local conectado com o Ganache, importamos os endereços.
- Usamos a linguagem de programação Solidity para desenvolvimento do contrado


## 🛠️ Instruções de execução

Utilize os codigos abaixo para instalação do Node JS e criação da carteira Bitcoin testnet

- 🤖 1. Acessar o site do Ganache para instalação.
- 🤖 2. Baixe a extensão do MetaMask para controlar a rede e carteira
- 🤖 1. Na IDE Remix desenvolva o contrato, compile o codigo e faça o deploy para interagir com o contrato


## 👨‍💻 Expert

<p>
    <img 
      align=left 
      margin=10 
      width=80 
      src="https://avatars.githubusercontent.com/u/111706212?v=4"
    />
    <p>&nbsp&nbsp&nbsp;David Evaristo<br>
    &nbsp&nbsp&nbsp
    <a href="https://github.com/david-evaristo">
    GitHub</a>&nbsp;|
    <a href="https://www.linkedin.com/in/david-evaristo/">LinkedIn</a>
&nbsp;|&nbsp;
</p>
<br/><br/>
<p>

---

Por [David Evaristo](https://github.com/david-evaristo)
