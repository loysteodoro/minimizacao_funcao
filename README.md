# Minimizacao da Função

Este projeto implementa um algoritmo genético para encontrar o valor de \( x \) que minimiza a função \( f(x) = x^3 - 6x + 14 \) dentro do intervalo \([-10, +10]\).

## Funcionamento

O algoritmo genético utiliza os seguintes componentes:

- **Codificação**: \( x \) é representado como um vetor binário.
- **População Inicial**: O algoritmo cria uma população inicial configurável com indivíduos.
- **Mutação**: A taxa de mutação é configurável, atualmente definida em 1%.
- **Crossover**: O algoritmo aplica crossover de 1 ou 2 pontos de corte.
- **Seleção**: A seleção é feita por torneio ou roleta viciada.
- **Elitismo**: Possui a opção de implementar elitismo, configurável para definir o percentual de indivíduos.
- **Critério de Parada**: O algoritmo para após um número máximo de gerações, configurável.

## Requisitos

- Python 3.x
- Bibliotecas necessárias (se houver)

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/loysteodoro/minimizacao_funcao.git
   cd minimizacao_funcao
