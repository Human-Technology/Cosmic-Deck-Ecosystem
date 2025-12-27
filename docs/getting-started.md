# 🚀 Getting Started — Cosmic Deck (Community Edition)

Bienvenido a **Cosmic Deck Community Edition**.

En esta guía aprenderás a:
- Conectar tu Arduino
- Flashear el firmware
- Crear tu primer botón funcional

⏱️ Tiempo estimado: **5–10 minutos**

---

## 🧩 Requisitos

Antes de comenzar, asegúrate de tener:

- Arduino **Uno, Nano o Mega**
- Botones conectados (ver [`community-wiring.md`](https://github.com/Human-Technology/Cosmic-Deck-Ecosystem/blob/main/docs/community-wiring.md))
- Cosmic Deck App (Community Edition)
- Windows 10 / 11

---

## 🖥️ Paso 1 — Abre Cosmic Deck

Al iniciar la aplicación verás la interfaz principal:

<p align="center">
  <img src="/assets/cosmic_deck.png" width="750">
</p>

### Elementos principales:
- **Selector de perfil** (arriba a la izquierda)
- **Estado de conexión** (Disconnected / Connected)
- **Grid de botones** (9 botones por espacio)
- **Panel de edición** (lado derecho)

---

## 🔌 Paso 2 — Conecta tu Arduino
<p align="center">
  <img src="/assets/arduino_firmware.gif" width="750">
</p>

1. Conecta tu Arduino al PC por USB
2. Selecciona el **puerto COM** en la parte superior
3. Presiona **Connect**

Cuando el Arduino se conecta:
- El firmware se flashea automáticamente
- El estado cambia a **Connected**
- El grid queda habilitado

> ⚠️ Si es la primera vez, el proceso puede tardar unos segundos.

---

## 🎛️ Paso 3 — Entiende los Espacios

Cosmic Deck Community incluye **3 espacios por perfil**.

- Cada espacio reutiliza los mismos 9 botones
- Los botones físicos inferiores permiten cambiar de espacio
- El espacio activo se resalta en azul
- Puedes renombrar cada espacion dando clic derecho

<p align="center">
  <img src="/assets/cosmic_deck_space_2.gif" width="750">
</p>

---

## 🟦 Paso 4 — Configura un perfil

1. Los perfiles se Listan del Lado izquierdo superior.
2. Siempre existira el de por default.
3. Al dar clic derecho podras crear un nuevo perfil
4. En la version community puedes crear tres perfiles (Incluyendo el Default).
5. Puedes Renombrar cada perfil.

   
<p align="center">
  <img src="/assets/cosmic_deck_profiles.gif" width="750">
</p>

---

## 🟦 Paso 5 — Configura tu primer botón

1. Haz clic en uno de los botones del grid
2. Se abrirá el panel **Editing Button**

### ✏️ Apariencia
- Cambia el **nombre del botón**
- Asigna un **icono** (opcional)

### ⚙️ Acción
Selecciona el **Action Type** que deseas:
- Keyboard Shortcut
- Open Program
- Open URL
- Write Text
- Multimedia
- Command

> Al seleccionar una acción, aparecerán las opciones correspondientes.

---

## ▶️ Paso 6 — Prueba el botón

1. La configuracion se Guarda Automaticamente
2. Presiona el botón físico conectado al Arduino
3. La acción se ejecutará inmediatamente
   
---

## 🔁 Paso 7 — Cambia de espacio

Usa los botones auxiliares físicos:

- ⬅️ Botón izquierdo → Espacio anterior
- ➡️ Botón derecho → Espacio siguiente

Cada espacio puede tener acciones completamente diferentes.

---

## 🛠️ Consejos rápidos

- Empieza con acciones simples (abrir apps, texto)
- Usa nombres claros en los botones
- Organiza un espacio por tarea (trabajo, edición, sistema)

---

## 🧪 Solución de problemas

**❌ No conecta**
- Verifica el puerto COM
- Desconecta y vuelve a conectar el Arduino

**❌ El botón no responde**
- Revisa el cableado
- Verifica el pin correcto
- Asegúrate de estar en el espacio correcto

**❌ Acción incorrecta**
- Revisa la configuración del botón
- Confirma que esté marcado como **Active**

---

## 🚀 ¿Qué sigue?

Una vez que domines lo básico, puedes:
- Crear macros complejas
- Usar múltiples perfiles
- Optimizar tu flujo de trabajo

Consulta:
- [`community-wiring.md`](https://github.com/Human-Technology/Cosmic-Deck-Ecosystem/blob/main/docs/community-wiring.md)
- [Tutorial completo](https://...)
---

## ❤️ Bienvenido a Cosmic Deck

Cosmic Deck Community está diseñado para:
- Reutilizar hardware
- Aprender
- Crear herramientas reales de productividad

Gracias por ser parte de la beta 🚀  
Creado por **José Sánchez**
