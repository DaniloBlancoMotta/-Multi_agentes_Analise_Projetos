
# 🚀 Multi-agentes para Análise de Projetos e Startups

![Python Version](https://img.shields.io/badge/python-3.10+-blue.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://your-streamlit-app-url.com) Uma aplicação interativa construída com **Streamlit** que simula uma equipe de executivos (CEO, CTO, PM, Dev, CS) para fornecer análises multifacetadas sobre ideias de projetos e startups, utilizando o poder de múltiplos agentes de IA com **OpenAI** e **Agency-Swarm**.

<br>

<p align="center">
  <img src="URL_DO_SEU_GIF_OU_IMAGEM_AQUI.gif" alt="Demonstração da Aplicação" width="700"/>
</p>

---

## ✨ Principais Funcionalidades

* **🤖 Simulação de Equipe:** Obtenha feedback de diferentes perspectivas como se estivesse apresentando sua ideia para um C-Level completo.
* **📊 Análise Multifacetada:** Cada agente analisa o projeto sob sua ótica especializada (visão de negócios, viabilidade técnica, produto, desenvolvimento e cliente).
* **🖥️ Interface Intuitiva:** Interface simples e direta construída com Streamlit para facilitar a inserção de dados e a visualização dos resultados.
* **🔑 Integração Segura de API:** Use sua própria chave da OpenAI com segurança, seja através da interface ou de um arquivo `.env`.

---

## 🤖 Conheça a Equipe de Agentes

<details>
<summary>Clique para expandir e ver os perfis dos agentes</summary>

| Agente | Ícone | Responsabilidade |
| :--- | :---: | :--- |
| **CEO** | 💼 | Avalia a visão de negócios, potencial de mercado, estratégia e viabilidade financeira do projeto. |
| **CTO** | 💻 | Analisa a arquitetura técnica, escalabilidade, stack de tecnologia e desafios de implementação. |
| **Product Manager**| 📈 | Foca no product-market fit, na experiência do usuário (UX), no roadmap e nas funcionalidades propostas. |
| **Developer** | ⚙️ | Fornece uma perspectiva sobre o esforço de desenvolvimento, complexidade do código e possíveis débitos técnicos. |
| **Customer Support**| 💬 | Antecipa as possíveis dúvidas e problemas dos clientes, avaliando a usabilidade e o suporte necessário. |

</details>

---

## 🛠️ Começando

Siga os passos abaixo para configurar e executar o projeto em seu ambiente local.

### Pré-requisitos

* **Python 3.10+**
* **Chave de API da OpenAI:** Você pode criar a sua em [platform.openai.com/api-keys](https://platform.openai.com/api-keys).

### Instalação

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
    cd seu-repositorio
    ```

2.  **Crie e ative um ambiente virtual:**

    * **Windows (PowerShell):**
        ```powershell
        python -m venv .venv
        .\.venv\Scripts\Activate.ps1
        ```
    * **Windows (CMD):**
        ```cmd
        python -m venv .venv
        .venv\Scripts\activate.bat
        ```
    * **Linux / macOS:**
        ```bash
        python3 -m venv .venv
        source .venv/bin/activate
        ```

3.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Configure sua chave de API:**
    Crie um arquivo chamado `.env` na raiz do projeto e adicione sua chave da OpenAI.
    ```env
    # Não compartilhe este arquivo e não o envie para o GitHub!
    OPENAI_API_KEY="sua_chave_secreta_aqui"
    ```

---

## ▶️ Como Executar

Com o ambiente virtual ativado, inicie a aplicação Streamlit com o seguinte comando:

```bash
streamlit run startup.py




├── 📄 .env                  # Arquivo para variáveis de ambiente (sua chave da API)
├── 📜 .gitignore             # Arquivos e pastas a serem ignorados pelo Git
├── 🚀 startup.py             # Script principal da aplicação Streamlit e definição dos agentes
├── 📋 requirements.txt       # Lista de dependências Python do projeto
└── 📖 README.md               # Este arquivo que você está lendo 


