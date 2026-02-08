# PDV Tanque Digital

Sistema completo de ponto de venda com envio de cupom por WhatsApp, CPF/CNPJ no cupom e suporte local de Natal/RN.

## 🚀 Instalação Rápida

### Passo 1: Criar Projeto no Supabase
1. Acesse https://supabase.com
2. Clique em "New Project"
3. Preencha:
   - Name: `pdv-tanque-digital`
   - Database Password: (escolha uma senha forte)
   - Region: `Brazil (São Paulo)`
4. Clique em "Create new project"

### Passo 2: Executar Script SQL
1. No painel do Supabase, clique em **SQL Editor**
2. Clique em **New Query**
3. Copie e cole o conteúdo de `SUPABASE_SETUP.sql`
4. Clique em **RUN**

### Passo 3: Obter Chaves de Acesso
1. No Supabase, clique em **Settings** (engrenagem)
2. Clique em **API**
3. Copie:
   - **Project URL**: `https://xxxxx.supabase.co`
   - **anon/public key**: (cole a chave)

### Passo 4: Atualizar Configuração
1. Abra os arquivos HTML (`index.html`, `dashboard.html`, `sales.html`)
2. Substitua as chaves nas linhas 2-3:
   ```javascript
   const SUPABASE_URL = 'https://SEU_PROJETO.supabase.co';
   const SUPABASE_ANON_KEY = 'SUA_ANON_KEY_AQUI';