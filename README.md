# Portal do Leão 🦁

Portal **independente e não oficial** inspirado no Sport Club do Recife, expandido a partir do projeto de tela de login enviado pelo autor.

## Como executar

Abra `index.html` no navegador. Recomendado: extensão **Live Server** do VS Code, ou `python -m http.server 5500` e acesso a `http://localhost:5500`.

## Recursos

- Home com identidade rubro-negra, destaques e chamadas para ações
- Notícias editoriais demonstrativas e páginas individuais
- Jogos e reservas **simuladas** de ingressos
- Loja conceitual com filtros e carrinho persistido no `localStorage`
- Elenco demonstrativo com busca e filtros de posição
- História do clube em linha do tempo
- Cadastro, login, sessão e área do torcedor **simulados**
- Layout **mobile first**, menu adaptativo, estados de foco, HTML semântico e imagens responsivas

## Importante: segurança e dados reais

Este projeto é um **protótipo front-end**, não uma plataforma de vendas. O cadastro armazena senhas em texto simples no `localStorage` **somente para demonstração**. **Não use senhas reais, nem publique como autenticação de produção.** Para disponibilizar contas reais, substitua o login por autenticação no servidor com hash de senhas, sessões seguras, proteção contra abuso e gestão de dados conforme LGPD.

Jogos, preços, reservas, produtos e elenco são **fictícios ou placeholders**. Notícias são conteúdos editoriais ilustrativos, não notícias em tempo real. Não há cobrança, emissão de ingressos, estoque ou conexão com serviços oficiais. Para produção, integrar fontes licenciadas/atualizadas, provedores autorizados de bilheteria e pagamentos, backend e banco de dados.

## Estrutura

- `index.html` — casca da aplicação, cabeçalho, navegação e modal
- `assets/style.css` — design system responsivo, começando pelo mobile
- `assets/app.js` — rotas por hash, dados de exemplo e interações
- `assets/img/` — imagens e escudo reaproveitados do projeto enviado

## Próximas etapas sugeridas

1. Migrar para React + Vite, com React Router e componentes reutilizáveis.
2. Criar API Node.js + Express e banco PostgreSQL.
3. Implementar autenticação segura, painel administrativo e controle de permissões.
4. Integrar notícias e calendário por fontes autorizadas.
5. Integrar checkout real somente com credenciamento e homologação.

**Aviso:** marca e imagens do clube pertencem aos respectivos titulares; este é um projeto de estudo/portfólio e não representa o Sport Club do Recife.
