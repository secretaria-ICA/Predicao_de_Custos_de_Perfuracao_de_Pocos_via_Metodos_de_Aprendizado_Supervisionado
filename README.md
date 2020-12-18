# Predição de Custos de Perfuração de Poços via Métodos de Aprendizado Supervisionado

#### Aluno: [Manoela Teixeira Lopes](https://github.com/ManoelaLopes).
#### Orientadora: [Manoela Kohler](https://github.com/manoelakohler).

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

---

### Resumo

Esta monografia visa apresentar a aplicação de métodos de aprendizado supervisionado à predição de custos de perfuração em poços e representa uma atualização de estudo anterior desenvolvido por equipe técnica da Petrobras. O uso de aprendizado de máquina para o processo de orçamentação apresenta uma série de vantagens, entre elas, a redução de HH envolvido, melhoria no grau de assertividade do custo estimado, celeridade na resposta e possibilidade de testar diferentes cenários de projeto em menor tempo. O estudo de caso apresentado pode ser classificado como um problema de regressão cujo rótulo numérico é o custo da perfuração, o qual é avaliado em moeda local (reais- BRL). Foram testados 7 diferentes métodos aplicáveis a problemas de regressão usando a plataforma RapidMiner e considerando duas formas de validação dos modelos: segmentação da base em treino e teste em proporção 85% – 15% e validação cruzada. O primeiro caso assumindo a situação de uso de duração planejada ou observada de poços como atributo para a validação. E o segundo caso, empregando a validação cruzada (leave one out) para contornar a característica da base de dados que contém baixo número de registros. No que tange às variáveis preditoras, foram considerados atributos gerais do projeto de perfuração dos poços. Como estudo adicional, foi avaliada a influência de indicadores de mercado sobre os custos totais. Em etapa subsequente, os métodos que se mostraram mais promissores em termos das métricas de validação foram reavaliados em seus hiperparâmetros via programação em Python através da aplicação jupyter notebook. Como o modelo anteriormente desenvolvido pela Petrobras já havia contemplado o uso de Random Forest e LightGBM, foram criados dois modelos adicionais com regressão linear e redes neurais artificiais. O modelo em redes neurais artificiais apresentou o melhor resultado considerando a predição de custos em reais.

---

Matrícula: 192.190.068

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
