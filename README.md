# 🔐 Sistema de Cadastro e Login Responsivo

Um sistema completo de autenticação com páginas de login e cadastro, desenvolvido com design moderno e totalmente responsivo.

## ✨ Funcionalidades

### 📋 Página de Cadastro (`signup.html`)
- **Formulário de registro** com validação em tempo real
- **Verificação de senha** - Confirmação de correspondência entre senhas
- **Requisitos de senha forte**:
  - Mínimo de 8 caracteres
  - Pelo menos 1 letra maiúscula (A-Z)
  - Pelo menos 1 letra minúscula (a-z)
  - Pelo menos 1 número (0-9)
  - Pelo menos 1 caractere especial (@$!%*?&)
- **Design responsivo** que se adapta a todos os dispositivos
- **Navegação integrada** entre login e cadastro

### 🔐 Página de Login (`index.html`)
- **Interface intuitiva** para autenticação de usuários
- **Validação de campos** para e-mail e senha
- **Link para cadastro** para novos usuários
- **Design consistente** com a página de cadastro

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica e acessível
- **CSS3** - Estilização avançada com Flexbox, Gradientes e Media Queries
- **JavaScript** - Validações e interatividade do formulário
- **Google Fonts** - Família de fontes Poppins para melhor legibilidade

## 📁 Estrutura do Projeto

```
sistema-autenticacao/
│
├── index.html          # Página de login
├── signup.html         # Página de cadastro (nova)
├── assets/
│   ├── styles/
│   │   └── style.css   # Estilos (opcional)
│   └── images/
│       └── Sign up-amico.svg  # Ilustração do cadastro
└── README.md           # Documentação
```

## 🚀 Como Utilizar

1. **Faça o download** de todos os arquivos
2. **Abra o arquivo `index.html`** no navegador para acessar a página de login
3. **Clique em "Create account"** para ser redirecionado para a página de cadastro
4. **Preencha o formulário** com:
   - Nome completo
   - E-mail válido
   - Senha forte (atendendo aos requisitos)
   - Confirmação de senha (deve ser idêntica à senha)
5. **Clique em "Sign up"** para finalizar o cadastro

## 📱 Layout Responsivo

### Desktop
- Layout dividido em duas colunas (formulário + ilustração)
- Experiência imersiva com gradiente de fundo
- Espaçamento adequado entre elementos

### Mobile
- Layout empilhado em coluna única
- Ilustração acima do formulário
- Campos de entrada otimizados para touch
- Fontes com tamanho aumentado para melhor legibilidade

## 🎨 Personalização

Para modificar o aspecto visual, edite as seguintes propriedades no CSS:

```css
/* Cores principais */
--primary-color: #7e22ce;
--secondary-color: #a855f7;
--accent-color: #ec4899;

/* Gradiente de fundo */
background: linear-gradient(135deg, #a855f7, #7e22ce);

/* Cores dos botões */
background: linear-gradient(135deg, #ec4899, #a855f7);
```

## 🔧 Funcionalidades Técnicas

### Validações Implementadas
- **Validação de e-mail** nativa do HTML5
- **Pattern validation** para senha forte
- **Verificação de correspondência** entre senha e confirmação
- **Prevenção de envio** com campos inválidos
- **Feedback visual** para campos com erro

### Experiência do Usuário
- **Mensagens de erro** claras e específicas
- **Alertas visuais** para problemas de validação
- **Transições suaves** entre estados
- **Ícones e ilustrações** para melhor engajamento

## 📋 Requisitos de Senha

A senha deve atender aos seguintes critérios:

| Requisito | Exemplo |
|-----------|---------|
| Mínimo 8 caracteres | 8 ou mais caracteres |
| 1 letra maiúscula | A-Z |
| 1 letra minúscula | a-z |
| 1 número | 0-9 |
| 1 caractere especial | @$!%*?& |

## 🌐 Navegadores Suportados

- Chrome (versões recentes)
- Firefox (versões recentes)
- Safari (versões recentes)
- Edge (versões recentes)
- Navegadores mobile (iOS Safari, Chrome Mobile)

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar, modificar e distribuir.

## 🐛 Reportar Problemas

Encontrou um bug ou tem uma sugestão de melhoria? [Abra uma issue](https://github.com/seu-usuario/login-system/issues) no GitHub.

---

**Nota**: Este é um projeto frontend estático para demonstração de interface. Para um sistema completo de autenticação, é necessário integrar com um backend para autenticação real.
