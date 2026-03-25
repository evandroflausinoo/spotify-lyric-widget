# Spotify Lyric Widget

Protótipo de um widget mobile de letras para o Spotify — exibe a letra e a tradução em tempo real, linha a linha, como um overlay na parte inferior do celular.

A ideia é replicar no mobile a experiência que o Spotify Desktop já oferece nativamente: letra sincronizada aparecendo enquanto a música toca, sem precisar sair do app.

---

## Conceito

O widget funciona como uma **subtela dentro do próprio celular** — uma camada que aparece sobre o app do Spotify mostrando:

- Linha atual da letra em destaque
- Tradução logo abaixo
- Linha anterior e próxima em tom mais fraco (contexto)
- Controles de player integrados
- Barra de progresso da música

---

## Funcionalidades (protótipo atual)

- Exibição de letra linha a linha com animação fade
- Tradução sincronizada abaixo da letra
- Contexto visual: linha anterior e próxima em tom reduzido
- Controles: play/pause, próxima, anterior, shuffle, repeat
- Barra de progresso com timer
- Troca de músicas
- Design dark mode estilo Spotify
- Interface responsiva (mobile-first)

---

## Tecnologias

- HTML5
- CSS3 (animações, backdrop-filter, variáveis CSS)
- JavaScript vanilla

---

## Como rodar

1. Clone o repositório:
```bash
git clone https://github.com/evandroflausinoo/spotify-lyric-widget.git
cd spotify-lyric-widget
```

2. Abra o `index.html` no navegador — não precisa de servidor.

---

## Próximos passos

- [ ] Integração com **Spotify Web API** — puxar a música tocando em tempo real
- [ ] Sincronização real de letras via API de lyrics
- [ ] Versão nativa mobile (React Native ou Flutter)
- [ ] Modo overlay real no Android (Floating Window)
- [ ] Suporte a múltiplos idiomas na tradução

---

## Estrutura

```
spotify-lyric-widget/
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## Autor

**Evandro Flausino**  
Estudante de Ciência da Computação — UFU  
[github.com/evandroflausinoo](https://github.com/evandroflausinoo)
