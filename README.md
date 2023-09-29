# Projeto Análise dos Dados da PRF - Acidentes de trânsito

<img src="https://images.unsplash.com/photo-1530685932526-48ec92998eaa?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Transito"> 

## Dados Abertos da PRF
A elaboração do Plano de [Dados Abertos da PRF](https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-da-prf) vem ao encontro do disposto na Lei de Acesso à Informação (LAI), na Instrução Normativa SLTI nº 4, de 13 de abril de 2012 (que institui a Infraestrutura Nacional de Dados Abertos), no Decreto nº 8.777, de 11 de maio de 2016 (que institui a Política de Dados Abertos no Executivo Federal), bem como dos compromissos assumidos pelo Brasil no âmbito do Plano de Ação Nacional de Governo Aberto.

Por meio desse site é possível baixar de 2007 até 2023 (presente). Os arquivos usados nessa análise estão estão compactados (zipados) neste [link](https://drive.google.com/file/d/1-Yk6TV00CH3PixTkKmkoUJQsNiUc5xLm/view).

## Objetivo
Objetivos e quais os problemas a serem resolvidos
O objetivo desse projeto é analisar os dados a fim de obter insights sobre os acidentes e responder perguntas. Para melhor nos guiar na análise, formulei o problema no seguinte conjunto de questões, para que possamos explorá-lo com maior profundidade:

* Qual a maior causa de acidentes?
* Qual dia da semana há mais acidentes Qual dia da semana há mais acidentes? E em qual fase do dia?
* Qual tipo de acidente ocorre com mais frequência?
* Qual o top 5 de municípios com mais ocorrência de acidentes? E os estados?
* Em quais rodovias os acidentes são mais frequentes?

## Ferramentas
  * Python
  * Google Colab
  * Matplotlib, Seaborn
  * Limpeza dos dados
  * Pandas

## Competências
  * Limpeza dos dados
  * Análise Exploratória de Dados
  * Visualização de Dados

## Insights obtidos
### Q1 -  Qual a maior causa de acidentes?
![q1](https://github.com/silvaelaine/data-analysis-PRF-01/assets/103846225/596033e8-0ec2-4a76-832e-3f777706414b) 
Reação tardia ou ineficiente é a maior causa de acidentes, o que nos faz pensar em como as pessoas são distraídas durante o trânsito. Seja por causa até mesmo de celulares ou até conversas com outros ocupantes do carro.

### Q2 - Qual dia da semana há mais acidentes? E em qual fase do dia?
![q2](https://github.com/silvaelaine/data-analysis-PRF-01/assets/103846225/07b0c073-986b-454a-b348-ccfd83667ad5)
O dia da semana que mais ocorre acidentes é domingo e a fase do dia é em pleno dia, o que nos faz pensar que esses acidentes geralmente ocorrem quando as pessoas estão indo passear, já que é fim de semana, é consequentemente há mais trânsito.

### Q3 - Qual tipo de acidente ocorre com mais frequência?
![q3](https://github.com/silvaelaine/data-analysis-PRF-01/assets/103846225/781cfaf0-dbb4-4aa0-95a0-4c7e9583c986)
Colisão traseira é o tipo de acidente que ocorre com mais frequência. Foi esse o motivo do acidente envolvendo o maior número de pessoas do dataset (73) no estado de Goiás.

### Q4 - Qual o top 5 de municípios com mais ocorrência de acidentes? E os estados?
![q4](https://github.com/silvaelaine/data-analysis-PRF-01/assets/103846225/c6a24c27-95e0-4cff-a4c1-8badab30c63c)

### Q5 - Em quais rodovias os acidentes são mais frequentes?
![q5](https://github.com/silvaelaine/data-analysis-PRF-01/assets/103846225/4a1bdc78-cb8c-4cbc-a4e7-77ccd97f0ab3)
A BR-101 tem início no município de Touros, no estado do Rio Grande do Norte, e termina em São José do Norte, no Rio Grande do Sul. Também é localizada ao lado da BR-116, que encontra-se em segundo lugar no ranking das que ocorrem acidentes como mostra o gráfico acima.

### Conclusão
É de extrema importância sempre frizar o quão importante é ser atento no trânsito, afinal, tudo pode acontecer. Estar atento com o que acontece dentro do seu veículo e fora dele é essencial para evitarmos tantos acidentes e consequentemente tantas mortes.

  
  
  
