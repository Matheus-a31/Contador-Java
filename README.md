# Contador Java Desafio DIO

Este projeto Java simples demonstra o uso de exceções personalizadas e controle de fluxo básico para contar e imprimir números entre dois parâmetros fornecidos pelo usuário.

## Funcionalidades

- Solicita ao usuário dois números inteiros como parâmetros
- Verifica se o segundo parâmetro é maior que o primeiro
- Imprime uma sequência de números entre os parâmetros fornecidos
- Implementa tratamento de erros com exceção personalizada

## Requisitos

- Java JDK 8 ou superior
- Ambiente de desenvolvimento Java (opcional)

## Como Executar

1. Compile os arquivos Java:
   ```
   javac Contador.java ParametroInvalidoException.java
   ```

2. Execute o programa:
   ```
   java Contador
   ```

3. Siga as instruções no terminal:
   - Digite o primeiro parâmetro (número inteiro)
   - Digite o segundo parâmetro (número inteiro maior que o primeiro)

## Exemplo de Uso

```
Digite o primeiro parâmetro:
5
Digite o segundo parâmetro:
10
Imprimindo o número 6
Imprimindo o número 7
Imprimindo o número 8
Imprimindo o número 9
Imprimindo o número 10
```

## Tratamento de Erros

Se o segundo parâmetro for menor ou igual ao primeiro, o programa lançará uma exceção com a mensagem:
```
O segundo parâmetro deve ser maior que o primeiro
```

## Estrutura do Projeto

- `Contador.java`: Classe principal contendo a lógica do programa e método main
- `ParametroInvalidoException.java`: Exceção personalizada para parâmetros inválidos

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
