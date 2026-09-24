# Registro de Testes Unitários

Aluno: Pietro Dipiassa
Grupo: 04
Data: 24/09/2026

## Testes escritos

| # |      Arquivo       |                          O que o teste verifica                          |          Tipo           |
| - | ------------------ | ------------------------------------------------------------------------ | ----------------------- |
| 1 | ambiente.test.js   | visualizam o toBe, verificando que 1+1 tem que ser =2                    |         sucesso         |
| 2 | validators.test.js | verifica se o Email está válido ou inválido                              |         sucesso         |
| 3 | validators.test.js | Nome com no maximo 3 letras                                              |         sucesso         |
| 4 | parseld.test.js    | lança o ValidatorsError quando o id contém letras misturadas com números |          falha          |

## Resultado

Passaram: 1, 2, 3
Falharam: 4

## Defeito encontrado

Teste: 1- verificar 1+1=2
       2- verificar email inválido
       3- nome com no maximo 3 letras
       4- erro se houver letras misturadas com números

Esperado: 1- Resultado igual a 2
          2- email válido
          3- nome com 3 letras
          4- somente letras

Obtido: 1- Resultado igual a 2
        2- email válido (ana@senai.com)
        3- nome com 3 letras (Ana)
        4- nome misturado com número (12abc)

## Cobertura

% Lines da linha "helpers":
Em uma frase, o que esse número significa: