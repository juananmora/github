# Comparativa Detallada: GitHub Enterprise Cloud vs GitHub Enterprise Server

## Introducción

Este documento presenta una comparativa exhaustiva entre GitHub Enterprise Cloud y GitHub Enterprise Server, analizando en detalle todas sus capacidades, ventajas y consideraciones para ayudar a las organizaciones españolas a tomar una decisión informada sobre cuál de estas soluciones se adapta mejor a sus necesidades específicas.

## Modelo de Despliegue

### GitHub Enterprise Cloud
- **Tipo de servicio**: SaaS (Software as a Service)
- **Alojamiento**: Completamente gestionado por GitHub/Microsoft
- **Infraestructura**: No requiere infraestructura propia
- **Mantenimiento**: Gestionado por GitHub, sin necesidad de mantenimiento por parte del cliente
- **Actualizaciones**: Automáticas, siempre con la última versión disponible
- **Residencia de datos**: Opción de elegir región específica para almacenamiento de datos (importante para cumplimiento RGPD)

### GitHub Enterprise Server
- **Tipo de servicio**: On-premises o IaaS (Infrastructure as a Service)
- **Alojamiento**: Autogestionado en infraestructura propia o en la nube pública
- **Infraestructura**: Requiere aprovisionamiento y gestión de servidores
- **Mantenimiento**: Responsabilidad del cliente
- **Actualizaciones**: Manuales, programadas por el equipo de TI
- **Residencia de datos**: Total control sobre la ubicación de los datos

## Acceso y Autenticación

### GitHub Enterprise Cloud
- **Cuentas de usuario**: Dos opciones:
  - Cuentas personales de GitHub.com
  - Enterprise Managed Users (cuentas aprovisionadas desde sistema externo)
- **Autenticación**: 
  - SAML SSO
  - SCIM para aprovisionamiento automático
  - Autenticación de dos factores
  - Soporte para proveedores de identidad externos

### GitHub Enterprise Server
- **Cuentas de usuario**: Gestionadas localmente en la instancia
- **Autenticación**:
  - Autenticación integrada
  - LDAP
  - SAML
  - CAS
  - Integración con Active Directory
  - Autenticación de dos factores

## Características de Colaboración

### GitHub Enterprise Cloud
- **Repositorios**: Públicos, privados e internos
- **Pull Requests**: Completo soporte con revisiones de código
- **Issues**: Sistema completo de seguimiento de problemas
- **Proyectos**: Tableros Kanban para gestión de proyectos
- **Discusiones**: Foros de discusión para equipos
- **Wikis**: Documentación colaborativa
- **GitHub Pages**: Sitios web estáticos (opción de publicación privada)
- **Codespaces**: Entornos de desarrollo basados en la nube
- **Copilot**: Asistente de codificación basado en IA (requiere suscripción adicional)

### GitHub Enterprise Server
- **Repositorios**: Públicos, privados e internos
- **Pull Requests**: Completo soporte con revisiones de código
- **Issues**: Sistema completo de seguimiento de problemas
- **Proyectos**: Tableros Kanban para gestión de proyectos
- **Discusiones**: Foros de discusión para equipos
- **Wikis**: Documentación colaborativa
- **GitHub Pages**: Sitios web estáticos
- **Codespaces**: No disponible directamente (requiere GitHub Connect)
- **Copilot**: No disponible directamente (requiere GitHub Connect)

## CI/CD y Automatización

### GitHub Enterprise Cloud
- **GitHub Actions**: Incluido con minutos adicionales
  - Runners hospedados por GitHub
  - Soporte para runners autohospedados
  - Acceso a GitHub Marketplace para acciones
- **GitHub Packages**: Registro de paquetes integrado
- **Webhooks**: Integración con sistemas externos
- **API**: Acceso completo a REST y GraphQL APIs

### GitHub Enterprise Server
- **GitHub Actions**: Disponible como característica opcional
  - Requiere configuración de runners autohospedados
  - Acceso limitado a GitHub Marketplace (requiere GitHub Connect)
- **GitHub Packages**: Disponible como característica opcional
- **Webhooks**: Integración con sistemas internos y externos
- **API**: Acceso completo a REST y GraphQL APIs

## Seguridad y Cumplimiento

### GitHub Enterprise Cloud
- **Advanced Security**: Disponible como complemento
  - Análisis de código (CodeQL)
  - Escaneo de secretos
  - Revisión de dependencias
