<div align="center">

<img src="assets/readme/logo.png" alt="Velora" width="120" />

# Velora

**Chatbot con inteligencia artificial para Android, hecho en Flutter.**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)

[Descargar APK](../../releases/latest) · [Reportar un problema](../../issues)

</div>

---

## Sobre el proyecto

Velora es una app de chatbot con IA que permite conversar manteniendo el contexto y generar imágenes. La app está hecha en Flutter y se comunica con un backend propio en NestJS, que se encarga de las peticiones a Gemini a través de Vertex AI.

El proyecto nació como práctica del curso **Flutter + Gemini: Aplicaciones con inteligencia artificial** de [DevTalles](https://cursos.devtalles.com).

## Funciones

- **Chat con IA** que mantiene el contexto de la conversación
- **Generación de imágenes** con IA
- **Accesos rápidos** desde el ícono de la app:
  - Nuevo chat
  - Última conversación
  - Imágenes

## Capturas

<div align="center">
  <img src="assets/readme/screen_1.png" width="220" />
  <img src="assets/readme/screen_2.png" width="220" />
  <img src="assets/readme/screen_3.png" width="220" />
</div>

## Tecnologías

| Capa | Tecnología |
|---|---|
| App móvil | Flutter / Dart |
| Backend | NestJS |
| Inteligencia artificial | Gemini (Vertex AI, SDK Google Gen AI) |

## Descarga

Descarga la última versión del APK desde la sección [Releases](../../releases/latest).

1. Descarga el archivo `.apk` en tu teléfono Android.
2. Ábrelo y permite la instalación desde fuentes desconocidas si te lo pide.
3. Instala y abre Velora.

## Ejecutar el proyecto

**Requisitos:** Flutter SDK y un emulador o dispositivo Android.

```bash
git clone https://github.com/Leandrop011/velora.git
cd velora
flutter pub get
flutter run
```

> La app necesita el backend de Velora en ejecución. Configura la URL del backend antes de correrla.

## Privacidad

El backend guarda los mensajes, para mantener el contexto de la conversación, y las imágenes generadas, por un máximo de **30 días**.

Política de privacidad: [LINK]

## Soporte

¿Encontraste un error o tienes una sugerencia? Abre un [issue](../../issues) o escribe a **velorasoporte9@gmail.com**.

## Autor

**Leandro Pozo** · [GitHub](https://github.com/Leandrop011)

Publicado bajo **SoftDo**.
