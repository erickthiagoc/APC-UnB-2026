## Código Little Man Computer (LMC)

Este projeto inclui uma rotina desenvolvida para o Little Man Computer (LMC). O objetivo deste algoritmo é receber um número do usuário e imprimir uma contagem sequencial a partir de zero até esse número.

### Código Fonte

```assembly
        INP
        ADD UM
        STA LIMITE
LOOP    LDA CONT
        OUT
        ADD UM
        STA CONT
        SUB LIMITE
        BRP FIM
        BRA LOOP
FIM     HLT
CONT    DAT 0
LIMITE  DAT 0
UM      DAT 1
