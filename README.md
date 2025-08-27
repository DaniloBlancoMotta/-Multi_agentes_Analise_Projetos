# Multi-agentes para projetos e start ups reviews

Aplicação Streamlit com múltiplos agentes (CEO, CTO, PM, Dev, CS) para analisar projetos e startups. Integração com OpenAI e `agency-swarm`.

## Requisitos
- Python 3.10+
- Chave da OpenAI (crie em https://platform.openai.com/api-keys)

## Configuração
1. Clone ou baixe o repositório.
2. Crie o ambiente virtual (Windows):
   - PowerShell
     ```powershell
     python -m venv .venv
     .\.venv\Scripts\Activate.ps1
     ```
   - CMD
     ```cmd
     python -m venv .venv
     .venv\Scripts\activate.bat
     ```
3. Instale as dependências:
   ```powershell
   pip install -r requirements.txt
   ```
4. Crie o arquivo `.env` na raiz do projeto com sua chave:
   ```env
   OPENAI_API_KEY=coloque_sua_chave_aqui
   ```

## Executar
- Via venv (recomendado):
  ```powershell
  .\.venv\Scripts\python.exe -m streamlit run startup.py
  ```
- Ou, se a venv estiver ativada:
  ```powershell
  streamlit run startup.py
  ```

## Como usar
- Informe a chave da OpenAI na sidebar (será pré-preenchida se existir em `.env`).
- Preencha os dados do projeto e clique em "Analyze Project".
- As respostas são exibidas em abas por agente.

## Estrutura principal
- `startup.py`: app Streamlit, definição dos agentes e fluxo.
- `requirements.txt`: dependências (Streamlit, agency-swarm, pydantic, python-dotenv, openai).
- `.env`: chave da OpenAI (não commitar).




   ```

---
