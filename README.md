# Luan — Copywriter & Conteúdo Estratégico

Portfólio de copywriting: 10 peças, 10 nichos diferentes, cada uma com o texto completo e a explicação de por que aquela abordagem foi escolhida. Bilíngue (PT/EN).

**Ao vivo:** https://luancaldeira.github.io/portfolio-copywriting/

## O que tem na página

- **Hero** com proposta de valor e duas chamadas (amostra grátis / contratar pacote).
- **10 cards de portfólio** — confeitaria, fitness, moda, coaching, finanças pessoais, saúde mental, tech/SaaS, gastronomia, creator economy — cada um abre um modal com o copy completo e o raciocínio por trás (`⚡ POR QUE FUNCIONA`).
- **3 fluxos de contato**, cada um um modal próprio: amostra grátis, escolha de pacote (4 planos) e comissão avulsa.
- **Seção "Sobre"** com o ângulo diferencial (desenvolvedor frontend + analista de dados escrevendo copy — decisão de onde a pessoa para de rolar, não só o texto em si).

## Como é construído

HTML único (`index.html`), sem build, sem framework — CSS puro com variáveis e um JS vanilla cuidando de:

- **i18n PT/EN** via atributos `data-i18n` / `data-i18n-attr`, trocando o dicionário sem recarregar a página.
- **Modais em camada** (peça → contexto → pacote → formulário) controlados por JS puro, sem lib de modal.
- **Envio de formulário** direto pro [Formspree](https://formspree.io/) (3 endpoints, um por fluxo) — sem backend próprio.

## Rodar local

Não precisa de nada além de abrir o arquivo:

```bash
open index.html   # ou clique duas vezes
```

## Licença

Conteúdo autoral (textos e copy). Sem licença de código declarada.
