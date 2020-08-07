# Relatório de casos confirmados e óbitos por covid-19 na Bahia

Este repostório tem por finalidade guardar scripts e dados para construção de relatórios diários com uso do Rmarkdown.

Todos os gráficos foram gerados utilizando os microdados públicos dos casos notificados de covid-19 na Bahia, disponibilizado diariamente pela Secretaria de Saúde da Bahia - SESAB, no portal https://bi.saude.ba.gov.br/transparencia/ desde o dia 15 de julho de 2020. 

Os scripts, escritos na linguagem **R** e **Markdown** estão disponíveis no repositório: https://github.com/jonates/report_covid19_BA. Este repositório é público. O autor aguarda que surjam contribuições tanto de ajustes e melhorias nos scripts, quanto acréscimos de novas visualizações.

Como qualquer conjunto de dados, existem erros em alguns registros do conjunto de dados, bem como valores ausentes. Assim, na ausência da data do início do sintoma foi considerado a data do exame, e, na ausência dessas 2 datas, foi considerada a data da notificação.

A semana epidemiológica foi definida com a função EpiWeek da biblioteca Epitools.  

Vale ressaltar que este arquivo parte de iniciativa acadêmica, passível de ajustes, e, não é documento oficial do Governo da Bahia.