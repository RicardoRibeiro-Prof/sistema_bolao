# Bolão da Copa Online

Sistema de bolão online com:

- Login de administrador e jogador
- Cadastro de jogadores
- Cadastro de jogos pelo administrador
- Palpites dos jogadores
- Pagamento via Pix com QR Code
- Aprovação manual de pagamento
- Resultado manual dos jogos
- Ranking automático
- Regulamento editável
- Dados salvos no Supabase

## Acesso inicial

Usuário: `admin`  
Senha: `1234`

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie os arquivos deste projeto para o repositório.
3. Vá em **Settings**.
4. Clique em **Pages**.
5. Em **Build and deployment**, escolha:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Clique em **Save**.
7. Aguarde o GitHub gerar o link do site.

## Arquivos principais

- `index.html`: arquivo principal do sistema.
- `.nojekyll`: evita problemas de publicação no GitHub Pages.
- `README.md`: instruções do projeto.

## Importante

Antes de usar, crie as tabelas no Supabase usando o SQL correto.

O sistema usa a URL e a chave pública do Supabase configuradas dentro do `index.html`.

Nunca coloque no código:

- service_role key
- secret key
- senha do banco
- senha da conta Supabase

Use apenas a publishable key ou anon public key.
