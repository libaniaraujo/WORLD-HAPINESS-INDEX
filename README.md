# WORLD HAPINESS INDEX (ÍNDICE MUNDIAL DA FELICIDADE)


<img src = "https://user-images.githubusercontent.com/94937578/173049146-3ccc434c-cc96-4fad-9f95-0f36ac5a6149.png" width="1000px" />
</div>


## 1. Resumo

- [<b>Código no Jupyter Notebook</b>]
- [<b>Dashboard no Power BI</b>]

## 2. Contexto:

O World Happiness Report (Relatório Mundial da Felicidade) é uma publicação da Sustainable Development Solutions Network (Rede de Soluções de Desenvolvimento Sustentável) alimentada pelos dados da Gallup World Poll.

Os dados são coletados de pessoas em mais de 150 países (em 2021 foram 156) e cada variável mensurada revela uma pontuação média ponderada por população numa escala de 0 a 10, que é monitorada com o passar do tempo e comparada com a de outros países. Atualmente, essas variáveis incluem: PIB per capita real, assistência social, expectativa de vida saudável, liberdade para fazer escolhas, generosidade e percepções de corrupção. Cada país também é comparado a um país hipotético chamado Distopia. Distopia representa as menores médias nacionais para cada variável chave e, juntamente com erros residuais, é usado como ponto de referência de regressão.

(Fonte: https://pt.wikipedia.org/wiki/Relat%C3%B3rio_Mundial_da_Felicidade)
  
## 3. Problema:

Propõe-se aqui realizar a análise dos dados disponibilizados pelo World Happiness Report para 2021, obtendo conclusões a partir disso sobre a felicidade dos indivíduos ao redor do mundo e os fatores que a influenciam. 

## 4. Planejamento da solução:

- <b>Passo 1:</b> Coletar os dados. 
- <b>Passo 2:</b> Descrever e limpar os dados.
- <b>Passo 3:</b> Realizar a análise exploratória dos dados e obter a partir disso algumas análises.
- <b>Passo 6:</b> Apresentar as análises em um dashboard no Power BI.

## 5. Dados:

<b>Os atributos apresentados no conjunto de dados do Relatório Mundial da Felicidade para o ano de 2021 são descritos na tabela abaixo:</b>

**Atributo** | **Descrição**
--- | --- 
`Country name` | Nome do país
`Regional indicator` | Indicador regional
`Ladder score` | Índice de Felicidade
`Standard error of ladder score` | Erro padrão do Índice de Felicidade
`upperwhisker` | Limite superior
`lowerwhisker` | Limite inferior
`Logged GDP per capita` | PIB per capita
`Social support` | Suporte social (ter alguém com quem contar em períodos de dificuldade)
`Healthy life expectancy` | Expectativa de vida saúdavel
`Freedom to make life choices` | Liberdade para fazer escolhas
`Generosity` | Generosidade
`Perceptions of corruption` | Percepção da corrupção
`Ladder score in Dystopia` | Índice de felicidade em Distopia
`Explained by: Log GDP per capita` | O quanto do índice de felicidade é explicado pelo PIB per capita
`Explained by: Social support` | O quanto do índice de felicidade é explicado pelo suporte social
`Explained by: Healthy life expectancy` | O quanto do índice de felicidade é explicado pela expectativa de vida saúdavel
`Explained by: Freedom to make life choices` | O quanto do índice de felicidade é explicado pela liberdade de fazer escolhas
`Explained by: Generosity` | O quanto do índice de felicidade é explicado pela generosidade
`Explained by: Perceptions of corruption` | O quanto do índice de felicidade é explicado pela percepção de corrupção
`Dystopia + residual` | Distopia + resíduo

## 6. Principais resultados:

<b>Análises realizadas a partir dos dados:</b>

- Em 2021, os 10 países com **maior** Índice de Felicidade foram:

**País** | **Índice de Felicidade**
--- | --- 
`Finlândia` | 7,842
`Dinamarca` | 7,620
`Suíça` | 7,571
`Islândia` | 7,554
`Países Baixos` | 7,464
`Noruega` | 7,392
`Suécia` | 7,363
`Luxemburgo` | 7,324
`Nova Zelândia` | 7,277
`Austria`| 7,268

- Em 2021, os 10 países com **menor** Índice de Felicidade foram:

**País** | **Índice de Felicidade**
--- | --- 
`Burundi` | 3,775
`Iémen` | 3,658
`Tanzânia` | 3,623
`Haiti` | 3,615
`Malawi` | 3,600
`Lesoto` | 3,512
`Botsuana` | 3,467
`Ruanda` | 3,415
`Zimbábue` | 3,145
`Afeganistão` | 2,523

- O Índice de Felicidade médio por região é:


**Região** | **Índice de Felicidade**
--- | --- 
`América do Norte, Austrália e Nova Zelândia` | 7,128
`Europa Ocidental` | 6,915
`Europa Central e Oriental` | 5,985
`América Latina e Caribe` | 5,908
`Leste Asiático` | 5,810
`Comunidade de Estados Independentes` | 5,467
`Sudeste Asiático` | 5,407
`Oriente Médio e Norte da África` | 5,219
`África Subsaariana` | 4,494
`Sul da Ásia` | 4,418

- O Índice de Felicidade está diretamente correlacionado com o PIB per capita. Isto é, em geral os países que apresentaram maiores Índices de Felicidade são aqueles com maior PIB per capita.

## 7. Dashboard:

## 8. Referências:

- [Tutorial do canal do Youtube "Simplilearn".](https://www.youtube.com/watch?v=HNtEq-dK3C4&t=2334s)
- [Base de dados do World Hapiness Report disponível na plataforma do Kaggle.](https://www.kaggle.com/datasets/mathurinache/world-happiness-report?resource=download&select=2022.csv)

