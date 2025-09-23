Lucas Kenzo Nishiwaki - RM561325

INSTRUÇÕES DA ENTREGA:
A atividade pode ser desenvolvida em grupo.

Apenas um integrante submete o arquivo.

Enviar apenas o link do repositório. Não envie arquivos .txt ou .pdf.

Dataset Solar Radiation Prediction

Esse dataset é um conjunto de dados meteorológicos coletados pela estação HI-SEAS (no Havaí), durante setembro a dezembro de 2016,
e a ideia é usá-lo para prever radiação solar — ou seja, estimar quanta energia solar estará disponível para geração elétrica em determinado momento.

 Estrutura do dataset
Colunas principais:
Solar_radiation (variável alvo, em W/m²)
Temperature (°F)
Humidity (%)
Barometric pressure (inHg)
Wind direction (°)
Wind speed (mph)
Sunrise e Sunset (hora local)
Date e Time (timestamp UNIX e data legível)

 Características
Período: setembro a dezembro de 2016 (4 meses).
Granularidade: registros a cada poucos minutos.


Dataset Wind Turbine Scada Dataset

Esse dataset Wind Turbine SCADA (2018, Turquia) traz medições de uma turbina eólica real ao longo de quase um ano, com intervalos de 10 minutos. 
Ele é muito usado para estudos de modelagem de geração de energia, manutenção preditiva e otimização de turbinas.

 Estrutura do dataset
Date/Time → registro temporal (intervalos de 10 minutos).
LV ActivePower (kW) → potência real gerada pela turbina.
Wind Speed (m/s) → velocidade do vento na altura do hub.
Theoretical_Power_Curve (kW) → potência teórica que a turbina deveria gerar, dado a velocidade do vento.
Wind Direction (°) → direção do vento na altura do hub.

  Características
Período: janeiro a dezembro de 2018 (12 meses).
Granularidade: registros a cada 10 minutos.
