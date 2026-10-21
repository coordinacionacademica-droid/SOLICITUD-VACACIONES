# Generador de Solicitud de Vacaciones Corporativas (Perú RRHH)

Aplicación web Split-Screen de alta fidelidad para la generación, redacción automática y exportación en formato A4 formal de solicitudes de vacaciones laborales corporativas en el Perú.

## Características Principales
- **Diseño Split-Screen:** Panel de configuración interactivo a la izquierda y hoja carta/A4 en tiempo real (*live preview*) a la derecha.
- **Redacción Dinámica Automática:**
  - **Un solo día:** Adapta la redacción a *"Solicito a cuenta de vacaciones en el mes de [mes] el [DD/MM/AAAA]..."*
  - **Rango de fechas:** Modifica la redacción a *"Solicito a cuenta de vacaciones en el mes de [mes] del [DD/MM/AAAA] al [DD/MM/AAAA]..."*
- **Alineación con el Formato Corporativo Peruano:**
  - Lema oficial del año configurable en encabezado.
  - Lugar y fecha de emisión.
  - Destinatario formal con cargo.
  - Asunto oficial destacado.
  - Párrafo de identidad con concordancia gramatical (Masculino / Femenino).
  - Bloque de firma centrado con línea y DNI.
- **Exportación Limpia a PDF:** Reglas `@media print` estrictas que aíslan la hoja del documento, ocultando botones y barras de herramientas.
- **Despliegue Instantáneo en Vercel:** Archivo `index.html` 100% estático y autocontenido (HTML5 + Tailwind CSS CDN + JavaScript nativo).

## Despliegue en Vercel
Simplemente conecta este repositorio a Vercel o utiliza el CLI de Vercel:
```bash
vercel --prod
```
No requiere pasos de compilación (`Build Command: None`, `Output Directory: None`).
