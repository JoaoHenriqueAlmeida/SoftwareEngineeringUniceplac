# Compilação e Interpretação em Java

Este documento aborda os conceitos de compilação e interpretação no contexto da linguagem Java, além de discutir as fases de execução de um programa em Java.

## Linguagens Compiladas vs. Interpretadas

- **Linguagens Compiladas**: O código-fonte é diretamente traduzido para código de máquina pela máquina de destino. Exemplos: C.

  - **Vantagens**: Maior controle sobre o hardware, melhor performance.
  - **Desvantagens**: Tempo adicional necessário para o processo de compilação.

- **Linguagens Interpretadas**: O código-fonte é executado por um interpretador, que traduz e executa o código simultaneamente. Exemplos: PHP, JavaScript.

  - **Vantagens**: Flexibilidade, não depende da plataforma.
  - **Desvantagens**: Execução mais lenta.

- **Java**: Uma linguagem que combina compilação e interpretação. O código-fonte Java é compilado para bytecodes, que são posteriormente interpretados pela JVM (Máquina Virtual Java).

## Fases de Execução de um Programa Java

1. **Edição**:

   - O código-fonte é escrito em um editor de texto e salvo com a extensão `.java`.

2. **Compilação**:

   - O código-fonte é transformado em bytecodes, gerando um arquivo `.class` que é entendível pela JVM.

3. **Carregamento**:

   - A JVM carrega os bytecodes do arquivo `.class` para a memória primária do computador.

4. **Verificação**:

   - A JVM verifica se os bytecodes são válidos e se cumprem as restrições de segurança do Java.

5. **Execução**:
   - A JVM executa os bytecodes, utilizando uma combinação de interpretação e compilação Just-In-Time (JIT) para melhorar a performance.

## Conceitos Importantes

- **Bytecodes**: Um código de nível intermediário gerado após a compilação do código-fonte Java.
- **JVM (Java Virtual Machine)**: Responsável por carregar, verificar e executar os bytecodes.
- **Compilação Just-In-Time (JIT)**: Técnica usada pela JVM para compilar partes do bytecode em tempo de execução, melhorando a performance.

## Exemplo Simples de Código Java

```java
public class OlaMundo {
  public static void main(String[] args) {
    System.out.println("Olá Mundo!");
  }
}
```
