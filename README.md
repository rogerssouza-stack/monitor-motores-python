# monitor-motores-python

### elaboração da documentação Técnica em markdown ###

## Entendimento do código ##
** O código funciona realizando a leitura dos motores de acordo com id, setor, temperatura e corrente fazendo destes campos obrigatórios e estabelecendo limites para temperatura, rpm, vibração e corrente, caso as informações não estejam preenchidas ou então forem menores que 0 o sistema da resposta como falsa senão da uma resposta como verdadeira. **

# Funcionamento após primeira analise #
* O código ele vai analisar as leituras válidas e colocar os motores com as leituras corretas em uma lista de motores válidos analisando se cada uma das inforções listadas ultrapassam ou não o limite e caso ultrapasse as informações são somadas em uma lista de alertas que vai determinar se ele esta normal, alerta ou critico e depois vai retorna essas informações. *

# Seguimento da explicação #
__* Após isso ele vai calcular as estatisticas calculando o total de motores,fazendo a média da temperatura, rpm, vibrações e potencia em kw alem de registrar o motor mais quente pelo id do mesmo

# Última parte da explicação #
_ Após isso ele vai exibir as informações em um painel onde vai mostrar o nome do sistema e a versão do mesmo mostrando data e hora e nesse mesmo painel vai ter a analise de alertas dos motores e após isso vai dar um resumo disso mostrado o numero de motores, a media de temperatura, corrente e potencia alem de mostrar a maior temperatura e vai exibir os motores válidos _