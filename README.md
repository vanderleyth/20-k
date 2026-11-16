# Meta 20k - App Android (Build Automático via GitHub Actions)

Este pacote já contém o aplicativo web completo (`www/index.html`) e a automação do **GitHub Actions** (`.github/workflows/build-apk.yml`) que compila o `.apk` automaticamente na nuvem sem precisar instalar Android Studio no seu computador.

## Como gerar o APK em 3 minutos:
1. Crie um repositório novo no seu **GitHub** (pode ser público ou privado, ex: `meta-20k-app`).
2. Extraia este arquivo `.zip` e envie todos os arquivos para o repositório (mantendo a pasta `www/` e a pasta oculta `.github/workflows/build-apk.yml`).
3. No GitHub, abra a aba **Actions** do repositório.
4. Clique em **Build Android APK** > **Run workflow** (ou aguarde o build iniciar automaticamente após o envio).
5. Quando aparecer o ícone verde (cerca de 2 a 3 minutos), entre na execução concluída, role até **Artifacts** e baixe **`Meta20k-Android-APK`**.
6. Descompacte o `app-debug.apk` no seu celular Samsung e instale normalmente!
