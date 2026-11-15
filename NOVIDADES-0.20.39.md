# Radar RMT PokeIdle v0.20.39 — Resultados de sorteios e avisos do servidor

## Correção principal
- O Radar agora reconhece eventos `mktSorteio` (entrada, lista e resultado) e avisos do mercado que chegam em `batalha.ev`.
- Quando o servidor informa `market.sorteioPerdeu`, a tentativa é reconhecida como rejeitada/perdida, sem ficar indefinidamente em recuperação.
- Após essa confirmação, o AutoBuy **mantém a ordem ativa e retoma a busca por ofertas**, respeitando filtros, intervalos e limites.
- Avisos sem identificador do anúncio são usados para diagnóstico, mas não bastam para justificar uma compra repetida.
- Uma vitória em sorteio ainda exige confirmação efetiva de compra ou inventário.
- Mantidas proteções para evitar compras duplicadas quando o resultado não puder ser determinado com segurança.

## Teste no jogo
O teste com Water Stone demonstrou que, depois de `market.sorteioPerdeu`, o Radar retomou a consulta do mercado. A confirmação do caminho de uma compra efetivamente concluída ainda precisa ser observada.

## Instalação
1. Baixe o arquivo `Radar_RMT_PokeIdle_v0.20.39_RESULTADOS_SORTEIO.zip` anexado à Release.
2. Extraia o ZIP e carregue a pasta no IdleDeck (recomendado) ou Google Chrome.
3. Desative/remova a versão antiga antes de ativar a nova.
4. Configure limites de compra e acompanhe o histórico na primeira execução.

Consulte o [guia de instalação e segurança](README.md).

**Versão beta. Projeto independente e não oficial do PokeIdle.**
