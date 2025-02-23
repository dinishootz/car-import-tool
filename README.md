
# Car Import Backend

Este é o backend para análise de importação de carros.

## 🚀 Como usar

### 1️⃣ Instalar as dependências
```bash
pip install -r requirements.txt
```

### 2️⃣ Iniciar o servidor
```bash
uvicorn main:app --host 0.0.0.0 --port 8000 --reload
```

### 3️⃣ Aceder ao endpoint para análise
Abrir no navegador:
```
http://127.0.0.1:8000/analyze?url=https://www.mobile.de/example
```

## 📦 Como hospedar no GitHub + Vercel
1. **Fazer upload do código para um repositório no GitHub**.
2. **Criar um projeto no [Vercel](https://vercel.com/)**.
3. **Conectar o repositório e fazer deploy automático**.

Agora podes usar a API online sem precisar de um servidor próprio! 🚀
