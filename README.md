# Poste Digital - Iluminação Pública do Recife
<img width="1907" height="803" alt="image" src="https://github.com/user-attachments/assets/7820decc-1114-4783-8208-7dc269db5d49" />


Postes- iluminação pública do Recife
Histórias baseadas nos 3Cs
1. Distribuição de postes por bairro
Card: Como gestor, quero saber quantos postes existem por bairro para planejar investimentos equilibrados.
 Conversation: Contar postes agrupados por bairro.
 Confirmation: Quando gerar relatório, deve exibir ranking de bairros com total de postes.

2. Tipos de luminárias instaladas
Card: Como analista, quero conhecer a distribuição de tipos de luminárias (LED, vapor, etc.) para avaliar modernização.
 Conversation: Agrupar por tipo_luminaria.
 Confirmation: Relatório mostra o percentual de cada tipo no município.

3. Potência média por bairro
Card: Como setor estratégico, quero calcular a potência média das luminárias por bairro para identificar áreas de maior gasto energético.
 Conversation: Calcular média de potencia por bairro.
 Confirmation: Dashboard exibe bairros com maior e menor potência média.

4. Postes fora de funcionamento
Card: Como coordenador, quero identificar a quantidade de postes inativos por bairro para priorizar manutenção.
 Conversation: Filtrar situacao = inativo.
 Confirmation: Relatório lista bairros com total de postes inativos.

5. Idade/ano de instalação dos postes
Card: Como gestor, quero analisar o ano de referência de cada poste para planejar substituições.
 Conversation: Agrupar por ano_referencia.
 Confirmation: Gráfico mostra número de postes instalados por ano.

6. Cobertura por região administrativa
Card: Como planejador urbano, quero saber a distribuição de postes por região administrativa para avaliar cobertura da iluminação.
 Conversation: Agregar postes por regiao.
 Confirmation: Dashboard exibe mapa com densidade de postes por região.

7. Comparar LED vs não LED
Card: Como gestor, quero saber a proporção de postes já convertidos para LED em relação ao total.
 Conversation: Comparar tipo_luminaria = LED contra os demais.
 Confirmation: Indicador exibe percentual de postes LED.

8. Consumo estimado de energia
Card: Como setor estratégico, quero estimar o consumo energético dos postes para prever custos.
 Conversation: Calcular soma de potencia × horas médias.
 Confirmation: Relatório exibe consumo mensal estimado por bairro.

9. Mapa de falhas recorrentes
Card: Como coordenador, quero visualizar em mapa os locais com maior incidência de falhas registradas para agir preventivamente.
 Conversation: Filtrar ocorrências/tickets vinculados a poste_id.
 Confirmation: Mapa exibe clusters de falhas por área.

10. Planejamento de expansão
Card: Como gestor estratégico, quero identificar áreas com baixa densidade de postes para planejar novas instalações.
 Conversation: Cruzar densidade de postes por km² com população/bairros.
 Confirmation: Dashboard lista bairros/regiões com menor densidade de postes.



