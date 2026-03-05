En este archivo debes **listar los problemas encontrados** en el formulario.

Se recomienda clasificar los hallazgos usando las siguientes categorías:

### Categorías sugeridas

**UX (Experiencia de usuario)**  
- claridad del flujo  
- botones confusos  
- acciones poco claras  

**Accesibilidad**  
- falta de labels  
- bajo contraste  
- problemas de navegación  

**Validación**  
- campos sin validación  
- tipos incorrectos  
- campos que deberían ser `required`  

**Jerarquía visual / Layout**  
- orden incorrecto  
- agrupación deficiente  
- mala organización de campos  

**Responsive**  
- problemas en pantalla móvil  
- layout que se rompe  
- elementos demasiado grandes o pequeños  

**Contenido**  
- textos confusos  
- requisitos absurdos  
- instrucciones poco claras  

---

# 📊 Formato recomendado

Puedes usar una tabla como esta:

| # | Problema detectado | Categoría | Evidencia | ¿Por qué es un problema? |
|---|---|---|---|---|
| 1 | El campo nombre no tiene label | Accesibilidad | Campo “Nombre” | Los lectores de pantalla no pueden interpretarlo correctamente |
| 2 | Botón cancelar junto al enviar | UX | Botones al final | Puede provocar errores al usuario |
| 3 | Confirmar correo es opcional | Validación | Campo email | Puede causar inconsistencias |

Se recomienda identificar **al menos 10 problemas**.

---

# 📸 Evidencia visual

Además del archivo `AUDITORIA.md`, debes agregar **capturas de pantalla** del formulario.

Incluye al menos:

### 1️⃣ Vista en escritorio
Ventana normal del navegador.

### 2️⃣ Vista en móvil
Ventana reducida o modo responsive del navegador.

Puedes nombrarlas por ejemplo:
captura-escritorio.png
captura-movil.png

---
# 🚫 Regla importante

❌ **No debes modificar el HTML o CSS del formulario.**  

Esta actividad es únicamente de **análisis y auditoría**.
---

# 📦 Entrega

Realiza un **commit en tu repositorio** que incluya:

AUDITORIA.md
captura-escritorio.png
captura-movil.png


Mensaje de commit sugerido:
Auditoría UX del formulario: identificación de problemas de diseño


---

# 💡 Consejo

Piensa como un **usuario real** que intenta completar el formulario.

Si algo te confunde, probablemente **también confundirá a otros usuarios**.
