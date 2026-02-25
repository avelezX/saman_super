# Saman Super

## Qué es
Dashboard y herramientas de reportes regulatorios para el cliente Saman ante la Superintendencia. Genera reportes automatizados y visualizaciones de datos de riesgo país.

## Stack
- Python 3
- Jupyter Notebooks
- HTML (dashboard estático)

## Estructura
- `main.py` - Script principal
- `funciones_xp.py` - Funciones de Xerenity Platform
- `index.html` - Dashboard HTML
- `/assets` - Assets del dashboard
- `*.csv` - Datos de riesgo país
- `*.ipynb` - Notebooks de análisis

## Comandos
```bash
pip install -r requirements.txt
python main.py
```

## Reglas
- Siempre referenciar una issue en commits: `closes #X`
- No pushear directo a main, usar PRs
- No commitear datos del cliente en el repo
- Archivos .env nunca van al repo
