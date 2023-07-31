## Instrucciones para instalar crear un entorno Python usando entornos venv

### Paso 1: Instalar Python

1. Abre una terminal, ubicate en el directorio que quieras instalar Python y ejecuta el siguiente comando para crear un entorno para Python en la ubicación e:

```
python -m venv .env_python
source .env_python/bin/activate
.env_python\Scripts\Activate.ps1
```

## Instrucciones para instalar Python usando entornos conda

### Paso 1: Instalar Python

1. Abre una terminal, ubicate en el directorio que quieras instalar Python y ejecuta el siguiente comando para crear un entorno conda para Python en la ubicación e instalar Python en el entorno:

```
conda create -p .env_python -c conda-forge python
```

### Paso 2: Activar el entorno Python

1. Abre una terminal y ejecuta el siguiente comando para activar el entorno Python:

```
conda activate ./.env_python
```

### Paso 3: Verificar la instalación

1. Abre una terminal y ejecuta el siguiente comando para verificar la instalación de Python:

```
python --version
```

Debería ver una salida similar a la siguiente:

```
Python 3.11.4
```

### Paso 4: ¡Ahora estás listo para comenzar a codificar en Python!

#### Código de ejemplo 1: ¡Hola mundo!

Aquí hay un pequeño código de ejemplo que muestra cómo usar Python para imprimir "Hola mundo!" en la consola:

```
print("¡Hola mundo!");
```

Para compilar y ejecutar este código, abre una terminal en el directorio que contiene el código y ejecuta los siguientes comandos:

```
python ./src/main.py
```

¡Deberías ver la siguiente salida en la consola:

```
¡Hola mundo!
```
