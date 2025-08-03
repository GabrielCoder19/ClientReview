# Analíse de sentimento com Azure Language Studio
# Atividade Proposta Pela DIO.

Utilizando da tecnologia Language studio da Azure, extrai algumas avaliações do google de uma empresa e utilizei o Azure para analisar
se determinada avaliação foi positiva ou negativa.

Após a classificação gerada pela API, gerei um arquivo JSON com a resposta obtida.

Em seguida com auxilio do CHATGPT, Criei uma tabela para separar por nome de colaborador e setor o qual está inserido para facilitar a visualização 

codigo aplicação Azure Utilizada https://sentimentalanalisys.cognitiveservices.azure.com/
# Análise de Sentimentos por Nome

## 🧑‍💼 Fernanda

| Sentença                                                               | Sentimento | Avaliação | Confiança |
|------------------------------------------------------------------------|------------|-----------|-----------|
| Fernanda excelente atendente me atendeu super bem.                    | Positive   | excelente | 1.00      |

---

## 🧑‍🔧 Gabriel (Técnico)

| Sentença                                                                                                                                       | Sentimento | Avaliação | Confiança |
|------------------------------------------------------------------------------------------------------------------------------------------------|------------|-----------|-----------|
| Gabriel o técnico excelente deu um problema no conduíte [...] ele não desistiu até conseguir deixar conectado a internet na minha casa [...] | Positive   | excelente | 1.00      |
| Gabriel Cardoso                                                                                                                                | Neutral    | —         | 0.97      |

---

## 🧑‍💼 Evelyn

| Sentença                                                                                                               | Sentimento | Avaliação    | Confiança |
|------------------------------------------------------------------------------------------------------------------------|------------|--------------|-----------|
| Fui muito bem atendido pela Evelyn, muito prestativa, super recomendo, Obrigado Evelyn 🤗 Renato aqui!                | Positive   | bem atendido | 1.00      |
|                                                                                                                        |            | prestativa   | 1.00      |
|                                                                                                                        |            | recomendo    | 1.00      |

---

## 🙋‍♀️ Geral / Sem Nome Específico

| Sentença                          | Sentimento | Avaliação | Confiança |
|----------------------------------|------------|-----------|-----------|
| Obrigada pela atenção Excelente!!! | Positive   | —         | 1.00      |
| Um forte abraço.                 | Positive   | —         | 0.99      |

