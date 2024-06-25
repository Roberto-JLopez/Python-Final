TRABAJO FINAL PYTHON 

1. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window

2. Creamos una carpeta o directorio: 

```
mkdir python-final
```

3. Entramos en ella: 

```
cd python-final
```

4. Iniciamos el repositorio:

```
git init
```

5. Creamos un archivo:

```touch finales.py```

6. Abrimos VSC:

```
code .
```

7. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:

```
python -V
```

```
python3 -V
```

8. Creamos el entorno virtual en Python:

```
python -m venv venv
```
#Creamos el entorno virtual

9. Activamos el entorno virtual:

```
venv/scripts/activate
```
#En windows

10. Hacemos actualización del pip de Python

```
python -m pip install --upgrade pip
```
#Actualizamos el pip

11. Investigar ¿Qué es el pip y porque lo actualizamos?

## ¿Qué es pip?

**pip** es el acrónimo de "Pip Installs Packages" y es el gestor de paquetes oficial de Python. Permite a los usuarios instalar y gestionar bibliotecas y dependencias adicionales que no están incluidas en la biblioteca estándar de Python. Con pip, puedes descargar, instalar y actualizar paquetes desde el [Python Package Index (PyPI)](https://pypi.org/), que es un repositorio con miles de paquetes disponibles.

## ¿Por qué actualizamos pip?

Actualizar pip es importante por varias razones:

1. **Nuevas Características**:
   - Las actualizaciones de pip a menudo incluyen nuevas características y funcionalidades que mejoran la experiencia del usuario y amplían las capacidades del gestor de paquetes.

2. **Mejoras de Seguridad**:
   - Las versiones más recientes de pip pueden contener parches de seguridad que corrigen vulnerabilidades detectadas en versiones anteriores. Mantener pip actualizado ayuda a proteger el entorno de desarrollo contra posibles ataques.

3. **Corrección de Errores**:
   - Las actualizaciones incluyen corrección de errores y problemas conocidos en versiones anteriores. Esto puede prevenir problemas durante la instalación de paquetes y mejorar la estabilidad general de pip.

4. **Compatibilidad**:
   - Las actualizaciones aseguran que pip sea compatible con la última versión de Python y otros paquetes. Esto es crucial para mantener un entorno de desarrollo coherente y funcional.

5. **Mejoras de Rendimiento**:
   - Las nuevas versiones de pip a menudo traen mejoras en el rendimiento que pueden acelerar el proceso de instalación y gestión de paquetes.

## ¿Cómo actualizar pip?

Puedes actualizar pip utilizando el siguiente comando en la terminal:

```
python -m pip install --upgrade pip
```

12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.

13. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.
