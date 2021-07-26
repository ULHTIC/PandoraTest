
**UNIVERSIDADE LUSÓFONA DE HUMANIDADES E TECNOLOGIAS**


# Exercício -

Na resolução deste trabalho deve ser utilizada a Linguagem de Programação C. Para além da correta implementação dos requisitos, tenha em conta os seguintes aspetos:
- O código apresentado deve ser bem indentado. 
- O código deve compilar sem erros ou *warnings* utilizando o *gcc* com as seguintes flags:
 `-Wall -ansi -Wextra -Wpedantic`
- Tenha em atenção os nomes dados das variáveis, para que sejam indicadores daquilo que as mesmas vão conter.
- Evite o uso de constantes mágicas. 
- Evite duplicação de código. 
- Considere a implementação de funções para melhorar a legibilidade, evitar a duplicação e criar soluções mais genéricas.
- É proíbida a utilização de variáveis globais - i.e. variáveis declaradas fora de qualquer função.
- Recomenda-se a não utilização da biblioteca de sistema string.h.

## Descrição do problema
Faça um programa que lê uma string do stdin e imprime no stdout a mesma string invertida. A string deverá ter um máximo de 16 caracteres (excluíndo o caracter terminador).

Exemplo:
```bash
./inverte
maratona
anotaram
```
No exemplo assume-se que o programa compilado tem o nome `inverte`.

O programa não deverá imprimir no `stdout` qualquer mensagem adicional. Mensagens impressas no `stderr` serão ignoradas.

