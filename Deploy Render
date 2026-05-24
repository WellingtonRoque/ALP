# 🚀 Deploy Projeto Python no Render

Este guia mostra como publicar o projeto final da disciplina no Render utilizando Flask.

O sistema principal continuará no arquivo:

```plaintext
sistema.py
```

E o Flask ficará responsável apenas por disponibilizar uma página online através do:

```plaintext
app.py
```

---

# 📂 Estrutura do Projeto

```plaintext
Projeto_Final/
│
├── app.py
├── sistema.py
├── produtos.txt
├── clientes.txt
├── requirements.txt
└── README.md
```

---

# ✅ PASSO 1 — Instalar Flask

No terminal do VSCode ou PyCharm:

```bash
pip install flask
```

---

# ✅ PASSO 2 — Criar requirements.txt

Criar um arquivo chamado:

```plaintext
requirements.txt
```

Conteúdo:

```txt
flask
```

---

# ✅ PASSO 3 — Criar sistema.py

Neste arquivo ficará o sistema principal desenvolvido durante a disciplina.

Exemplo:

```python
def menu():

    print("===== SISTEMA COMERCIAL =====")

    print("1 - Produtos")

    print("2 - Clientes")

menu()
```

---

# ✅ PASSO 4 — Criar app.py

O arquivo `app.py` será responsável pelo Flask e pelo deploy no Render.

```python
from flask import Flask

app = Flask(__name__)

@app.route("/")
def home():

    return """
    <h1>🚀 Sistema de Gestão Comercial</h1>

    <p>Projeto desenvolvido na disciplina de Algoritmos e Lógica de Programação.</p>

    <h2>✅ Funcionalidades</h2>

    <ul>
        <li>Cadastro de Produtos</li>
        <li>Cadastro de Clientes</li>
        <li>Persistência em Arquivos</li>
        <li>Tratamento de Erros</li>
    </ul>

    <p>Projeto publicado utilizando Flask + Render.</p>
    """

if __name__ == "__main__":

    app.run(host="0.0.0.0", port=10000)
```

---

# ✅ PASSO 5 — Testar Localmente

Executar:

```bash
python app.py
```

Abrir no navegador:

```plaintext
http://127.0.0.1:10000
```

---

# ✅ PASSO 6 — Inicializar Git

Dentro da pasta do projeto:

```bash
git init
```

---

# ✅ PASSO 7 — Adicionar Arquivos

```bash
git add .
```

---

# ✅ PASSO 8 — Criar Commit

```bash
git commit -m "Projeto final da disciplina"
```

---

# ✅ PASSO 9 — Criar Repositório no GitHub

Acessar:

```plaintext
https://github.com
```

Criar um novo repositório.

---

# ✅ PASSO 10 — Conectar Projeto ao GitHub

```bash
git remote add origin URL_DO_REPOSITORIO
```

Exemplo:

```bash
git remote add origin https://github.com/usuario/projeto.git
```

---

# ✅ PASSO 11 — Enviar Projeto

```bash
git push -u origin main
```

---

# ✅ PASSO 12 — Criar Conta no Render

Acessar:

```plaintext
https://render.com
```

---

# ✅ PASSO 13 — Criar Web Service

No painel do Render:

1. Clicar em **New +**
2. Selecionar **Web Service**
3. Conectar conta GitHub
4. Selecionar o repositório do projeto

---

# ✅ PASSO 14 — Configurar Build Command

```bash
pip install -r requirements.txt
```

---

# ✅ PASSO 15 — Configurar Start Command

```bash
python app.py
```

---

# ✅ PASSO 16 — Finalizar Deploy

Clique em:

```plaintext
Create Web Service
```

---

# 🚀 RESULTADO FINAL

O Render irá gerar um link parecido com:

```plaintext
https://projeto-final.onrender.com
```

---

# 🔄 Atualizações Futuras

Sempre que atualizar o projeto:

```bash
git add .

git commit -m "Atualizacao do sistema"

git push
```

O Render atualizará automaticamente o projeto online 🚀

---

# 🎯 Objetivo Pedagógico

Este processo permite aplicar:

✅ Python  
✅ Algoritmos  
✅ Arquivos  
✅ Git  
✅ GitHub  
✅ Flask  
✅ Deploy  
✅ Publicação de Sistemas Online  
