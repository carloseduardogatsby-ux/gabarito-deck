# Gabarito Deck - Gerador de APK pelo GitHub

Este projeto contém o app de gabarito offline e um fluxo do GitHub Actions para gerar um APK Android sem precisar de computador.

## Como usar pelo celular

1. Crie um repositório no GitHub.
2. Envie todos os arquivos deste projeto para o repositório.
3. Abra a aba **Actions**.
4. Escolha **Gerar APK Android**.
5. Toque em **Run workflow**.
6. Aguarde a build terminar.
7. Abra a execução concluída e baixe o artifact **Gabarito-Deck-APK-debug**.
8. Extraia o ZIP do artifact e instale o arquivo `app-debug.apk` no Android.

O APK gerado é de teste/debug, ideal para instalar no seu próprio celular. Para publicar em loja, será necessário gerar uma versão assinada/release.
