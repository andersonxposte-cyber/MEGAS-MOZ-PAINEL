MEGAS MOZ — Painel administrativo v2

Ficheiros:
- index.html: painel ADM com cálculos e registos.
- manifest.webmanifest: instalação como PWA.
- sw.js: cache básico da aplicação.
- icon.svg: ícone.

FUNÇÕES:
- Configurar custo de compra, quantidade do lote e receita de venda.
- Calculadora de valor entre 1 e 999 MT.
- Registar entradas de stock, vendas e perdas.
- Calcular stock atual, investimento, receita e lucro/prejuízo realizado.
- Histórico local e exportação CSV.
- Link para abrir ChatGPT com uma pergunta sobre gestão de megas.

REGRAS E LIMITAÇÕES:
- Os dados são guardados no armazenamento local do navegador/dispositivo; não sincronizam entre aparelhos.
- Exporta o histórico regularmente. Limpar dados do navegador pode apagar os registos.
- Lucro mostrado é bruto/operacional com base no custo médio do stock, sem despesas gerais, impostos ou taxas de pagamento.
- A configuração inicial é 180 MT por 10 GB e venda por 220 MT por 10 GB: custo 18 MT/GB, venda 22 MT/GB, diferença bruta 4 MT/GB.
- Se o custo real for 22 MT/GB, altera a configuração para 220 MT por 10 GB.
- Não há ligação automática à Vodacom, M-Pesa ou e-Mola.
- Não é uma aplicação oficial da Vodacom.

INSTALAÇÃO:
1. Extrai o ZIP.
2. Para instalação PWA em Android/iPhone, publica os ficheiros num alojamento HTTPS.
3. Abre o endereço no Chrome (Android) ou Safari (iPhone), e escolhe instalar/adicionar ao ecrã principal.
