# Obra Fácil Pro — Documentação legal e páginas públicas

Repositório **público** com políticas e páginas estáticas do app **Obra Fácil Pro**.

> **Este repo não contém código do app.**

## Propósito

- Política de Privacidade e Termos de Uso em PT-BR
- Páginas estáticas que a **Play Store** e o app podem linkar
- Hospedagem simples via **GitHub Pages**

## Conteúdo

| Caminho | Descrição |
|---------|-----------|
| [`privacy/index.html`](privacy/index.html) | Política de Privacidade |
| [`terms/index.html`](terms/index.html) | Termos de Uso |
| [`index.html`](index.html) | Página inicial com links |

## Como publicar (GitHub Pages)

1. No GitHub: **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / pasta `/ (root)`
4. Após o deploy, as URLs típicas serão:
   - `https://dccouto.github.io/obra-facil-pro-doc/`
   - `https://dccouto.github.io/obra-facil-pro-doc/privacy/`
   - `https://dccouto.github.io/obra-facil-pro-doc/terms/`

Opcional: domínio customizado em **Pages → Custom domain**.

## Contexto do app (resumo)

- App Android Flutter **offline-first**
- **Sem cadastro obrigatório** e **sem backend obrigatório**
- Dados ficam no dispositivo (SQLite)
- Monetização: **AdMob** (anúncios no freemium) + **RevenueCat** / Google Play Billing (Premium)
- Planos: mensal e vitalício (valores no app / loja)

## Manutenção

Atualize as páginas HTML quando mudar coleta de dados, parceiros de ads/billing ou funcionalidades que afetem privacidade. Mantenha a data de “última atualização” no rodapé de cada página.
