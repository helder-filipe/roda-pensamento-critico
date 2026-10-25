# A Roda do Pensamento Crítico

Site estático e responsivo, em português de Portugal, baseado nas 24 perguntas da imagem fornecida.

## Iniciar

Abra `index.html` num navegador, ou sirva esta pasta com `python3 -m http.server 8000` e visite `http://localhost:8000`.

Pode publicar a pasta diretamente na Vercel, Netlify ou GitHub Pages. Não necessita de compilação nem de chaves de API. A fonte tipográfica tenta carregar Google Fonts; se estiver offline, são usadas fontes locais alternativas.

## Organização
- `index.html`: estrutura semântica, secções e janela de histórias.
- `styles.css`: estilo editorial, adaptação a ecrãs móveis, modo escuro e acessibilidade.
- `app.js`: 8 dimensões, 24 perguntas, 120 histórias determinísticas (cinco universos narrativos recorrentes × 24 perguntas), exercícios, filtros e progresso.

## Persistência e privacidade
O progresso e as reflexões são guardados apenas no `localStorage` do navegador. Não há registo, contas nem transferência destes conteúdos para servidores. A opção «Repor progresso» apaga estes dados locais. As histórias são ficcionadas, estáveis e geradas a partir de textos fixos do código; não utilizam IA nem sorteio. O botão «Surpreender-me» só sorteia uma pergunta, nunca a respetiva história.

## Nota pedagógica
As situações são exemplos ilustrativos, não estudos científicos nem aconselhamento médico, jurídico ou profissional. Em futuras versões, pode ser acrescentada revisão editorial individual das 120 histórias, referências bibliográficas, avaliações e exportação de progresso.
