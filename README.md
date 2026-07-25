# EzCommerce

Plataforma de comercio electrónico orientada a compra y venta de productos de segunda mano.

## Estructura

```
├──docs/                    # Documentación del proyecto
└──source/
    ├──backend/           # API REST con Django y base de datos SQLite3
    └──frontend/          # Interfaz de usuario con React y Vite
```

## Stack tecnológico

| Componente | Tecnología | Versión |
| :--------: | :--------: | :-----: |
|  Backend   |   Django   |  5.0.8  |
|  Frontend  |   React    | 19.0.0  |

## Requisitos

- [Python](https://www.python.org/)
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

## Instalación

```bash
# Clonar el repositorio
git clone <url_del_repositorio>

# Entrar al directorio del proyecto
cd ezcommerce

# Instalar dependencias del backend
cd source/backend
pip install -r requirements.txt

# Instalar dependencias del frontend
cd ../frontend
npm install
```

## Ejecución

```bash
# Ejecutar el backend
cd source/backend
python manage.py runserver

# Ejecutar el frontend
cd ../frontend
npm run dev
```
