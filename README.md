# Estúdio Marquesani Club

App PWA para controle de **assinaturas** do Estúdio Marquesani (modelo *Tattoo Club*): planos, formas de pagamento (PIX / cartão recorrente), acúmulo de crédito, crédito bônus, indicações e controle de inadimplência — conforme o regulamento oficial.

## Recursos
- Cadastro de assinantes com plano, contato e forma de pagamento
- Planos: **FLASH** R$150 · **CUSTOM** R$300 · **SIGNATURE** R$500 · **BLACK** R$800 (com bônus por mensalidade)
- Registro de pagamento por competência → gera crédito + crédito bônus
- Indicações (R$50 de crédito por indicação consolidada)
- Utilização de crédito em tatuagens
- Cancelamento de bônus por inadimplência (2 meses consecutivos)
- Painel com MRR e inadimplentes
- Backup/restauração em JSON
- **PWA**: instalável e funciona offline

## Como rodar localmente
```bash
node server.js
```
Depois abra <http://localhost:5173> no navegador.

## Publicado em
GitHub Pages (veja a aba *Pages* nas configurações do repositório).

---
Dados ficam salvos no próprio dispositivo (localStorage). Faça backup com frequência.
