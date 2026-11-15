# 🔍 Radar RMT PokeIdle

**Uma extensão para Google Chrome criada para facilitar o acompanhamento do mercado e a automação de tarefas no PokeIdle.**

O Radar RMT PokeIdle reúne ferramentas de monitoramento e gerenciamento de compras e vendas em uma interface integrada ao jogo.

## 🔐 Segurança e privacidade do jogador

**Sua conta e suas configurações merecem transparência.** O Radar RMT foi desenvolvido para funcionar diretamente na sessão já aberta do PokeIdle, sem exigir que você informe sua senha à extensão.

- **Sem login adicional:** a extensão usa a sessão do jogo que já está aberta no Chrome ou IdleDeck; você não precisa digitar sua senha no Radar RMT.
- **Acesso limitado ao jogo:** na versão 0.20.35, o manifesto restringe a atuação da extensão a páginas de `https://pokeidle.io/`.
- **Preferências locais:** as regras e configurações do Radar são armazenadas localmente pelo navegador, usando o armazenamento da extensão.
- **Comunicação com o PokeIdle:** consultas e comandos de compra utilizam a conexão já estabelecida pelo jogo. A extensão consulta também um catálogo público de itens do próprio PokeIdle para validar preços.
- **Controle das automações:** você decide quais ordens ativar, seus filtros e seus limites. Para evitar compras duplicadas, uma compra sem confirmação não deve ser repetida automaticamente.

**Atenção:** esta é uma versão beta. Automações podem realizar compras e consumir moedas ou gemas da sua conta; revise os limites antes de ativá-las. Nenhuma extensão é isenta de riscos, e este projeto não possui certificação independente de segurança. Baixe somente arquivos disponibilizados neste repositório e confira as permissões na instalação.


## ✨ Funcionalidades

- 🔎 **Radar RMT:** acompanhe oportunidades no mercado do jogo.
- 🛒 **AutoBuy:** configure regras para compras automáticas.
- 💰 **AutoSell:** configure critérios para vendas automáticas.
- ⚙️ **Filtros personalizados:** ajuste as condições de suas ordens.
- 📊 **Histórico de atividades:** acompanhe os resultados e avisos das automações.

## 📥 Download

Acesse a seção **Releases** deste repositório e baixe a versão disponível para testes.

**Status:** versão beta — em desenvolvimento e testes.

## 🧩 Como instalar

### ⭐ Recomendado: IdleDeck (Windows)

Para quem mantém o PokeIdle aberto por bastante tempo, **recomendamos utilizar o Radar RMT pelo [IdleDeck](https://idledeck.com.br/)**. O aplicativo mantém as sessões do jogo ativas mesmo quando sua janela está minimizada, evitando limitações comuns de abas em segundo plano nos navegadores tradicionais.

**Instalação no IdleDeck (versão beta em ZIP):**

1. Acesse a seção **Releases** deste repositório e baixe o ZIP da extensão.
2. **Extraia o ZIP** para uma pasta no computador. Confira se essa pasta contém o arquivo `manifest.json`.
3. Instale e abra o [IdleDeck](https://idledeck.com.br/), caso ainda não o utilize.
4. Abra sua conta do **PokeIdle** dentro do IdleDeck.
5. Na conta do jogo, abra a **janela de extensões** do IdleDeck e ative o **Modo do desenvolvedor**.
6. Use a opção de **carregar uma extensão local a partir de uma pasta** e selecione a pasta extraída que contém o `manifest.json`.
7. Revise as informações e permissões apresentadas pela análise do IdleDeck; prossiga apenas se confiar na extensão.
8. Ative a extensão nessa conta, abra ou recarregue o PokeIdle e configure o Radar RMT.

**Observação:** no IdleDeck, as extensões são habilitadas por conta. Se você usar mais de uma conta permitida pelas regras do jogo, será necessário configurar a extensão em cada sessão desejada. As opções e nomes dos botões podem variar conforme a versão do aplicativo.

### 🌐 Alternativa: Google Chrome

1. Baixe o arquivo ZIP disponibilizado em **Releases**.
2. Extraia o arquivo para uma pasta no computador.
3. No Chrome, acesse `chrome://extensions`.
4. Ative o **Modo do desenvolvedor**.
5. Clique em **Carregar sem compactação**.
6. Selecione a pasta extraída que contém o arquivo `manifest.json`.
7. Abra ou atualize o PokeIdle e configure a extensão.

**Importante:** mantenha apenas uma versão do Radar RMT ativa por conta, para evitar automações duplicadas. Instalações locais precisam ser atualizadas manualmente. Use a extensão respeitando as regras do jogo.

## 🔄 Atualizações

Novas versões serão disponibilizadas na seção Releases, acompanhadas de suas respectivas mudanças e correções.

As versões instaladas manualmente precisam ser atualizadas manualmente.

## ⚠️ Avisos importantes

- Projeto independente, não oficial e sem vínculo com a equipe do PokeIdle.
- O uso da extensão é de responsabilidade de cada jogador.
- Recursos automáticos podem apresentar falhas durante a fase beta.
- Consulte as regras do jogo antes de utilizar automações.

## 🐛 Problemas e sugestões

Encontrou um erro ou tem uma sugestão?

Abra uma solicitação na aba **Issues** deste repositório, descrevendo o problema e, se possível, incluindo uma captura de tela.

---

**Radar RMT PokeIdle — desenvolvido para a comunidade de jogadores.**
