# Portfólio Pessoal - React + To-Do List

Um portfólio pessoal moderno e responsivo desenvolvido com React, incluindo um projeto To-Do List interativo com persistência de dados.

## 🚀 Características

✨ **Portfólio:**
- Design moderno e responsivo
- Gradientes visuais atraentes
- Totalmente adaptado para mobile
- Navegação suave (smooth scroll)
- Formulário de contato funcional
- 6 projetos showcase

🎯 **To-Do List Interativo:**
- Adicionar, marcar e deletar tarefas
- Filtrar por: Todas, Ativas, Concluídas
- Persistência de dados com localStorage
- Interface intuitiva com modal
- Estatísticas de tarefas
- Responsivo e acessível

## 📁 Estrutura do Projeto

```
protifolio2/
├── public/
│   ├── index.html
│   ├── styles.css (opcional - fallback HTML)
│   └── script.js (opcional - fallback HTML)
├── src/
│   ├── App.js (Componente principal)
│   ├── App.css
│   ├── index.js (Entrada React)
│   ├── index.css
│   └── components/
│       ├── Header.js
│       ├── Header.css
│       ├── About.js
│       ├── About.css
│       ├── Projects.js
│       ├── Projects.css
│       ├── ProjectCard.js
│       ├── ProjectCard.css
│       ├── Contact.js
│       ├── Contact.css
│       ├── Footer.js
│       ├── Footer.css
│       ├── TodoModal.js (To-Do List)
│       └── TodoModal.css
└── package.json
```

## 📦 Instalação

### Pré-requisitos
- Node.js (v14 ou superior)
- npm ou yarn

### Passos

1. **Navegue até a pasta do projeto:**
```bash
cd protifolio2
```

2. **Instale as dependências:**
```bash
npm install
```

3. **Inicie o servidor de desenvolvimento:**
```bash
npm start
```

O navegador abrirá automaticamente em `http://localhost:3000`

## 🎮 Como Usar o To-Do List

1. Clique no card "To-Do List" na seção de Projetos
2. **Adicionar tarefa:** Digite no input e clique em "Adicionar"
3. **Marcar concluída:** Clique no checkbox
4. **Deletar:** Clique no ícone 🗑️
5. **Filtrar:** Use os botões Todas/Ativas/Concluídas
6. **Limpar concluídas:** Clique em "Limpar Concluídas"
7. **Exportar dados:** As tarefas são salvas automaticamente no seu navegador

## 🛠️ Scripts Disponíveis

```bash
npm start      # Executa em modo desenvolvimento
npm build      # Cria build para produção
npm test       # Executa testes
npm eject      # (Cuidado: irreversível)
```

## 🎨 Customização

### Alterar cores
Edite as cores em `src/App.css` ou em cada arquivo de componente CSS.

### Adicionar novos projetos
Edite o array `projects` em `src/components/Projects.js`

### Modificar informações pessoais
- **Nome:** `src/components/Header.js`
- **Sobre:** `src/components/About.js`
- **Contato:** `src/components/Contact.js`

## 📱 Responsividade

O projeto é totalmente responsivo com breakpoints para:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (< 768px)

## 💾 Armazenamento de Dados

O To-Do List utiliza o `localStorage` do navegador para persistir os dados. Isso significa que suas tarefas serão salvas mesmo após fechar o navegador.

## 🌐 Deploy

Para fazer deploy da aplicação:

```bash
npm run build
```

A pasta `build/` será criada com os arquivos otimizados prontos para produção.

## 📚 Tecnologias Utilizadas

- React 18.2
- JavaScript ES6+
- CSS3 (Flexbox, Grid, Animations)
- localStorage API
- Font Awesome (ícones)

## 📝 Personalizando o Portfólio

### Alterar Informações Pessoais

1. **Header** - Edite `src/components/Header.js`:
   - Altere o texto de boas-vindas
   - Modifique seu nome e descrição

2. **Sobre** - Edite `src/components/About.js`:
   - Atualize sua biografia
   - Modifique a lista de habilidades

