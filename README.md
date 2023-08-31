# Sistema Bancário V.2
## Objetivo
Otimizar o sistema bancário criado anteriormente. Separar as funções existentes de saque, depósito e extrato em funções. Criar duas novas funções: cadastrar usuário (cliente) e cadastrar conta bancária.

### Premissas e Restrições (Novas)
* Deixar o código mais modularizado, criando funções para as operações existentes: depositar e visualizar histórico;
* Criar duas novas funções: usuário(cliente do banco) e criar conta corrente(vincular com usuário);
* Saque: deve receber argumentos apenas por nome (keyword only);
* Depósito: deve receber os argumentos apenas por posição(positional only);
* Extrato: deve receber os argumentos por posição e nome (positional only and keyword only);
* Criar Usuário: deve armazenar em uma lista, um usuário composto por(nome, data de nascimento, cpf e endereço). O enderço é uma string com o formato (logradouro - nro - bairro - cidade/sigla estaado). Deverá ser armazenado somente os números do CPF. Não podemos cadastar 2 usuários com o mesmo CPF.
* Criar conta corrente: deverá armazenar contas em uma lista, uma conta é composta por: agência, número da conta e usuário. O número da conta é sequencial, iniciando em 1. O número da agência é fixo "0001". O usuário pode term mais de uma conta, mas uma conta pertence apenas a um usuário.


### Premissas e Restrições (Antiga)
* Deve ser  possível depositar apenas valores positivos na minha conta bancária;
* O projeto trabalhará inicialmente com apenas um usuário, dessa forma não será necessário se preocupar em identificar o número da agência e conta bancária;
* Todos os depósitos devem ser armazenados em uma variável e exibidos na operação extrato;
* O sistema será limitado a 3 saques diários com limite máximo de R$ 500,00/saque;
* Caso o usuário não tenha saldo em conta, o sistema deverá exibir uma mensagem informando a não realização da operaçõa por falta de saldo;
* Todos os saques devem ser armazenados em uma variável e exibidos na operação de extrato;
* A operação de extrato deverá listar todos os depósitos e saques realizados na conta e no final exibir o saldo atual da conta;
* Se o extrato estiver em branco, exibir a mensagem "Não foram realizadas movimentações"
* Os valores deverão ser exibidos utilizando o formato R$ xxx.xx

