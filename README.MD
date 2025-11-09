# 🌌 Projeto: Gerador de eBook — "JavaScript Wars"

Este projeto define um **prompt estruturado** para gerar automaticamente **títulos e conteúdos de eBooks** sobre **JavaScript**, com uma **temática épica inspirada em Star Wars**.
Projeto realizado durante o bootcamp Fundamentos da IA Generativa do Santander.
---

## 🪐 Objetivo

Criar um material educativo e divertido sobre **JavaScript**, explorando seus principais conceitos de forma simples, envolvente e visualmente atrativa — como se fosse uma saga galáctica do código.

---

## ⚙️ Estrutura do Prompt

| Campo | Descrição |
| :------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **título** | Gera 5 variações de títulos curtos e épicos sobre JavaScript, inspirados em Star Wars. |
| **conteúdo** | Produz textos para eBook explicando tópicos fundamentais de JavaScript com exemplos práticos e linguagem simples. |

---

## 🧠 Exemplos de uso

Você pode usar este prompt em modelos de linguagem (como GPT) para gerar conteúdos automáticos:

```javascript
// Exemplo de uso com API ou CLI
const prompt = `
Crie um título de um ebook sobre o tema de JavaScript,
o ebook é do nicho de programação e o subnicho é JavaScript,
o título deve ser épico e curto, e tenha uma temática de Star Wars no título,
me liste 5 variações de títulos.

Depois, faça um texto para ebook com foco em JavaScript,
listando os principais conceitos com exemplos de código.
Explique de forma simples, enxuta e com títulos criativos por tópico.
`;
