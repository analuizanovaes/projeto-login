**README - Sistema de Login**

🔐 Sistema de Login Responsivo

Um formulário de login moderno e responsivo com validação de campos e design adaptativo para diferentes dispositivos.

 ✨ Funcionalidades

- **Design Responsivo** - Adapta-se perfeitamente a desktop, tablet e mobile
- **Validação de Campos** - Verificação de e-mail e requisitos de senha
- **Efeitos Visuais** - Transições suaves e feedback visual
- **Gradiente Moderno** - Design atraente com cores atuais
- **Validação de Senha Forte** - Exige:
  - Mínimo 8 caracteres
  - 1 letra maiúscula
  - 1 letra minúscula  
  - 1 número
  - 1 caractere especial (@$!%*?&)

🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização com Flexbox, Gradientes e Media Queries
- **JavaScript** - Validação e interatividade do formulário
- **Google Fonts** - Fontes Inter e Montserrat

 📁 Estrutura do Projeto

login-system/
│
├── index.html          # Arquivo principal
├── assets/
│   ├── styles/
│   │   └── style.css   # Estilos (opcional)
│   └── images/
│       └── login-illustration.svg  # Ilustração do login
└── README.md           # Este arquivo
```
🚀 Como Usar

1. **Faça o download dos arquivos**
2. **Abra o arquivo `index.html`** no seu navegador
3. **Teste o login**:
   - Preencha com um e-mail válido
   - Use uma senha que atenda aos requisitos
   - Clique em "Sign In"

📱 Layout Responsivo

- **Desktop**: Layout dividido em duas colunas (imagem + formulário)
- **Mobile**: Layout empilhado com fundo rosa sólido

🎨 Personalização

Para modificar as cores, edite estas variáveis no CSS:

```css
/* Gradiente do fundo */
background: linear-gradient(135deg, #6366F1, #A855F7, #EC4899);

/* Cor do lado esquerdo */
background: #7C3AED;

/* Cor de fundo para mobile */
background: #C350D1;
```
🔧 Funcionalidades Técnicas

- Validação de e-mail nativa do HTML5
- Pattern validation para senha forte
- Prevenção de envio padrão do formulário
- Feedback visual nos campos
- Design responsivo com media queries

📋 Requisitos de Senha

A senha deve conter:
- ✓ Mínimo 8 caracteres
- ✓ Pelo menos 1 letra maiúscula (A-Z)
- ✓ Pelo menos 1 letra minúscula (a-z)  
- ✓ Pelo menos 1 número (0-9)
- ✓ Pelo menos 1 caractere especial (@$!%*?&)

🌐 Navegadores Suportados

- Chrome (versões recentes)
- Firefox (versões recentes)
- Safari (versões recentes)
- Edge (versões recentes)

📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar e modificar.

🐛 Reportar Problemas

Encontrou um bug? [Abra uma issue](https://github.com/seu-usuario/login-system/issues) no GitHub.

---

**Nota**: Este é um projeto frontend estático para demonstração de interface. Para um sistema completo de login, é necessário integrar com um backend para autenticação real.
```
