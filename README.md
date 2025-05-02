# 🎓 Brothers Learning

**Brothers Learning** é uma plataforma de ensino a distância completa e escalável, desenvolvida com foco em **arquitetura limpa**, **segurança**, **manutenibilidade** e **experiência do usuário**. Utilizando tecnologias consolidadas como **Laravel**, **PHP** e **MySQL**, a plataforma conecta instituições, professores e alunos em um ambiente virtual moderno, responsivo e funcional.

---

## 📌 Sumário

- [🚀 Objetivo do Projeto](#-objetivo-do-projeto)
- [⚙️ Tecnologias Utilizadas](#️-tecnologias-utilizadas)
- [🎯 Funcionalidades Principais](#-funcionalidades-principais)
- [📦 Funcionalidades em Desenvolvimento](#-funcionalidades-em-desenvolvimento)
- [🛠️ Como Executar Localmente](#️-como-executar-localmente)
- [🤝 Contribuindo](#-contribuindo)
- [📝 Licença](#-licença)

---

## 🚀 Objetivo do Projeto

Fornecer uma solução robusta e extensível para **educação online**, permitindo que instituições de ensino ofereçam cursos em formato digital com recursos como:

- Gerenciamento de conteúdos (cursos, módulos, aulas)
- Controle de usuários com diferentes permissões
- Acompanhamento de desempenho acadêmico
- Comunicação direta entre professores e alunos

---

## ⚙️ Tecnologias Utilizadas

| Tecnologia     | Descrição                                        |
|----------------|--------------------------------------------------|
| **PHP 8+**     | Linguagem principal de backend                   |
| **Laravel 10** | Framework moderno e escalável para aplicações web |
| **MySQL**      | Banco de dados relacional                        |
| **Blade**      | Engine de templates nativa do Laravel            |
| **HTML5/CSS3** | Estruturação e estilização do frontend           |
| **JavaScript** | Interatividade e manipulação dinâmica no cliente |
| **Bootstrap**  | Design responsivo e mobile-first (UI Framework)  |

---

## 🎯 Funcionalidades Principais

- ✅ **Gestão de Cursos e Módulos**  
  Cadastro, edição e organização de conteúdos educacionais.

- ✅ **Aulas em Vídeo**  
  Upload, categorização e exibição de vídeos educacionais por tópico.

- ✅ **Sistema de Permissões e Acessos**  
  Gerenciamento de usuários por perfis: Administrador, Professor e Aluno.

- ✅ **Área de Interação**  
  Espaço de comunicação entre professores e estudantes, com suporte a comentários e dúvidas.

- ✅ **Dashboard de Acompanhamento** *(em breve)*  
  Métricas e visualizações sobre progresso e engajamento dos alunos.

---

## 📦 Funcionalidades em Desenvolvimento

- 💳 Integração com gateways de pagamento (ex: Stripe, PayPal)  
- 📜 Certificação automática ao fim de cursos  
- 🧵 Fóruns de discussão por turma/módulo  
- 🗓️ Agenda e calendário acadêmico compartilhado  
- 📈 Relatórios gerenciais e exportação de dados  

---

## 🛠️ Como Executar Localmente

> Pré-requisitos: PHP 8+, Composer, MySQL, Node.js e NPM

```bash
# Clone o repositório
git clone https://github.com/brunosuassuna/Brothers-Learning.git

# Acesse o diretório
cd brothers-learning

# Instale as dependências PHP
composer install

# Instale as dependências JS (caso utilize Vue/React no futuro)
npm install && npm run dev

# Copie e configure o arquivo .env
cp .env.example .env

# Gere a chave da aplicação
php artisan key:generate

# Execute as migrations
php artisan migrate

# Inicie o servidor local
php artisan serve
```


---

### 📄 `CONTRIBUTING.md`

Salve este conteúdo como `CONTRIBUTING.md` na raiz do seu repositório:

```markdown
# Guia de Contribuição

Obrigado por considerar contribuir com o Brothers Learning! 🎓

---

## 💡 Como Contribuir

1. **Fork** este repositório
2. Crie uma branch com sua funcionalidade/correção:

   git checkout -b feature/nome-da-feature
```

## ✉️ Contato
- **Email:** brunosuassuna.dev@gmail.com
- **LinkedIn:** www.linkedin.com/in/brunosuassuna

