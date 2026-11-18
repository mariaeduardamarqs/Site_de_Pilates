<div align="center">

# 🧘‍♀️ Studio Equilíbrio · Pilates

**Site institucional de um studio de pilates com turmas pequenas, atendimento próximo e um ambiente acolhedor.**

> 🎓 **Projeto com fins exclusivamente educacionais.** O Studio Equilíbrio é fictício, e nome, endereço, telefone e e-mail são apenas exemplos.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.8-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

</div>

---

## 📖 Sobre o projeto

Página única (*one-page*) desenvolvida para apresentar o **Studio Equilíbrio**, um espaço dedicado à prática de pilates com calma, atenção e cuidado. O site explica o que é o método, apresenta o studio, mostra dias e horários disponíveis, exibe uma galeria de fotos e oferece um formulário para quem quer começar.

## ✨ Funcionalidades

- 🧭 **Menu de navegação rápida** com âncoras para todas as seções
- 🏷️ **Barra superior** com logo e nome do studio
- 🖼️ **Imagem de capa** em destaque
- 📚 **Apresentação** sobre o pilates e sobre o studio
- 🃏 **Cartões informativos**: turmas, avaliação inicial e horários flexíveis
- 🗓️ **Tabela de dias e horários** com nível da turma e vagas
- 📸 **Galeria de fotos** com layout variado (esquerda, direita e centralizado)
- 📍 **Local e contato**: endereço, telefone e e-mail
- 📝 **Formulário de cadastro** com nome, e-mail, telefone, interesse, mensagem e aceite de termos
- 🔗 **Rodapé** com direitos autorais e link para a localização

## 🗂️ Seções da página

| Seção | Âncora | Descrição |
|-------|--------|-----------|
| Home | `#imagem` | Imagem de capa e título |
| Apresentação | `#inicio` | O que é o pilates e sobre nós |
| Observações | `#observacoes` | Cartões com turmas, avaliação e horários |
| Dias e Horários | `#tabela` | Tabela de aulas disponíveis |
| Galeria | `#galeria` | Fotos de alunos e instrutores |
| Local e Contato | `#contato` | Endereço, telefone e e-mail |
| Formulário | `#formulario` | Cadastro de interessados |

## 🕐 Aulas

| Dia | Horário | Nível | Vagas |
|-----|---------|-------|-------|
| Segunda | 7h | Iniciante | 4 |
| Terça | 18h | Intermediário | 2 |
| Quinta | 7h | Iniciante | 3 |
| Sábado | 9h | Livre | 5 |

> Turmas com no máximo **5 alunos** e possibilidade de reposição.

## 🛠️ Tecnologias

- **HTML5** com marcação semântica (`header`, `nav`, `main`, `section`, `footer`)
- **CSS3** em arquivo próprio (`estilos.css`)
- **[Bootstrap 5.3.8](https://getbootstrap.com/)** via CDN (grid, cards, tabela, formulário e utilitários)

## 📁 Estrutura de arquivos

```text
📦 studio-equilibrio
 ┣ 📂 img/
 ┃ ┣ logo.avif
 ┃ ┣ capa.png
 ┃ ┣ pilates.jpg
 ┃ ┣ delado.png · deitada.png · meditacao.png
 ┃ ┣ roupaclara.jpg · trio.jpg · homem.jpg
 ┃ ┣ auxiliando.avif · instrutor.avif
 ┃ ┗ localizacao.png · telefone.png · mensagem.png
 ┣ 📄 index.html
 ┣ 🎨 estilos.css
 ┗ 📄 README.md
```

## 🚀 Como executar

Não é necessário instalar nada.

1. Clone ou baixe o repositório:
   ```bash
   git clone <url-do-repositorio>
   ```
2. Abra a pasta do projeto.
3. Dê um duplo clique em `index.html` ou abra-o no navegador.

> 💡 Uma conexão com a internet é necessária para carregar o Bootstrap pelo CDN.

## ♿ Acessibilidade

- Idioma da página definido (`lang`)
- Texto alternativo (`alt`) em todas as imagens
- Navegação identificada com `aria-label`
- Campos do formulário associados a `label`

## 🔮 Próximos passos

- [ ] Enviar os dados do formulário para um serviço real (hoje o `action` é `#`)
- [ ] Adicionar o atributo `name` nos campos do formulário
- [ ] Trocar o `type="nome"` do campo de nome por `type="text"`
- [ ] Tornar a imagem de capa responsiva (largura fixa de 1890px)
- [ ] Substituir os espaçamentos feitos com `<br>` por regras de CSS
- [ ] Incluir o texto completo dos termos e condições

## 📬 Contato (fictício)

> ⚠️ Os dados abaixo são **fictícios** e foram criados apenas para fins educacionais. O endereço foi baseado no nome do studio fictício.

📍 Rua Edy Lourdes, 63 · Taboão · Bragança Paulista · SP
📞 (11) 90000-0011
✉️ contato@studioequilibrio.exemplo

---

<div align="center">

🎓 Projeto educacional · © 2026 Studio Equilíbrio · Pilates (fictício)

</div>
