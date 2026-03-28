# Togethr ✈️ - App Social de Eventos y Viajes

Togethr es una aplicación web diseñada para fomentar la interacción entre usuarios, permitiendo que se comuniquen y organicen eventos y viajes de forma divertida e inolvidable.

## 🏗️ Arquitectura del Proyecto (Full Stack)
Este repositorio es un **Monorepo** que contiene:
- **Backend:** Django 5.x (Python) + MySQL.
- **Frontend:** Vue.js 3 (Vite) + Pinia/Router.

---

## 🚀 Guía de Instalación para el Equipo

### 1. Clonar el repositorio
```bash
git clone [https://github.com/ivangarcia116/app_togethr.git](https://github.com/ivangarcia116/app_togethr.git)
```
### 2. Configurar BackEnd (Django)
```bash
cd togethr_back
# Crear y activar entorno virtual
python -m venv venv
.\venv\Scripts\activate
# Instalar dependencias
pip install django django-cors-headers mysqlclient
# Ejecutar servidor
python manage.py runserver
```
### 3. Configurar FrontEnd (Vue.js)
```bash
cd togethr_front
# Instalar dependencias de Node
npm install
# Ejecutar en modo desarrollo
npm run dev
```
