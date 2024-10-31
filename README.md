# README - Calibrar Pneus com a Bomba da SBC

## Descrição do Problema

Calibrar os pneus do carro é uma tarefa essencial para a segurança e desempenho do veículo. Para facilitar esse processo, os postos de gasolina utilizam bombas de ar eletrônicas que permitem ao motorista indicar a pressão desejada através de um teclado. Ao conectar a bomba ao pneu, a bomba lê a pressão atual e calcula a diferença entre a pressão desejada e a pressão lida. Em seguida, a bomba ajusta a pressão do pneu conforme necessário.

Este programa foi desenvolvido para a SBC - Sistemas de Bombas Computadorizadas, com o objetivo de calcular a diferença de pressão entre a pressão desejada e a pressão lida.

## Entrada

- A primeira linha da entrada contém um inteiro \( N \), que representa a pressão desejada pelo motorista (1 ≤ \( N \) ≤ 40).
- A segunda linha da entrada contém um inteiro \( M \), que representa a pressão lida pela bomba (1 ≤ \( M \) ≤ 40).

## Saída

- O programa deve imprimir uma única linha contendo a diferença entre a pressão desejada e a pressão lida. A saída deve ser calculada como:
  
  \[
  \text{diferença} = N - M
  \]

## Exemplo de Uso

### Exemplo 1

**Entrada:**
```
30
25
```

**Saída:**
```
5
```

### Exemplo 2

**Entrada:**
```
35
40
```

**Saída:**
```
-5
```

## Considerações

- A diferença pode ser negativa se a pressão lida for maior que a pressão desejada, indicando que o pneu deve ser esvaziado.
- Este programa deve ser executado em um ambiente que suporte a leitura de entradas padrão.

## Implementação

O código pode ser implementado em Python da seguinte maneira:

```python
# Leitura da pressão desejada
N = int(input())

# Leitura da pressão lida pela bomba
M = int(input())

# Cálculo da diferença
diferenca = N - M

# Impressão da diferença
print(diferenca)
```

## Conclusão

Este programa é uma solução simples e eficiente para calcular a diferença de pressão entre a pressão desejada e a lida em um sistema de bomba de ar, contribuindo para a manutenção adequada dos pneus e a segurança dos motoristas.
