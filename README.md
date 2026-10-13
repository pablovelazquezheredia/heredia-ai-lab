# Heredia AI Lab

Laboratorio experimental de inteligencia artificial de Grupo Heredia.

## Versión 0.1 — Demostración visual

Abre `index.html` en cualquier navegador. No requiere instalación, claves API ni servicios externos.

- Panel interactivo en español
- Datos HORECA totalmente ficticios
- Chat de demostración con respuestas predefinidas (no es un LLM)
- Simulación de configuración de ajuste fino (no entrena modelos)
- Métricas ilustrativas, no medidas

## Tecnología prevista

[S​oup](https://github.com/MakazhanAlpamys/Soup) es un proyecto independiente para fine-tuning. **Todavía no está integrado** en esta versión.

## Aislamiento y seguridad

No existe conexión a ORION, Plataforma 360, ERP, correo ni información real de clientes. No incluir secretos o datos personales en el repositorio. Antes de cargar datos reales se revisarán permisos y protección de datos.

## Próximos hitos

1. Publicar la demostración visual en un entorno controlado.
2. Crear datos sintéticos de entrenamiento y evaluación separados.
3. Instalar Soup en entorno compatible y ejecutar un entrenamiento reproducible.
4. Comparar el modelo base y el ajustado con métricas reales.
