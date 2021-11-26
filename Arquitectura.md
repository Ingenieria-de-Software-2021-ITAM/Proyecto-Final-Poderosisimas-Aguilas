## Arquitectura
Para nuestro proyecto decimios usar una mezcla de arquitecturas de microservicios y eventos

| Arquitectura| Microservicios | Eventos|
| ----------- |-----------|-----------|
| Agilidad   |✓|✓|
| Despliegue  |✓|✓|
| Pruebas      |✓|X|
| Desempeño      |X|✓|
| Escalabilidad      |✓|✓|
| Facil de desarrollar |✓|X|


Decidimos usar estas dos formas de arquitectura porque son dos que mejor se adaptan entre ellas y a nuestro trabajo
Como nuestro proyecto no tendra cambios urgentes (en el mundo ideal) es mejor usar estas arquitecturas puesto que no tendremos prisa si nos organizamos bien.
Al ser una muy lenta y la otra muy rapida, dividimos lo que se va a mostrar en dos capas: prioritario y secundario
Lo prioritario se desarrollara dentro de la capa de eventos, ya que esto es fundamental se mueste rapido para asi no perder el interes del publico.
Y lo secundario ira en la arquitectura de microservicios, como esta seraa usada para cosas que no tienen que atraer a gente, se pueden tomar su tiempo sin verse afectada la opinion de las personas.
Nuestra fase principal estara dentro de la arquitectura de eventos.
