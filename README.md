# Bolão da Copa - Regulamento e Pontuação Corrigidos

Esta versão corrige o regulamento e garante que a pontuação seja automática após o admin lançar o placar final.

## Regulamento aplicado

REGULAMENTO DO BOLÃO DA COPA — FASE DE TESTE

1. O jogador deve se cadastrar no sistema para participar do bolão.

2. O jogador deve registrar seus palpites antes do início de cada partida.

3. Nesta fase de teste, não haverá cobrança de pagamento para participar.

4. Os palpites confirmados entram automaticamente no ranking, sem necessidade de aprovação de pagamento.

5. Após o início da partida, o palpite não poderá mais ser registrado ou alterado.

6. A pontuação será calculada automaticamente pelo sistema depois que o administrador lançar o placar final da partida.

7. O placar exato vale 5 pontos.

8. Acertar o vencedor ou o empate vale 3 pontos.

9. Acertar a quantidade de gols de um dos times vale 1 ponto.

10. O administrador lançará manualmente os resultados das partidas no sistema.

11. O ranking será atualizado automaticamente após os resultados serem lançados.

12. Em caso de empate na pontuação, ficará melhor colocado o jogador com maior número de acertos.

13. Esta versão é apenas para teste. As regras de pagamento poderão ser ativadas futuramente.

## Pontuação automática

A pontuação só é atribuída depois que o administrador lança o placar final da partida.

Regras:

- Placar exato: 5 pontos.
- Vencedor ou empate correto: 3 pontos.
- Gols de um dos times: 1 ponto por time acertado.

## Importante

Como o regulamento antigo pode estar salvo no Supabase, incluí o arquivo:

ATUALIZAR-REGULAMENTO-SUPABASE.sql

Rode esse SQL uma vez no Supabase para substituir o regulamento antigo que aparece no app.
