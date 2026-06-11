# Política de Privacidade — CalcFrete

Página estática (`index.html`) com a Política de Privacidade do app **CalcFrete**, pronta para
publicar no **GitHub Pages** e usar como link obrigatório no **Google Play Console**.

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub (ex.: `calcfrete-privacidade`) e envie estes arquivos:
   ```bash
   cd privCalcFrete
   git init
   git add .
   git commit -m "Política de Privacidade do CalcFrete"
   git branch -M main
   git remote add origin https://github.com/SEU_USUARIO/calcfrete-privacidade.git
   git push -u origin main
   ```
2. No GitHub: **Settings → Pages**.
3. Em **Source**, selecione a branch `main` e a pasta `/ (root)` e clique em **Save**.
4. Após alguns minutos, a página ficará disponível em:
   `https://SEU_USUARIO.github.io/calcfrete-privacidade/`

## Como usar no Google Play Console

1. Acesse **Play Console → seu app → Política → Conteúdo do app → Política de Privacidade**.
2. Cole a URL pública do GitHub Pages.
3. Em **Segurança dos dados**, declare os dados coletados de acordo com esta política
   (conta/e-mail, dados financeiros e de uso inseridos pelo usuário, áudio quando usar a voz).

## Personalização

- **E-mail de contato:** o arquivo usa `kevinramon121@gmail.com`. Altere se necessário.
- **Nome do app:** se você renomear o CalcFrete, atualize o título e os textos do `index.html`.
- **Data:** atualize "Última atualização" sempre que mudar a política.
