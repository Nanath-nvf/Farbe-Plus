# Farbe+ — Farmácia Virtual Demonstrativa

Projeto acadêmico de Engenharia de Software. Aplicação React + Vite com identidade visual azul e branca.

## Como executar

Instale o Node.js (versão LTS) e execute no terminal dentro da pasta do projeto:

```bash
npm install
npm run dev
```

Abra o endereço local exibido no terminal (normalmente http://localhost:5173).

Para gerar arquivos de publicação:

```bash
npm run build
```

## Recursos

- Página inicial, categorias, catálogo e busca
- Detalhes de produtos, carrinho e checkout simulado
- Pedidos e linha do tempo de acompanhamento
- Perfis demonstrativos: cliente, administrador, farmacêutico e entregador
- Administração de produtos, estoque, pedidos e atribuição de entregas
- Análise de receitas **fictícias** para produtos marcados
- Persistência local no navegador via `localStorage`

## Roteiro de demonstração

1. No perfil Cliente, adicione produtos ao carrinho e finalize um pedido simulado.
2. Em **Ver perfis de demonstração**, selecione Administrador.
3. Em Pedidos, acompanhe o pedido e atribua o entregador **Carlos**.
4. Entre no perfil Entregador e marque o pedido como **Saiu para entrega** e **Entregue**.
5. Volte ao perfil Cliente e confira o status em Meus pedidos.
6. Para demonstrar receitas, compre um produto com a etiqueta de receita, selecione a receita fictícia no checkout e entre no perfil Farmacêutico para aprovar ou rejeitar.

## Limitações importantes

**Protótipo acadêmico, não destinado a operação comercial.** Não há autenticação real nem permissões seguras: a troca de perfil é apenas demonstrativa. Os dados são armazenados no navegador do usuário e não são sincronizados entre dispositivos. Pagamentos, endereços e receitas são simulados; não informe dados reais. Não há integração com serviços farmacêuticos, gateways de pagamento ou logística.

## GitHub

Crie um repositório `Farbe-Plus`, extraia o ZIP, abra um terminal na pasta e execute:

```bash
git init
git add .
git commit -m "feat: primeira versão demonstrativa da Farbe+"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/Farbe-Plus.git
git push -u origin main
```

Substitua `SEU-USUARIO` pelo seu usuário do GitHub. Se o repositório remoto já tiver um README, é melhor criar um repositório vazio ou integrar o histórico antes do push.
