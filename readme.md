# Análise de dados com Pandas
# Estudando as empresas listadas na bolsa de valores B3

Este projeto tem o objetivo de fazer uma análise exploratória de dados, das empresas listadas na [B3](https://www.b3.com.br/pt_br/b3/institucional/quem-somos/). Utilizando métodos e recursos e técnicas de Análise de Dados com a Linguagem Python. os dados para análise foram extraídos do portal [Fundamentus](https://www.fundamentus.com.br/resultado.php) no dia 01/02/2024.


### :computer: Ambiente de Execução
Para executar o arquivo principal `main.ipynb`, você pode baixar o arquivo e importar num ambiente com suporte para [Jupyter Notebook](https://jupyter.org/about), como no [Google Colaboratory](https://colab.google/).

#### Principais Tecnologias 
* Pandas
* Matplotlib
* Seaborn
* yfinance


### :one: Etapa

1. :white_check_mark: Importar dados da bolsa
2. :white_check_mark: Visualizar as primeiras 7 linhas e as últimns 5 do DataFrame.
3. :white_check_mark: Conferir a quantidade de linhas e colunas do DataFrame
4. :white_check_mark: Explorar as colunas do DataFrame e analisar tipos dos dados presentes em cada coluna
5. :white_check_mark: Limpar/interpolar dados ausentes da base de dados
6. :white_check_mark: Transformar os dados numéricos float
7. :white_check_mark: Calcular estatísticas descritivas básicas das principais colunas numéricas do DataFrame

### :two: Etapa

1. :white_check_mark: Calcular a média do [*DIVIDEND YIELD*](https://pt.wikipedia.org/wiki/Dividend_yield) das empresas com [*MARGEM LÍQUIDA*](https://vexpenses.com.br/blog/margem-liquida/#:~:text=A%20margem%20l%C3%ADquida%20%C3%A9%20um,ajuda%20a%20tomar%20melhores%20decis%C3%B5es.) ACIMA DE 10%
2. :white_check_mark: Verificar percentual de empresas que tem [P/L](https://www.suno.com.br/artigos/preco-lucro/) acima de 4.
3. :white_check_mark: Analisar quais empresas tem [*LIQUIDEZ CORRENTE*](https://riconnect.rico.com.vc/blog/liquidez-corrente/?psafe_param=1&campaignid=316171546&adgroupid=55392294370&feeditemid=&targetid=aud-437331571629:dsa-19959388920&loc_interest_ms=&loc_physical_ms=9101429&matchtype=&network=g&device=c&devicemodel=&ifmobile=&ifmobile=0&ifsearch=1&ifsearch=&ifcontent=0&ifcontent=&creative=340508776298&keyword=&placement=&target=&utm_source=google&utm_medium=cpc&utm_term=&utm_campaign=GGLE_PESQ_DSA&hsa_tgt=aud-437331571629:dsa-19959388920&hsa_net=adwords&hsa_kw=&hsa_grp=55392294370&hsa_acc=7134496929&hsa_ver=3&hsa_ad=340508776298&hsa_cam=316171546&hsa_mt=&hsa_src=g&gclid=Cj0KCQiA5-uuBhDzARIsAAa21T88L4A5A3NrG-TMouQqHIizP6zG25V-Qrq-cnPD2WpAfwoMQFVXYvcaAulBEALw_wcB) acima de 1, TEM [*ROE*](https://riconnect.rico.com.vc/blog/roe/?campaignid=316171546&adgroupid=55392294370&feeditemid=&targetid=aud-544301642320:dsa-19959388920&loc_interest_ms=&loc_physical_ms=9101429&matchtype=&network=g&device=c&devicemodel=&ifmobile=&ifmobile=0&ifsearch=1&ifsearch=&ifcontent=0&ifcontent=&creative=340508776298&keyword=&placement=&target=&utm_source=google&utm_medium=cpc&utm_term=&utm_campaign=GGLE_PESQ_DSA&hsa_tgt=aud-544301642320:dsa-19959388920&hsa_net=adwords&hsa_kw=&hsa_grp=55392294370&hsa_acc=7134496929&hsa_ver=3&hsa_ad=340508776298&hsa_cam=316171546&hsa_mt=&hsa_src=g&gclid=Cj0KCQiA5-uuBhDzARIsAAa21T-7OsQlowYf_FvTizFy6_7n9YP3Q1J4n5Vp3TjbzkoywnhWLKZJMgUaAs0VEALw_wcB) acima da média das empreas e *DIVIDEND YIELD* maior ou igual a 6.
4. :white_check_mark: Criar Gráfico de Barra Horizontal com as 5 primeiras empresas, resultantes da análise anterior
