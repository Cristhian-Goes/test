# Sistema de Gestão - Gráfica

Sistema completo de gestão para gráficas, desenvolvido com React, TypeScript, Tailwind CSS e Supabase.

## 🚀 Funcionalidades

- **Dashboard** - Visão geral das operações
- **Cadastros** - Clientes, colaboradores, veículos, ferramentas e estabelecimentos
- **Atendimentos** - Registro e acompanhamento de atendimentos
- **Orçamentos** - Criação e gestão de orçamentos com sistema de pagamento
- **Pedidos** - Controle de produção e instalação
- **Despesas** - Controle financeiro de despesas
- **Recuperação de Vendas** - Acompanhamento de orçamentos recusados
- **Financeiro** - Fluxo de caixa e movimentações

## 🛠️ Tecnologias

- React 18
- TypeScript
- Tailwind CSS
- Supabase (Backend as a Service)
- Lucide React (Ícones)
- jsPDF (Geração de PDFs)
- Vite (Build tool)

## 📋 Pré-requisitos

- Node.js 18+
- Conta no Supabase

## 🔧 Configuração

### 1. Clone o repositório
```bash
git clone <url-do-repositorio>
cd sistema-gestao-grafica
```

### 2. Instale as dependências
```bash
npm install
```

### 3. Configure o Supabase

1. Acesse [supabase.com](https://supabase.com) e crie uma conta
2. Crie um novo projeto
3. Vá para Settings > API
4. Copie a URL do projeto e a chave anônima (anon key)

### 4. Configure as variáveis de ambiente

1. Copie o arquivo `.env.example` para `.env`:
```bash
cp .env.example .env
```

2. Edite o arquivo `.env` e substitua pelos valores do seu projeto Supabase:
```env
VITE_SUPABASE_URL=https://seu-projeto.supabase.co
VITE_SUPABASE_ANON_KEY=sua-chave-anonima
```

### 5. Execute as migrações do banco

As migrações já estão configuradas no projeto. Elas serão aplicadas automaticamente quando você conectar o Supabase.

### 6. Inicie o projeto
```bash
npm run dev
```

## 🗄️ Estrutura do Banco de Dados

O sistema utiliza as seguintes tabelas:

- `clientes` - Cadastro de clientes
- `colaboradores` - Cadastro de colaboradores
- `veiculos` - Cadastro de veículos
- `ferramentas` - Cadastro de ferramentas
- `estabelecimentos` - Cadastro de estabelecimentos
- `atendimentos` - Registro de atendimentos
- `orcamentos` - Orçamentos com sistema de pagamento
- `pedidos` - Pedidos de produção
- `despesas` - Controle de despesas
- `movimentos_financeiros` - Fluxo de caixa

## 👤 Usuários de Teste

O sistema possui usuários de teste pré-configurados:

- **Admin**: admin@grafica505.com

**Senha**: Grafica2025!

## 📱 Responsividade

O sistema é totalmente responsivo e funciona em:
- Desktop
- Tablet
- Mobile

## 🎨 Temas

- Modo claro
- Modo escuro (toggle no header)

## 📄 Geração de PDFs

O sistema gera PDFs profissionais para orçamentos com:
- Cabeçalho da empresa
- Dados do cliente
- Descrição do serviço
- Grid para medidas
- Condições de pagamento

## 🔐 Segurança

- Row Level Security (RLS) habilitado
- Autenticação via Supabase Auth
- Políticas de acesso por usuário

## 🚀 Deploy

Para fazer deploy da aplicação:

1. Build do projeto:
```bash
npm run build
```

2. Deploy no Netlify, Vercel ou similar
3. Configure as variáveis de ambiente no serviço de deploy

## 📞 Suporte

Para suporte ou dúvidas, entre em contato através do sistema de atendimentos.