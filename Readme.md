Algoritmo "Menu Lanchonete : Iasmim Sousa"

Var
opcao, total, valor_item: Real
Inicio

total <- 0

Escreval("Bem-vindo à Lanchonete Da Iasmim!")
Escreval("Menu de Lanches:")
Escreval("1 – X-Salada: R$8,00")
Escreval("2 – X-Bacon: R$10,00")
Escreval("3 – X-Egg: R$9,00")
Escreval("4 – Refrigerante: R$6,50")
Escreval("5 – Finalizar pedido")

Repita
    Escreval("Digite a opção desejada (1 a 5): ")
    Leia(opcao)

    Se opcao = 1 Entao
        valor_item <- 8.0
    Senao
     Se opcao = 2 Entao
        valor_item <- 10.0
    Senao
     Se opcao = 3 Entao
        valor_item <- 9.0
    Senao
     Se opcao = 4 Entao
        valor_item <- 6.5
    Senao
     Se opcao = 5 Entao
        Escreval("Pedido finalizado. Total a pagar: R$", total)
    Senao
        Escreval("Opção inválida. Escolha uma opção válida.")
    FimSe
    fimse
    fimse
    fimse
    fimse


        total <-(total + valor_item)


Ate opcao = 5
FimAlgoritmo
