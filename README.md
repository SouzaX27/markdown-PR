# Style Guide do Projeto
## Linguagem Typescript
### Variáveis
```
  Sempre adicione a tipagem primitiva
```
```
  //Ruim
  nome = "Gustavo"
  nome: any = "Vai Curintia"

  //Bom
  nome: string = "Sem Mundial"
```
---
```
  Evite o uso do ELSE.
```
```
  //Ruim
    if (a == b)
      console.log('iguais')
    else
    console.log('diferentes')

  //Bom
    if (a == b)
      console.log('iguais')
    if (a != b)
      console.log('diferentes')