# 🚀 Projeto HTML + Apache com Docker Compose

Este projeto demonstra como rodar uma aplicação **HTML + CSS + JS** dentro de um **container Apache (httpd)** utilizando **Docker Compose**.  

## 📌 Objetivo
- Criar um ambiente web simples usando Docker;
- Servir páginas estáticas (HTML, CSS e JS) pelo Apache;
- Aprender conceitos básicos de containers e volumes.

---

## 🛠️ Estrutura do Projeto

apache-docker-html/
│── docker-compose.yml # Configuração do Docker Compose
│── site/ # Código da aplicação
│ ├── index.html
│ ├── style.css
│ └── script.js


---

## ▶️ Como executar o projeto

1. **Clonar o repositório**
   ```sh
   git clone https://github.com/seu-usuario/apache-docker-html.git
   cd apache-docker-html

2. **Subir os containers**
docker compose up -d

3. **Verificar se o container está rodando**
docker ps

Deve aparecer algo como:
CONTAINER ID   IMAGE         COMMAND              PORTS                  NAMES
123abc456def   httpd:latest  "httpd-foreground"   0.0.0.0:8080->80/tcp   apache-html

4. **Abrir no navegador**
👉 http://localhost:8080

✨ **Exemplo da aplicação**

Página principal (index.html)

Estilo em (style.css)

Script JS em (script.js)

Quando você acessa a página, vê o texto estilizado e ao clicar no botão recebe um alert do JavaScript 🎉

📦 **Comandos úteis**

* Subir os containers
docker compose up -d

* Parar os containers
docker compose down

* Ver logs
docker logs apache-html

👨‍💻 **Autor**

Projeto desenvolvido por Fabio Antonio dos Santos 🚀