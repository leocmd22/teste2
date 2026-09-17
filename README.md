# Portfólio — Leonardo | Editor de Vídeo

Site de portfólio em página única (`index.html`), autossuficiente — não precisa de servidor, build ou instalação.

**Link publicado:** https://claude.ai/artifact/EbYLrWkbC7Uyc1jBRD5Qog

## O que tem no site
- Fundo preto com pontos brancos minimalistas
- Tipografia arredondada (Quicksand, do Google Fonts), em branco
- Cabeçalho com foto circular + "Leonardo | Editor" + "Video editing for Youtubers"
- 3 vídeos em destaque, lado a lado, em cartões quadrados com ícone de play — ao clicar, abre o vídeo no YouTube em uma nova aba
- 3 Shorts, em cartões verticais, logo abaixo, com o mesmo comportamento de clique
- Contato: e-mail (abre o app de e-mail do visitante), X/Twitter (redireciona) e Discord (abre um cartão para copiar seu usuário)

**Sobre os vídeos:** o ambiente de preview do Claude bloqueia players do YouTube incorporados diretamente na página (por isso apareceu aquele aviso de "conteúdo bloqueado"). Por isso os cartões de vídeo funcionam como um link estilizado: ícone de play + clique abre o vídeo real no YouTube em uma nova aba. Isso também deixa a página mais rápida, já que não carrega vários players ao mesmo tempo.

## Pendências para você me enviar
1. **Sua foto** — ainda não recebi nenhum arquivo de imagem, então o avatar está com um "L" no lugar. Assim que enviar a foto, eu troco.
2. **Seu e-mail real** — hoje está com um endereço de exemplo (`seuemail@aqui.com`). Me diga o e-mail correto e eu atualizo.

## Como personalizar você mesmo (opcional)
Tudo está no arquivo `index.html`. Abra-o em qualquer editor de texto:

- **Foto de perfil:** procure o comentário `<!-- Para colocar sua foto... -->` dentro da `div class="avatar"` e troque o `<span class="initials">L</span>` por `<img src="sua-foto.jpg" alt="Foto de Leonardo">`.
- **E-mail de contato:** troque `seuemail@aqui.com` no `href="mailto:..."` pelo seu e-mail.
- **Trocar um vídeo ou short:** troque o link no `href` de cada cartão (`<a class="card ...">`) pela URL completa do novo vídeo ou short do YouTube.
- **Usuário do Discord:** aparece em dois lugares — no texto dentro do cartão (`<span>leonardo.edicao</span>`) e na variável `username` dentro do `<script>`. Troque nos dois.
- **Link do X/Twitter:** está no `href="https://x.com/home"` do botão do X.

## Hospedagem
O site já está publicado com um link do Claude (acima), que você pode abrir e compartilhar diretamente. Se preferir hospedar em outro lugar (domínio próprio, Netlify, Vercel, GitHub Pages), basta pegar o arquivo `index.html` e subir — ele funciona sozinho, sem dependências além da fonte carregada do Google Fonts.
