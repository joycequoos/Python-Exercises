# Python Exercises

[← Voltar a Engenharia de Dados](https://github.com/joycequoos/Data_Enginer/blob/main/README.md)

Coleção de exercícios práticos de Python, cobrindo desde os conceitos mais básicos (variáveis, tipos e operadores) até estruturas de dados, funções, condicionais, laços, tratamento de erros e leitura de arquivos. O objetivo é consolidar a base da linguagem através da prática, exercício por exercício, antes de avançar para projetos mais complexos de automação e ETL.

## Índice

- [Objetivo](#objetivo)
- [Exercícios](#exercícios)
- [Próximos passos](#próximos-passos)

---

## Objetivo

Praticar, de forma incremental, os fundamentos da linguagem Python — tipos de dados, operadores, strings, listas, funções, condicionais, laços, sets, dicionários, tratamento de exceções e manipulação de arquivos — como base para tópicos mais avançados, como ETL e automação de dados.

## Exercícios

| Exercício | Tema | O que faz |
| --- | --- | --- |
| [Exercicio01.py](https://github.com/joycequoos/Python-Exercises/blob/main/Exercicio01.py) | Variáveis e f-strings | Declara variáveis de tipos diferentes (string, int, float, bool) e as exibe usando f-strings, incluindo a reatribuição de uma variável para outro tipo |
| [Exercicio02.py](https://github.com/joycequoos/Python-Exercises/blob/main/Exercicio02.py) | Tipos numéricos e operadores | Converte valores entre `float` e `int`, testa operadores aritméticos (soma, subtração, potência, módulo, divisão inteira) e funções matemáticas como `abs`, `pow`, `max`, `min`, `round` e o módulo `math` (`floor`, `ceil`, `sqrt`) |
| [Exercicio03.py](https://github.com/joycequoos/Python-Exercises/blob/main/Exercicio03.py) | Manipulação de strings | Testa métodos de string como `upper()`, `lower()`, `capitalize()`, `isupper()`, `strip()`, `len()` e o operador `in` para verificar substrings |
| [Execicios04.py](https://github.com/joycequoos/Python-Exercises/blob/main/Execicios04.py) | Entrada de dados (`input`) | Lê dois números digitados pelo usuário com `input()`, converte para `int` e imprime a soma — uma calculadora básica |
| [Exercicios05.py](https://github.com/joycequoos/Python-Exercises/blob/main/Exercicios05.py) | Listas | Cria listas, ordena (`sort()`) e inverte (`reverse()`) uma lista de idades, além de exemplos comentados de alteração, extensão (`extend()`) e inclusão de itens (`append()`) |
| [Exercicios06.py](https://github.com/joycequoos/Python-Exercises/blob/main/Exercicios06.py) | Funções | Define funções com um ou mais parâmetros (`fazer_big_mac`, `preparar_refrigerante`), uma função que retorna um valor (`soma_num`) e uma que encontra o maior número de uma lista (`maior_num`) |
| [Execicios07.py](https://github.com/joycequoos/Python-Exercises/blob/main/Execicios07.py) | Condicionais | Usa `if`/`else` combinado com operadores lógicos (`or`) para decidir entre duas ações com base em duas variáveis booleanas |
| [Exercicios08.py](https://github.com/joycequoos/Python-Exercises/blob/main/Exercicios08.py) | Laços aninhados | Percorre uma matriz (lista de listas) com dois `for` aninhados, imprimindo cada valor individualmente |
| [Exercicio09.py](https://github.com/joycequoos/Python-Exercises/blob/main/Exercicio09.py) | Sets | Cria sets com diferentes tipos de dados (strings, números, booleanos) e observa como o set remove valores duplicados automaticamente |
| [Exercicio09-dict.py](https://github.com/joycequoos/Python-Exercises/blob/main/Exercicio09-dict.py) | Dicionários | Cria um dicionário mapeando abreviações de meses para o nome completo, acessando valores diretamente pela chave e com `get()` (incluindo valor padrão para chave inexistente) |
| [Exercicio10.py](https://github.com/joycequoos/Python-Exercises/blob/main/Exercicio10.py) | Tratamento de exceções | Usa `try`/`except` para capturar erro de conversão ao ler um número digitado pelo usuário, evitando que o programa quebre com uma entrada inválida |
| [Exercicio11.py](https://github.com/joycequoos/Python-Exercises/blob/main/Exercicio11.py) | Leitura de arquivos | Abre um arquivo de texto (`teste.txt`) em modo leitura (`"r"`), com exemplos comentados de `readable()`, `read()` e `readline()` |

## Próximos passos

- Completar os exercícios 12 (`Exercicios12.py` e `Exercicios12_tools.py`), que ainda estão vazios no repositório.
- Adicionar comentários explicando o objetivo de cada exercício diretamente no código.
- Padronizar a nomenclatura dos arquivos (hoje mistura `Exercicio`, `Exercicios` e `Execicios`).
- Fechar o arquivo aberto no Exercício 11 com `arquivo.close()` ou usar o gerenciador de contexto `with open(...) as arquivo:`.
