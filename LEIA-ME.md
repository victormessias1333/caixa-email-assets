# Assets dos e-mails — Caixa Consórcio · abandono-imob

Todos em PNG, em 2x do tamanho exibido no e-mail. Cada imagem tem fundo sólido da cor de onde fica, para não sumir quando o cliente de e-mail ativa o modo escuro.
Suba todos os arquivos **na mesma pasta** e me passe a URL dessa pasta (ex.: `https://SEU-USUARIO.github.io/caixa-email-assets/`).

| Arquivo | Exibido em | Onde entra | Opções |
|---|---|---|---|
| logo-caixa-consorcio-cor_360x54.png | 180×27 | Header (fundo branco) | A, B, C |
| logo-caixa-consorcio-cor-negativa_360x54.png | 180×27 | Reserva: header ou blocos sobre Azul Caixa | — |
| logo-caixa-rodape_256x62.png | 128×31 | Rodapé de redes (fundo #001364) | A, B, C |
| rede-whatsapp/instagram/facebook/youtube/tiktok/linkedin_72x72.png | 36×36 | Rodapé de redes | A, B, C |
| icone-caixa-calendario_96x96.png | 48×48 | Item de lista "Todo mês você concorre…" | A |
| icone-caixa-cifrao_96x96.png | 48×48 | Item de lista "Você pode dar lance…" | A |
| icone-caixa-casa_96x96.png | 48×48 | Item de lista "Contemplado, você usa a carta…" | A |
| icone-info-azul_40x40.png | 20×20 | Tarja de aviso azul | A, B, C (E1) |
| icone-info-laranja_40x40.png | 20×20 | Tarja de aviso laranja | A e B (E2) |
| icone-check_48x48.png | 24×24 | Itens do Bloco agrupado | C |

## Ainda não existe (precisa ser produzido)
- **Banners 1200×600** (exibidos em 600×300): Opção B (E1 e E2) e Opção C (E1 e E2). Na Opção C a frase vai **dentro** da imagem: "Seu imóvel começa no próximo passo" (E1) e "O plano do seu imóvel continua" (E2). JPG até ~200 KB.
- Os ícones das listas são **provisórios** (desenhados no estilo da família Caixa). Quando chegarem os oficiais, troque mantendo os mesmos nomes de arquivo e nada no HTML muda.

## Onde subir de graça para teste
**Recomendado: GitHub Pages**
1. Crie uma conta em github.com (se não tiver).
2. Crie um repositório **público** chamado `caixa-email-assets`.
3. Clique em *Add file → Upload files* e arraste todos os PNGs. Clique em *Commit changes*.
4. Vá em *Settings → Pages*, em *Branch* escolha `main` e `/ (root)` e salve.
5. Em 1 a 2 minutos os arquivos ficam em `https://SEU-USUARIO.github.io/caixa-email-assets/NOME-DO-ARQUIVO.png`.

Cuidados:
- O repositório é público: qualquer pessoa com o link vê as imagens. Use só para teste e apague depois.
- Não suba banner de campanha que ainda não foi lançada, se isso for sensível.
- Em produção, as imagens devem ficar no servidor oficial da Caixa (Azure, `sgemktcaixa.blob.core.windows.net`), como nos e-mails atuais.
