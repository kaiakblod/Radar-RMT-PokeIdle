# Radar RMT PokeIdle v0.20.36 — Recuperação automática do AutoBuy RMT

Versão beta: melhoria de estabilidade após uma tentativa de compra sem confirmação.

## O que mudou

- Uma compra RMT enviada sem confirmação não desmarca mais a regra **Ativa**.
- O AutoBuy entra em **recuperação automática** e consulta novamente eventos do servidor e inventário para detectar compras confirmadas tardiamente.
- Enquanto uma compra permanece incerta, seu valor fica reservado e novas compras RMT ficam suspensas, para não repetir o mesmo anúncio e duplicar gastos.
- Quando a compra é confirmada, o Radar registra quantidade e gasto e retoma o monitoramento sem exigir reativação manual.
- Quando o servidor rejeita explicitamente a compra, a reserva é liberada; o AutoBuy volta a procurar outras ofertas e mantém o anúncio rejeitado bloqueado naquela sessão.
- Se não houver evidência de sucesso nem de rejeição, a regra permanece ativa, **mas a compra fica em espera segura**, sem novos envios automáticos.
- Preservados os fluxos do Market NPC, AutoSell, filtros e limites de saldo.

## Testes e observações

Foram realizados testes locais simulados de recuperação, comprovantes e rejeições, além de validação de sintaxe. Isso não substitui testes no ambiente real do PokeIdle. O comportamento em uma compra incerta continua deliberadamente conservador para proteger o saldo do usuário.

**Instalação:** baixe o arquivo ZIP anexado à Release, extraia e carregue a pasta no IdleDeck (recomendado) ou no Chrome conforme o guia do [README](README.md). Desative versões antigas antes de ativar a nova, evitando automações simultâneas.

**Projeto independente e não oficial, em versão beta.**
