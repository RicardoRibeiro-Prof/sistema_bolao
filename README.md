# Bolão da Copa - Cadastro e Resultado Melhorados

Melhorias desta versão:

- Cadastro com confirmação de senha.
- Recuperação de senha pela tela de login.
- Área de resultados mais clara para o administrador.
- Botão: Salvar resultado e atualizar ranking.
- Ranking atualiza automaticamente após lançar o resultado.
- Mantém ícone premium, PWA/APK e Supabase Auth + RLS.

## Como atualizar o ranking

No app, entre como admin:

1. Abra a aba **Resultados**.
2. Escolha o jogo.
3. Informe o placar final.
4. Clique em **Salvar resultado e atualizar ranking**.

O sistema finaliza o jogo e recalcula os pontos automaticamente.

## Recuperação de senha

Na tela de login, clique em:

**Esqueci minha senha**

O Supabase enviará um link de recuperação para o e-mail cadastrado.

Atenção: se aparecer limite de e-mail, configure SMTP próprio no Supabase ou aguarde o limite liberar.