3. **Projetos** - Edite `src/components/Projects.js`:
   - Adicione, remova ou edite projetos no array `projects`
   - Atualize títulos, descrições e tecnologias

4. **Contato** - Edite `src/components/Contact.js`:
   - Atualize o email e links sociais
   - Customize a mensagem de boas-vindas

### Alterar Cores

Edite o gradiente nas seções CSS:
- `Header.css` - Procure por `linear-gradient(135deg, #667eea 0%, #764ba2 100%)`
- Altere para suas cores preferidas

## 🎨 Tecnologias Utilizadas

- **React 18** - Biblioteca JavaScript para UI
- **CSS3** - Estilização com Grid e Flexbox
- **JavaScript ES6+** - Seletores modernos

## 📱 Responsividade

O portfólio é totalmente responsivo e se adapta a:
- 📱 Celulares (< 768px)
- 📱 Tablets (768px - 1024px)
- 💻 Desktops (> 1024px)

## 🤝 Contribuições

Sinta-se livre para fazer fork deste projeto e criar sua própria versão personalizada!

## 📝 Licença

Este projeto está disponível para uso pessoal.

## 👤 Autor

**Vitor**

- GitHub: [@Vitor](https://github.com)
- Linkedin: [Vitor](https://www.linkedin.com/in/vitor-martimiani-0ab245268)

---

Feito com ❤️ usando React
│   ├── components/
│   │   ├── Header.js
│   │   ├── Header.css
│   │   ├── About.js
│   │   ├── About.css
│   │   ├── Projects.js
│   │   ├── Projects.css
│   │   ├── ProjectCard.js
│   │   ├── ProjectCard.css
│   │   ├── Contact.js
│   │   ├── Contact.css
│   │   ├── Footer.js
│   │   └── Footer.css
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   └── index.css
├── package.json
├── .gitignore
└── README.md
```

## 🛠️ Instalação

1. **Clone o repositório:**
   ```bash
   git clone <seu-repositorio>
   cd protifolio2
   ```

2. **Instale as dependências:**
   ```bash
   npm install
   ```

3. **Inicie o servidor de desenvolvimento:**
   ```bash
   npm start
   ```

O aplicativo abrirá automaticamente em [http://localhost:3000](http://localhost:3000)

## 📦 Build para Produção

```bash
npm run build
```

Cria uma versão otimizada pronta para produção na pasta `build/`

## 📝 Personalizando o Portfólio

### Alterar Informações Pessoais

1. **Header** - Edite `src/components/Header.js`:
   - Altere o texto de boas-vindas
   - Modifique seu nome e descrição

2. **Sobre** - Edite `src/components/About.js`:
   - Atualize sua biografia
   - Modifique a lista de habilidades

3. **Projetos** - Edite `src/components/Projects.js`:
   - Adicione, remova ou edite projetos no array `projects`
   - Atualize títulos, descrições e tecnologias

4. **Contato** - Edite `src/components/Contact.js`:
   - Atualize o email e links sociais
   - Customize a mensagem de boas-vindas

### Alterar Cores

Edite o gradiente nas seções CSS:
- `Header.css` - Procure por `linear-gradient(135deg, #667eea 0%, #764ba2 100%)`
- Altere para suas cores preferidas

## 🎨 Tecnologias Utilizadas

- **React 18** - Biblioteca JavaScript para UI
- **CSS3** - Estilização com Grid e Flexbox
- **JavaScript ES6+** - Seletores modernos

## 📱 Responsividade

O portfólio é totalmente responsivo e se adapta a:
- 📱 Celulares (< 768px)
- 📱 Tablets (768px - 1024px)
- 💻 Desktops (> 1024px)

## 🤝 Contribuições

Sinta-se livre para fazer fork deste projeto e criar sua própria versão personalizada!

## 📝 Licença

Este projeto está disponível para uso pessoal.

## 👤 Autor

**Vitor**

- GitHub: [@Vitor](https://github.com)
- Linkedin: [Vitor](https://www.linkedin.com/in/vitor-martimiani-0ab245268)

---

Feito com ❤️ usando React
