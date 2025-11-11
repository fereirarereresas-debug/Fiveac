# 🌾 Porteira Preta - Sistema de Gerenciamento de Fazenda

## ⚠️ AVISO DE SEGURANÇA

**Este projeto implementa autenticação no front-end APENAS para demonstração/protótipo.**

🔒 **Credenciais de demonstração:**
- **Usuário:** `Porteira Preta`
- **Senha:** `26122008`

⚡ **IMPORTANTE:** Não use este método em produção! Para ambiente de produção, implemente:
- Backend seguro (Node.js, PHP, Python, etc.)
- Armazenamento de senhas com hash (bcrypt, argon2)
- Autenticação por sessões ou JWT
- HTTPS obrigatório
- Validação server-side

---

## 🚀 Como Executar

1. **Baixe todos os arquivos** mantendo a estrutura de pastas
2. **Abra o arquivo `login.html`** no seu navegador (duplo clique)
3. **Faça login** com as credenciais acima
4. **Navegue** pelo painel e calculadoras

---

## 📂 Estrutura de Arquivos

```
porteira-preta/
│
├── README.md
├── index.html        (painel protegido)
├── login.html        (página de login)
├── calculadoras.html (calculadoras protegidas)
├── sobre.html        (sobre o projeto)
├── contato.html      (formulário de contato)
├── css/
│   └── style.css     (estilos globais)
└── js/
    ├── auth.js       (autenticação e sessão)
    └── script.js     (funcionalidades)
```

---

## 🎯 Funcionalidades

### 🔐 Sistema de Login
- Autenticação com credenciais fixas (demo)
- Persistência de sessão com localStorage
- Logout com limpeza de sessão
- Proteção de páginas (redirect automático)

### 📊 Calculadoras
1. **Consumo de Ração** - Calcula kg/dia e kg/semana
2. **Custo por Animal** - Custos totais e por cabeça
3. **Lucro por Lote** - Receita, custos e margem %

### 🎨 Interface
- Design moderno e responsivo
- Modo claro/escuro (opcional)
- Paleta rural (verdes, marrom, bege)
- Compatível mobile e desktop

---

## 🛠️ Tecnologias

- HTML5
- CSS3 (Grid, Flexbox)
- JavaScript Vanilla (ES6+)
- Google Fonts (Poppins)
- LocalStorage API

---

## 📝 Licença

Projeto de demonstração - Livre para uso educacional

---

**Desenvolvido para demonstração de conceitos front-end**
```