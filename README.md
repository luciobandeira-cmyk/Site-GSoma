# G-Soma — site institucional

Site estático (HTML, CSS e JS puros) pronto para o GitHub Pages. Não precisa de build.

## Como publicar

1. Crie um repositório no GitHub (ex.: `gsoma-site`).
2. Envie **todo o conteúdo desta pasta** para a raiz do repositório (inclusive `.nojekyll` e a pasta `img/`).
3. Em **Settings → Pages**, em *Build and deployment*, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
4. Em 1–2 minutos o site abre em `https://SEU-USUARIO.github.io/gsoma-site/`.

Todos os links usam caminhos relativos, então funcionam em qualquer nome de repositório.

## Formulário de orçamento

O envio usa o FormSubmit (`comercial@reviversaude.com.br`). Na **primeira** solicitação feita no site publicado, o FormSubmit manda um e-mail de ativação para esse endereço: é preciso clicar no link dele uma vez. Antes disso, os envios não chegam.

## Pendências do cliente

- **E-mail:** quando o novo domínio estiver pronto, trocar `comercial@reviversaude.com.br` em todos os arquivos `.html` (barra superior, rodapé, página Contato, endpoint do formulário).
- **LinkedIn:** o link do rodapé ainda aponta para a página antiga.
- **Favicon:** `favicon.svg` é provisório (letra G). Substituir pelo ícone oficial.
- **Domínio próprio (opcional):** criar um arquivo `CNAME` com o domínio e configurar o DNS conforme a documentação do GitHub Pages.

## Estrutura

- `*.html` — 15 páginas + `404.html`
- `img/` — fotos em WebP
- `favicon.svg`, `robots.txt`, `.nojekyll`
