# Atividade 1:

Um software que lê um arquivo no formato CSV e, para cada linha, calcula a soma das duas primeiras colunas e gera um arquivo CSV, contendo as mesmas linhas, mas o arquivo gerado contém uma coluna adicional que a soma obtida para cada linha. Criar o diretório csv no seu repositório e depositar nele o arquivo design.md contendo a descrição do software que atende esta demanda. Não é a implementação, mas o software a ser construído. Coloque sua proposta no diretório csv no seu repositório ds-2023-02.

## Nome do Programa: CalcFirst

O software a ser desemvolvido deve ler um arquivo CSV de entrada, pegar o conteudo deste arquivo e calcular a soma das duas primeiras colunas para cada linha e gerar um novo arquivo CSV de saída com uma coluna adicional que contém a soma.

**Design do Software**

Primeiramente, devemos receber o arquivo CSV como entrada, para depois realizarmos as outras operações.

### 1 -  Entrada de dados:
- O programa deve ser capaz de receber um arquivo CVS.
- O software deve permitir que o usuário especifique o arquivo CVS de entrada.

### 2 - Leitura de Dados:
- O Software deve abrir o arquivo CVS de entrada.
- Ler o conteudo do arquivo CVS de entrada e para cada linha do arquivo deve:
                     - Dividir o conteudo de cada linha em colunas
                     - Extrair os valores das duas primeiras colunas.
                     - Realizar a soma desses valores extraidos.   
