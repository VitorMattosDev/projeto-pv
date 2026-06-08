# 💌 Pedido de Namoro — Vitor & Patrícia

Página web interativa, romântica e 100% responsiva (funciona no celular e no notebook).
A música começa em **0:55** e fica em **loop**, em qualquer aparelho.

## 📁 O que tem aqui
```
index.html        → a página inteira (HTML + CSS + JS num arquivo só)
assets/           → as 8 fotos de vocês (foto1.jpg ... foto8.jpg)
```

## 🚀 Publicar no GitHub Pages (passo a passo)
1. Crie um repositório novo no GitHub (pode ser privado ou público).
2. Suba **o conteúdo desta pasta** — ou seja, o `index.html` e a pasta `assets/`
   devem ficar na **raiz** do repositório (não dentro de uma subpasta).
3. No repositório: **Settings → Pages**.
4. Em *Source*, escolha **Deploy from a branch**, branch **main**, pasta **/ (root)** e salve.
5. Aguarde ~1 minuto. O GitHub vai te dar a URL, algo como:
   `https://seu-usuario.github.io/nome-do-repo/`
6. Abra a URL no celular pra testar antes do grande dia. 😉

## 📱 Gerar o QR Code
Depois que tiver a URL final, gere o QR num site como `qrserver.com` ou `qr-code-generator.com`.
Aponte o QR para a URL do GitHub Pages e pronto. Me manda a URL que eu monto o QR pra você também.

## 🎵 Sobre a música (importante)
Navegadores de celular **bloqueiam áudio automático**. Por isso a página tem a tela
de abertura ("toque para abrir"): o toque dela é o que **libera o som**. Funciona
no iPhone (Safari), Android (Chrome) e no notebook. É só ela tocar para abrir. ✅

## ✏️ Como personalizar (você é programador, vai ser fácil)
Tudo está no `index.html`, bem comentado em português:

- **A carta**: procure por `<section id="carta">` e edite os parágrafos. Capricha! 💛
- **Data do primeiro beijo**: procure por `new Date(2025,9,24...` (mês 9 = outubro).
- **Início da música**: a constante `const START_AT=55;` (em segundos).
- **Outra música**: troque o `videoId:'dJ0_bEI_l7s'` pelo ID do vídeo desejado.
- **Trocar/adicionar fotos**: coloque as imagens em `assets/` e ajuste as tags
  `<img>` dentro de `<section id="galeria">`.
- **Textos das telas**: é só procurar pelo texto que você quer mudar.

Boa sorte, Vitor. Ela vai amar. ❤️
