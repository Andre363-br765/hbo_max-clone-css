<img src="./docs/readme-images/logo_hbo-max.png" alt="Logotipo da HBO Max" width="200" />

# HBO Max Clone

Clone visual da plataforma **HBO Max**, desenvolvido com **HTML5 e CSS3 puro**, com foco em **layout**, **animações**, **interações visuais modernas** e **responsividade** para múltiplos dispositivos.

O projeto foi criado com o objetivo de **praticar organização de CSS**, efeitos visuais avançados e boas práticas de estruturação front-end.

---

## 📌 Sumário

- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Funcionalidades](#-funcionalidades)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Recursos CSS Aplicados](#-recursos-css-aplicados)
- [Aprendizados do Projeto](#-aprendizados-do-projeto)
- [Prévia do Design](#-prévia-do-design)

---

## 🛠 Tecnologias Utilizadas

- **HTML5**
- **CSS3**
  - Flexbox
  - Grid Layout
  - Variáveis CSS (CSS Custom Properties)
  - Animações e transições
- **Google Fonts**
  - [Raleway](https://fonts.google.com/specimen/Raleway)
  - [Quicksand](https://fonts.google.com/specimen/Quicksand)

```css
@import url("https://fonts.googleapis.com/css2?family=Raleway:wght@300;400;500;600;700&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;700&display=swap");
```

---

## ✨ Funcionalidades

### Interface

* Navbar fixa com logo e botões de ação
* Header com **gradiente animado**
* Layout inspirado na identidade visual da HBO Max

### Interações

* Cards de planos com **efeito 3D utilizando perspective**
* Cards de conteúdos com **troca de imagem ao passar o mouse**
* Scroll customizado via CSS

### Páginas e Conteúdo

* Página inicial
* Página de login
* Lista de filmes e séries
* Rodapé completo com links institucionais e redes sociais

### Responsividade e Usabilidade

* Layout adaptado para:

  * Celulares
  * Tablets
  * Desktops
* Media queries específicas por tamanho de tela
* **Efeitos de hover e transformações desativados automaticamente em dispositivos touch**, garantindo melhor usabilidade

---

## 📁 Estrutura do Projeto

```text
hbo-max-clone/
├─ src/
│  ├─ css/
│  │   ├─ global/
│  │   │   ├─ base.css          # Reset, variáveis e estilos globais
│  │   │   └─ components.css    # Botões, menu, footer e componentes reutilizáveis
│  │   │
│  │   ├─ layout/
│  │   │   ├─ home.css          # Layout da página inicial
│  │   │   ├─ login.css         # Layout da página de login
│  │   │   └─ animations.css   # Animações e efeitos visuais
│  │   │
│  │   ├─ responsive/
│  │   │   ├─ global.css        # Ajustes globais responsivos
│  │   │   ├─ home.css          # Responsividade da home
│  │   │   └─ login.css         # Responsividade do login
│  │   │
│  │   ├─ index.css             # Arquivo principal da home
│  │   └─ signIn.css            # Arquivo principal do login
│  │
│  ├─ assets/
│  │   ├─ images/
│  │   └─ icons/
│  │
│  └─ pages/
│       └─ signIn.html
│
├─ index.html
└─ README.md
```

---

## 🎨 Recursos CSS Aplicados

* Fundamentos do CSS
* Flexbox e Grid Layout
* Design responsivo
* Pseudo-classes (`:hover`, `:focus`)
* Pseudo-elementos
* Transformações 2D e 3D
* Transições e animações
* Seletores modernos (`:has`)
* Media queries baseadas em tipo de ponteiro (`pointer: coarse`)
* Scrollbar customizado
* Validação visual de campos de formulário

---

## 📚 Aprendizados do Projeto

* Organização escalável de CSS por responsabilidade
* Criação de layouts complexos sem uso de JavaScript
* Uso de seletores modernos para interações avançadas
* Desenvolvimento de animações puramente com CSS
* Adaptação de efeitos visuais para dispositivos touch
* Separação clara entre estilos globais, layout e responsividade

---

## 📸 Prévia do Design

<img src="./docs/readme-images/design.png" alt="Prévia do design do projeto HBO Max Clone" width="1300" />