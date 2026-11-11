# QA Mobile — Appium + BrowserStack (scaffold)

Scaffold y guía para **automatización móvil iOS/Android** con Appium y ejecución en la nube (BrowserStack), pensado para portafolio de QA Automatizador.

> Nota: este repo documenta el enfoque y un ejemplo de capabilities. Para correr en BrowserStack se requieren credenciales propias (`BROWSERSTACK_USERNAME` / `BROWSERSTACK_ACCESS_KEY`).

## Qué cubre
- Estrategia de pruebas móviles (smoke / regresión)
- Capabilities Appium (Android / iOS)
- Flujo BrowserStack remoto
- Relación con Espresso / XCUITest (nativo) vs Appium (cross-platform)

## Estructura sugerida
```
tests/
  smoke/
  regression/
config/
  android.capabilities.json
  ios.capabilities.json
```

## Autora
[Ximena Sarrazola](https://github.com/ximena012-code)
