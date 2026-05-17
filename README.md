# Proyecto: Pruebas Web de Rutas Urbanas (Urban Routes)

## 📝 Descripción del Problema
Urban Routes es una aplicación web de transporte y movilidad orientada a optimizar la reserva de taxis y rutas urbanas. El objetivo principal de este proyecto fue diseñar y ejecutar una estrategia integral de pruebas (QA) tanto manuales como automatizadas para validar la estabilidad de la plataforma, la usabilidad de la interfaz en flujos críticos (como la configuración del conductor y tarifas) y garantizar un despliegue libre de errores críticos para el negocio.

## 🛠️ Tecnologías y Herramientas Utilizadas
- **Gestión de Pruebas:** Checklists detallados, Matrices de Casos de Prueba.
- **Seguimiento de Errores (Bug Tracking):** Jira Software (Metodología Ágil/Scrum).
- **Pruebas de API / Entorno Técnico:** Postman (Pruebas de endpoints básicos).
- **Automatización:** Selenium WebDriver (Scripts para verificación de flujos repetitivos).
- **Entornos:** Google Chrome, Mozilla Firefox y DevTools para análisis de elementos web.

## 📊 Alcance de las Pruebas y Qué se Probó
1. **Flujo Principal de Reserva:** Selección de origen/destino, cálculo de tarifas según el tipo de servicio y métodos de pago.
2. **Interfaz de Usuario (UI/UX):** Validación de campos obligatorios, restricciones de caracteres y responsividad.
3. **Casos Límite y Negativos:** Comportamiento del sistema ante entradas inválidas o interrupciones en el flujo de reserva.

## 🐛 Resultados y Reporte de Bugs encontrados
Durante el ciclo de pruebas se identificaron y documentaron errores críticos utilizando Jira, priorizando según el impacto en el negocio:
- **Bug Crítico - Bloqueo de Tarifa:** Se detectó que bajo ciertas combinaciones de ruta el botón de "Reservar" se inhabilitaba de forma intermitente sin mostrar errores al usuario. *(Estado: Reportado y Documentado en Jira)*.
- **Bug Menor - Interfaz:** Desalineación de elementos gráficos en resoluciones móviles específicas dentro del formulario de datos del conductor.

## 🚀 Cómo Ejecutar u Observar el Proyecto
1. **Documentación de Pruebas:** Puedes revisar la matriz de casos de prueba y reportes simulados dentro de la carpeta `/docs` *(Nota: Si tienes un PDF o Excel de tus tablas, puedes subirlo a una carpeta dentro de este repositorio)*.
2. **Pruebas Automatizadas:** Los scripts de automatización se encuentran estructurados en la sección `/src` ejecutables bajo entornos locales de pruebas.

---
*Proyecto desarrollado como parte de mi formación avanzada en Software Testing (QA).*
