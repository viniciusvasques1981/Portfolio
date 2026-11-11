# Portfólio — Vinicius Vasques

Site estático (HTML, CSS e JavaScript em um único arquivo), pronto para o **GitHub Pages**.

## Arquivos

- `index.html`: o site inteiro (textos, imagens dos cases e estilos).
- `Vinicius_Vasques_Curriculo.pdf`: o currículo (sem telefone). O botão "Baixar Currículo" já tem esse PDF embutido no `index.html`; o arquivo aqui serve como cópia para links diretos.
- `.nojekyll`: faz o GitHub Pages publicar os arquivos como estão.

## Publicar no GitHub Pages (pela interface)

1. No GitHub, clique em **New repository**. Escolha o nome (por exemplo `portfolio`), deixe como **Public** e crie.
2. Na página do repositório, clique em **Add file > Upload files** e arraste o conteúdo desta pasta (`index.html`, o PDF, o `README.md` e o `.nojekyll`). Clique em **Commit changes**.
3. Vá em **Settings > Pages**. Em **Build and deployment**, escolha **Deploy from a branch**, a branch **main** e a pasta **/ (root)**. Clique em **Save**.
4. Em alguns minutos o endereço aparece na mesma tela:
   - repositório com o nome `SEU-USUARIO.github.io`: `https://SEU-USUARIO.github.io/`
   - qualquer outro nome: `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`

## Publicar pelo terminal

```bash
git init
git add .
git commit -m "Portfólio"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git
git push -u origin main
```

Depois siga o passo 3 acima.

## Domínio próprio (opcional)

Em **Settings > Pages > Custom domain**, informe o domínio e aponte o DNS conforme a documentação do GitHub Pages.

## Atualizar o site

Edite o `index.html` (ou envie uma nova versão pelo **Upload files**) e faça o commit. A publicação é refeita sozinha.

## Observações

- O repositório público expõe todo o conteúdo do site, inclusive as telas dos cases. Revise se há dados internos de clientes antes de publicar.
- Os protótipos do Figma nos cases carregam do próprio Figma (`embed.figma.com`) e as fontes carregam do Google Fonts. As demais imagens e o PDF do currículo estão dentro do `index.html`.
- A navegação usa endereços com `#` (por exemplo `/#case-mrs`), que funcionam no GitHub Pages sem configuração extra.
