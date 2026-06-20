# Guía de Configuración del Entorno - Reto Unidad 1

Este documento detalla los pasos necesarios para configurar el entorno virtual profesional e instalar las dependencias requeridas para ejecutar de forma correcta el pipeline de datos del Reto Integrador de la Unidad 1.

---

## Pasos de Instalación

Sigue detalladamente las siguientes instrucciones desde tu terminal o consola de comandos:

### 1. Clonar el repositorio localmente
Si aún no has clonado el proyecto en tu máquina, ejecuta:
```bash
git clone https://github.com/Camilo-COL/RetoUnidad1

### crear un entorno virtual con Conda 
conda create -n reto_u1 python=3.12 -y
conda activate reto_u1

### Para Python nativo 
python -m venv venv
.\venv\Scripts\activate

### Instalacion de dependencias 
pip install -r requirements.txt