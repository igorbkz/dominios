# Domínios dos Sonhos

Landing page estática para promover venda de domínios e oferta de criação de sites personalizados.

## Visão geral

Este projeto é composto por um único arquivo `index.html`, com:

- Layout responsivo com duas áreas principais (hero + card informativo);
- Estilo visual com gradiente, efeito glassmorphism e tipografia Poppins;
- CTA para contato direto via Instagram;
- Estrutura pronta para deploy rápido em hospedagem estática.

## Estrutura do projeto

```text
.
├── index.html
├── README.md
└── vercel.json
```

## Executar localmente

Como é um projeto estático, basta abrir o `index.html` no navegador.

Se preferir rodar com servidor local:

```bash
python3 -m http.server 8080
```

Depois acesse: `http://localhost:8080`

## Personalização rápida

No arquivo `index.html`, você pode ajustar:

- **Título da página** (`<title>`);
- **Textos da seção principal** (`h1`, `p` e botão);
- **Link de contato** no botão de CTA;
- **Itens de benefício** no card lateral;
- **Cores do tema** alterando variáveis CSS em `:root`.

## Deploy na Vercel

Este repositório inclui um `vercel.json` configurado para servir diretamente o `index.html`, evitando detecção incorreta de framework.

Passos:

1. Importe o repositório na Vercel;
2. Mantenha as configurações padrão de projeto estático;
3. Faça o deploy.

## Licença

Uso livre para adaptação no seu próprio projeto.
