# 🤖 ChatBot com IA - Streamlit + OpenAI

Este é um projeto simples de ChatBot construído com **Python**, utilizando o **Streamlit** como interface web e a **API da OpenAI** para gerar respostas com inteligência artificial.

### 🔗 Repositório GitHub

📂 [github.com/isaaczinrs2/PythonDev](https://github.com/isaaczinrs2/PythonDev)

---

## 📌 Funcionalidades

* Interface interativa com o usuário via `streamlit.chat_input`.
* Histórico de mensagens salvo em `st.session_state` para manter a conversa.
* Integração com a API da OpenAI utilizando o modelo `gpt-4o`.
* Respostas geradas automaticamente com base na entrada do usuário.

---

## 🚀 Como Executar Localmente

### 1. Clone o Repositório

```bash
git clone https://github.com/isaaczinrs2/PythonDev.git
cd PythonDev
```

### 2. Instale as Dependências

Crie e ative um ambiente virtual (opcional, mas recomendado):

```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows
```

Instale os pacotes necessários:

```bash
pip install streamlit openai
```

### 3. Adicione sua Chave da API da OpenAI

No código `main.py` (ou nome que você salvou), substitua:

```python
api_key="sua_chave_de_api_aqui"
```

Por sua chave pessoal da OpenAI.

> ⚠️ Nunca compartilhe sua chave da API publicamente.

### 4. Execute o Projeto

```bash
streamlit run main.py
```

---

## 🧠 Tecnologias Usadas

* **[Python](https://www.python.org/)**
* **[Streamlit](https://streamlit.io/)**
* **[OpenAI API](https://platform.openai.com/docs)**

---

## 📂 Estrutura do Código

```bash
PythonDev/
├── main.py               # Código principal do chatbot
├── README.md             # Documentação do projeto
└── auxiliar.py           
```

---

## ✅ Exemplo de Conversa

```
Usuário: O que é Python?
IA: Você quis dizer: O que é Python?
```

> *Atualmente, a IA apenas replica a mensagem do usuário com um prefixo, mas o código está preparado para utilizar respostas reais da API da OpenAI.*

---


## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se livre para abrir uma *issue* ou um *pull request*.

---

## 📬 Contato

Criado por [Isaac Amorim(@isaaczinrs2)](https://github.com/isaaczinrs2)
📧 Dúvidas ou sugestões: abra uma issue no repositório!

---
