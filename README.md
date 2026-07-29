# Padaria Manager

Sistema de gestão para padaria, construído em React, TypeScript e Vite. A versão atual usa `localStorage` com uma camada centralizada em `src/lib/storage.ts`.

## Executar

```bash
npm install
npm run dev
```

Acesse a URL informada pelo Vite. Login de demonstração: `admin` / `admin123`.

## Recursos implementados

- Login local, layout responsivo e todas as rotas do menu;
- Dashboard com métricas calculadas das vendas locais;
- Cadastro de produtos, estoque e ajuste de movimentações;
- PDV com produtos por unidade e por peso, carrinho e baixa de estoque;
- Vendas, clientes, fornecedores, caixa, financeiro e backup/restauração;
- Dados de demonstração brasileiros e persistência imediata no navegador.

Para restaurar a base demonstrativa, use a tela **Backup**.
