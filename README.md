**README**

### Contador de Intervalo

Este é um programa Java simples que solicita ao usuário dois parâmetros e conta os números entre esses dois parâmetros, excluindo o primeiro e incluindo o último. Ele também inclui um tratamento de exceção para verificar se os parâmetros são válidos.

### Funcionamento

1. **Entrada de Parâmetros**: O programa solicita ao usuário que insira dois parâmetros inteiros através do console.

2. **Contagem de Números**: Após receber os parâmetros, o programa conta os números entre esses dois parâmetros, excluindo o primeiro e incluindo o último.

3. **Tratamento de Exceção**: Se o segundo parâmetro for menor ou igual ao primeiro, uma exceção é lançada indicando que os parâmetros são inválidos.

### Como Usar

1. **Compilação**: Compile o programa Java com o comando `javac App.java Contador.java`.

2. **Execução**: Execute o programa compilado com o comando `java App`.

3. **Entrada de Parâmetros**: Digite os dois parâmetros solicitados pelo programa.

### Estrutura do Projeto

- **App.java**: Contém o método `main` onde o programa é iniciado. Solicita os parâmetros ao usuário e chama a função de contar números.

- **Contador.java**: Define a lógica para contar os números entre os parâmetros fornecidos. Também inclui uma exceção para lidar com parâmetros inválidos.

- **ParametrosInvalidosException.java**: Define a classe de exceção personalizada para indicar que os parâmetros fornecidos são inválidos.

### Observações

- Este programa é um exemplo simples de manipulação de entrada do usuário e tratamento de exceção em Java.

- Certifique-se de fornecer dois parâmetros inteiros válidos ao executar o programa para evitar exceções.
