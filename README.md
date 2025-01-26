# Blockchain Platforma Strangere de Fonduri

Acest proiect este o platformă bazată pe blockchain pentru strângerea de fonduri, unde utilizatorii pot crea și contribui la campanii utilizând Ethereum.

## Comenzi Terminal

În folderul proiectului, executați următoarele comenzi:

```sh
npx hardhat clean
npx hardhat compile
npx hardhat test
npx hardhat node
```

Într-un alt terminal, în același folder al proiectului:

```sh
npx hardhat run scripts/deploy.js --network localhost
```

## Instalare și rulare interfață web

Intrați în folderul `web` și porniți aplicația:

```sh
cd web
npm start
```

## Funcționalități principale

- Creare campanii de strângere de fonduri
- Contribuții în Ethereum
- Monitorizare progres campanii
- Integrare cu rețeaua blockchain

## Tehnologii utilizate

- Solidity
- Hardhat
- Ethereum
- React
- Node.js
