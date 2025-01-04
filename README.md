#Anotações Estudo de JavaScript
## Modulo: JAVASCRIPT:
- OBJETIVOS:
- ARRAYS
- OBJETOS
- LOCAL STORAGE
- DOM
- MAP
## CONTEUDO:
- CRUD COM ARRAYS E LOCALSTORAGE

## Array
- Começa sempre da posição **0**.
- É possível utilizar todos os tipos de dados **(String, Bolean, Number...)**
- Representado como: **[]** ou **Array()**
- É possível usar um objeto e outros arrays dentro do array principal

## Objeto
- Estrutura: Pares chave-valor.
- Criação: {} ou new Object().
- Acesso: Ponto ou colchetes.
- Valores: Qualquer tipo de dado.
## Conceitos de JavaScript
- Get = **consultar (Obter ou recuperar o valor de uma varipavel ou propriedade)**
- Set = **Setar (Atribuir ou Definir um valor a uma variável ou propriedade)**

## LocalStorage
 **O que é**: localStorage é uma API de armazenamento web que permite salvar dados no navegador de forma persistente.
  
**Persistência**: Os dados são mantidos mesmo após o fechamento do navegador ou reinício do computador.

**Capacidade:** Geralmente permite armazenar até 5MB de dados por domínio.
Acesso: Acessível através de localStorage no JavaScript, sem necessidade de servidores.

**Armazenamento:** Armazena dados como pares chave-valor (strings).
Métodos principais: setItem(), getItem(), removeItem(), clear().

**Escopo:** É limitado ao domínio que salvou os dados (não acessível por outros sites).

**Segurança:** Não é criptografado, portanto, não deve ser usado para informações sensíveis.
Limitações: Não suporta dados complexos diretamente (ex: objetos), deve-se usar JSON.stringify() e JSON.parse().

**Sincronicidade:** Operações são síncronas e bloqueiam o thread principal.

  
