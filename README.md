# MT5 Backtest Analysis

Este proyecto analiza reportes de Strategy Tester de MetaTrader 5 para extraer estadísticas de rachas (streaks) y generar visualizaciones.

## Estructura

- `notebooks/`: Contiene los Jupyter Notebooks de análisis.
- `data/`: Almacena los reportes HTML de MT5 y los datos procesados (JSON).

## Requisitos

- Python 3.13+
- [uv](https://github.com/astral-sh/uv) para la gestión de dependencias.

## Instalación y Uso

1.  **Instalar `uv` (si no lo tienes):**
    
    *macOS/Linux:*
    ```bash
    curl -LsSf https://astral.sh/uv/install.sh | sh
    ```
    *Windows:*
    ```powershell
    powershell -c "irm https://astral.sh/uv/install.ps1 | iex"
    ```

2.  **Clonar el proyecto:**
    ```bash
    git clone git@github.com:fmunozse-trading/mt5-backtest-analysis.git
    cd mt5-backtest-analysis
    ```

3.  **Sincronizar dependencias:**
    ```bash
    uv sync
    ```

4.  **Ejecutar Jupyter Lab:**
    ```bash
    uv run jupyter lab
    ```

5.  **Abrir el notebook:**
    Navega a la carpeta `notebooks/` y abre `streak_analysis.ipynb`.

