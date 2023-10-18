# Análise exploratória: série temporal dos preços de combustíveis e de tributações estaduais (2018.1 a 2023.2)

**Projeto - Técnicas de Programação I**

Instrutores: Alex Lima e Maurício Sobrinho

**Equipe: Gabriel Miranda, Marcus Thadeu, Ruann Campos e Thiago Caveglion**

**O projeto como um todo tem como objetivos:**

* Analisar de forma exploratória a série histórica de preços de combustíveis no Brasil no período de 2018.1 a 2023.1;
* Analisar de forma exploratória a série histórica de arrecadações tributárias estaduais no mesmo período;
* Relacionar ambos datasets.

**Execução**

* Para rodar o arquivo localmente, certifique-se que a variável ```descompactar``` (no notebook *Análise_Exploratória_Combustível.ipynb*) e a variável ```rodando_localmente``` (no notebook *Análise_Exploratória_Tributação.ipynb*) esteja marcada como ```True```.
  * Outra forma é baixar os datasets diretamente do site dados.gov, como explicaremos a seguir, e coloca-los na pasta *datasets_combustivel*.
    
**Informações importantes sobre os dois notebooks do projeto:**

- Análise_Exploratória_Combustíveis.ipynb: notebook onde construímos a análise exploratória sobre os combustíveis.
  - Pasta datasets_combustível: onde está armazenado os datasets referentes aos preços dos combustíveis (não conseguimos realizar o upload desses arquivos aqui devido ao tamanho: cerca de 2 GB). Dados disponíveis em: https://www.gov.br/anp/pt-br/centrais-de-conteudo/dados-abertos/serie-historica-de-precos-de-combustiveis.
  - Pata datasets_combustível_comprimido: de forma alternativa, os notebooks podem ser executados baixando-se os datasets compactados nessa pasta e seguindo o que foi descrito acima na seção *Execução*.
  - Pasta IBGE_Aux: onde está armazenado o dataset auxiliar com os dados de geolocalização utilizado para a construção dos mapas na análise.
-  Análise_Exploratória_Tributação.ipynb: notebook onde construímos a análise exploratória sobre as tributações dos estados.
    - Dataset_Tributos.xls: dataset utilizado para aquisão de dados referentes às tributações. Dados disponíveis em: https://dados.gov.br/dados/conjuntos-dados/boletim-de-arrecadacao-dos-tributos-estaduais.
