# Marvel Fans — Site simples em Flask

> Um site simples e completo feito em **Flask**, HTML, CSS e JavaScript (AJAX), onde fãs se cadastram para ser o **fã número 1 da Marvel**.

---

> **Coloque suas imagens aqui**: substitua `./.github/IMG_PLACEHOLDER.png` por capturas de tela do seu carrossel e do formulário.

---

## O que eu fiz

Este projeto implementa uma **única página** que contém:

- Um **carrossel automático** de imagens dos filmes da Marvel (troca a cada **5 segundos**).
- Uma chamada central: **“Faça um cadastro para ser o fã número 1 da Marvel!”**
- Um **formulário de cadastro** com os campos:
  - Nome (texto)
  - Idade (número)
  - Super-herói favorito (select)
  - Filme favorito (select)
  - Descrição (textarea)
  - Botão **Enviar Cadastro**
- Envio dos dados via **AJAX (fetch)** para a rota Flask `/cadastrar`.
- Os cadastros são **armazenados em memória** (lista Python — sem banco de dados).
- Após enviar, o site mostra uma mensagem de sucesso e **atualiza dinamicamente** um ranking com todos os fãs cadastrados.
- O ranking é **embaralhado** na primeira exibição (sorteio do primeiro lugar) — cadastros novos entram pela ordem de chegada.
- Layout: fundo preto, textos em branco e vermelho, fonte moderna (Poppins/Roboto), centralizado, CSS simples (sem frameworks).

---

## Estrutura do projeto

