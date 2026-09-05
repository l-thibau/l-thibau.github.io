# Leonardo Thibau — site acadêmico

Site estático oficial de Leonardo Thibau, mestrando em Sociologia na UFBA, publicado em GitHub Pages.

## Conteúdo público

- apresentação acadêmica;
- linhas de pesquisa e projetos;
- produções selecionadas a partir do Currículo Lattes;
- métodos e competências técnicas documentadas no GitHub;
- links para Lattes, GitHub, slides e contato.

## Desenvolvimento local

```bash
python -m http.server 8000
```

Abra `http://localhost:8000`.

## Publicação

GitHub Pages deve publicar a partir da branch `main`, pasta `/ (root)`.

## Segurança

O site não usa JavaScript, formulários, analytics, rastreamento, APIs nem ativos de terceiros em runtime. A política CSP está declarada no HTML; links externos usam `rel="noopener"`.

## Trocar a foto de perfil

1. Abra a pasta `assets`.
2. Substitua `profile.jpg` pela nova foto, mantendo exatamente esse nome.
3. Abra `index.html` no navegador para testar localmente.
4. Se quiser deslocar o recorte circular, procure `.portrait` em `styles.css` e ajuste `object-position` (por exemplo: `center top`, `center 25%` ou `center center`).
