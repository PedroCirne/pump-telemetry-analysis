# Pump Monitoring — Telemetria e Manutenção Preditiva

Este projeto simula a análise de telemetria de bombas industriais com foco em **monitoramento inteligente**, **detecção de anomalias** e **manutenção preditiva**. Inspirado em aplicações reais da indústria, como as bombas [XXXXX], ele demonstra como dados de sensores podem ser utilizados para otimizar a operação e evitar falhas críticas.

---

## 📊 Sobre os Dados

O dataset simulado contém leituras a cada 15 minutos de três bombas industriais distintas, com os seguintes parâmetros monitorados:

- `timestamp`
- `pump_id`
- `pressure_in` (bar)
- `pressure_out` (bar)
- `vibration` (mm/s)
- `temperature` (°C)
- `rpm` (rotações por minuto)
- `flow_rate` (L/min)
- `power_consumption` (kW)

Os dados estão disponíveis em: [`/data/pump_telemetry.csv`](data/pump_telemetry.csv)

---

## 🧠 Notebooks

- 📈 **01_eda.ipynb** — Análise exploratória dos dados
- 🚨 **02_anomaly_detection.ipynb** — Identificação de anomalias operacionais
- 🔮 **03_predictive_model.ipynb** — Criação de modelo preditivo (ex: manutenção preditiva)

---

## 🛠️ Tecnologias utilizadas

- Python (Pandas, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- Arduino IDE (opcional)
- Git e GitHub

---

## 🚀 Como executar

1. Clone o repositório:

```bash
git clone https://github.com/pedro-cirne/pump-monitoring.git
cd pump-monitoring
