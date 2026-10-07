# Concord — downloads e atualizações

Este repositório público contém somente os instaladores, pacotes de distribuição e arquivos de atualização do Concord. O código-fonte permanece privado.

Baixe a versão de teste mais recente na aba **Releases**:

- Windows x64: `Concord-Windows-Setup.exe` (instalação por usuário, sem administrador).
- macOS Intel e Apple Silicon: `Concord-macOS.zip`; mova o app extraído para Aplicativos.
- Linux x64: `Concord-Linux-x64.tar.gz`; mantenha `lib` e `data` junto de `bundle/concord`.

A partir da versão 0.3, macOS e Windows consultam atualizações públicas e verificam assinaturas Ed25519 antes de instalar. Encerre chamadas e aguarde os envios antes da atualização. No Linux, o aplicativo avisa e abre o download; a substituição é manual.

Não há certificado de distribuição Apple/Windows nesta beta. Os sistemas podem apresentar avisos na primeira instalação. Não desative as proteções do sistema. Se não quiser aprovar a instalação, use o [site](https://concord-topaz.vercel.app).

A release técnica `appcast` hospeda os feeds permanentes; ela não é um instalador.
