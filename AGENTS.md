# Regras do Projeto — Davi Rian Tech

- **Documentação:** Consulte `docs/ARQUITETURA.md` antes de atualizar o portfólio.
- **Arquivos Principais:** `index.html`, `termos.html`, `privacidade.html`, `vercel.json`, `assets/`.
- **Qualidade:** Manter imagens otimizadas (`.webp`) e metatags Open Graph intactas.

## Padrões de Qualidade & Engenharia (Antigravity Suite)
- **Rigor Técnico (Gravitas)**: Ler os componentes e seus chamadores antes de mutações; validar integridade com testes e checagem de sintaxe (
ode --check ou 
pm run build).
- **Design & UI Anti-Slop (Impeccable)**:
  - Usar /impeccable critique ou /impeccable polish antes de fechar alterações de interface.
  - Evitar gradientes genéricos roxo/violeta sem motivo, manter contraste WCAG AA (mínimo 4.5:1) e hierarquia tipográfica com saltos mínimos de 1.25x entre títulos.
  - Não aninhar cards dentro de cards desnecessariamente.
- **Arquitetura (Graphify)**: O projeto possui grafo AST indexado em graphify-out/. Para navegar por dependências ou refatorações de alto impacto, consulte o grafo ou execute graphify query.
