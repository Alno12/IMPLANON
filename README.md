# Consulta Implante Etonogestrel

App estático para padronizar a consulta pré-inserção do implante de etonogestrel 68 mg (Implanon NXT®):

- avaliação de elegibilidade e contraindicações;
- nota pronta para o prontuário;
- botão **Gerar termo (PDF)**, que preenche o termo da Secretaria de Saúde de Guaíra (`termo.pdf`) no próprio navegador.

Nenhum dado de paciente é enviado a servidor: tudo roda no navegador e some ao fechar a aba.

## Arquivos

- `index.html` — o app.
- `termo.pdf` — termo em branco usado como base.
- `pdf-lib.min.js` — biblioteca pdf-lib 1.17.1 (MIT), usada para preencher o PDF.

## Publicação no Netlify

Add new site → Import an existing project → GitHub → este repositório. Build command e publish directory em branco (raiz). Cada push na branch `main` publica de novo.
