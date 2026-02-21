# 🚗 Urban Routes – Testing Funcional Web

## 📌 Descripción del Proyecto

Este proyecto se enfoca en el testing funcional de una aplicación web para la funcionalidad de Car Sharing de la plataforma Urban Routes.

### El alcance incluyó:

- Testing de interfaz de usuario (validación de diseño)
- Testing funcional
- Testing cross-browser
- Diseño de casos de prueba
- Reporte de bugs en Jira
- Seguimiento de ejecución (PASS / FAIL / BLOCKED)

---

## 🖥 Entornos de Prueba

### Las pruebas se realizaron en:

- Google Chrome – Resolución 800x600
- Mozilla Firefox – Resolución 1920x1080

Las pruebas de diseño fueron ejecutadas en ambos entornos.
La validación de lógica funcional se realizó en un entorno según lo requerido.

---

## 📋 Documentación de Testing

Toda la documentación fue estructurada en un único archivo Excel que contiene cuatro hojas:

- Design Checklist (más de 54 puntos de verificación)
- Checklist Funcional – Método de Pago y Agregar Tarjeta
- Casos de Prueba – Lógica del botón "Reservar"
- Casos de Prueba – Flujo completo de reserva

Cada caso de prueba fallido incluye un enlace al bug reportado en Jira.

---

## 🔍 Alcance del Testing

### 1️⃣ Testing de UI / Diseño

Validaciones realizadas:

- Verificación de layout
- Validación de tipografía y ortografía
- Posicionamiento de elementos
- Validación del comportamiento del mapa
- Verificación de ventanas modales
- Comparación entre navegadores

Se identificaron y documentaron bugs críticos relacionados con el mapa.

---

### 2️⃣ Método de Pago y Validación de Tarjeta

#### Técnicas aplicadas:

- Partición en Clases de Equivalencia
- Análisis de Valores Límite

#### Validaciones realizadas:

- Longitud y formato del número de tarjeta
- Reglas de validación del CVV
- Estados habilitado/deshabilitado de botones
- Manejo de múltiples tarjetas
- Prevención de duplicados
- Problemas de usabilidad (se detectó un bug de autoformato)

---

### 3️⃣ Lógica del Botón "Reservar"

#### Validaciones realizadas:

- Todos los posibles estados del botón
- Cambios dinámicos de texto
- Comportamiento según campos completados
- Flujos positivos y negativos

#### Los casos de prueba incluyen:

- ID
- Precondiciones
- Pasos
- Resultados Esperados
- Resultados Actuales
- Enlace al bug (cuando aplica)

---

### 4️⃣ Testing del Flujo de Reserva

#### Validaciones realizadas:

- Proceso completo de reserva
- Flujo de cancelación
- Modales de confirmación
- Dependencia de defectos previos
- Uso correcto del estado BLOCKED cuando fue necesario

---

## 🐞 Reporte de Bugs

Los defectos fueron reportados en Jira incluyendo:

- Pasos claros de reproducción
- Resultado Esperado vs Resultado Actual
- Especificación del entorno
- Identificación correcta de severidad

### Bugs críticos identificados:

- Orientación incorrecta del vehículo en el mapa
- Problemas de renderizado del mapa
- Inconsistencias en validaciones de pago
- Estados incorrectos del botón

---

## 🛠 Herramientas Utilizadas

- Excel – Documentación y seguimiento de ejecución
- Jira – Reporte y gestión de defectos
- Browser DevTools – Inspección de UI
- Testing cross-browser (Chrome y Firefox)

---

## 💪 Habilidades de QA Demostradas

- Testing de aplicaciones web
- Validación cross-browser
- Testing funcional
- Validación de interfaz de usuario
- Gestión del ciclo de vida de defectos
- Testing de valores límite
