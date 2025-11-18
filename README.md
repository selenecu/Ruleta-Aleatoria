# 🎁 Ruleta Aleatoria — Amigo Secreto

Aplicación web para realizar sorteos de *Amigo Secreto* de manera rápida, segura y divertida.  
El organizador ingresa a los participantes, ejecuta la ruleta y se genera un **link único con los resultados encriptados en la URL**.  
Cada participante solo puede ver su propio resultado, garantizando privacidad total.

---

## 🚀 Características principales

### 🎡 Ruleta interactiva
- Los participantes se sortean usando una ruleta visual animada.
- El resultado se asigna sin repeticiones y sin emparejamientos hacia sí mismo.

### 🔗 Link único y seguro
- Después del sorteo se genera un **enlace único** que contiene:
  - Todos los resultados en formato comprimido.
  - Datos encriptados dentro de la URL (Base64 + estructura JSON segura).
- El organizador solo comparte este enlace por WhatsApp u otro medio.

### 🔐 Privacidad garantizada
- Cada participante escribe su nombre al abrir el link.
- Solo puede ver **quién le tocó a él**.
- No puede ver los resultados de nadie más.
- No se necesita servidor: todo sucede en el navegador.

---

## 🧩 ¿Cómo funciona?

### 👤 1. El organizador
1. Ingresa a la app.
2. Registra la lista de participantes.
3. Ejecuta la ruleta para generar los emparejamientos.
4. Obtiene un link único con los resultados encriptados.
5. Lo comparte con todos los jugadores.

### 🎁 2. Cada participante
1. Abre el enlace enviado.
2. Escribe su nombre tal como fue registrado.
3. La app descifra únicamente su resultado.
4. Ve quién es su *Amigo Secreto*.

---

## 🛠️ Tecnologías utilizadas

- **HTML, CSS y JavaScript puro**
- **LocalStorage** para estado temporal
- **Base64 + JSON** para codificación de datos
- **URL dinámicas** para compartir resultados
- **Vercel / GitHub Pages** para despliegue

---

## 📦 Instalación (opcional para desarrollo)

Clona el repositorio:

```bash
git clone https://github.com/TU-USUARIO/ruleta-aleatoria.git
cd ruleta-aleatoria
