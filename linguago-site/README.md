# LinguaGO — documentos legais (GitHub Pages)

Hospedagem pública: **GitHub Pages** (páginas legais).

Repo: https://github.com/altavistaholdingltda-design/altavistaholdingltda-design.github.io (pasta `linguago-site/`)

- Início: https://altavistaholdingltda-design.github.io/linguago-site/
- Termos: https://altavistaholdingltda-design.github.io/linguago-site/termos/
- Privacidade: https://altavistaholdingltda-design.github.io/linguago-site/privacidade/
- Excluir conta: https://altavistaholdingltda-design.github.io/linguago-site/excluir-conta/

Fonte local espelhada em `docs/` neste workspace. Para republicar:

```bash
./tools/publish-github-pages.sh
```

## App Links

O Android consulta obrigatoriamente `https://altavistaholdingltda-design.github.io/.well-known/assetlinks.json`,
não o arquivo dentro de `/linguago-site/`. Publique o `assetlinks.json` também no repositório que serve a raiz
`altavistaholdingltda-design.github.io`. O arquivo local já inclui os certificados de debug e upload;
se a Play Console usar uma chave de assinatura diferente da chave de upload, acrescente também o SHA-256
exibido em Play Console → Integridade do app → Assinatura de apps do Google Play.
