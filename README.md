# Snowstorm

Uma página simples com efeito de neve, reprodução de áudio e sincronização de letras (lyrics) diretamente no front-end.

**Status:** Pronto — versão mínima funcional

**Sumário**
- **Descrição:** Página estática que reproduz uma faixa de áudio, exibe letras sincronizadas e adiciona efeito visual de neve.
- **Demo:** Abra [index.html](index.html) no seu navegador.
- **Tecnologias:** HTML, CSS, JavaScript — scripts locais `snowstorm.js` e `rabbit-lyrics.js`.

**Recursos**
- Efeito de neve com `snowstorm.js`.
- Reprodutor de áudio com controles e reprodução automática (`snowstorm.opus`).
- Sincronização de letras com Rabbit Lyrics (implementado em `rabbit-lyrics.js`).
- Estilos para as letras em `rabbit-lyrics.css`.
- Estilos gerais da página em `style.css`.

**Como executar**
1. Clone ou baixe este repositório.
2. Abra o arquivo [index.html](index.html) no navegador (Chrome, Firefox ou outro navegador moderno).

**Uso**
1. Ao abrir [index.html](index.html) a faixa em `content/snowstorm.opus` será carregada e iniciará (autoplay).
2. Use o player (controles de `audio`) para pausar, ajustar volume ou avançar.
3. As letras são exibidas e sincronizadas automaticamente conforme a posição do áudio.
4. O efeito de neve é executado em segundo plano; desative-o removendo ou comentando a inclusão de `content/snowstorm.js` em [index.html](index.html).

Comportamento padrão:
- O volume inicial é definido via script inline em [index.html](index.html) (valor padrão atual: 0.2). Para alterar, edite o bloco de script abaixo do elemento `audio`.
- As letras estão embutidas no HTML dentro da div com classe `rabbit-lyrics` em [index.html](index.html).

**Estrutura do projeto**
- [index.html](index.html) — página principal, inclui áudio, letras e scripts.
- [content/rabbit-lyrics.css](content/rabbit-lyrics.css) — estilos para exibição das letras.
- [content/rabbit-lyrics.js](content/rabbit-lyrics.js) — lógica de sincronização de letras (Rabbit Lyrics).
- [content/snowstorm.js](content/snowstorm.js) — script do efeito de neve.
- [content/snowstorm.opus](content/snowstorm.opus) — arquivo de áudio usado pela página.
- [style.css](style.css) — estilos gerais da página.

**Licença / Notas**
- O `snowstorm.js` inclui cabeçalho indicando licença BSD.
- O `rabbit-lyrics` menciona licença GPLv3 (veja comentários em `content/rabbit-lyrics.js`).
- Verifique os cabeçalhos dos arquivos para detalhes de licença antes de redistribuir.

**Contribuindo**
- Sugestões, correções e melhorias são bem-vindas. Abra uma issue descrevendo a proposta antes de enviar um pull request.

**Autor**
- Denis Bittencourt — https://denisbm.com