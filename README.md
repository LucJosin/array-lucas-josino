# Estrutura de Dados - Array em Python

Atividade de Estrutura de Dados 2025.2 usando Python 3.

## O que foi feito

- Criei uma lista com 5 nomes.
  - ```python
    array = ["Lucas", "Amanda", "Ana", "David", "Pedro"]
    ``` 
- Usei os índices para mostrar na tela:
  - O primeiro elemento da lista.
    - ```python
      print("Primeiro elemento:", array[0])
      ```
  - O terceiro elemento da lista.
    - ```python
      print("Primeiro elemento:", array[2])
      ```
  - O último elemento da lista.
    - ```python
      print("Primeiro elemento:", array[-1])
      ```
- Verifiquei se o nome **Carla** está na lista.
  - ```python
    if "Carla" in array:
      print("Carla está na lista!")
    else:
      print("Carla não foi encontrada na lista.")
    ```

## Como executar o programa

Caso você estiver utilizando Windows, precisa fazer a instalação do [Python](https://python.org.br/instalacao-windows/). 

No caso de Linux, sua distribuição provavalmente já vem com Python instalado, para verificar utilize o comando no terminal:

```bash
python3 --version
```

### Rodando o programa no terminal

Como o programa não necessita de nenhum pacote externo, podemos pular a parte de configuração de dependências e apenas usar comando abaixo para rodar o programa (Linux):

```bash
cd <pasta-do-seu-arquivo> 
```

```bash
python3 array.py
```

## Exemplo da saída gerada

```bash
Primeiro elemento: Lucas
Terceiro elemento: Ana
Último elemento: Pedro
Carla não foi encontrada na lista.
```
