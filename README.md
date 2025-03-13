# Warmup - Aritmética Morse

## Integrantes do Grupo

- **Brayan Pereira** - RA: 2023100832
- **Bernardo Rodrigues** - RA: 2023100357
- **João Gabriel** - RA: 2023100603

## Solução

### Estrutura do Projeto

- **Sources**: Contém o código-fonte principal, incluindo o arquivo `warmup.c` e a lógica de resolução no `warmup_solver.c`.
- **Headers**: Contém o arquivo de cabeçalho `warmup_solver.h` com a definição das funções.
- **02-aritmetica-morse**: Contém o diretório `input/` com arquivos de instâncias numeradas de `instance_1` até `instance_112`.
- **output**: O arquivo `solution.txt` será gerado aqui com os resultados das expressões.

### Como o Programa Funciona

O programa lê os arquivos de instâncias do diretório `input/` e processa cada um de acordo com o formato definido. Para cada instância, ele:

1. Converte os números Morse (como `.` e `-`) para valores inteiros.
2. Avalia a expressão matemática respeitando a precedência dos operadores.
3. O resultado de cada instância é gravado no arquivo `solution.txt`, localizado no diretório `output/`.

### Funções

- **morse_to_value**: Mapeia caracteres Morse (., -, :, =) para valores inteiros.
- **parse_morse_number**: Converte uma sequência Morse em um número inteiro.
- **evaluate_expression**: Avalia a expressão matemática com números e operadores.
- **solve_warmup**: Processa a expressão de um arquivo de entrada e escreve o resultado.
- **check_warmup_solution**: Verifica se a solução está correta.
- **main**: Lê os arquivos do diretório, chama as funções para processar e gerar a solução.

### Como Executar

#### Configuração do Ambiente

1. Verifique se os arquivos de instância estão no diretório `02-aritmetica-morse/input/`, com nomes de `instance_1` até `instance_112`.
2. O diretório
