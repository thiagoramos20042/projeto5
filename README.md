![alt text](https://fdr.com.br/wp-content/uploads/2020/12/imovel-financiamento-aluguel-1593808631898_v2_750x421.jpg)

# Projeto módulo 5 - Crédito para Financiamento de Imóveis

# Contextualização
A PyCoders Ltda., cada vez mais especializada no mundo da Inteligência Artificial e Ciência de Dados, foi procurada por uma fintech para desenvolver um projeto de concessão de crédito para imóveis. Nesse projeto, espera-se a criação de valor que discrimine ao máximo os bons pagadores dos maus pagadores.

Para isso, foi disponibilizada uma base de dados com milhares de casos de empréstimos do passado com diversas características dos clientes.

Entrega: um modelo com a melhor performance possível.

Métrica de performance (inicialmente proposta): ROC-AUC.

# Base de Dados
Serão utilizadas bases de dados com informações cadastrais, histórico de crédito e balanços financeiros de diversos clientes.

O conjunto de dados está dividido em treino e teste, todos no formato csv.

Toda a modelagem, validação e avaliação deve ser feita em cima do conjunto de treino, subdividindo tal base como a squad achar melhor.

Existe também os das variáveis explicativas, para ajudar no desenvolvimento do projeto.

Serão necessários diversos cruzamentos e vocês estão livres para usar os dados da maneira que acharem mais conveniente.

Clique aqui pra baixar os dados (eles estão disponiveis no arquivo zipado credito-imoveis.zip).

# Regras de Entrega
Deve ser entregue um arquivo csv com as predições para a base de teste.

Essa base deverá ser um Data Frame com duas colunas: a primeira sendo o SK_ID_CURR e a segunda a probabilidade de inadimplência.

# IMPORTANTE!
Entregar as predições com a probabilidade da inadimplência ocorrer, não a classe predita.

Além do arquivo com as predições, claro, entreguem também o notebook com o código utilizado. É importante que ele tenha:

(i) a análise exploratória e construção das variáveis explicativas;

(ii) a análise de modelagem, mostrando o processo das avaliações dos modelos e os motivos das decisões tomadas sobre qual modelo usar.

# Dicas
Explorar o conceito das variáveis: existe risco de imagem uma empresa utilizar variável de sexo para determinar risco de crédito? Vale a pena trazer a variável para o modelo?

Criar novas variáveis usando as variáveis que já estão na base: criatividade!
