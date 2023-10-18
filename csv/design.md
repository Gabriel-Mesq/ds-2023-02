# Design de software para ler arquivo .csv

## Objetivo
O objetivo é produzir um software que lê um arquivo no formato CSV e, para cada linha, calcula a soma das duas primeiras colunas e gera um arquivo CSV. O arquivo gerado deve conter uma coluna adicional com a soma das duas primeiras colunas.

## Design
### Interface de usuário
   - O software pode ter uma interface de usuário simples para que os usuários possam selecionar o arquivo de entrada e especificar o nome do arquivo de saída.

### Funcionalidade principal:
   - Entrada de Arquivo: 
     - Selecionar o arquivo csv de entrada.
   - Processamento do Arquivo:
     - O software lê o arquivo CSV de entrada linha por linha.
     - Para cada linha, ele extrai os valores das duas primeiras colunas e calcula a soma.
     - Adiciona a soma como um novo valor à linha.
   - Saída do Arquivo:
     - O software cria um novo arquivo CSV de saída com um nome especificado pelo usuário ou com um nome padrão.
     - Ele escreve as linhas processadas, incluindo a nova coluna com a soma, no arquivo de saída.

### Tratamento de Erros:
   - Exemplos que devem ser considerados são arquivos de entrada ausentes, formatos de arquivo inválidos ou valores não numéricos nas colunas.

### Fluxo de Uso:
   1. Iniciar o aplicativo.
   2. Selecionar o arquivo CSV.
   3. Definir as configurações.
   4. Escolher um nome de arquivo para saída.
   5. Iniciar o processamento.
   6. Processar o arquivo e criar um novo CSV com as somas.
   7. Notificar a conclusão.
   8. Publicar o arquivo de saída gerado.
