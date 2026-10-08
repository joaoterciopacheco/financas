# 💰 Minhas Finanças

Um aplicativo web super leve e simples para gerenciamento de finanças e despesas pessoais. Criado com foco na experiência mobile, ele funciona diretamente no navegador do seu celular como se fosse um aplicativo nativo, sem necessidade de internet ou banco de dados em nuvem.

## ✨ Funcionalidades

* **Registro de Despesas:** Adicione o valor, descrição e data de vencimento.
* **Despesas Recorrentes:** Suporte nativo para parcelamentos (ex: 1/10, 2/10) e contas fixas mensais.
* **Exclusão Inteligente:** Ao deletar uma despesa recorrente, escolha se quer excluir apenas aquele mês, o mês atual e os próximos, ou todas as ocorrências de uma vez.
* **Controle de Pagamentos:** Marque as contas como pagas com um clique.
* **Indicadores Visuais:** Cores intuitivas (verde para pago, branco para pendente, vermelho para atrasado).
* **Resumo Mensal:** Veja rapidamente o total de despesas do mês e o saldo que ainda falta pagar.
* **100% Offline e Privado:** Todos os dados são salvos no `localStorage` do seu próprio aparelho. Nenhuma informação é enviada para servidores externos.

## 🚀 Como Usar (Instalação)

Como este projeto não possui backend e roda em um único arquivo HTML, hospedá-lo e instalá-lo no celular é muito rápido.

### Passo 1: Hospedar no GitHub Pages
1. Faça o upload do arquivo `index.html` para o seu repositório no GitHub.
2. Vá na aba **Settings** (Configurações) do seu repositório.
3. No menu lateral, clique em **Pages**.
4. Em *Source*, selecione a branch `main` (ou `master`) e clique em **Save**.
5. O GitHub vai gerar um link para o seu site (ex: `https://seunome.github.io/seu-repositorio/`).

### Passo 2: Adicionar ao Celular (Instalar o App)
1. Abra o link gerado pelo GitHub Pages no navegador do seu celular (Google Chrome no Android ou Safari no iPhone).
2. Abra o menu de opções do navegador.
3. Toque na opção **"Adicionar à Tela Inicial"** (Add to Home Screen).
4. Pronto! O atalho ficará junto com seus outros aplicativos e abrirá em tela cheia, parecendo um app nativo.

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído para ser o mais simples possível de se manter, utilizando apenas ferramentas front-end via CDN, concentradas em um único arquivo:

* **HTML5 / CSS3**
* **React 18** (Importado via ESM e compilado no navegador com Babel Standalone)
* **Tailwind CSS** (Estilização rápida e responsiva via CDN)
* **Lucide React** (Ícones da interface)
* **API de LocalStorage** (Persistência de dados offline)
