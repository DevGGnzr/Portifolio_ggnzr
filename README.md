# 🚀 Meu Portfólio

Um portfólio moderno e responsivo para mostrar seus projetos do GitHub de forma elegante.

## ✨ Características

- **Design Responsivo**: Funciona perfeitamente em desktop, tablet e mobile
- **Performance Otimizada**: Carregamento rápido e animações suaves
- **Acessibilidade**: Seguindo as melhores práticas de acessibilidade
- **GitHub Pages Ready**: Pronto para deploy no GitHub Pages
- **Interatividade**: Formulário de contato funcional e navegação suave
- **Modern Design**: Interface limpa e profissional

## 🛠️ Tecnologias Utilizadas

- HTML5 semântico
- CSS3 com variáveis customizadas
- JavaScript vanilla (ES6+)
- Font Awesome para ícones
- Google Fonts (Inter)

## 📁 Estrutura do Projeto

```
portifolio/
├── index.html          # Página principal
├── style.css           # Estilos CSS
├── script.js           # JavaScript interativo
└── README.md           # Documentação
```

## 🎯 Como Personalizar

### 1. Informações Pessoais

Edite o arquivo `index.html` e substitua:

- **Nome e título**: Altere "Meu Portfólio" e "Desenvolvedor" no cabeçalho
- **Informações de contato**: Substitua os placeholders de email, LinkedIn e GitHub
- **Texto sobre**: Personalize a seção "Sobre Mim" com suas informações

### 2. Projetos

Para cada um dos 4 projetos, edite no arquivo `index.html`:

```html
<!-- Exemplo de como personalizar um projeto -->
<div class="project-card">
    <div class="project-image">
        <i class="fab fa-js-square"></i> <!-- Mude o ícone -->
    </div>
    <div class="project-content">
        <h3 class="project-title">Nome do Seu Projeto</h3>
        <p class="project-description">
            Descrição detalhada do seu projeto...
        </p>
        <div class="project-tech">
            <span class="tech-tag">Tecnologia 1</span>
            <span class="tech-tag">Tecnologia 2</span>
            <!-- Adicione mais tecnologias -->
        </div>
        <div class="project-links">
            <a href="https://github.com/SEUUSUARIO/SEUPROJETO" target="_blank" class="project-link">
                <i class="fab fa-github"></i> Código
            </a>
            <a href="https://SEUUSUARIO.github.io/SEUPROJETO" target="_blank" class="project-link">
                <i class="fas fa-external-link-alt"></i> Demo
            </a>
        </div>
    </div>
</div>
```

### 3. Links dos Repositórios

Substitua os links dos projetos:

1. **Projeto 1**: `https://github.com/SEUUSUARIO/projeto1`
2. **Projeto 2**: `https://github.com/SEUUSUARIO/projeto2`
3. **Projeto 3**: `https://github.com/SEUUSUARIO/projeto3`
4. **Projeto 4**: `https://github.com/SEUUSUARIO/projeto4`

### 4. Informações de Contato

Atualize os links e informações:

```html
<!-- Email -->
<p>seu.email@example.com</p>

<!-- LinkedIn -->
<p>linkedin.com/in/seuusuario</p>

<!-- GitHub -->
<p>github.com/seuusuario</p>
```

## 🎨 Personalização Visual

### Cores

As cores podem ser facilmente alteradas no arquivo `style.css` através das variáveis CSS:

```css
:root {
    --primary-color: #6366f1;        /* Cor principal */
    --primary-dark: #4f46e5;         /* Cor principal escura */
    --secondary-color: #f1f5f9;      /* Cor secundária */
    --text-primary: #1e293b;         /* Cor do texto principal */
    --text-secondary: #64748b;       /* Cor do texto secundário */
}
```

### Fontes

Para alterar a fonte, substitua no cabeçalho do HTML:

```html
<link href="https://fonts.googleapis.com/css2?family=SuaFonte:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

E no CSS:

```css
body {
    font-family: 'SuaFonte', sans-serif;
}
```

## 🚀 Deploy no GitHub Pages

### 1. Criar Repositório

1. Crie um novo repositório no GitHub
2. Nome sugerido: `portfolio` ou `meu-portfolio`
3. Faça o repositório público

### 2. Upload dos Arquivos

```bash
# Clone o repositório
git clone https://github.com/SEUUSUARIO/NOMEREPOSITORIO.git
cd NOMEREPOSITORIO

# Adicione os arquivos do portfólio
# Copie: index.html, style.css, script.js, README.md

# Commit e push
git add .
git commit -m "Adicionar portfólio inicial"
git push origin main
```

### 3. Ativar GitHub Pages

1. Vá para o repositório no GitHub
2. Clique em **Settings**
3. Role até **Pages**
4. Em **Source**, selecione **Deploy from a branch**
5. Escolha **main** branch e **/ (root)**
6. Clique em **Save**

### 4. Acesso

Seu portfólio estará disponível em:
`https://SEUUSUARIO.github.io/NOMEREPOSITORIO`

## 📱 Recursos Incluídos

### Navegação
- Menu responsivo com hambúrguer no mobile
- Scroll suave entre seções
- Header com efeito de transparência

### Interatividade
- Animações de entrada para elementos
- Efeitos hover em cartões e botões
- Formulário de contato com validação

### Performance
- CSS otimizado com animações GPU
- JavaScript com throttling para scroll
- Lazy loading preparado para imagens

## 🔧 Personalização Avançada

### Adicionar Mais Seções

Para adicionar novas seções, siga este padrão:

```html
<section id="nova-secao" class="nova-secao">
    <div class="container">
        <h2 class="section-title">Título da Seção</h2>
        <p class="section-subtitle">Subtítulo da seção</p>
        <!-- Conteúdo da seção -->
    </div>
</section>
```

### Adicionar Animações

Use as classes CSS disponíveis:

```html
<div class="fade-in-up">Elemento com animação</div>
```

### Integrar com APIs

O formulário pode ser integrado com serviços como:
- [Formspree](https://formspree.io/)
- [Netlify Forms](https://www.netlify.com/products/forms/)
- [EmailJS](https://www.emailjs.com/)

## 📧 Suporte

Se precisar de ajuda:

1. Verifique se todos os arquivos estão no repositório
2. Confirme se o GitHub Pages está ativo
3. Aguarde alguns minutos para o deploy

## 📄 Licença

Este projeto é de uso livre. Sinta-se à vontade para usar e modificar conforme necessário.

---

**Dica**: Lembre-se de atualizar regularmente seu portfólio com novos projetos e conquistas! 🎯