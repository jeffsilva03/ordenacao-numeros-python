# ordenacao-numeros-python — Ordenador de Números em Python

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Terminal](https://img.shields.io/badge/Terminal-000000?style=for-the-badge&logo=gnubash&logoColor=white)
![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen?style=for-the-badge)

**Projeto em Python que implementa um ordenador de três números no terminal, explorando fundamentos da programação como entrada de dados, comparações lógicas e controle de fluxo com estruturas condicionais aninhadas.**

</div>

---

## Sobre o projeto

Este projeto foi desenvolvido como exercício prático dos fundamentos da linguagem Python. A proposta foi construir um programa funcional no terminal que demonstrasse, de forma aplicada, a leitura e conversão de dados do usuário, o uso de operadores lógicos para comparação entre múltiplos valores e a organização da lógica com estruturas condicionais aninhadas.

O programa solicita três números inteiros ao usuário e os exibe em ordem crescente, sem utilizar funções prontas de ordenação — toda a lógica de comparação é implementada manualmente com `if/elif/else`.

## Objetivos da entrega

- Utilizar **input e conversão de tipo** para capturar números inteiros do usuário.
- Implementar **comparações lógicas** com operadores `and` para identificar o menor valor.
- Usar **estruturas condicionais aninhadas** (`if/elif/else`) para cobrir todos os casos de ordenação.
- Exibir o resultado **ordenado de forma crescente** sem bibliotecas de ordenação.
- Manter o código em **um único arquivo**, legível e direto.

## Funcionalidades

| Funcionalidade | Descrição |
|---|---|
| **Leitura de entrada** | Solicita três números inteiros ao usuário via terminal |
| **Identificação do menor** | Determina qual dos três números é o menor usando comparações lógicas |
| **Ordenação crescente** | Exibe os três números em ordem do menor para o maior |
| **Cobertura de casos** | Lida com todas as combinações possíveis de ordenação entre os três valores |

## Conceitos aplicados

```
1. input()         — leitura de dados digitados pelo usuário no terminal
2. int()           — conversão de string para inteiro
3. if/elif/else    — estrutura condicional para cobrir todos os casos de ordem
4. if aninhado     — segundo nível de comparação para definir a posição dos demais
5. Operador and    — comparação simultânea de dois valores na mesma condição
6. print()         — exibição dos valores ordenados separados por espaço
```

## Tecnologias

- **Python 3** — linguagem principal do projeto

Nenhuma biblioteca externa. Roda em qualquer ambiente com Python 3 instalado.

## Estrutura do projeto

```
ordenacao-numeros-python/
└── main.py    # Código-fonte completo com leitura, comparação e exibição ordenada
```

## Como usar

### Pré-requisitos

- Python 3 instalado (`python3 --version` para verificar)
- Terminal (Linux, macOS ou Windows com PowerShell/CMD)

### Execução

```bash
# Clone o repositório
git clone https://github.com/jeffsilva03/ordenacao-numeros-python.git

# Acesse a pasta
cd ordenacao-numeros-python

# Execute
python3 main.py
```

### Uso no terminal

```
Digite um número: 8
Digite outro número: 3
Digite outro número: 5
3 5 8
```

O programa lê os três valores e exibe a saída em ordem crescente na mesma linha.

## Lógica de funcionamento

O programa identifica o menor dos três números comparando cada um com os demais usando o operador `and`. Uma vez identificado o menor, um segundo `if` interno compara os dois restantes para definir a ordem entre eles. O resultado é impresso diretamente com `print`.

```
Entrada: num1, num2, num3
   ↓
Qual é o menor? → num1? num2? num3?
   ↓
Entre os outros dois, qual vem primeiro?
   ↓
Saída: menor  meio  maior
```

## Limitações conhecidas

| Limitação | Comportamento |
|---|---|
| Apenas números inteiros | O programa usa `int()` — entradas decimais causam erro |
| Sem tratamento de exceção | Entrada não numérica encerra o programa com erro |
| Exatamente três valores | Não suporta quantidade variável de números |

> Essas limitações são intencionais para o escopo do exercício. Tratamento de exceções com `try/except` e suporte a `float` podem ser implementados como próximo passo.

## Licença

Este projeto é de uso livre para fins educacionais. Sinta-se à vontade para adaptar, expandir e usar como base de estudo.

---

<div align="center">

Desenvolvido como exercício prático dos fundamentos da linguagem Python.

</div>
