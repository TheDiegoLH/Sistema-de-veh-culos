# Sistema_vehiculos

# Sistema de Gestión de Vehículos 

Proyecto académico en **Python** para la materia *Programación Orientada a Objetos*.  
El objetivo es diseñar un sistema que gestione una flota de vehículos aplicando **herencia**, **reutilización de miembros con `super()`**, **redefinición de métodos** y **polimorfismo**.

---

Instalación
1. Descarga el archivo `.zip` del repositorio.  
2. Descomprime el contenido en tu computadora.  
3. Asegúrate de tener instalado **Python 3.10 o superior**.  
   - Verifica con:
     ```bash
     python --version
     ```

---

Estructura del proyecto

vehiculos_simulator/
├── main.py          # Menú interactivo
└── clases/
└── vehiculos.py # Definición de clases Vehiculo, Coche y Moto
- **`vehiculos.py`** → Contiene la clase base `Vehiculo` y las clases derivadas `Coche` y `Moto`.  
- **`main.py`** → Implementa el menú principal y la lógica de interacción con el usuario.

---

Ejecución
1. Abre una terminal en la carpeta raíz `vehiculos_simulator`.  
2. Ejecuta:
   ```bash
   python main.py

