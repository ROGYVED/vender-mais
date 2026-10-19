# Vender+ (V+) — Protótipo demonstrativo

Protótipo interativo de uma plataforma SaaS para operação imobiliária, com visual escuro premium e detalhes dourados. Criado para apresentação e validação inicial da ideia.

**Crédito:** Criado pela KRYVAN | Tecnologia digital.

## Páginas incluídas
- Login demonstrativo (nome obrigatório; senha opcional pelo botão “Entrar sem senha”)
- Visão geral com indicadores, gráfico de desempenho, canais e imóveis em destaque
- Imóveis: catálogo, busca, cadastro, status e remoção/ações demonstrativas
- Publicações: seleção de imóvel/canais, agendamento simulado e histórico de atividade
- Leads & CRM: contatos de demonstração, busca, status e cadastro de leads
- Discador: fila de contatos e controles de simulação
- Calendário comercial com eventos ilustrativos
- Relatórios com indicadores, distribuição por canal e exportação dos dados demonstrativos
- Equipe comercial
- Configurações, canais simulados, preferências e restauração dos dados de exemplo

## Rodar localmente
Requer Node.js instalado.

```bash
npm install
npm run dev
```

## Publicar na Vercel
Importe o repositório no painel da Vercel. O projeto usa Vite; configurações esperadas:
- Build command: `npm run build`
- Output directory: `dist`

## Limites importantes
Este é um protótipo de front-end. Os dados ficam no armazenamento local do navegador. As conexões com OLX, Instagram, Facebook, telefonia e calendários são simuladas; não publica anúncios nem realiza chamadas reais. Login e dados não são adequados para produção. Para lançar o SaaS será necessário backend, autenticação real, banco de dados, isolamento por imobiliária, integrações autorizadas e controles de segurança/LGPD.
