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
- <b>Passo 3:</b> Realizar a análise exploratória dos dados e realizar algumas análises a partir disso.
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
<img src = "https://user-images.githubusercontent.com/94937578/174214049-64c7e0f9-d772-48cb-a112-51de60577dda.png" width="250px" />
</div>

- Em 2021, os 10 países com **menor** Índice de Felicidade foram:

<img src = "https://user-images.githubusercontent.com/94937578/174214438-31c80c72-7f97-430b-afc6-587d118366c1.png" width="250px" />
</div>

- O Índice de Felicidade médio por região é:

<img src = "https://user-images.githubusercontent.com/94937578/174213652-c85fe408-1d3d-478c-a9ce-b50589947a6e.png" width="400px" />
</div>

- Pode-se observar ainda a correlação entre o Índice de Felicidade e os demais indicodores disponibilizados para cada país:

<img src = "https://user-images.githubusercontent.com/94937578/174214966-913db43e-d10c-4bef-9700-27fa6b3aa52b.png" width="500px" />
</div>

- O Índice de Felicidade mostrou-se diretamente correlacionado com o PIB per capita. Isto é, em geral os países que apresentaram maior Índice de Felicidade são aqueles com maior PIB per capita.

<img src = "https://user-images.githubusercontent.com/94937578/174215443-f20d18d7-f88d-4b9e-99b3-c3c4ef6fee0e.png" width="500px" />
</div>

- Foram analisados ainda os indicadores por região:

<img src = "https://user-images.githubusercontent.com/94937578/174495122-d09ede08-bccc-4b42-bce9-41bb1179ebab.png" width="500px" />
</div>

<img src = "https://user-images.githubusercontent.com/94937578/174215712-305d2e17-8df5-4feb-a001-ca9324f8f682.png" width="500px" />
</div>


## 7. Dashboard:

<img src = "https://user-images.githubusercontent.com/94937578/174494614-a5540a3f-ce33-4278-8f1a-9fad173570f2.png" width="800px" />
</div>

<img src = "https://user-images.githubusercontent.com/94937578/174494671-120ff6f1-0c3f-4b6b-a2ca-345e455bea97.png" width="800px" />
</div>

<img src = "https://user-images.githubusercontent.com/94937578/174494713-74e3cfa4-157e-4e5c-8e6b-3229f0963bea.png" width="800px" />
</div>

<img src = "https://user-images.githubusercontent.com/94937578/174494758-a62e2ea7-3676-433b-bf3e-b310009ada3a.png" width="800px" />
</div>

<img src = "https://user-images.githubusercontent.com/94937578/174494789-bb10f402-8e14-41b5-bac0-a06f6f64a063.png" width="800px" />
</div>

## 8. Referências:

- [Tutorial do canal do Youtube "Simplilearn".](https://www.youtube.com/watch?v=HNtEq-dK3C4&t=2334s)
- [Base de dados do World Hapiness Report disponível na plataforma do Kaggle.](https://www.kaggle.com/datasets/mathurinache/world-happiness-report?resource=download&select=2022.csv)