- **Dependabot**: 
  - Alertas de seguridad
  - Actualizaciones de seguridad automáticas
  - Actualizaciones de versión
- **Políticas de seguridad**: 
  - A nivel de organización y empresa
  - Reglas de protección de ramas
  - Conjuntos de reglas de repositorio
- **Auditoría**: 
  - Registros de auditoría detallados
  - Exportación de registros
  - Integraciones con SIEM
- **Cumplimiento**: 
  - Informes de cumplimiento de GitHub
  - Certificaciones (SOC 1/2, ISO 27001, FedRAMP, etc.)
  - Residencia de datos para cumplimiento regional

### GitHub Enterprise Server
- **Advanced Security**: Disponible como complemento
  - Análisis de código (CodeQL)
  - Escaneo de secretos
  - Revisión de dependencias
- **Dependabot**: 
  - Alertas de seguridad (requiere GitHub Connect)
  - Actualizaciones limitadas sin GitHub Connect
- **Políticas de seguridad**: 
  - A nivel de organización y empresa
  - Reglas de protección de ramas
  - Conjuntos de reglas de repositorio
- **Auditoría**: 
  - Registros de auditoría detallados
  - Control total sobre los registros
  - Integración con sistemas de monitorización internos
- **Cumplimiento**: 
  - Control total para adaptarse a requisitos específicos
  - Posibilidad de implementar en entornos air-gapped
  - Adaptable a requisitos regulatorios específicos

## Disponibilidad y Recuperación ante Desastres

### GitHub Enterprise Cloud
- **SLA**: 99.9% de tiempo de actividad
- **Respaldos**: Gestionados por GitHub
- **Recuperación**: Gestionada por GitHub
- **Escalabilidad**: Automática según necesidades

### GitHub Enterprise Server
- **SLA**: Depende de la implementación y configuración
- **Respaldos**: 
  - Sistema de Utilidades de Backup
  - Responsabilidad del cliente
- **Recuperación**: 
  - Réplicas pasivas para conmutación por error
  - Procedimientos definidos por el cliente
- **Escalabilidad**: 
  - Réplicas activas para usuarios dispersos
  - Requiere planificación y configuración manual

## Integración con Sistemas Externos

### GitHub Enterprise Cloud
- **Integraciones**: 
  - Amplio catálogo de integraciones en GitHub Marketplace
  - APIs para desarrollo de integraciones personalizadas
  - Webhooks para eventos
- **GitHub Apps**: Soporte completo
- **OAuth Apps**: Soporte completo

### GitHub Enterprise Server
- **Integraciones**: 
  - Integraciones con sistemas internos
  - Acceso limitado a GitHub Marketplace (requiere GitHub Connect)
  - APIs para desarrollo de integraciones personalizadas
  - Webhooks para eventos
- **GitHub Apps**: Soporte completo
- **OAuth Apps**: Soporte completo

## Administración y Gestión

### GitHub Enterprise Cloud
- **Gestión de usuarios**: 
  - A través de la cuenta empresarial
  - Integración con proveedores de identidad
  - SCIM para aprovisionamiento automático
- **Políticas**: 
  - Aplicación a nivel de empresa
  - Herencia a organizaciones
- **Facturación**: 
  - Centralizada a nivel de empresa
  - Basada en usuarios y complementos

### GitHub Enterprise Server
- **Gestión de usuarios**: 
  - Administración local
  - Integración con sistemas de directorio
- **Políticas**: 
  - Control total sobre políticas
  - Aplicación a nivel de instancia
- **Licencias**: 
  - Basadas en usuarios
  - Gestión local de licencias

## Rendimiento y Escalabilidad

### GitHub Enterprise Cloud
- **Rendimiento**: Optimizado y gestionado por GitHub
- **Escalabilidad**: Automática sin límites prácticos
- **Límites**: 
  - Muy altos para repositorios y tamaño de archivos
  - Cuotas ajustables para Actions y Packages

### GitHub Enterprise Server
- **Rendimiento**: Dependiente del hardware aprovisionado
- **Escalabilidad**: 
  - Limitada por recursos de hardware
  - Requiere planificación de capacidad
- **Límites**: 
  - Determinados por la infraestructura
  - Ajustables según necesidades

## Costos y Licenciamiento

### GitHub Enterprise Cloud
- **Modelo**: Suscripción anual
- **Base de cálculo**: Por usuario
- **Complementos**: 
  - GitHub Advanced Security
  - Copilot Enterprise
  - Premium Support
