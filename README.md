# IA 2025 — Materiais da Disciplina
## Como rodar
1) Crie e ative um ambiente Python (venv/anaconda)
2) `pip install -r requirements.txt`
3) Exemplos:
   - Aspirador: `python aspirador/aspirador.py`
   - Diagnóstico (CLI): `python diagnostico/agente_diagnostico.py`
   - Diagnóstico (UI): `streamlit run diagnostico/diagnostico_streamlit.py`

## Entrega de exercícios
- Faça um fork (ou use seu repo da Classroom)
- Crie uma branch com seu nome `aluno_nome/sprint1`
- Abra PR para revisão

 ## Requisitos

Python 3.10+

(UI) streamlit

(WhatsApp) conta Twilio + variáveis TWILIO_SID/TWILIO_TOKEN

IA_2025/requirements.txt (exemplo):
streamlit
fastapi
uvicorn
twilio
graphviz
