# Bolão da Copa - Versão de Teste sem Pagamento

Nesta versão, o pagamento obrigatório foi retirado temporariamente.

## O que mudou

- Jogador cadastra e faz login normalmente.
- Jogador preenche todos os palpites da rodada.
- Ao confirmar a rodada, os palpites já ficam válidos.
- Não gera Pix.
- Não exige aprovação de pagamento.
- Ranking considera os palpites de todos os jogadores.
- Admin lança resultado e o ranking atualiza automaticamente.

## Para voltar com pagamento depois

No `index.html`, procure:

const PAYMENT_REQUIRED = false;

E altere para:

const PAYMENT_REQUIRED = true;

Depois será necessário reativar o menu Pix e o fluxo de aprovação.
