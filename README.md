
# Painel Weber (Checkout Pix)

Painel de vendas com carrinho e pagamento via **Pix**.

---

## 🚀 Deploy em 1 clique

Clique no botão abaixo para instalar no **Render**:

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/carlosferreira-hub/painel-weber)

---

## ⚙️ Variáveis de ambiente necessárias

No Render, adicione em **Environment Variables**:

```
PIX_KEY=8ea8b0d0-fe5e-405c-b602-d8f211ed837f
ADMIN_TOKEN=sua-senha-secreta
```

- `PIX_KEY` → sua chave Pix (já configurada).
- `ADMIN_TOKEN` → senha de administrador para acessar `/admin`.

---

## Como funciona
1. O cliente adiciona serviços no carrinho.
2. Na finalização, recebe a chave Pix para pagamento.
3. Pedido fica com status **aguardando_pagamento** até confirmação.
4. Você pode marcar como **pago**, **em_execucao** ou **concluido** no painel Admin.

---

## Aviso Importante
Este painel é genérico para **serviços digitais legítimos** (criação de conteúdo, gestão de anúncios, consultorias, UGC, etc.).  
Não automatiza seguidores/curtidas falsos — respeita as regras do Instagram/TikTok e legislação vigente.
