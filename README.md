
## Conta Bancária em Java - POO

O desafio será criar uma solução em Java e utilizar os conceitos de POO já apreendidos.<br>
Você deverá criar um programa que solicitará duas opções:

1. Criar conta
2. Acessar conta

### Opção: Criar conta
Ao selecionar "Criar conta" o usuário deverá informar para o cadastro os seguintes dados:

- Nome
- CPF
- Valor de depósito inicial (reais e centavos)

Após informar os dados acima, o programa deverá imprimir a mensagem:

"Conta bancária de número XXXX criada com sucesso."

REGRAS:

- O "Número da conta" é gerado de forma aleatória de comprimento igual a 4, exemplo 0153.
- Não pode existir dois números de contas iguais para clientes diferentes.
- Cada CPF só pode ter uma única conta.


### Opção: Acessar conta
Ao selecionar "acessar conta" o usuário deverá informar o "número da conta" para acesso e após isso o programa deverá realizar as seguintes ações escolhidas pelo usuário:

- depositar valor
- sacar valor
- obter o saldo disponível

Qualquer uma das operações solicitadas deverá imprimir uma mensagem no console de acordo com<br>
com a operação realizada.

Ex.:

"Depósito de R$ 100,00 realizado com sucesso."

### Observações Importantes

Caso o usuário tente sacar um valor superior ao valor que ele possua em conta, informar:

"Saldo insuficiente para realizar a operação."

Caso o usuário queira sacar um valor acima de R$ 5000,00 , informar a seguinte mensagem:

"Valor do saque acima do permitido."
