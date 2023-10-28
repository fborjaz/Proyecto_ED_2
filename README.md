# 🛒 Simulador de Lista de Compras 🛍

Este es el repositorio del proyecto "Simulador de Lista de Compras". A continuación, se presenta la estructura del directorio del proyecto:

```text

📂 Simulador_/
|-- 📁 backend/
| |-- 📁 media
| |-- 📁 orders
| |-- 📁 products
| |-- 📁 users
|-- 📁 frontend/
| |-- 📁 public
| |-- 📁 src
|-- 📁 env/
|-- 📓 README.md

```


## Descripción del Proyecto 📝

En este proyecto, los estudiantes crearán un simulador de lista de compras que permitirá a los usuarios agregar elementos a una lista de compras y realizar operaciones comunes como agregar, eliminar y verificar la disponibilidad de artículos.

## Requisitos y Funcionalidades del Simulador de Lista de Compras 📋

### Interfaz de Usuario 👩‍💻

Crear una interfaz de usuario en la consola que permita a los usuarios interactuar con el simulador.

### Agregar Artículos a la Lista de Compras 📦

Los usuarios deben poder agregar artículos ingresando su nombre y cantidad.

### Eliminar Artículos de la Lista 🗑️

Permitir a los usuarios eliminar artículos de la lista de compras.

### Verificación de Disponibilidad ✅

Implementar una función que permita a los usuarios verificar la disponibilidad de artículos en la lista de compras.

# Instalar y Usar 🚀

1. Asegúrate de tener Python instalado en tu sistema. 🐍
2. Crea un entorno virtual en la carpeta `backend/` usando `env` o tu gestor de entornos virtual preferido.
3. Activa el entorno virtual. 📦

### 4. Clonamos el repositorio  y accedemos.
```bash
git clone https://github.com/fborjaz/Proyecto_ED_2.git
cd Proyecto_ED_2.git
```

### 5. Creamos el entorno virtual y activamos.
```bash
python3 -m venv env
source env/bin/activate
```

### 6. Instalamos todas las independencias.
```bash
pip install -r requirements.txt
```

### 7. Creamos carpeta para los archivos generados.
```bash
mkdir dist
mkdir dist/static
```

### 8. Creamos un Super User para acceder al PadAdmin.
```bash
python3 manage.py createsuperuser
```

### 9. Corremos el bakend
```bash
python3 manage.py runserver
```

### 10. En una nueva terminal accedemos al frontend
```bash
cd frontend
```
### 11. Instalamos e iniciamos server frontend
```bash
npm i
npm run dev
```

#### Abre la siguiente url e inicia session con el usuario que creaste con Django
<a href="http://localhost:5173/">http://localhost:5173/</a> 🌟
