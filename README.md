# MT5 Backtest Analysis

Este proyecto analiza reportes de Strategy Tester de MetaTrader 5 para extraer estadísticas de rachas (streaks) y generar visualizaciones.

## Estructura

- `notebooks/`: Contiene los Jupyter Notebooks de análisis.
- `data/`: Almacena los reportes HTML de MT5 y los datos procesados (JSON).

## Requisitos

- Python 3.13+
- [uv](https://github.com/astral-sh/uv) para la gestión de dependencias.

## Instalación y Uso

1.  **Clonar/Navegar al proyecto:**
    ```bash
    cd mt5-backtest-analysis
    ```

2.  **Sincronizar dependencias:**
    ```bash
    uv sync
    ```

3.  **Ejecutar Jupyter Lab:**
    ```bash
    uv run jupyter lab
    ```

4.  **Abrir el notebook:**
    Navega a la carpeta `notebooks/` y abre `streak_analysis.ipynb`.

> [!IMPORTANT]
> **Ajuste de rutas:** Como el notebook se movió a la carpeta `notebooks/`, asegúrate de que las rutas a los datos apunten al directorio padre.
>
> Cambia:
> ```python
> file_path = "data/..."
> ```
> por:
> ```python
> file_path = "../data/..."
> ```
