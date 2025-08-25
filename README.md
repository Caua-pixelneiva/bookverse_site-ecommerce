# BookVerse - E-commerce de Livros

## 📚 Sobre o Projeto

BookVerse é um site de e-commerce completo para venda de livros, desenvolvido com HTML5 e CSS3 puro, sem JavaScript. O projeto foi criado seguindo as melhores práticas de desenvolvimento web responsivo e acessibilidade.

## 🎨 Design e Identidade Visual

### Logotipo
- **Nome**: BookVerse
- **Conceito**: Livraria online moderna e acessível
- **Arquivo**: `images/bookverse_logo.png`

### Paleta de Cores
- **Azul Profundo**: #1E3A8A (confiança e conhecimento)
- **Laranja Vibrante**: #F97316 (energia e criatividade)
- **Branco**: #FFFFFF (limpeza e clareza)
- **Cinza Claro**: #F3F4F6 (neutralidade)

### Tipografia
- **Títulos**: Inter (moderna e legível)
- **Corpo do texto**: Open Sans (clara para leitura)

## 🏗️ Estrutura do Projeto

```
bookverse-ecommerce/
├── index.html                 # Página inicial
├── css/
│   └── styles.css            # Estilos responsivos
├── images/
│   └── bookverse_logo.png    # Logotipo
├── pages/
│   ├── quem-somos.html       # Página institucional
│   ├── busca.html            # Resultados de busca
│   ├── produtos.html         # Grade de produtos
│   ├── produto.html          # Produto individual
│   ├── contato.html          # Formulário de contato
│   ├── cadastro.html         # Formulário de registro
│   └── pedidos.html          # Carrinho e pedidos
└── README.md                 # Documentação
```

## 📱 Páginas Implementadas

### 1. **Página Inicial** (`index.html`)
- Hero section com call-to-action
- Livros em destaque
- Categorias populares
- Newsletter signup
- Layout responsivo com Grid/Flexbox

### 2. **Quem Somos** (`pages/quem-somos.html`)
- História da empresa
- Missão e valores
- Informações da equipe
- Layout em duas colunas (desktop)

### 3. **Busca** (`pages/busca.html`)
- Resultados de pesquisa
- Filtros por categoria, preço e avaliação
- Ordenação de produtos
- Paginação

### 4. **Grade de Produtos** (`pages/produtos.html`)
- Catálogo completo de livros
- Sidebar com filtros avançados
- Grid responsivo de produtos
- Sistema de ordenação

### 5. **Produto Individual** (`pages/produto.html`)
- Detalhes completos do livro
- Galeria de imagens
- Avaliações de clientes
- Produtos relacionados
- Botões de compra

### 6. **Contato** (`pages/contato.html`)
- Formulário de contato completo
- Informações da empresa
- Mapa de localização (placeholder)
- Redes sociais

### 7. **Cadastro** (`pages/cadastro.html`)
- Formulário de registro detalhado
- Validação de campos
- Endereço de entrega
- Vantagens de ter conta

### 8. **Pedidos** (`pages/pedidos.html`)
- Sistema de abas (Todos, Carrinho, Em Andamento, Entregues)
- Carrinho de compras funcional
- Tracking de pedidos
- Histórico de compras

## 🎯 Funcionalidades

### E-commerce
- ✅ Catálogo de produtos com filtros
- ✅ Sistema de busca
- ✅ Carrinho de compras
- ✅ Processo de checkout
- ✅ Tracking de pedidos
- ✅ Avaliações de produtos
- ✅ Newsletter

### Formulários
- ✅ Contato
- ✅ Cadastro de usuário
- ✅ Newsletter
- ✅ Busca de produtos

### Navegação
- ✅ Menu principal responsivo
- ✅ Breadcrumbs
- ✅ Paginação
- ✅ Links internos

## 📐 Responsividade

### Breakpoints
- **Mobile**: < 550px
- **Tablet**: 550px - 1100px  
- **Desktop**: > 1100px

### Adaptações por Dispositivo

#### Mobile (< 550px)
- Layout de coluna única
- Navegação empilhada
- Grid de produtos em 1 coluna
- Formulários simplificados
- Botões otimizados para touch

#### Tablet (550px - 1100px)
- Layout de 2-3 colunas
- Navegação adaptada
- Grid de produtos em 2 colunas
- Sidebar reduzida

#### Desktop (> 1100px)
- Layout completo multi-coluna
- Navegação horizontal
- Grid de produtos em 4 colunas
- Sidebar fixa

## 🛠️ Tecnologias Utilizadas

### HTML5
- Estrutura semântica
- Formulários acessíveis
- Meta tags responsivas
- Validação nativa

### CSS3
- **Grid Layout**: Para layouts de produtos e categorias
- **Flexbox**: Para navegação e componentes flexíveis
- **Media Queries**: Para responsividade
- **Custom Properties**: Para cores e espaçamentos
- **Transitions**: Para interações suaves

### Sem JavaScript
- Funcionalidade baseada em CSS puro
- Estados hover e focus
- Navegação por âncoras
- Formulários nativos

## 🎨 Design System

### Componentes
- **Botões**: Primary, Secondary, Outline, Danger
- **Cards**: Produtos, Categorias, Pedidos
- **Formulários**: Inputs, Selects, Textareas
- **Navegação**: Header, Footer, Breadcrumbs
- **Layout**: Container, Grid, Flexbox

### Estados Visuais
- **Hover**: Efeitos de elevação e cor
- **Focus**: Contornos acessíveis
- **Active**: Estados de clique
- **Disabled**: Estados inativos

## 🚀 Como Usar

1. **Abrir o projeto**:
   ```bash
   # Navegue até o diretório
   cd bookverse-ecommerce
   
   # Abra index.html no navegador
   open index.html
   ```

2. **Testar responsividade**:
   - Use as ferramentas de desenvolvedor do navegador
   - Teste nos breakpoints: 400px, 768px, 1200px
   - Verifique a navegação em dispositivos móveis

3. **Navegar pelo site**:
   - Explore todas as páginas através do menu
   - Teste os formulários
   - Verifique os filtros de produtos
   - Simule um processo de compra

## ✅ Checklist de Requisitos

### Técnicos
- ✅ **Sem JavaScript**: Apenas HTML e CSS
- ✅ **Sem Tabelas**: Layout com Grid e Flexbox
- ✅ **Responsivo**: 3 breakpoints implementados
- ✅ **Grid/Flexbox**: Layouts modernos
- ✅ **8 Páginas**: Todas implementadas

### Design
- ✅ **Logotipo**: Criado e integrado
- ✅ **Wireframe**: Documentado
- ✅ **Identidade Visual**: Cores e fontes definidas
- ✅ **Consistência**: Design uniforme

### Funcionalidades
- ✅ **E-commerce**: Funcionalidades completas
- ✅ **Formulários**: Contato e cadastro
- ✅ **Navegação**: Intuitiva e acessível
- ✅ **Conteúdo**: Lorem ipsum conforme solicitado

## 📋 Próximos Passos (Opcional)

Para expandir o projeto, considere:

1. **Backend**: Integração com banco de dados
2. **JavaScript**: Interatividade avançada
3. **SEO**: Otimização para motores de busca
4. **Performance**: Otimização de imagens e CSS
5. **Acessibilidade**: Melhorias WCAG
6. **PWA**: Transformar em Progressive Web App

## 📞 Suporte

Para dúvidas ou sugestões sobre o projeto BookVerse, entre em contato através da página de contato do site.

---

**BookVerse** - Sua livraria online completa e responsiva! 📚✨

