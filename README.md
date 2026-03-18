# GeoCalc — Calculadora Geométrica

Aplicativo Android para cálculos geométricos do paralelepípedo.

## Fórmulas

- **Área (Superfície Total):** `AT = 2(bh + bp + hp)`
- **Perímetro Total:** `P = 4(b + h + p)`
- **Volume:** `V = b × h × p`

## Tecnologias

- HTML / CSS / JavaScript (PWA)
- Capacitor (empacotamento Android)

## Como gerar o APK

### Pré-requisitos

- Node.js (v18+)
- Android Studio (com SDK instalado)

### Passos

```bash
npm install
npx cap sync android
cd android
export JAVA_HOME="/c/Program Files/Android/Android Studio/jbr"
export ANDROID_HOME="$LOCALAPPDATA/Android/Sdk"
./gradlew assembleDebug
```

O APK será gerado em `android/app/build/outputs/apk/debug/app-debug.apk`.

## Instalação no celular

1. Envie o arquivo `.apk` para o celular (WhatsApp, email, cabo USB, etc.)
2. Permita instalação de fontes desconhecidas nas configurações do Android
3. Abra o arquivo e instale
4. Funciona 100% offline
