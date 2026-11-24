# 🌾 Sistema de Alertas Tempranas en la Volatilidad del Mercado del Arroz en Colombia (2018–2026)

Repositorio oficial del **Equipo 10** para la asignatura **Adquisición e Integración de Datos** (Ingeniería en Ciencia de Datos).

- **Integrantes:** Sebastián Cardona Franco & Miguel Ángel Echavarría
- **Periodo analizado:** Enero de 2018 – Octubre de 2026 (`106` observaciones mensuales)

## 📂 Estructura del Repositorio

```text
volatilidad-arroz-colombia-2018-2026/
├── README.md
├── requirements.txt
├── 01_datos_fuentes/
│   ├── Fuente1_Primaria_Sensor_Agroclimatico.csv
│   ├── Fuente2_Secundaria_SIPSA_DANE_Arroz.csv
│   └── Fuente3_Internacional_PinkSheet_BancoMundial.csv
├── 02_integracion_etl/
│   ├── Notebook_Integracion_Arroz_2018_2026.ipynb
│   └── Arroz_Integrado_2018_2026.csv
├── 03_diagramas/
│   ├── Diagrama_Ishikawa_Arroz.png
│   └── Diagrama_5_Porques_Arroz_v2.png
└── 04_documentacion_y_anexos/
    ├── Diccionario_Datos_Tres_Fuentes.docx
    └── Anexo_Prompts_IA_Generativa.docx
```

## 🚀 Ejecución del Pipeline ETL

```bash
pip install -r requirements.txt
cd 02_integracion_etl
jupyter notebook Notebook_Integracion_Arroz_2018_2026.ipynb
```
