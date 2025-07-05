# climatrack-daily-weather-api-pipeline
Automatiza la consulta diaria del clima en múltiples ciudades usando la API de OpenWeatherMap, estructurando los datos en archivos CSV listos para análisis, visualización o integración.

> Un proyecto ideal para aprendizaje práctico de APIs REST, procesamiento de datos con Python, y principios básicos de automatización tipo SaaS.

---

## 🧠 ¿Qué hace?

- Conecta con la API de OpenWeatherMap
- Extrae:
  - Temperatura
  - Humedad
  - Descripción del clima
  - Fecha y hora
- Guarda la información en un archivo `.csv` nombrado por la fecha
- Organizado con funciones para facilitar mantenimiento y escalabilidad

---

## 🧰 Tecnologías utilizadas

- Python 3
- requests
- pandas
- datetime
- JSON / CSV

---

## 📦 Instalación

1. Clona el repositorio:
git clone https://github.com/tuusuario/climatrack-daily-weather-api-pipeline.git
cd climatrack-daily-weather-api-pipeline
Instala las dependencias:

pip install -r requirements.txt
Si no tienes un archivo requirements.txt, simplemente instala manualmente:


pip install requests pandas
Consigue tu API Key gratuita en https://openweathermap.org/api

Reemplaza "TU_API_KEY" en el código por tu clave.

## 🚀Uso
Ejecuta el script principal:
python climatrack.py
Se generará automáticamente un archivo .csv como:

datos_clima_2025-06-19.csv
Con un contenido como:

ciudad	temperatura	humedad	descripcion	fecha
Madrid	31.5	45	clear sky	2025-06-19 10:00:00
Barcelona	28.2	50	scattered clouds	2025-06-19 10:00:00
