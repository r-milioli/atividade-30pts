# 📘 Atividade 30PTS - Int. Tec. Informação

## 🎯 Objetivo do Projeto

Este projeto tem como objetivo servir uma página HTML simples utilizando o servidor web **NGINX** dentro de um container **Docker**.  
A atividade foi desenvolvida para a disciplina de **Introdução à Tecnologia da Informação**.

---

## 🛠️ Comandos Utilizados

### 📦 Criar a imagem Docker personalizada

```bash
docker build -t atividade .
```

### 🚀 Executar o container

```bash
docker run -d -p 8080:80 --name atividade-ngix atividade
```

### 📋 Verificar containers ativos

```bash
docker ps
```

### 🛑 Parar o container

```bash
docker stop atividade-ngix
```

### 🗑️ Remover o container

```bash
docker rm atividade-ngix
```

### 📜 Ver logs do container

```bash
docker logs atividade-ngix
```

---

## ▶️ Como Executar o Container

1. Certifique-se de estar no diretório onde estão os arquivos:

```
index.html  
style.css  
Dockerfile  
assets/ (opcional, para imagens)  
```

2. Construa a imagem Docker:

```bash
docker build -t atividade .
```

3. Rode o container:

```bash
docker run -d -p 8080:80 --name atividade-ngix atividade
```

4. Acesse o projeto no navegador:

```
http://localhost:8080
```

Você verá a página HTML estilizada rodando dentro do container Docker com NGINX.

---

## 📁 Estrutura do Projeto

```plaintext
.
├── index.html
├── style.css
├── Dockerfile
├── assets/
│   └── img1.png (opcional)
└── README.md
```

---

## 👨‍💻 Autor

Atividade realizada por **[Seu Nome]**  
Disciplina: **Introdução à Tecnologia da Informação**
