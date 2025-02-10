holamundo-pyside6

 Documentación de la Aplicación "Hola Mundo" con PySide6

 Pasos de Instalación y Ejecución

1. Instalación de Python 3

#### Windows
1. Descarga el instalador de Python 3 desde [python.org](https://www.python.org/downloads/).
2. Verifica la instalación abriendo la terminal (cmd) y escribiendo:

    ```bash
    python --version
    ```

#### Linux
1. Verifica si Python 3 ya está instalado ejecutando el siguiente comando:

    ```bash
    python3 --version
    ```

2. Si no está instalado, instálalo con:

    ```bash
    sudo apt update
    sudo apt install python3
    ```

### 2. Instalación y Activación de pip

1. Verifica si `pip` está instalado ejecutando:

    ```bash
    pip --version
    ```

2. Si `pip` no está instalado, puedes instalarlo ejecutando:

    ```bash
    python get-pip.py
    ```

### 3. Creación y Activación de Entorno Virtual

#### Windows
1. Crea un entorno virtual con:

    ```bash
    python -m venv venv (en el segundo venv puedes poner el nombre que quieras para tu entorno)
    ```

2. Actívalo con:

    ```bash
    .\venv\Scripts\activate (sustituye venv con el nombre de tu entorno si has puesto otro)
    ```

#### Linux
1. Crea un entorno virtual con:

    ```bash
    python3 -m venv venv (en el segundo venv puedes poner el nombre que quieras para tu entorno)
    ```

2. Actívalo con:

    ```bash
    source venv/bin/activate (sustituye venv con el nombre de tu entorno si has puesto otro)
    ```

### 4. Instalación de Dependencias

Con el entorno virtual activado, instala PySide6 con el siguiente comando:

```bash
pip install PySide6
