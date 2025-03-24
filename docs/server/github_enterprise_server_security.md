# Características de seguridad de GitHub Enterprise Server

GitHub ofrece características de seguridad que ayudan a mantener el código y los secretos seguros en los repositorios y en toda la organización. Algunas características están disponibles para todos los repositorios, mientras que otras características adicionales están disponibles para organizaciones y empresas que utilizan GitHub Advanced Security.

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

GitHub Advanced Security es una característica opcional que se puede configurar en GitHub Enterprise Server para mejorar la seguridad:

### Análisis de código
- Detecta automáticamente vulnerabilidades de seguridad y errores de codificación en código nuevo o modificado.
- Destaca problemas potenciales con información detallada.
- Permite corregir el código antes de que se fusione con la rama predeterminada.

### Escaneo de secretos
- Detecta automáticamente tokens o credenciales que se han incluido en un repositorio.
- Muestra alertas para cualquier secreto que GitHub encuentre en el código.
- Ayuda a identificar qué tokens o credenciales deben tratarse como comprometidos.

### Reglas de auto-clasificación personalizadas
- Ayuda a gestionar las alertas de Dependabot a escala.
- Control sobre las alertas que se quieren ignorar, posponer o para las que se quiere activar una actualización de seguridad de Dependabot.

### Revisión de dependencias
- Muestra el impacto completo de los cambios en las dependencias.
- Permite ver detalles de cualquier versión vulnerable antes de fusionar una pull request.

## Ventajas de seguridad específicas de GitHub Enterprise Server

- **Control total de la infraestructura**: Se ejecuta en su propia infraestructura y se rige por los controles de acceso y seguridad que usted defina.
- **Firewalls y políticas de red**: Puede implementar políticas de seguridad de red específicas para su organización.
- **IAM y monitoreo**: Integración con sus sistemas de gestión de identidad y acceso existentes.
- **VPNs**: Puede restringir el acceso a través de VPN corporativa.
- **Cumplimiento normativo**: Adecuado para empresas sujetas a requisitos de cumplimiento normativo específicos.
- **Aislamiento de datos**: Los datos permanecen dentro de su infraestructura, lo que puede ser un requisito para ciertos sectores regulados.
