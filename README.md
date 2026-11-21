# WebMCP Agent Developer â€” FormaÃ§Ã£o 4

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


FormaÃ§Ã£o prÃ¡tica dedicada ao papel **WebMCP Agent Developer**. O projeto ensina a construir o agente de navegador que descobre, seleciona e executa ferramentas oferecidas pela pÃ¡gina sem entregar autorizaÃ§Ã£o ao modelo.

## O que estÃ¡ incluÃ­do

- arquitetura de 4 capÃ­tulos Agent Developer, cada um com seus prÃ³prios mÃ³dulos;
- CapÃ­tulo 1 publicado com 4 mÃ³dulos completos, 24 tÃ³picos e cerca de 12 horas;
- progresso, dÃºvidas, anotaÃ§Ãµes, temas e exportaÃ§Ã£o/importaÃ§Ã£o da jornada;
- console local para auditar o contexto apresentado ao agente;
- validador avanÃ§ado de catÃ¡logos, tools e JSON Schemas;
- geraÃ§Ã£o estÃ¡tica pronta para GitHub Pages e Vercel.

## CapÃ­tulos e mÃ³dulos

O menu superior navega pelos capÃ­tulos da formaÃ§Ã£o Agent Developer. A numeraÃ§Ã£o segue `capÃ­tulo.mÃ³dulo`: `1.1`, `1.2`, `2.1` e assim por diante.

O CapÃ­tulo 1 estÃ¡ publicado com estes mÃ³dulos:

1. Descoberta de ferramentas;
2. ExecuÃ§Ã£o de ferramentas;
3. Cross-origin e permissÃµes;
4. Loop conversacional.

Os capÃ­tulos 2 (RaciocÃ­nio e polÃ­ticas), 3 (Adaptadores de modelos) e 4 (Entrega Agent Developer) jÃ¡ estÃ£o mapeados no Ã­ndice e serÃ£o publicados progressivamente.

## Executar localmente

```bash
npm run build
npm test
npm run serve
```

Abra `http://localhost:4173`. O curso tambÃ©m Ã© legÃ­vel abrindo `index.html`, mas um servidor local representa melhor o contexto de execuÃ§Ã£o.

## Console Page Agent

O laboratÃ³rio em `labs/validador-tools.html` recebe um descritor JSON auditÃ¡vel. Ele verifica:

- unicidade, nomes, tÃ­tulos e descriÃ§Ãµes;
- estrutura de `inputSchema`;
- coerÃªncia de `required` e `properties`;
- annotations do draft;
- evidÃªncia de `AbortSignal`;
- risco, confirmaÃ§Ã£o humana, fallback e exemplo de resultado.

O console Ã© local, determinÃ­stico e nÃ£o registra nem executa tools. Campos de governanÃ§a como `risk`, `fallback` e `resultExample` nÃ£o pertencem ao draft WebMCP; servem para revisar prontidÃ£o operacional.


## EspecificaÃ§Ã£o e limites

WebMCP permanece em evoluÃ§Ã£o. O conteÃºdo foi conferido em 30 de agosto de 2026 contra o [repositÃ³rio oficial WebMCP](https://github.com/webmachinelearning/webmcp), a [especificaÃ§Ã£o renderizada](https://webmachinelearning.github.io/webmcp/) e o [explainer da API declarativa](https://github.com/webmachinelearning/webmcp/blob/main/declarative-api-explainer.md).

O curso ensina `document.modelContext`, `registerTool()`, `getTools()`, `executeTool()` e ciclo de vida por `AbortSignal`. NÃ£o trata WebMCP como substituto do backend, de autorizaÃ§Ã£o ou de MCP.

## ProgressÃ£o da formaÃ§Ã£o

Todas as fases usam `<meta name="inema-course" content="webmcp-zero-expert">`. No GitHub Pages da organizaÃ§Ã£o, o estado local Ã© compartilhado pela mesma origem. Para outros domÃ­nios, o aluno pode exportar e importar a jornada em JSON com merge nÃ£o destrutivo.

Consulte [o contrato de entrega e passagem](docs/entrega-e-progressao.md).

## LicenÃ§a

CÃ³digo sob licenÃ§a MIT. ConteÃºdo educacional Â© INEMA.

<!-- inema-backlink:v1 -->
## Mais no INEMA.CLUB

- [Ficha completa deste curso](https://www.inema.club/cursos/249-formacao-webmcp-4-agent-developer/)
- [Guia: como aprender inteligÃªncia artificial](https://www.inema.club/aprender-inteligencia-artificial/)
- [Todos os cursos](https://www.inema.club/cursos/)
<!-- /inema-backlink:v1 -->

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>