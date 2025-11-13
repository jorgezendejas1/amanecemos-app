# 💸 Amanecemos App

Aplicación inteligente para registrar gastos diarios con aprendizaje automático, desarrollada con **Firebase**, **Google Cloud** y **Vertex AI**.
Diseñada para usuarios que buscan una experiencia **intuitiva, moderna y 100% en español**.

---

## 🧭 Descripción general

**Amanecemos App** permite registrar gastos diarios, asociar fotos de tickets, controlar presupuestos semanales y visualizar reportes automáticos.
Usa IA para clasificar los gastos en categorías y subcategorías inteligentes, aprender de los hábitos del usuario y actualizar presupuestos dinámicamente.

---

## 🚀 Tecnologías principales

* **Firebase Firestore** – Base de datos en tiempo real
* **Firebase Cloud Functions (Node.js)** – Lógica backend
* **Google Cloud Storage** – Almacenamiento de imágenes
* **Vertex AI + Cloud Vision API** – Inteligencia Artificial
* **Firebase Hosting** – Despliegue web

---

## 📱 Pantallas principales

1. **Inicio** – Registro diario de gastos (con IA y fotos)
2. **Presupuesto** – Definición y edición de presupuestos por categoría
3. **Dashboard** – Gráficas y reportes dinámicos
4. **Amanecimos / Anochecemos** – Saldo inicial y final del día

---

## 🧠 Inteligencia Artificial

* Clasifica gastos automáticamente (texto y foto).
* Sugiere presupuestos iniciales y reajustes.
* Aprende de aprobaciones del usuario.
* Identifica categorías y subcategorías recurrentes.

---

## 💾 Estructura de datos

Colecciones principales en Firestore:

* `usuarios`
* `gastos`
* `presupuestos`
* `categorias`
* `resumen_diario`

---

## ⚙️ Funciones automáticas

* Guardado automático (autosave)
* Detección de categoría/subcategoría por IA
* Sincronización en tiempo real
* Exportación de reportes (PDF / Excel)
* Dashboard comparativo mensual/anual

---

## 💰 Moneda

Usa **pesos mexicanos (MXN)** en toda la app.

---

## 📤 Despliegue

1. Clona este repositorio
2. Conecta tu proyecto a Firebase
3. Ejecuta `firebase deploy`
4. Accede a la app desde tu URL en Firebase Hosting

---

## ✨ Créditos

Desarrollado por **Jorge Zendejas Lovera**
Arquitectura diseñada con ayuda de ChatGPT (GPT-5)
