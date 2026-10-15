# envia.ai

Envie arquivos e textos entre celular e computador direto pelo navegador, sem login e sem guardar nada em servidor.

## Como usar

1. No primeiro aparelho, clique em **Criar conexão**.
2. No segundo aparelho, escaneie o QR code com a câmera (ou abra o site e digite o código de 6 caracteres).
3. Escolha arquivos ou escreva um texto. Funciona nos dois sentidos.

Os dados trafegam direto entre os aparelhos (WebRTC, criptografado). Só o "aperto de mão" inicial passa pelo servidor público gratuito do PeerJS.

## Publicar no GitHub Pages (grátis)

1. Crie uma conta em https://github.com (se ainda não tiver).
2. Clique em **New repository**, nomeie como `envia-ai` e deixe **Public**.
3. Clique em **uploading an existing file**, envie `index.html` e `README.md`, depois **Commit changes**.
4. Vá em **Settings → Pages**. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
5. Em 1 a 2 minutos o site fica em `https://SEU-USUARIO.github.io/envia-ai/`.

### Usar o domínio envia.ai (opcional, pago)

O GitHub Pages é grátis, mas o domínio `.ai` precisa ser comprado em um registrador (costuma custar dezenas de dólares por ano). Se comprar, em **Settings → Pages → Custom domain** digite `envia.ai` e aponte o DNS conforme a documentação do GitHub. Sem isso, o endereço `github.io` acima funciona normalmente.

## Limitações

- Precisa de internet nos dois aparelhos (mesma rede Wi-Fi não é obrigatória, mas ajuda).
- Algumas redes escolares ou corporativas bloqueiam conexões diretas (WebRTC). Se não conectar, tente o 4G do celular ou outra rede.
- Arquivos recebidos ficam na memória do navegador até o download, então prefira arquivos de até algumas centenas de MB.
- Mantenha a aba aberta e a tela ligada durante o envio.
