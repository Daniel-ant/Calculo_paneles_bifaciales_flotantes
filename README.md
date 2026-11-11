# Calculo_paneles_bifaciales_flotantes
Herramienta de cálculo energético y económico de paneles solares bifaciales flotantes y comparación con su equivalente en tierra.
Se recomienda ejecutar en Google Colab con el acceso que ya incorpora el código, ya que ha sido desarrollado para su ejecución sin instalación.
Handle a la memoria completa del TFM que se desarrolló junto al proyecto: http://hdl.handle.net/10366/172186
------------------------------------------------------------------------------------------------------
La energía solar fotovoltaica flotante (FPV) constituye una solución emergente frente a las
limitaciones de uso del suelo de la fotovoltaica convencional, con la ventaja añadida del efecto
refrigerante del agua sobre los módulos. Pese a su creciente interés, la falta de herramientas de
cálculo específicas que integren las particularidades del FPV, especialmente cuando se combina
con tecnología bifacial, dificulta evaluar sus ventajas reales. Este trabajo presenta el desarrollo
de una herramienta de simulación, implementada en Python con la librería pvlib y ejecutable en
Google Colab mediante una interfaz gráfica accesible, capaz de modelar el comportamiento
energético y económico de una instalación bifacial flotante y compararla con su equivalente en
tierra. El modelo integra el cálculo de la irradiancia bifacial, dos modelos de temperatura de
célula en tierra y otro en agua, el modelo de diodo simple resuelto por Newton-Raphson y el
cálculo del coste nivelado de la energía (LCOE). La herramienta se valida sobre un caso de estudio
real que es el embalse de Las Cogotas (Ávila), con un módulo bifacial de 520 W. Los resultados
muestran que, a igualdad de condiciones, la instalación en tierra produce más energía que la
flotante (408,5 MWh anuales con el modelo de Faiman frente a 383,2 MWh de la flotante, un
6,6 % más) y presenta un LCOE inferior (35,89 frente a 38,25 €/MWh), debido a que el mayor
albedo del suelo proporciona una ganancia bifacial trasera muy superior a la del agua. No
obstante, la instalación flotante mantiene la célula notablemente más fría (media anual de 21,5
°C frente a 26,2 °C en tierra), lo que confirma el efecto refrigerante del agua. Se concluye que la
ventaja del FPV bifacial no radica en un mayor rendimiento energético bruto, que está limitado
por el bajo albedo del agua, sino en el efecto refrigerante y en sus beneficios no energéticos
(aprovechamiento de superficies infrautilizadas, reducción de la evaporación), y que las
correlaciones de diseño propias de la fotovoltaica terrestre no son directamente trasladables a
este tipo de instalaciones.
