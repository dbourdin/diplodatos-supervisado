# diplodatos-supervisado
Repositorio que contiene solución propuesta para la competencia de Kaggle durante la materia de Aprendizaje Supervisado

## Instrucciones para correr el proyecto
Instalar Python 3.6 y pip:<br/>
`$ sudo apt-get install python3.6 python3-pip`


Se recomienda instalar también virtualenv para evitar instalar las dependencias a nivel de sistema:<br/>
`$ sudo python3.6 -m pip install virtualenv`

En el caso de utilizar virtualenv, crear un nuevo env y activarlo:<br/>
`$ virtualenv -p /usr/bin/python3 diplodatos-supervisado`<br/>
`$ source diplodatos-supervisado/bin/activate`

Instalar las dependencias indicadas en el archivo de requerimientos:<br/>
`$ python3.6 -m pip install -r requirements.txt`

Ejecutar jupyter notebook:<br/>
`$ jupyter notebook`

Ubicar el archivo baseline.ipynb dentro del directorio src y ejecutar el notebook