- **Costos operativos**: Mínimos (no requiere infraestructura)
- **Previsibilidad**: Alta, basada en número de usuarios

### GitHub Enterprise Server
- **Modelo**: Licencia anual
- **Base de cálculo**: Por usuario
- **Complementos**: 
  - GitHub Advanced Security
  - Premium Support
- **Costos operativos**: 
  - Infraestructura (servidores, almacenamiento, red)
  - Personal para administración y mantenimiento
  - Costos de actualización
- **Previsibilidad**: Media, depende de costos de infraestructura y operación

## Consideraciones para Empresas Españolas

### GitHub Enterprise Cloud
- **RGPD**: 
  - Opción de residencia de datos en UE
  - Cumplimiento de requisitos de transferencia internacional
- **ENS**: Compatible con requisitos del Esquema Nacional de Seguridad
- **Soporte**: Disponible en español
- **Documentación**: Disponible en español

### GitHub Enterprise Server
- **RGPD**: 
  - Control total sobre los datos
  - Sin transferencia internacional si se aloja en España/UE
- **ENS**: 
  - Adaptable a cualquier nivel de ENS requerido
  - Mayor control para implementar medidas específicas
- **Soporte**: Disponible en español
- **Documentación**: Disponible en español

## Casos de Uso Recomendados

### GitHub Enterprise Cloud es ideal para:
- Organizaciones que prefieren soluciones SaaS sin gestión de infraestructura
- Empresas con equipos distribuidos geográficamente
- Organizaciones que requieren las últimas características sin demora
- Empresas con requisitos de cumplimiento que pueden satisfacerse con residencia de datos en UE
- Startups y empresas en crecimiento que valoran la escalabilidad automática

### GitHub Enterprise Server es ideal para:
- Organizaciones con requisitos estrictos de soberanía de datos
- Entornos altamente regulados con necesidades específicas de cumplimiento
- Sectores con restricciones de conectividad a internet (financiero, defensa, administración pública)
- Empresas con infraestructura existente que pueden aprovechar
- Organizaciones que requieren personalización profunda del entorno

## Tabla Comparativa de Características

| Característica | GitHub Enterprise Cloud | GitHub Enterprise Server |
|----------------|-------------------------|--------------------------|
| **Modelo de despliegue** | SaaS | On-premises o IaaS |
| **Mantenimiento** | Gestionado por GitHub | Responsabilidad del cliente |
| **Actualizaciones** | Automáticas | Manuales |
| **Autenticación** | SAML, SCIM | LDAP, SAML, CAS |
| **Repositorios** | Públicos, privados, internos | Públicos, privados, internos |
| **GitHub Actions** | Incluido con minutos adicionales | Opcional, runners autohospedados |
| **Codespaces** | Disponible | Requiere GitHub Connect |
| **Copilot** | Disponible (suscripción adicional) | Requiere GitHub Connect |
| **Advanced Security** | Disponible (complemento) | Disponible (complemento) |
| **Dependabot** | Completo | Limitado sin GitHub Connect |
| **Residencia de datos** | Opción de región específica | Control total |
| **SLA** | 99.9% | Depende de la implementación |
| **Escalabilidad** | Automática | Manual |
| **Costos operativos** | Bajos | Medios-Altos |
| **Cumplimiento RGPD** | Con residencia de datos en UE | Control total |

## Conclusión

La elección entre GitHub Enterprise Cloud y GitHub Enterprise Server depende fundamentalmente de los requisitos específicos de la organización en términos de control, cumplimiento normativo, recursos disponibles y preferencias operativas.

GitHub Enterprise Cloud ofrece una solución completamente gestionada con actualizaciones automáticas y acceso inmediato a las últimas características, ideal para organizaciones que prefieren centrarse en el desarrollo de software sin preocuparse por la infraestructura subyacente.

GitHub Enterprise Server proporciona un control máximo sobre los datos y el entorno, siendo la opción preferida para organizaciones con requisitos estrictos de cumplimiento normativo o necesidades específicas de personalización.

Para empresas españolas, ambas opciones pueden cumplir con los requisitos del RGPD, aunque GitHub Enterprise Server ofrece mayor control para entornos altamente regulados o con necesidades específicas de soberanía de datos.

La buena noticia es que al adquirir GitHub Enterprise, se obtiene acceso a ambas opciones de despliegue, lo que permite una estrategia híbrida adaptada a las necesidades específicas de cada parte de la organización.
