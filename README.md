# Ponto Escolar v6

Aplicativo Android para controle de presença escolar e tarefas.

## Recursos
- Bater entrada e saída com data e hora automáticas.
- Impede saída sem entrada e evita registros duplicados no mesmo dia.
- Permite marcar falta manualmente por dia.
- Calendário mensal com indicação visual de presença/falta.
- Detalhes de cada dia com entrada, saída, status e criação de tarefa.
- Resumo de frequência.
- Histórico de presença.
- Tarefas organizadas por data, com conclusão, edição e exclusão.
- Persistência local no aparelho.

## Requisitos
- Android Studio com Android SDK 35.
- Kotlin 2.0.21 / Android Gradle Plugin 8.7.3.
- Min SDK 24 (Android 7.0).

## Gerar o APK
Abra a pasta do projeto no Android Studio, aguarde a sincronização do Gradle e use **Build > Build APK(s)**.

> Observação: este pacote não inclui o Gradle Wrapper e, neste ambiente, não há uma instalação local do Gradle/Android SDK disponível para confirmar uma compilação de APK aqui.

## Gerar APK sem PC

O projeto inclui `.github/workflows/build-apk.yml`, que compila o APK usando o GitHub Actions. Consulte `README-CLOUD-BUILD.md` para o passo a passo pelo celular.
