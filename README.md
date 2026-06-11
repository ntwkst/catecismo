# Catecismo da Igreja Católica

Catecismo da Igreja Católica em formato JSON estruturado para consumo via API/web.

**Estrutura:**
- 4 Partes
- Seções, Capítulos, Artigos, Parágrafos
- 2865 parágrafos total (numerados conforme CCC oficial)

**Uso:**
```javascript
fetch('https://raw.githubusercontent.com/NTWKST/catecismo/main/catecismo.json')
  .then(r => r.json())
  .then(data => console.log(data.partes))
```

**Segunda Edição** — Texto integral em Português.
