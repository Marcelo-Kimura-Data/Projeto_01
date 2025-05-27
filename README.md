# Projeto_01: Automação de Indicadores

### Objetivo: Treinar e criar um Projeto Completo que envolva a automatização de um processo feito no computador

### Descrição:

Imagine que você trabalha em uma grande rede de lojas de roupa com 25 lojas espalhadas por todo o Brasil.

Todo dia, pela manhã, a equipe de análise de dados calcula os chamados One Pages e envia para o gerente de cada loja o OnePage da sua loja, bem como todas as informações usadas no cálculo dos indicadores.

Um One Page é um resumo muito simples e direto ao ponto, usado pela equipe de gerência de loja para saber os principais indicadores de cada loja e permitir em 1 página (daí o nome OnePage) tanto a comparação entre diferentes lojas, quanto quais indicadores aquela loja conseguiu cumprir naquele dia ou não.

Devemos criar um processo da forma mais automática possível para calcular o OnePage de cada loja e enviar um email para o gerente de cada loja com o seu OnePage no corpo do e-mail e também o arquivo completo com os dados da sua respectiva loja em anexo.

Ex: O e-mail a ser enviado para o Gerente da Loja A deve ser como exemplo

## Passo 01: Importação dos arquivos para o DataFrame

Iremos primeiramente realizar a importação dos arquivos para o formato de DataFrame (Pandas) para conseguir realizar as tratativas.

Nesse ponto, iremos precisar importar a biblioteca `Pandas` e usar os métodos `read_excel` e `read_csv` para realizar a leitura dos arquivos.


## Passo 02: Criando tabelas respectivas a cada loja

Como iremos precisar criar uma OnePage para cada uma das lojas e enviar, iremos criar tabelas referente a cada uma das lojas.

Para isso primeiro iremos executar um `merge` entre a tabela Vendas e a tabela Lojas, e depois iremos usar um laço for para poder criar as respectivas tabelas.

Após o `merge`, criamos um laço `for` para criar um dicionário onde a chave corresponderia ao nome da loja e o valor é o DataFrame correspondente a essa loja.

## Passo 03: Definição do período

Aqui apenas determinamos o período em que iremos estar realizando as comparações.

## Passo 04: Salvando os arquivos na pasta Backup

Nessa etapa importamos a biblioteca `Pathlib` para conseguir realizar as manipulações dos arquivos dentro da nossa máquina.

Em seguida nós criamos o caminho para onde os arquivos irão.

Criamos uma lista que irá interagir com os arquivos presentes dentro da pasta de backup e depois aplicamos o laço for para criar as pastas (se não existir) e salvar os arquivos dentro delas. Nesse processo, criamos também o nome para os respectivos arquivos.

## Passo 05: Desenvolvimento dos indicadores

Aqui nós calculamos os indicadores das respectivas lojas para poder enviar para os gerentes. Calculamos o faturamento, quantidade de produtos vendidos e ticket médio, todos as métricas segmentadas por ano e dia.

Inserimos também os valores das metas que a empresa precisa atingir.


## Passo 06: Criação da estruturação do email







































