# Portfólio — Vinicius Vasques

Site estático (HTML, CSS e JavaScript) para o **GitHub Pages**, com endereços limpos, uma página por case, português e inglês e medição com consentimento.

- Repositório: https://github.com/viniciusvasques1981/Portfolio
- Endereço do site: **https://viniciusvasques1981.github.io/Portfolio/**

## Estrutura

```
index.html                    página inicial
sobre/                        Sobre mim
privacidade/                  política de privacidade
cases/mrv-360/  cases/mrs/  cases/anglo-american/  cases/zig4plan/  cases/emvita/  cases/miobike/  cases/vaxie/
assets/                       estilos, scripts, imagens, fontes e o currículo em PDF
assets/config.js              IDs de medição
404.html  robots.txt  sitemap.xml  .nojekyll
```

## 1. Publicar

1. No repositório `Portfolio`, clique em **Add file > Upload files** e envie **todas as pastas e arquivos** deste pacote para a raiz (o `.nojekyll` é oculto e pode ficar de fora).
2. Em **Settings > Pages**, escolha **Deploy from a branch**, branch **main** e pasta **/ (root)**, e salve.
3. Em poucos minutos o site abre em **https://viniciusvasques1981.github.io/Portfolio/**.

O repositório precisa ser **público** para o Pages gratuito.

## 2. Medição

- **Microsoft Clarity:** já configurado (projeto `zcmxvzfp50`).
- **Google Analytics 4:** crie uma propriedade em analytics.google.com, copie o ID de medição (começa com `G-`) e cole em `assets/config.js`, no campo `ga`. O aviso de cookies e a política de privacidade passam a citar o Google Analytics automaticamente.
- Os serviços só carregam **depois que o visitante clica em Aceitar** no aviso de cookies. O rodapé tem **Gerenciar cookies** e há uma página de **Política de privacidade**. Revise o texto antes de divulgar; ele não substitui orientação jurídica.

## 3. Google Search Console (opcional)

1. Em search.google.com/search-console, adicione uma propriedade **Prefixo do URL** com `https://viniciusvasques1981.github.io/Portfolio/`.
2. Verifique pelo método **Arquivo HTML**: baixe o arquivo que o Google fornece (`googleXXXX.html`) e envie para a raiz do repositório.
3. Envie o sitemap: `https://viniciusvasques1981.github.io/Portfolio/sitemap.xml`.

## 4. Atualizar

Edite o arquivo e faça o commit. As imagens ficam em `assets/img/` e carregam sob demanda. O currículo fica em `assets/Vinicius_Vasques_Curriculo.pdf` (sem telefone).

## Observações

- A fonte Outfit é hospedada no próprio site.
- Os protótipos do Figma e as pré-visualizações do Behance e do Instagram são carregados desses serviços quando o visitante os abre.
- Endereços padronizados: `/sobre/`, `/cases/nome-do-case/`, `/privacidade/`.
