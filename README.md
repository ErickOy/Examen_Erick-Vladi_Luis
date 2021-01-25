# Examen_Erick-Vladi_Luis

Propósito: Tener un regado de jardin automático, con sus horas y días establecidos, y poder monitorearlo, así como los diferentes cambios de datos en la temperatura del agua y del ambiente así como la humedad del suelo y ambiental, se podrá reflejar en gráficas y servicio de api.
El proceso (¿Cómo se hace?)
 En general lo primero que se hace en proyecto integrador es estructurar la api, es trabajar con variables ver como esas variables van a estar guardadas en la base de datos para luego pasar directamente al archivo de json, ya después de esto se tiene que armar el circuito y programar en arduino lo que se le va mandar al json para que lo extraiga.
El resultado (¿Qué hace?)
 Lo que hace es monitorear el entorno de la planta toma datos como la temperatura de la planta, la humedad del suelo, la temperatura del agua con el que se va regar, una vez ya regados esos datos van directamente hacia la api ahí se van a gráficar y posteriormente el usuario puede estár monitoreando las condiciones de la planta.
 
 La velocidad: se refiere a los datos en movimiento por las constantes interconexiones que realizamos, es decir, a la rapidez en la que son creados, almacenados y procesados en tiempo real.
Visualización: nos referimos al modo en el que los datos son presentados. Una vez que los datos son procesados (los datos están en tablas y hojas de cálculo), necesitamos representarlos visualmente de manera que sean legibles y accesibles, para encontrar patrones y claves ocultas en el tema a investigar.

Volumen: los datos de nuestros sensores se toman en cada momento y se envían a la API
Veracidad: los datos al ser medidos por los sensores cuentan con una veracidad, ya que estos están creados para captar sus propias mediciones (humedad, temperatura, etc)
Valor: con los datos obtenidos se puede verificar el correcto funcionamiento del proyecto, y en caso de que los datos arrojados no estén siendo los habituales, se pueda solucionar, ejemplo que los datos de humedad sean bajos quiere decir que la tierra está cerca, por ende no hubo riego ese día o toda esa semana

Transformación: con los datos recopilados por cada sensor, serán Guardados y enviados a nuestra API, con la cual se redigiran a la página web para que se plasmen en graficas

