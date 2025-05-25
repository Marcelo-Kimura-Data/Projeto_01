# Projeto_01: Automação de Indicadores

### Objetivo: Treinar e criar um Projeto Completo que envolva a automatização de um processo feito no computador

### Descrição:

Imagine que você trabalha em uma grande rede de lojas de roupa com 25 lojas espalhadas por todo o Brasil.

Todo dia, pela manhã, a equipe de análise de dados calcula os chamados One Pages e envia para o gerente de cada loja o OnePage da sua loja, bem como todas as informações usadas no cálculo dos indicadores.

Um One Page é um resumo muito simples e direto ao ponto, usado pela equipe de gerência de loja para saber os principais indicadores de cada loja e permitir em 1 página (daí o nome OnePage) tanto a comparação entre diferentes lojas, quanto quais indicadores aquela loja conseguiu cumprir naquele dia ou não.

Devemos criar um processo da forma mais automática possível para calcular o OnePage de cada loja e enviar um email para o gerente de cada loja com o seu OnePage no corpo do e-mail e também o arquivo completo com os dados da sua respectiva loja em anexo.

Ex: O e-mail a ser enviado para o Gerente da Loja A deve ser como exemplo

### Passo 01: Importação dos arquivos para o DataFrame

Iremos primeiramente realizar a importação dos arquivos para o formato de DataFrame (Pandas) para conseguir realizar as tratativas.

Nesse ponto, iremos precisar importar a biblioteca `Pandas` e usar os métodos `read_excel` e `read_csv` para realizar a leitura dos arquivos.

