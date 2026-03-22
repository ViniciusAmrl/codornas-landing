# Codornas em 30 Dias — Landing Page

Página de vendas estática. Deploy via Vercel.

## Estrutura

```
codornas-landing/
├── index.html       # Página principal
├── vercel.json      # Configuração do Vercel
├── .gitignore
└── README.md
```

## Deploy no Vercel

### Via Git (recomendado)

```bash
git init
git add .
git commit -m "feat: landing page codornas"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/SEU_REPO.git
git push -u origin main
```

Depois conecte o repositório no [vercel.com](https://vercel.com):
1. New Project → Import Git Repository
2. Selecione o repositório
3. Framework Preset: **Other**
4. Build Command: *(deixe vazio)*
5. Output Directory: `.` (ponto)
6. Deploy

### Via Vercel CLI

```bash
npm i -g vercel
vercel --prod
```

## Rastreamentos ativos

| Ferramenta | ID | Evento |
|---|---|---|
| Meta Pixel | `927842906291543` | PageView + ViewContent (load) + InitiateCheckout (clique CTA) |
| Google Analytics 4 | `G-FTV81EXREW` | page_view + click_cta |

## Links de checkout

| Plano | Link |
|---|---|
| Básico R$9,90 | https://pagamento.compraweb.site/checkout/208971914:1 |
| Essencial R$19,90 | https://pagamento.compraweb.site/checkout/208971974:1 |
