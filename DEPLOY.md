# 🚀 Guia Rápido - GitHub Pages

## ✅ Checklist para Deploy

### 1. Preparação dos Arquivos
- [ ] `index.html` personalizado com seus dados
- [ ] `style.css` com suas preferências de cores
- [ ] `script.js` funcionando corretamente
- [ ] Links dos repositórios atualizados

### 2. Informações para Personalizar

**Substitua no `index.html`:**

```
SEUUSUARIO → seu-usuario-github
SEUEMAIL → seu.email@exemplo.com
SEULINKEDIN → linkedin.com/in/seu-usuario
```

**Links dos 4 Projetos:**
1. Projeto 1: `https://github.com/SEUUSUARIO/projeto1`
2. Projeto 2: `https://github.com/SEUUSUARIO/projeto2`  
3. Projeto 3: `https://github.com/SEUUSUARIO/projeto3`
4. Projeto 4: `https://github.com/SEUUSUARIO/projeto4`

### 3. Comandos Git

```bash
# Inicializar repositório
git init
git add .
git commit -m "Primeiro commit - Portfólio"

# Conectar ao GitHub
git remote add origin https://github.com/SEUUSUARIO/portfolio.git
git branch -M main
git push -u origin main
```

### 4. Ativar GitHub Pages

1. **Settings** → **Pages**
2. **Source**: Deploy from a branch
3. **Branch**: main
4. **Folder**: / (root)
5. **Save**

### 5. URL Final
`https://SEUUSUARIO.github.io/portfolio`

## 🎯 Personalização Rápida

### Alterar Cores Principais
No `style.css`, linha 13-20:
```css
:root {
    --primary-color: #6366f1;  /* Sua cor preferida */
    --primary-dark: #4f46e5;   /* Versão mais escura */
}
```

### Exemplos de Cores
- Azul: `#3b82f6`
- Verde: `#10b981` 
- Roxo: `#8b5cf6`
- Vermelho: `#ef4444`
- Orange: `#f59e0b`

### Ícones dos Projetos
Substitua as classes dos ícones:
- JavaScript: `fab fa-js-square`
- React: `fab fa-react`
- Python: `fab fa-python`
- Java: `fab fa-java`
- Node.js: `fab fa-node-js`
- PHP: `fab fa-php`

## 🛠️ Manutenção

### Adicionar Novo Projeto
1. Copie um bloco `project-card` existente
2. Atualize título, descrição, tecnologias e links
3. Faça commit das mudanças

### Atualizar Informações
- Sempre edite o `index.html`
- Teste localmente antes do commit
- As mudanças aparecem no GitHub Pages em alguns minutos

## 📱 Teste de Responsividade

Teste em diferentes tamanhos:
- Desktop (1920px+)
- Laptop (1366px)
- Tablet (768px)
- Mobile (375px)

## 🎨 Recursos Visuais

### Gradientes Disponíveis
```css
/* Azul para roxo */
background: linear-gradient(135deg, #6366f1, #8b5cf6);

/* Verde para azul */
background: linear-gradient(135deg, #10b981, #3b82f6);

/* Orange para vermelho */
background: linear-gradient(135deg, #f59e0b, #ef4444);
```

### Sombras
- Leve: `var(--shadow-sm)`
- Média: `var(--shadow-md)`
- Forte: `var(--shadow-lg)`
- Extra: `var(--shadow-xl)`

## 🚨 Problemas Comuns

### Página não carrega
- Verifique se o arquivo se chama `index.html`
- Confirme se está na pasta raiz
- Aguarde 5-10 minutos após ativar Pages

### CSS/JS não funcionam
- Confirme se os arquivos estão na mesma pasta
- Verifique os nomes dos arquivos (`style.css`, `script.js`)
- Teste localmente primeiro

### Links não funcionam
- Use URLs completas para repositórios
- Teste os links antes do deploy
- Confirme se os repositórios são públicos

## 📊 Métricas e Analytics

### Google Analytics (Opcional)
Adicione antes do `</head>`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

## 🔗 Recursos Úteis

- **Font Awesome Icons**: https://fontawesome.com/icons
- **Google Fonts**: https://fonts.google.com/
- **Color Picker**: https://coolors.co/
- **GitHub Pages Docs**: https://docs.github.com/pages

---
**Tempo estimado para setup completo: 15-30 minutos** ⏱️