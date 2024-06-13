 # Desafio_de_código_SQUADIO_intermediário
códigos python resolução

# Desafio 1

Você foi contratado por um banco para desenvolver um programa que auxilie seus clientes a realizar depósitos em suas contas. O programa deve solicitar ao cliente o valor do depósito e verificar se o valor é válido. Se o valor for maior do que zero, o programa deve adicionar o valor ao saldo da conta. Caso contrário, o programa deve exibir uma mensagem de erro. O programa deve solicitar apenas uma vez o valor de depósito.


Exemplos:
entrada 500.50          saida Depósito realizado com sucesso! Saldo atual: R$ 500.50
entrada -100               saída Valor inválido! Digite um valor maior que zero
entrada  0                     saída Encerrando o programa...


# Desafio 2

Após uma análise cuidadosa realizada pela equipe de desenvolvimento de uma empresa bancaria, foi identificado a necessidade de uma nova funcionalidade para otimizar os processos e melhorias da experiência dos usuários. Agora, sua tarefa é implementar uma solução que organize em ordem alfabética uma lista de ativos que será informada pelos usuários. Os ativos são representados por strings que representam seus tipos, como por exemplo: Reservas de liquidez, Ativos intangiveis e dentre outros.
Entrada

A primeira entrada consiste em um número inteiro que representa a  quantidade de ativos que o usuário possui. Em seguida, o usuário deverá  informar, em linhas separadas, os tipos (strings) dos respectivos ativos.
Saída

Seu programa deve exibir a lista de Ativos organizada em ordem alfabética. Cada ativo deve ser apresentado em uma linha separada.
Exemplos


# Desafio 3

Você está trabalhando para uma empresa que utiliza extensivamente os serviços da AWS, e após algumas análises a equipe de segurança identificou que algumas senhas dos usuários no IAM são fracas e podem representar um risco à segurança dos dados da empresa. Para resolver esse problema, foi solicitado que você desenvolva um programa capaz de analisar as senhas dos usuários e fornecer uma validação de força com base em critérios predefinidos.

Requisitos de segurança para a senha:

    A senha deve ter no mínimo 8 caracteres.
    A senha deve conter pelo menos uma letra maiúscula (A-Z).
    A senha deve conter pelo menos uma letra minúscula (a-z).
    A senha deve conter pelo menos um número (0-9).
    A senha deve conter pelo menos um caractere especial, como !, @, #, $, %, etc.

Entrada

A entrada será uma única string representando a senha que precisa ser validada.

Saída

Seu programa deve retornar uma mensagem indicando se a senha fornecida pelo usuário atende aos requisitos de segurança ou não, juntamente com um feedback explicativo sobre os critérios considerados.
