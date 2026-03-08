# amif_assistente_virtual_IA

AMIF, Seu Amigo Financeiro. Assistente Virtual Bancário baseado em IA Generativa
# 🤖 dio-lab-bia-do-futuro

Assistente virtual financeiro desenvolvido em **Python** com **IA Generativa**, inspirado na **BIA (Bradesco Inteligência Artificial)**.

Este projeto foi criado como parte de um **desafio do Bootcamp da DIO em parceria com o Bradesco**, com o objetivo de desenvolver um **assistente inteligente capaz de atuar como um amigo e conselheiro financeiro**, ajudando usuários a refletirem sobre decisões relacionadas a finanças pessoais.

A aplicação utiliza **modelos de linguagem rodando localmente via Ollama**, oferecendo uma interface simples e interativa construída com **Streamlit**.

---

# 🎯 Objetivo do Projeto

O objetivo deste projeto é demonstrar como **IA generativa pode ser aplicada ao setor financeiro** para criar experiências conversacionais mais humanas e úteis.

O assistente atua como:

* 💬 Um **companheiro de conversa sobre finanças**
* 📊 Um **orientador financeiro básico**
* 🧠 Um **assistente inteligente baseado em LLM**
* 💡 Um exemplo prático de **aplicação de IA generativa em produtos digitais**

---

# 🧠 Como Funciona

A aplicação funciona através de uma interface web criada com **Streamlit**, onde o usuário pode conversar com o assistente virtual.

O fluxo básico da aplicação é:

1. O usuário envia uma pergunta ou mensagem.
2. A aplicação envia o prompt para um **modelo de linguagem rodando no Ollama**.
3. O modelo gera uma resposta contextualizada.
4. A resposta é exibida na interface web.

Isso permite criar uma experiência semelhante a conversar com um **assistente financeiro inteligente**.

<img width="1053" height="660" alt="AMIF_Assistente_Virtual_Rodando" src="https://github.com/user-attachments/assets/4d26bd91-2e9a-4c07-a798-823e4066ae07" />



---

# 🛠️ Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando as seguintes tecnologias:

* **Python** – Linguagem principal do projeto
* **Streamlit** – Framework para criação da interface web
* **Ollama** – Execução local de modelos de linguagem (LLMs)
* **pandas** – Manipulação de dados

---

# 📂 Estrutura do Projeto

```
dio-lab-bia-do-futuro/
│
├── src/
│   └── app.py
├─ data
│   ├─ perfil_investidor.json
│   ├─ produtos_financeiros.json
│   ├─ transacoes.csv
│   └─ historico_atendimento.csv
├── README.md
└── requirements.txt
```

* **src/app.py** → Arquivo principal da aplicação Streamlit
* **requirements.txt** → Dependências do projeto
* **README.md** → Documentação do projeto

---

# ⚙️ Pré-requisitos

Antes de executar o projeto, certifique-se de ter instalado:

* **Python 3.9+**
* **pip**
* **Ollama**

Instale o Ollama através do site oficial:

[https://ollama.com](https://ollama.com)

Depois de instalar, execute um modelo local, por exemplo:

```
ollama run llama3
```

---

# 📦 Instalação

Clone o repositório:

```bash
git clone https://github.com/henriquehweber-bit/dio-lab-bia-do-futuro.git
```

Entre no diretório do projeto:

```bash
cd dio-lab-bia-do-futuro
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

ou

```bash
pip install streamlit pandas ollama
```

---

# ▶️ Como Executar

Execute a aplicação com o comando:

```bash
streamlit run src/app.py
```

Após iniciar, a interface estará disponível em:

```
http://localhost:8501
```

Abra o endereço no navegador para começar a conversar com o assistente.

---

# 💬 Exemplo de Uso

O usuário pode interagir com o assistente com perguntas como:

* "Como posso organizar melhor meu orçamento?"
* "Vale mais a pena guardar dinheiro ou investir?"
* "Como evitar dívidas no cartão de crédito?"
* "Quais hábitos ajudam a melhorar minha saúde financeira?"

O assistente irá responder utilizando **IA generativa**, simulando um **conselheiro financeiro amigável**.

---

# 🚀 Possíveis Melhorias Futuras

Algumas melhorias que podem evoluir o projeto:

* 📊 Integração com dados financeiros reais
* 🧾 Análise automática de gastos
* 📈 Recomendações personalizadas de investimento
* 🧠 Memória de conversas do usuário
* 🔐 Autenticação de usuários
* ☁️ Deploy em nuvem

---

# 🎓 Contexto Educacional

Este projeto foi desenvolvido como parte do:

**Bootcamp da DIO (Digital Innovation One) em parceria com o Bradesco**

O desafio consistia em construir um **assistente virtual inspirado na BIA**, explorando o uso de **IA generativa para aplicações financeiras**.

---

# 👨‍💻 Autor

Desenvolvido por:

**Henrique Weber**

GitHub
[https://github.com/henriquehweber-bit](https://github.com/henriquehweber-bit)

---

# ⭐ Contribuição

Contribuições são bem-vindas.

Se quiser contribuir:

1. Faça um **fork** do projeto
2. Crie uma nova **branch**
3. Envie um **Pull Request**

---

# 📄 Licença

Este projeto foi desenvolvido para fins educacionais dentro do Bootcamp da DIO.

Sinta-se livre para estudar, modificar e utilizar como base para outros projetos.

---

⭐ Se este projeto foi útil para você, considere dar uma **estrela no repositório**.
