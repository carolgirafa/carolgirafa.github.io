# Portfólio de Carolina Girafa: site (GitHub Pages)

Site estático em HTML e CSS, sem framework. Pode ser publicado direto no GitHub Pages.

## Estrutura
- `site/index.html`: home (hero, cases, sobre, contato)
- `site/cases/gestao-de-metas.html`: case de redesign do app de gestão de metas
- `site/cases/design-system-power-apps.html`: case do Design System e Component Library em Power Apps
- `site/assets/css/styles.css`: design tokens e todos os estilos
- `site/assets/img/nts/` e `site/assets/img/ds/`: imagens dos cases (anonimizadas)
- Planejado: versão em inglês em `en/`

## Direção visual
- Sóbria e aesthetic, em tons de bege e marrom
- Títulos em Fraunces (serifa, peso 300/400) e textos em Inter (400/600)
- Headline da home: "Design guiado por dados, pensado para pessoas." / "Data-informed design, built for people."

## Design tokens
**Cores, tema claro:**

| Token | Valor | Uso |
|---|---|---|
| bg | #F6F1EA | fundo |
| surface | #EDE3D6 | cartões |
| surface-strong | #E3D3BF | hover |
| text | #2A1F18 | texto (14.3:1) |
| text-muted | #5C4738 | texto secundário (7.7:1) |
| accent | #7A4526 | links e destaques (6.9:1) |
| border | #D6C5B0 | divisórias decorativas |
| border-ui | #8A6E58 | bordas de componentes (4.2:1) |

**Cores, tema escuro (pausado — será reativado depois que o tema claro estiver fechado):**

| Token | Valor |
|---|---|
| bg | #1C1612 |
| surface | #28201A |
| text | #F2E9DD |
| muted | #CDBBA6 |
| accent | #E0B088 |

**Espaçamento (sempre múltiplos de 4px):** 4, 8, 12, 16, 24, 32, 48, 64, 96, 128

**Raios:** 4, 8, 16 e pill

## Acessibilidade (WCAG 2.2 AA)
- Todos os pares de cor verificados (texto ≥ 4.5:1, elementos de interface ≥ 3:1)
- Skip link, landmarks, hierarquia de títulos e foco visível de 3px
- Alvos de toque de 44px ou mais
- `prefers-reduced-motion` respeitado
- `lang` e `hreflang` corretos nas versões PT e EN
- Auditado com axe-core: 0 violações em todas as páginas

## Pendências
- Imagens do case de metas (pasta `imagens_nts`) e do case de Design System, todas anonimizadas
- Tema escuro (reativar o bloco `prefers-color-scheme: dark` no CSS e `color-scheme: light dark` nas páginas)
- Versão em inglês (ao publicar, reativar o seletor PT/EN no cabeçalho e os links `hreflang`)
- PDF do currículo (`assets/curriculo-carolina-girafa.pdf`); ao subir o arquivo, reativar o botão "Currículo · PDF" no Contato
- Feedback de Carolina sobre o texto do "Sobre"
