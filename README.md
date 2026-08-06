# Documentos legais — CalcFrete

Páginas estáticas com os documentos legais do app **CalcFrete**, prontas para publicar no
**GitHub Pages** e usar como links obrigatórios no **Google Play Console** e no
**App Store Connect**:

| Arquivo | Conteúdo | URL publicada |
| --- | --- | --- |
| `index.html` | Política de Privacidade | `https://SEU_USUARIO.github.io/calcfrete-privacidade/` |
| `termos.html` | Termos de Uso | `https://SEU_USUARIO.github.io/calcfrete-privacidade/termos.html` |

As duas páginas têm navegação entre si (no topo e no rodapé).

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
2. Cole a URL pública do GitHub Pages (`index.html`).
3. Em **Segurança dos dados**, declare os dados coletados de acordo com esta política
   (conta/e-mail, dados financeiros e de uso inseridos pelo usuário, áudio quando usar a voz,
   identificador de publicidade para anúncios).

## Como usar no App Store Connect

1. **App Privacy → Privacy Policy URL**: cole a URL do `index.html`.
2. **Licença/EULA**: se optar por termos próprios em vez do padrão da Apple, informe a URL do
   `termos.html` (a Apple exige o link quando o app tem assinatura).
3. **Privacy Nutrition Labels**: declare de acordo com a política — conta/e-mail (inclusive login
   Google e Apple), dados financeiros inseridos, áudio da voz e identificador de publicidade.

## Personalização

- **E-mail de contato:** as páginas usam `innovateappsco@gmail.com`. Altere se necessário.
- **Nome do app:** se você renomear o CalcFrete, atualize títulos e textos das duas páginas.
- **Data:** atualize "Última atualização" sempre que mudar qualquer um dos documentos.

## ⚠️ Existe uma segunda cópia destes documentos

O mesmo conteúdo também é publicado no **Firebase Hosting**, em `App-Motorista/public/`
(`privacidade.html` e `termos.html`) — e é dessa cópia que o **aplicativo** puxa os links. Ao
alterar qualquer documento aqui, replique lá (e vice-versa), senão as versões divergem.
