# Programa básico de Algoritimos.

Algoritmo Quatro_operacoes_basicas

// rotina que recebe dois números e que apresenta o resultado 
das quatro operações feitas com eles

  Var
  
  NUM_A, NUM_B, SOMA, SUBTRACAO, MULTIPLICACAO, DIVISAO: real
  
    NUM_A = 0
    NUM_B = 0
    SOMA = 0
    SUBTRACAO = 0
    MULTIPLICACAO = 0
    DIVISAO = 0
    
  Início
  
    Escreva "Programa que executa as quatro operações básicas"
    Escreva "Informe o primeiro número:"
    Leia NUM_A
    Escreva "Informe o segundo número:"
    Leia NUM_B
    SOMA = NUM_A + NUM_B
    SUBTRACAO = NUM_A – NUM_B
    MULTIPLICACAO = NUM_A * NUM_B
    DIVISAO = NUM_A / NUM_B
    Escreva "A soma dos dois números é"
    Escreva SOMA
    Escreva "A subtração dos dois números é"
    Escreva SUBTRACAO
    Escreva "A multiplicação entre os dois números é"
    Escreva MULTIPLICACAO
    Escreva "A divisão entre os dois números é"
    Escreva DIVISAO
    
  Fim
