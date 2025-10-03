Aula 08 – Linguagem de Programação

Esta pasta contém os exercícios da Aula 08 da disciplina de Linguagem de Programação.

Estrutura das pastas:
exercicio1_conversor_temperaturas/
    conversor_temperaturas.c
exercicio2_calculadora_imc/
    calculadora_imc.c
exercicio3_desconto_progressivo/
    desconto_progressivo.c

Como compilar os programas

Para compilar, é necessário ter um compilador C instalado (ex.: GCC).

Passo a passo:
1. Abra o terminal (Linux/Mac) ou o Prompt de Comando (Windows).
2. Entre na pasta do exercício:
   cd caminho/da/pasta/exercicioX
3. Compile o código-fonte:
   gcc nome_do_arquivo.c -o nome_do_programa

Exemplos:
   gcc conversor_temperaturas.c -o conversor_temperaturas
   gcc calculadora_imc.c -o calculadora_imc
   gcc desconto_progressivo.c -o desconto_progressivo

4. Execute o programa:
   Linux/Mac: ./nome_do_programa
   Windows: nome_do_programa.exe

Observações importantes

- Substitua nome_do_arquivo.c pelo nome do arquivo do exercício.
- Substitua nome_do_programa pelo nome que deseja para o executável.
- Caso o exercício use mais de um arquivo .c ou .h, compile todos juntos, por exemplo:
  gcc arquivo1.c arquivo2.c -o programa

Entrega do trabalho

1. Crie uma pasta principal com seu nome e matrícula (exemplo: Nono_123456).
2. Coloque dentro dela todos os exercícios e este arquivo instrucoes.txt.
3. Compacte a pasta em formato .zip.
4. Envie o arquivo .zip conforme as orientações.

