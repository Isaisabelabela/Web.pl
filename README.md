# 🍕 Pizzaria Web em Prolog
A proposta é desenvolver uma aplicação web simulando o sistema de pedidos de uma pizzaria — mas com um diferencial curioso: o servidor web é escrito inteiramente em Prolog, uma linguagem declarativa usada comumente em Inteligência Artificial e Lógica Computacional.
 
## 🧠 Curiosidade: Prolog como servidor web?

Sim! Utilizamos **SWI-Prolog**, uma linguagem declarativa geralmente associada a lógica e IA, para criar uma aplicação **web dinâmica**. Com suas bibliotecas nativas (`http/thread_httpd`, `http_dispatch`, etc.), é possível montar um **servidor HTTP funcional**, ler formulários HTML e gerar páginas como resposta.

---

## 🚀 Funcionalidades

- [x] Formulário HTML para pedido de pizza
- [x] Envio dos dados via POST para um servidor Prolog
- [x] Processamento completo do pedido: cliente, horário, ingredientes
- [x] Exibição formatada dos dados usando HTML gerado em Prolog
- [x] Suporte a múltiplos ingredientes (mesmo 1 ou 0)
- [x] Compatível com acentuação (UTF-8)
- [ ] (Extra) Salvamento dos pedidos no arquivo `pedidos.pl`

---

## 🧩 Tecnologias

- **SWI-Prolog** (`http_dispatch`, `html_write`, `http_parameters`)
- **HTML5** (formulário do lado cliente)
- **CSS3** (estilo opcional)
- **Visual Studio Code** (ambiente de desenvolvimento sugerido)

---

## 📁 Estrutura do projeto

