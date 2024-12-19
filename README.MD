# UI Button Library

Uma biblioteca moderna e reutilizável de componentes de botão construída com SASS.

## 🚀 Características

- Múltiplas variações de botões (primário e secundário)
- Três tamanhos diferentes (pequeno, médio e grande)
- Suporte para ícones (Font Awesome)
- Totalmente personalizável via variáveis SASS
- Design responsivo e moderno
- Transições suaves

## 📦 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/ui-button-library.git
```

2. Instale as dependências:
```bash
npm install
```

3. Execute o projeto:
```bash
npm start
```

## 🎨 Personalização

Todas as cores, tamanhos e espaçamentos podem ser personalizados através do arquivo `styles/variables.scss`:

```scss
// Colors
$color-primary: #4CAF50;
$color-secondary: #2196F3;

// Sizes
$spacing-xs: 6px;
$spacing-sm: 12px;
$spacing-md: 20px;
$spacing-lg: 28px;

// Font sizes
$font-small: 14px;
$font-medium: 16px;
$font-large: 18px;
```

## 💻 Uso

### Botões Básicos

```html
<!-- Botão Primário -->
<button class="button button-primary button-medium">Botão Primário</button>

<!-- Botão Secundário -->
<button class="button button-secondary button-medium">Botão Secundário</button>
```

### Botões com Ícones

```html
<!-- Botão com Ícone à Esquerda -->
<button class="button button-primary button-medium button-icon">
    <i class="fas fa-plus"></i>
    Adicionar
</button>

<!-- Botão com Ícone à Direita -->
<button class="button button-secondary button-medium button-icon-right">
    Próximo
    <i class="fas fa-arrow-right"></i>
</button>
```

## 📏 Tamanhos Disponíveis

- Small: `button-small`
- Medium: `button-medium`
- Large: `button-large`

## 🎯 Variantes

- Primário: `button-primary`
- Secundário: `button-secondary`

## 🛠️ Tecnologias Utilizadas

- HTML5
- SASS/SCSS
- Font Awesome (para ícones)

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 🤝 Contribuindo

1. Faça um Fork do projeto
2. Crie sua Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a Branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request