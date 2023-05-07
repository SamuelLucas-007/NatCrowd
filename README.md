# NatCrowd - Nature CrowdFunding

<p align="center">
<img src= "https://github.com/ArthurTsuka/Semana01/blob/main/logo.png" border="0"></img>
</p>

## 💪 Integrantes:
 - <a href="https://www.linkedin.com/in/arthur-tsukamoto/"> Arthur Tsukamoto</a>
 - <a href="https://www.linkedin.com/in/gabriel--nascimento/">Gabriel Nascimento</a>
 - <a href="https://www.linkedin.com/in/guilherme-moura-9668821a5/">Guilherme Moura</a>
 - <a href="https://www.linkedin.com/in/samuel-lucas-de-almeida-241a77210/"> Samuel Lucas de Almeida</a>
## 📝 Descrição 
<p align="justify"> Nossa plataforma tem como objetivo promover a compra e venda de criptoativos sustentáveis, além de fornecer um ambiente para investidores e doadores encontrarem objetivos em comum, como apoiar causas sociais e alcançar metas de governança ambiental, social e corporativa (ESG). Com a nossa plataforma, os usuários podem encontrar oportunidades de investimento que não apenas atendem às suas necessidades financeiras, mas também contribuem para um futuro sustentável.
<br><br>
A NatCrowd tem como principal foco atuar no mercado sustentável, respeitando a natureza e os recursos do planeta. Acreditamos que o cuidado com o meio ambiente é fundamental para garantir um futuro melhor para todos. Por isso, buscamos contribuir de forma significativa para um mercado mais consciente e sustentável. Nosso objetivo é fazer a diferença, não apenas em nosso país, mas no mundo todo. Junte-se a nós nesta missão de construir um futuro mais próspero e sustentável para todos.
<br><br>
Através de nossa solução rápida e sem burocracia, a compra e venda de criptoativos sustentáveis se torna uma experiência única para o investidor. Com um modelo escalável e processo transparente baseado em blockchain, nossa plataforma atrai a atenção de grandes empresas que buscam demonstrar seu compromisso com temas ESG. Oferecemos uma oportunidade para investidores de todo o mundo fazerem parte de um mercado financeiro mais sustentável e consciente.
<br>
<br>
<p>Link do Projeto: <a href=""</a></p>
<br>

## 💡Tecnologias utilizadas:
<br>
- Solidity
<br>
- React
<br>
- Truffle
<br>
- Figma
<br>
- Typescript
<br>
- Javascript
<br>
- MetaMask
<br>


## 💻 Configuração para desenvolvimento

Aqui encontram-se todas as instruções necessárias para a instalação de todos os programas da aplicação web.

1. Baixar e instalar o node.js:  [https://nodejs.org/pt-br/](https://nodejs.org/pt-br/) (versão 18.10.0 LTS)
2. Clone o repositório.
3. Abra o "command prompt" ou o "terminal do VSCode" na pasta raíz(root) do repositório clonado:

```sh
npm install
```

Esse comando instalará todas as depedencias presente no arquivo <b>package.json</b>, o qual é importantatissimo para rodar o projeto. Em seguida, caso a demonstração continue, é necessario digitar o comando abaixo

```sh
npm run dev
```

O comando irá abrir uma porta local, que permitirá  o usuario ve e utilizar a plataforma NatCrowd
<br>
Após o comando npm run dev, o link da aplicação irá aparecer no terminal.

Como nao foi feito a integração, utilizamos o Remix para compilar e fazer o deploy dos contratos na testnet Mumbai.

É necessário a utilização da wallet MetaMask e da testnet Mumbai.
<br>
Para conectar a testnet Mumbai na MetaMask, acesse esse <a href="https://chainlist.org/?testnets=true&search=mumbai">Link</a>, conecta a metamask e permita a troca de rede.

1 - Acesse a plataforma do Remix: <a href="https://remix.ethereum.org/#lang=en&optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.19+commit.7dd6d404.js">Clique Aqui</a>
<br>
2 - Copie o contrato que se encontra no github: <a href="https://github.com/SamuelLucas-007/NatCrowd/blob/main/backend/contracts/CarbonCoin.sol">Clique Aqui</a>
<br>
3 - Colar o contrato em um novo contrato dentro do Remix.
<br>
4 - No terceiro icone(da lateral esquerda), selecione a versao 0.8.19+commit do compilador e compila o projeto.
<br>
5 - Apos compilar, no quarto icone da lateral, será realizado o deploy do contrato ao clicar em "deploy".
<br>
6 - Apos o deploy, o usario consegue mintar CarbonCoin, ao clicar na funcao Buy e colocar a quantidade de token.
<br>
7 - Apos a aquisicao dos CarbonCoin, o usuario consegue trocar por BTGDOL na <a href="https://app.uniswap.org/#/swap">Uniswap</a>.
<br>
