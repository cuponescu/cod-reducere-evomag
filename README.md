# Cod Reducere evoMAG

O colecție de coduri de reducere evoMAG. Le folosim pentru testarea cuvintelor cheie [cod reducere evoMAG](https://cuponescu.ro/magazin/evomag), [voucher evoMAG](https://cuponescu.ro/magazin/evomag), [cupon evoMAG](https://cuponescu.ro/magazin/evomag), și [cod promotional evoMAG](https://cuponescu.ro/magazin/evomag) de pe Cuponescu.ro.

## Instalare

Instalează `cod-reducere-evomag` prin NPM:

```bash
npm install cod-reducere-evomag
```

## Utilizare

Pachetul conține un array de obiecte reprezentând coduri de reducere.

În Node:

```javascript
var codes = require('cod-reducere-evomag')

console.log(codes)

// [
//   {
//     site: 'https://www.evomag.ro',
//     cod_reducere: 'EVOMAG10',
//     reducere: '10% reducere',
//     descriere: 'Reducere de 10% la electronice'
//   },
//   ...
// ]
```

## Despre

Cod-reducere-evomag a fost creat de echipa de la [Cuponescu](https://cuponescu.ro/) pentru a ajuta cu testarea.
