# 🚀 Guia Completo - NextStep Site

## 📋 Índice
1. [Introdução](#introdução)
2. [Estrutura do Projeto](#estrutura-do-projeto)
3. [Como Começar](#como-começar)
4. [Hospedagem Gratuita](#hospedagem-gratuita)
5. [Personalizações](#personalizações)
6. [Próximos Passos](#próximos-passos)
7. [Suporte Técnico](#suporte-técnico)

---

## 📖 Introdução

Este é o site oficial do **NextStep**, desenvolvido com tecnologias modernas e 100% gratuitas. 
O site é totalmente responsivo (funciona em celulares, tablets e computadores) e pronto para uso!

### 🛠️ Tecnologias Utilizadas
- **HTML5** - Estrutura do site
- **Tailwind CSS** - Estilização moderna e responsiva
- **JavaScript** - Interatividade
- **Font Awesome** - Ícones profissionais

---

## 📁 Estrutura do Projeto

```
nextstep-site/
│
├── index.html          # Página principal (arquivo único!)
├── README.md           # Este guia
└── DEPLOY.md          # Instruções de hospedagem
```

**ATENÇÃO:** Por enquanto, tudo está em um único arquivo (`index.html`) para facilitar! 
Mais tarde vocês podem dividir em múltiplos arquivos se quiserem.

---

## 🚀 Como Começar

### Opção 1: Abrir Localmente (Mais Fácil)

1. Baixe o arquivo `index.html`
2. Dê um duplo clique no arquivo
3. Ele abrirá no seu navegador!

### Opção 2: Usar um Editor de Código (Recomendado)

1. **Instale o VS Code** (gratuito)
   - Baixe em: https://code.visualstudio.com/

2. **Instale a extensão "Live Server"**
   - Abra o VS Code
   - Vá em Extensions (ícone de quadradinhos)
   - Procure por "Live Server"
   - Clique em "Install"

3. **Abra o projeto**
   - File → Open Folder
   - Selecione a pasta `nextstep-site`

4. **Rode o servidor local**
   - Clique com o botão direito em `index.html`
   - Selecione "Open with Live Server"
   - O site abrirá em `http://localhost:5500`

---

## 🌐 Hospedagem Gratuita

### OPÇÃO 1: GitHub Pages (RECOMENDADO) ⭐

**Vantagens:**
- ✅ 100% Gratuito
- ✅ Domínio: `seu-usuario.github.io/nextstep`
- ✅ SSL (HTTPS) automático
- ✅ Fácil de atualizar

**Passo a Passo:**

1. **Crie uma conta no GitHub**
   - Acesse: https://github.com
   - Clique em "Sign up"
   - Use o e-mail da escola: `mecanografia.ceteps@gmail.com`

2. **Crie um novo repositório**
   - Clique no `+` no canto superior direito
   - Selecione "New repository"
   - Nome: `nextstep`
   - Marque "Public"
   - Marque "Add a README file"
   - Clique em "Create repository"

3. **Faça upload do arquivo**
   - Clique em "Add file" → "Upload files"
   - Arraste o arquivo `index.html`
   - Clique em "Commit changes"

4. **Ative o GitHub Pages**
   - Vá em "Settings" (engrenagem)
   - No menu lateral, clique em "Pages"
   - Em "Source", selecione "main"
   - Clique em "Save"
   - Aguarde 2-3 minutos

5. **Acesse seu site!**
   - URL: `https://seu-usuario.github.io/nextstep`

**Vídeo Tutorial:** https://www.youtube.com/watch?v=p9kYo9KCKYs

---

### OPÇÃO 2: Vercel (Alternativa)

**Vantagens:**
- ✅ 100% Gratuito
- ✅ Mais rápido que GitHub Pages
- ✅ Interface intuitiva

**Passo a Passo:**

1. Acesse: https://vercel.com
2. Clique em "Sign Up"
3. Use "Continue with GitHub"
4. Importe o repositório `nextstep`
5. Clique em "Deploy"
6. Pronto! URL: `nextstep.vercel.app`

---

### OPÇÃO 3: Netlify (Alternativa)

**Passo a Passo:**

1. Acesse: https://www.netlify.com
2. Arraste a pasta `nextstep-site` para o site
3. Pronto! Netlify gera uma URL automaticamente

---

## 🎨 Personalizações

### Como Mudar as Cores

Procure por `gradient-bg` no código e altere:

```css
/* Código atual (roxo) */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Alternativas: */

/* Azul */
background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);

/* Verde */
background: linear-gradient(135deg, #43e97b 0%, #38f9d7 100%);

/* Laranja */
background: linear-gradient(135deg, #fa709a 0%, #fee140 100%);
```

### Como Adicionar Seu Logo

1. Prepare uma imagem PNG do logo (recomendado: 200x200px)
2. Salve como `logo.png` na mesma pasta do `index.html`
3. No código, procure por:
   ```html
   <i class="fas fa-graduation-cap text-3xl mr-3"></i>
   ```
4. Substitua por:
   ```html
   <img src="logo.png" alt="NextStep Logo" class="h-10 mr-3">
   ```

### Como Mudar os Números da Seção "Sobre"

Procure por esta seção no código:

```html
<h3 class="text-3xl font-bold">200+</h3>
<p>Alunos Beneficiados</p>
```

E altere os números conforme a realidade do projeto!

---

## 🔄 Próximos Passos (Fase 2)

Após o site básico estar no ar, vocês podem adicionar:

### 1. **Formulário Real com Google Forms**

No lugar do formulário atual, incorpore um Google Form:

```html
<iframe src="URL_DO_SEU_GOOGLE_FORM" width="100%" height="800"></iframe>
```

### 2. **Sistema de Agendamento**

Opções gratuitas:
- **Calendly** (https://calendly.com) - Integração fácil
- **Google Calendar** - Criar eventos de agendamento

### 3. **Chat ao Vivo**

- **Tawk.to** (https://www.tawk.to) - Chat gratuito
- **WhatsApp Business API**

### 4. **Banco de Dados (Futuro)**

Para armazenar inscrições:
- **Firebase** (Google) - Gratuito até 10GB
- **Supabase** - Alternativa open-source

### 5. **Gerador de Currículos**

Desenvolver uma ferramenta online onde alunos criem currículos:
- Templates pré-definidos
- Export em PDF
- Integração com Lattes

---

## 📚 Recursos para Aprender Mais

### HTML/CSS
- **W3Schools:** https://www.w3schools.com
- **MDN Web Docs:** https://developer.mozilla.org

### JavaScript
- **JavaScript.info:** https://javascript.info
- **FreeCodeCamp:** https://www.freecodecamp.org

### Tailwind CSS
- **Documentação Oficial:** https://tailwindcss.com/docs
- **Tailwind Components:** https://tailwindcomponents.com

### YouTube (Canais em Português)
- **Curso em Vídeo** - Gustavo Guanabara
- **Rocketseat**
- **Código Fonte TV**

---

## 🆘 Suporte Técnico

### Problemas Comuns

**1. Site não carrega no navegador**
- ✅ Verifique se está usando um navegador moderno (Chrome, Firefox, Edge)
- ✅ Limpe o cache: Ctrl + Shift + Delete

**2. GitHub Pages não funciona**
- ✅ Aguarde 5-10 minutos após ativar
- ✅ Verifique se o repositório está público
- ✅ Confirme que o arquivo se chama exatamente `index.html`

**3. Formulário não envia**
- ✅ Por enquanto, o formulário só mostra um alerta
- ✅ Para funcionar de verdade, precisam integrar com Google Forms ou criar backend

**4. Site não abre no celular**
- ✅ O site é responsivo! Teste no modo mobile do navegador (F12 → ícone de celular)

---

## 🎯 Checklist de Lançamento

Antes de divulgar o site, confirme:

- [ ] Todas as informações de contato estão corretas
- [ ] Links de redes sociais apontam para as páginas certas
- [ ] Números e estatísticas estão atualizados
- [ ] Testou em diferentes navegadores (Chrome, Firefox, Safari)
- [ ] Testou em celular e tablet
- [ ] Formulário de inscrição funciona
- [ ] Site está hospedado e acessível publicamente

---

## 📞 Contato dos Desenvolvedores

**Projeto NextStep - CETEP Sisal**

- **Pedro Henrique:** pedro.rodrigues3@aluno.enova.educacao.ba.gov.br
- **Brenda Tainalle:** brenda.silva507@aluno.enova.eduaccao.ba.gov.br
- **Orientador Thales:** thales.lima.nascimento@gmail.com
- **Telefone:** (75) 99198-8339

---

## 🌟 Dicas Finais

1. **Atualizem o site regularmente** - Mantenham as informações sempre frescas
2. **Peçam feedback** - Mostrem para outros alunos e professores
3. **Monitorem acessos** - Usem Google Analytics (gratuito) para ver quantas pessoas visitam
4. **Sejam criativos** - Personalizem com fotos reais do projeto!
5. **Compartilhem** - Divulguem nas redes sociais da escola

---

**Boa sorte com o NextStep! 🚀**

Vocês estão construindo algo muito importante para ajudar outros alunos. 
Continue aprendendo e melhorando o site aos poucos!
