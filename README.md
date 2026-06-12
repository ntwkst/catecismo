# 🙏 Catecismo da Igreja Católica — Completo em JSON

> **Salve Cristo Rei, Salve Maria Imaculada!**

## Apresentação

Este repositório contém o **Catecismo da Igreja Católica** completo e estruturado em formato JSON — **2.865 parágrafos** do magistério da Igreja, organizados em 5 partes e 26 capítulos.

O dataset é ideal para integração em plataformas web, aplicações móveis e sistemas de pesquisa que desejam oferecer acesso rápido, estruturado e confiável à doutrina católica oficial.

### 📖 Estrutura

```json
{
  "titulo": "Catecismo da Igreja Católica",
  "totalParagrafos": 2865,
  "partes": [
    {
      "numero": 1,
      "titulo": "A Profissão da Fé",
      "capitulos": [
        {
          "titulo": "...",
          "paragrafos": [
            {
              "numero": 1,
              "texto": "..."
            }
          ]
        }
      ]
    }
  ]
}
```

### ✨ Características

- ✅ **100% Completo** — Todos os 2.865 parágrafos do CCC
- ✅ **Bem Estruturado** — Partes, capítulos e parágrafos organizados
- ✅ **Encoding UTF-8** — Suporta caracteres acentuados em português
- ✅ **Pronto para Produção** — Testado e validado
- ✅ **Licença** — Texto conforme publicado pelo Vaticano

### 🚀 Como Usar

```javascript
// JavaScript/Node.js
const catecismo = require('./catecismo.json');

// Buscar parágrafo específico
const para = catecismo.partes[0].capitulos[0].paragrafos[0];
console.log(`§${para.numero}: ${para.texto}`);

// Iterar por partes
catecismo.partes.forEach(parte => {
  console.log(`Parte ${parte.numero}: ${parte.titulo}`);
});
```

### 📝 Exemplo de Parágrafo

```json
{
  "numero": 1,
  "texto": "Que procura o homem ao interrogar-se sobre o sentido e o fim da vida? Ele procura sinais de nossa identidade cristã em testemunhas vivas. Fora de toda dúvida, o primeiro lugar onde procurar a resposta é a Palavra de Deus transmitida pela Igreja..."
}
```

---

**Fiat voluntas tua. Veni, Domine Iesu!**

*Que se faça a tua vontade. Vem, Senhor Jesus!*
