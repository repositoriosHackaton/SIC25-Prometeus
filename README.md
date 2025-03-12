# Modelo GuardIA - Prototipo 1

El proyecto GuardIA ha sido desarrollado con el objetivo de asistir a empresas, organismos públicos y otras entidades en el ámbito de la vigilancia mediante cámaras de seguridad. Esta inteligencia artificial es capaz de detectar pistolas con la intención de notificar de manera inmediata, evitando así cualquier percance potencial. Actualmente, estamos trabajando para ampliar sus capacidades, de modo que pueda identificar cualquier tipo de arma en el menor tiempo posible.

Divido normalmente todos estos trabajos en varios archivos, para llevar una secuencia

## Parte 1: 

Realizo busqueda de imagenes de armas para clasificarlas, saco las imagenes de internet y de videos para conseguir los datos que necesito, el etiquetado se hace en la pagina de roboflow, en el caso de los videos lo que se hace es dividirlo en frames y etiquetar los frames, se toman los frames que tienen una distancia de 5 para evitar coincidencias

## Parte 2: 

Realizo el entrenamiento de la IA, entre varios hiperparametros se decidio que lo mejor podrian ser los indicados alli, el modelo escogido fue el yolov8m, el dataset se baja directo de la pagina de roboflow, 

## Parte 3: 

Realizamos una prueba clasificando un video, para esto defragmentamos el video en varios frames, predecimos y luego unimos todo
