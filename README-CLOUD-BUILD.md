# Ponto Escolar — gerar APK sem PC

Este projeto inclui um workflow do GitHub Actions em `.github/workflows/build-apk.yml`.
Ele compila automaticamente o APK de debug em um computador virtual do GitHub.

## Pelo celular

1. Crie uma conta no GitHub em https://github.com/.
2. Crie um repositório novo (pode ser privado), por exemplo `PontoEscolar`.
3. Envie **todos os arquivos e pastas deste projeto** para o repositório, mantendo a pasta `.github/workflows`.
4. Abra a aba **Actions** do repositório.
5. Entre em **Build Ponto Escolar APK**.
6. Toque em **Run workflow** (ou faça um novo commit; o workflow também roda em `main`).
7. Espere o processo terminar com um ✓ verde.
8. Abra a execução concluída e procure **Artifacts**.
9. Baixe `Ponto-Escolar-debug-apk` e extraia o `app-debug.apk`.
10. No Android, abra o APK para instalar. Se o sistema pedir, permita a instalação de aplicativos dessa fonte.

## Observação

O APK gerado por este workflow é uma build **debug**, adequada para testar o aplicativo no celular. Para publicar na Play Store ou distribuir como versão final, depois será necessário configurar assinatura de release.
