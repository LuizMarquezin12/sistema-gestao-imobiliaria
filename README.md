# Gestão Imobiliária — Dashboard Demonstrativo

> **Projeto de portfólio | Dados 100% fictícios**

Interface demonstrativa de uma plataforma interna de gestão imobiliária, com visão consolidada de imóveis, clientes, contratos, documentos e financeiro.

## Funcionalidades da demonstração

- Dashboard com indicadores, gráfico de ocupação e vencimentos.
- Carteira de imóveis com pesquisa e filtros por situação.
- Cadastro demonstrativo de imóveis, com persistência **somente no navegador** (localStorage).
- Listagens de clientes, contratos, cobranças e arquivo digital com dados fictícios.
- Layout responsivo e navegação por módulos.

## Tecnologias

- JavaScript (ES Modules)
- Vite
- HTML5 e CSS3
- localStorage para demonstração local

## Executar localmente

```bash
npm install
npm run dev
```

## Publicar na Vercel

1. Crie um repositório **público novo** no GitHub.
2. Envie **o conteúdo desta pasta**, incluindo `package.json`, `index.html` e `src/`.
3. Importe o repositório na Vercel, usando o preset **Vite**.
4. O comando de build é `npm run build` e o diretório de saída é `dist`.

## Segurança e escopo

**Esta é uma demonstração de interface, não um sistema de produção.** Não possui autenticação, backend, integração com Supabase, upload real de documentos nem emissão bancária de boletos. Não cadastre dados reais. A interface não contém credenciais, URLs privadas, informações de clientes reais ou código da operação de uma imobiliária.

Para uma versão operacional, seriam necessários autenticação, permissões, banco de dados, armazenamento privado, auditoria, backups e backend seguro para integrações financeiras.

## Portfolio / English summary

**Real Estate Management Dashboard — Frontend Demo**: responsive internal dashboard showcasing property inventory, tenant and landlord management, lease tracking, financial summaries, and a document archive concept. All records are fictional; data entry is stored only in the browser.
