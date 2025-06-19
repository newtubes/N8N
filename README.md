# 🌞 Ritual Diario Automágico – N8N Flow ✨

**Automatización matinal creada con amor, propósito y tecnología.**  
Este flujo ejecutado en N8N genera diariamente una afirmación positiva y una frase poética inspiradora mediante Hugging Face, y las envía por Telegram como un mensaje personalizado para comenzar el día en sintonía.

---

## 🔮 ¿Qué hace este flujo?

Cada día a las 8:00 AM:

1. Genera un mensaje mágico con IA (affirmación + frase poética).
2. Personaliza el mensaje para la usuaria.
3. Envía el resultado por Telegram al canal o usuario elegido.

---

## ⚙️ Tecnologías utilizadas

- [N8N](https://n8n.io/) – Plataforma de automatización de flujos low-code.
- [Hugging Face API](https://huggingface.co/inference-api) – Generación de texto con modelos de lenguaje.
- [Telegram Bot API](https://core.telegram.org/bots/api) – Para enviar el mensaje al usuario.

---

## 🧙‍♀️ ¿Cómo usar este flujo?

1. Cloná este repositorio o descargá el archivo `ritual_diario_automagico_n8n.json`.
2. Ingresá a tu N8N.
3. Importá el flujo (`Import workflow`).
4. Configurá tus credenciales:
   - Agregá tu API Key de Hugging Face en un nuevo credential HTTP.
   - Agregá tu bot de Telegram y obtené tu Chat ID.
5. ¡Listo! Probalo manualmente y luego activalo.

---

## 📬 Ejemplo de mensaje generado

```
✨ Buen día, Beca 🌞  
Afirmación: “Estoy guiada por mi luz interior. Cada paso es un milagro.”  
Mensaje del Oráculo: “El sol que llevás adentro no depende del cielo.”  
🎶 Hoy será hermoso.
```

---

## 🌈 Personalización

Podés expandir este flujo agregando:
- Clima diario con OpenWeather API
- Tareas Notion o Google Tasks
- Canción recomendada (Spotify API)
- Visuales con IA (DALL·E, Stable Diffusion)

---

## 💜 Autora

**Rebeca Romcy Ribeiro**  
Curadora de automatizaciones con alma.  
Estudiante de IA y ciberseguridad. Creadora de mundos.  
GitHub: [tu_usuario](https://github.com/tu_usuario)

---

## 🌟 Licencia

Este proyecto se distribuye bajo la licencia MIT.  
Usalo, modificá y compartilo… siempre con magia ✨
