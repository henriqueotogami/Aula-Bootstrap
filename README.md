# Aula-Bootstrap

> Repositório com os arquivos da aula de Bootstrap do Bootcamp Desenvolvedor Python Full Stack 2020. Página de demonstração com navbar, seções e layout responsivo usando o framework Bootstrap.

<br>
<div align="center">
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/henriqueotogami/Aula-Bootstrap">
  <img alt="GitHub license" src="https://img.shields.io/github/license/henriqueotogami/Aula-Bootstrap">
  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/henriqueotogami/Aula-Bootstrap">
</div>
<br>
<div align="center">
  <img src="https://img.shields.io/github/forks/henriqueotogami/Aula-Bootstrap?style=flat">
  <img src="https://img.shields.io/github/stars/henriqueotogami/Aula-Bootstrap?style=flat">
  <img src="https://img.shields.io/github/issues/henriqueotogami/Aula-Bootstrap">
</div>

---

## 📋 Sobre o Projeto

Este projeto contém uma página web de exemplo desenvolvida durante o Bootcamp Desenvolvedor Python Full Stack 2020. O foco é o aprendizado prático do **Bootstrap**: uso de componentes (navbar, grid, containers), customização com CSS e construção de um layout responsivo em uma única página com as seções Quem somos, Parceiros e Serviços.

## 📁 Estrutura do Projeto

### Página principal
- **index.html** — Página única com navbar, seções e footer; utiliza classes do Bootstrap e estilos customizados.

### Estilos
- **css/style.css** — Estilos personalizados (cores da navbar, seções, margens e tipografia).

### Framework
- **bootstrap/** — Arquivos do Bootstrap (CSS e JS) na pasta do projeto para uso offline.

### Recursos (referenciados no HTML)
- **icons/** — Logo e ícones (ex.: `logo-global-labs.jpg`).
- **images/** — Imagens das seções (wallpaper, parceiros, serviços). Coloque aqui os arquivos referenciados no `index.html` para que a página carregue corretamente.

## 📂 Estrutura do repositório

```
LICENSE
README.md
index.html              # página principal
css/
    style.css            # estilos customizados
bootstrap/
    css/                 # estilos Bootstrap
    js/                  # scripts Bootstrap
icons/                  # logos e ícones (adicionar arquivos)
images/                 # imagens das seções (adicionar arquivos)
```

## 🛠️ Tecnologias Utilizadas

- **HTML5** — Estrutura da página
- **Bootstrap** — Framework CSS para layout responsivo e componentes
- **CSS3** — Customização de cores, espaçamentos e tipografia

## 📝 Funcionalidades Principais

### Navbar
- Barra de navegação fixa com logo e links para as seções (Quem somos, Parceiros, Serviços).
- Estilo customizado (cor de fundo e contraste).

### Seções
- **Quem somos** — Área com título, imagem circular e texto descritivo.
- **Parceiros** — Grid com três colunas para exibição de logos de parceiros.
- **Serviços** — Três colunas com texto e imagens ilustrativas.

### Footer
- Rodapé com créditos do desenvolvedor e do bootcamp.

### Layout responsivo
- Uso do grid do Bootstrap (`container`, `row`, `col-lg-4`) para adaptação em diferentes tamanhos de tela.

## 🚀 Como visualizar o projeto

### Opção 1: Abrir direto no navegador
1. Clone o repositório:
   ```bash
   git clone https://github.com/henriqueotogami/Aula-Bootstrap.git
   cd Aula-Bootstrap
   ```
2. Abra o arquivo `index.html` no navegador (duplo clique ou arrastar para o navegador).

### Opção 2: Servidor local (recomendado)
Para evitar problemas com carregamento de arquivos locais (CORS), use um servidor HTTP simples:

```bash
# Com Python 3
python -m http.server 8000

# Ou com Node.js (npx)
npx serve .
```

Acesse no navegador: `http://localhost:8000`

### Imagens e ícones
O `index.html` referencia imagens em `icons/` e `images/`. Se essas pastas ou arquivos não existirem, inclua as imagens correspondentes ou ajuste os caminhos no HTML para que a página exiba corretamente.

## 📚 Conteúdos abordados

- ✅ Estrutura básica de uma página HTML5
- ✅ Uso do Bootstrap (CSS e grid system)
- ✅ Navbar e navegação entre seções
- ✅ Containers e sistema de grid (row/col)
- ✅ Componentes Bootstrap (rounded-circle, margin, etc.)
- ✅ Customização com CSS (cores, padding, tipografia)
- ✅ Layout responsivo com colunas (`col-lg-4`)
- ✅ Organização de pastas (css, bootstrap, images, icons)

## 📄 Licença

Este projeto está licenciado sob a MIT License — veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📖 Referências

- [Bootstrap — Documentação oficial](https://getbootstrap.com/docs/)
- Código-fonte em `index.html` e `css/style.css` neste repositório

---

### Hashtags
#Bootstrap #HTML #CSS #FrontEnd #ResponsiveDesign #WebDevelopment #Bootcamp #PythonFullStack #OpenSource #GitHub

### Meta Keywords
```
Bootstrap, HTML5, CSS3, layout responsivo, navbar, grid system,
bootcamp Python, desenvolvimento web, front-end, página única,
componentes Bootstrap, customização CSS
```
