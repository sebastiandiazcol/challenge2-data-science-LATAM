# Challenge 2: Data Science LATAM - TelecomX

Este proyecto forma parte del Challenge de Data Science de Alura/LATAM, enfocado en el análisis de datos de telecomunicaciones para predecir y entender el comportamiento de los clientes (**Churn**).

## 🚀 Estructura del Proyecto

El repositorio está organizado de la siguiente manera:

-   `data/`: Contiene el conjunto de datos `TelecomX_Data.json` y el diccionario de datos `TelecomX_diccionario.md`.
-   `notebooks/`: Contiene el archivo principal de análisis `TelecomX_LATAM.ipynb`.
-   `.venv/`: Entorno virtual gestionado por `uv`.

## 🛠️ Requisitos e Instalación

Este proyecto utiliza [uv](https://github.com/astral-sh/uv) para la gestión del entorno y dependencias.

Para configurar el entorno localmente:

1.  Asegúrate de tener `uv` instalado.
2.  Ejecuta el siguiente comando para instalar las dependencias:
    ```powershell
    uv sync
    ```
3.  Para abrir el notebook:
    ```powershell
    uv run jupyter notebook
    ```

## 📊 Datos

El análisis se centra en los datos de **TelecomX**, que incluyen:
- `customerID`: Identificación del cliente.
- `Churn`: Variable objetivo (si el cliente dejó la empresa).
- `Charges.Monthly` y `Charges.Total`: Información financiera.
- Datos demográficos y servicios contratados.

## ✒️ Autor
- **Sebastián Díaz** - [sebastiandiazcol](https://github.com/sebastiandiazcol)
