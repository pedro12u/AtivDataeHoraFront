# AtivDataeHoraFront

Este repositório contém um código HTML e JavaScript para calcular a diferença entre duas datas e horas. A interface permite que o usuário insira duas datas e horas em campos específicos, e o código calcula e exibe a data e hora maiores, a diferença entre elas em dias, horas e minutos, e a data e hora atuais.

Funcionalidades:

Entrada de data e hora: Dois campos de entrada do tipo datetime-local permitem que o usuário selecione datas e horas específicas.
Cálculo da diferença: O código JavaScript calcula a diferença absoluta em milissegundos entre as datas e horas informadas.
Conversão de unidades: A diferença em milissegundos é convertida e exibida em unidades de dias, horas e minutos.
Exibição de resultados: Os resultados são exibidos na página em elementos span com IDs específicos:
Maior Data: Mostra a data e hora maiores entre as duas entradas.
Intervalo de Tempo: Mostra a diferença entre as datas e horas em dias, horas e minutos formatados.
Data Atual: Mostra a data e hora atual no momento da execução do cálculo.
Botão de ação: Um botão com o texto "Mostrar Resultados" aciona a função JavaScript para calcular e exibir os resultados.
Como usar:

Abra o arquivo index.html em um navegador web.
Insira duas datas e horas nos campos de entrada.
Clique no botão "Mostrar Resultados".
Os resultados da diferença entre as datas e horas, a data e hora maiores e a data e hora atual serão exibidos na página.
Observações:

O código assume que as datas e horas estão no mesmo fuso horário. Se as datas e horas estiverem em fusos horários diferentes, você precisará ajustar o código para levar isso em consideração.
O código pode ser adaptado para calcular a diferença entre datas e horas em diferentes formatos. Por exemplo, você pode calcular a diferença entre datas apenas (sem horas), ou entre horas apenas (sem datas).
