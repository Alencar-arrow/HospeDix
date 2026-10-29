<div align="center">

  <h1>💻 HospeDix</h1>

  <p align="center">
    Os melhores planos de hospedagem e domínio para todas as suas necessidades, com suporte ilimitado.
  </p>

  <!-- Botão Principal -->
  <a href="https://alencar-arrow.github.io/Hospedix/" target="_blank">
    <img src="https://img.shields.io/badge/ Acessar%20HospeDix%20Ao%20Vivo-FF4B4B?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Acessar HospeDix" />
  </a>

  <br/><br/>

  <!-- Badges de Tecnologia e Estado com espaçamento -->
  ![](https://img.shields.io/badge/Status-Em%20Desenvolvimento-orange?style=flat-square)&nbsp;&nbsp;
  ![](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)&nbsp;&nbsp;
  ![](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)&nbsp;&nbsp;
  ![](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

</div>

---

### 🌐 Sobre o Projeto
O **HospeDix** é uma plataforma moderna voltada para serviços de hospedagem web e domínios, oferecendo uma interface limpa, responsiva e focada na experiência do utilizador.

### 💻 Tecnologias Utilizadas
- **HTML5** — Estruturação e semântica das páginas web
- **CSS3** — Estilização avançada, layout flexível e design responsivo
- **JavaScript** — Manipulação do DOM para interatividade e dinamismo do menu mobile

### 🚀 Funcionalidades
* **Hero Section Atraente:** Apresentação principal com chamadas para ação (*CTA*) diretas ("Testar agora" e "Testar depois").
* **Menu Responsivo Dinâmico:** Navegação adaptada para dispositivos móveis com alternância de estado e troca de ícones.
* **Métricas de Impacto:** Exibição de estatísticas e indicadores de confiança da marca (+50 mil clientes, +20 mil funcionários e 80 mil projetos).

### ⚙️ Destaque de Código (JavaScript)
O menu responsivo da aplicação foi desenvolvido de forma autónoma utilizando lógica em JavaScript puro para gerenciar a abertura/fecho do menu e a alternância dos ícones:

```javascript
var menuIcon = document.querySelector('.menu-icon');
var ul = document.querySelector('.ul');

menuIcon.addEventListener('click', () => {
    if (ul.classList.contains('ativo')) {
        ul.classList.remove('ativo');
        document.querySelector('.menu-icon img').src = 'img/menu.png';
    } else {
        ul.classList.add('ativo');
        document.querySelector('.menu-icon img').src = 'img/close.png';
    }
});
