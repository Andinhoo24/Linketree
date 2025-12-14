# Linketree - Andinho

Página simples em HTML/CSS para centralizar links pessoais.

Como executar localmente:

1. Abra o diretório do projeto:

```sh
cd /home/andinho/Documentos/GitHub/Linketree
```

2. Inicie um servidor HTTP (Python 3):

```sh
python3 -m http.server 8000
```

3. Abra no navegador: http://localhost:8000

Alterações realizadas:
- HTML reescrito com marcação semântica (`header`, `main`, `nav`, `footer`).
- Links convertidos para `a` com classes (`.link-btn`) ao invés de `button > a`.
- Acessibilidade melhorada com `aria-labels` e focus styles.
- CSS atualizado: layout centrado, card de conteúdo, link styles, animações e suporte a `prefers-reduced-motion`.

Sugestões futuras:
- Adicionar imagem de perfil real ou ícones (SVG) para links; usar `og:` e `twitter:` meta tags para melhor social sharing.
- Considerar usar um gerador de site estático (ex: Hugo, Jekyll) para páginas maiores.
