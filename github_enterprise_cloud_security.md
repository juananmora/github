# Características de seguridad de GitHub Enterprise Cloud

GitHub ofrece características de seguridad que ayudan a mantener el código y los secretos seguros en los repositorios y en toda la organización. Algunas características están disponibles para repositorios en todos los planes, mientras que otras características adicionales están disponibles para organizaciones y empresas que utilizan GitHub Advanced Security.

## Características disponibles para todos los repositorios

### Política de seguridad
- Facilita a los usuarios informar confidencialmente sobre vulnerabilidades de seguridad encontradas en el repositorio.

### Alertas y actualizaciones de seguridad de Dependabot
- Ver alertas sobre dependencias con vulnerabilidades de seguridad conocidas.
- Opción de generar automáticamente pull requests para actualizar estas dependencias.
- Reglas de auto-clasificación de Dependabot para filtrar automáticamente falsos positivos.

### Actualizaciones de versión de Dependabot
- Genera automáticamente pull requests para mantener las dependencias actualizadas.
- Reduce la exposición a versiones antiguas de dependencias.
- Facilita la aplicación de parches si se descubren vulnerabilidades de seguridad.

### Gráfico de dependencias
- Permite explorar los ecosistemas y paquetes de los que depende el repositorio.
- Muestra los repositorios y paquetes que dependen del repositorio.
- Posibilidad de exportar el gráfico de dependencias como una Lista de Materiales de Software (SBOM) compatible con SPDX.

### Resumen de seguridad
- Permite revisar el panorama general de seguridad de la organización.
- Ver tendencias y otros insights.
- Gestionar configuraciones de seguridad.
- Monitorear el estado de seguridad de la organización.
- Identificar los repositorios y organizaciones con mayor riesgo.

## Características disponibles con GitHub Advanced Security

Las siguientes características están disponibles para organizaciones dentro de una empresa que tiene una licencia de GitHub Advanced Security:

### Análisis de código
- Detecta automáticamente vulnerabilidades de seguridad y errores de codificación en código nuevo o modificado.
- Destaca problemas potenciales con información detallada.
- Permite corregir el código antes de que se fusione con la rama predeterminada.

### Alertas de escaneo de secretos
- Detecta automáticamente tokens o credenciales que se han incluido en un repositorio.
- Muestra alertas para cualquier secreto que GitHub encuentre en el código.
- Ayuda a identificar qué tokens o credenciales deben tratarse como comprometidos.

### Reglas de auto-clasificación personalizadas
- Ayuda a gestionar las alertas de Dependabot a escala.
- Control sobre las alertas que se quieren ignorar, posponer o para las que se quiere activar una actualización de seguridad de Dependabot.

### Revisión de dependencias
- Muestra el impacto completo de los cambios en las dependencias.
- Permite ver detalles de cualquier versión vulnerable antes de fusionar una pull request.

## Características adicionales de seguridad

Con GitHub Enterprise Cloud, también se obtienen características adicionales de seguridad como:

- Autenticación SAML
- Restricción de notificaciones por correo electrónico a dominios verificados
- Opción de alojar los datos de la empresa en una región específica
- Informes de cumplimiento de GitHub
- Conjuntos de reglas de repositorio para aplicar políticas de seguridad
