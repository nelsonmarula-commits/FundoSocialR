# Fundo Social Resiliência Android WebView

Aplicativo Android WebView para abrir:

https://fundosocial.resilience.co.mz

## Conteúdo incluído

- `.github/workflows/android.yml`
- `gradlew`
- `gradlew.bat`
- `gradle/wrapper/gradle-wrapper.jar`
- `gradle/wrapper/gradle-wrapper.properties`
- `MainActivity.java`

## Como gerar APK no GitHub

1. Crie um repositório novo no GitHub.
2. Faça upload de **todo o conteúdo** deste projeto, incluindo a pasta `.github` e a pasta `gradle/wrapper`.
3. Vá em **Actions**.
4. Abra **Build Android APK**.
5. Aguarde terminar.
6. Baixe o artefacto **app-debug**.

## Como gerar localmente

```bash
chmod +x gradlew
./gradlew assembleDebug
```

O APK será gerado em:

`app/build/outputs/apk/debug/app-debug.apk`
