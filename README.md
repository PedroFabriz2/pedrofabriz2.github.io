# Portfólio de Hardware

Página única, pronta para hospedar no GitHub Pages.

## Estrutura

```
portfolio/
├── index.html              → a página (edite diretamente)
├── assets/
│   ├── curriculo.pdf        → COLOQUE AQUI o seu currículo em PDF
│   └── hardwares/
│       ├── driver-motor-bldc.svg   → troque por fotos reais dos seus projetos
│       ├── estacao-solda.svg
│       ├── modulo-iot.svg
│       └── fonte-bancada.svg
```

As imagens dos hardwares são placeholders (ilustrações esquemáticas) só para
você ver o layout funcionando. Troque cada uma por uma foto real do seu
projeto (pode ser `.jpg`, `.png` ou `.webp` — só ajuste a extensão no
`src=""` do `index.html`).

## Como personalizar

1. Abra `index.html` num editor de texto.
2. No topo do arquivo, os comentários `<!-- ... -->` explicam onde trocar
   nome, bio, currículo e cada projeto.
3. Para adicionar um novo hardware, copie um bloco inteiro
   `<article class="project"> ... </article>` e cole logo abaixo do último,
   depois edite imagem, título, descrição e as especificações da lista
   `<ul class="specs">`.
4. Salve o PDF do currículo como `assets/curriculo.pdf` (ou mude o `href`
   do botão no `<header>` se preferir outro nome).

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (por exemplo `seu-usuario.github.io`,
   ou qualquer nome, como `portfolio`).
2. Envie todo o conteúdo desta pasta para a raiz do repositório.
3. No GitHub, vá em **Settings → Pages**.
4. Em "Source", selecione a branch `main` e a pasta `/ (root)`.
5. Salve. Em alguns minutos a página estará em:
   - `https://seu-usuario.github.io/` (se o repositório se chamar
     `seu-usuario.github.io`), ou
   - `https://seu-usuario.github.io/nome-do-repositorio/` (para qualquer
     outro nome de repositório).
