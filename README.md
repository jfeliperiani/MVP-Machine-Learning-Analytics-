# MVP-Machine-Learning-Analytics-
MVP (Minimum Viable Product) Sprint da Disciplina de Machine Learning &amp; Analytics da PUC-Rio

Pontifícia Universidade Católica do Rio de Janeiro / Pós-Graduação em Ciência de Dados e Analytics / Disciplina: Sprint -  Machine Learning & Analytics (40530010056_20260_01) Matrícula: 4052025001401

### *MVP - (Minimum Viable Product)*
## Internações Hospitalares no Setor Privado Suplementar de Saúde no Estado de São Paulo em dezembro de 2024  

### Objetivo
O objetivo deste MVP é construir e avaliar modelos de Machine Learning para prever se a internação hospitalar terá um dia de tempo de permanência hospitalar ou se terá mais de um dia de tempo de permanência hospitalar. Foram consideras características dos pacientes e da internação, comparando uma abordagem baseline com modelos candidatos e discutindo suas limitações. 

### Conjunto de dados (SP_202412_HOSP_CONS.csv)

O conjunto de dados é disponibilizado pela Agência Nacional de Saúde Suplementar – ANS no Portal de Dados Abertos - PDA (https://www.gov.br/ans/pt-br/acesso-a-informacao/perfil-do-setor/dados-abertos-1).

Foi selecionada a competência mais recente disponível (dezembro de 2024) e a Unidade da Federação com maior quantidade de internações hospitalares (São Paulo) (https://dadosabertos.ans.gov.br/FTP/PDA/TISS/HOSPITALAR/2024/SP/SP_202412_HOSP_CONS.zip).

O conjunto de dados foi selecionado para o presente trabalho por possuir diferentes características, possibilitando que sejam exploradas diferentes condições, que podem estar associadas ao tempo de permanância na internação hospitalar.

Considerando que o Portal de Dados Abertos observa parâmetros legais da Lei Geral de Proteção de Dados, não há restrições relativas à disponibilização do conjunto de dados e de suas análises decorrentes.


### Notebook do Google Colab, composto por: 
- Descrição do Problema
- Hipóteses do Problema
- Tipo do Problema
- Seleção de Dados
- Atributos do Dataset
- Importação das bibliotecas necessárias e carga de dados
- Análise de Dados Exploratória - EDA
- Considerações sobre pré-processamento de dados
- Respostas 
- Conclusão


### Síntese
O presente trabalho buscou construir e avaliar modelos de Machine Learning para prever a probabilidade de uma internação hospitalar ser de 'longa permanência' (mais de um dia), utilizando as seguintes características dos pacientes: sexo, faixa etária e tipo de doença (diferenecianso as principais doenças crônicas não transimissíveis das demais doenças crônicas ou agudas). Após a exploração de diversos modelos candidatos e a otimização de hiperparâmetros, o RandomForestClassifier Otimizado foi identificada como a melhor solução entre as alternativas.


### Como Executar
Acesse o notebook no Google Colab

Execute todas as células em ordem: Runtime → Executar todas

Nenhuma instalação adicional é necessária — todas as bibliotecas utilizadas estão disponíveis por padrão no Colab
