# Tabla Comparativa: GitHub Enterprise Cloud vs GitHub Enterprise Server

## Características Generales

| Característica | GitHub Enterprise Cloud | GitHub Enterprise Server |
|----------------|-------------------------|--------------------------|
| **Modelo de despliegue** | Alojado en la nube por GitHub | Autohospedado en infraestructura propia |
| **Actualizaciones** | Automáticas, siempre con las últimas funcionalidades | Manuales, según ciclo de lanzamientos |
| **Mantenimiento** | Gestionado por GitHub | Responsabilidad de la empresa |
| **Tiempo de inactividad** | No requiere programar tiempo de inactividad | Requiere planificación para actualizaciones |
| **Acceso a nuevas funcionalidades** | Inmediato | Después de actualizar a nuevas versiones |
| **Escalabilidad** | Gestionada automáticamente | Requiere planificación de recursos |
| **Integración con GitHub.com** | Nativa a través de GitHub Connect | A través de GitHub Connect |
| **Licenciamiento** | Suscripción por usuario | Licencia por usuario |
| **Prueba gratuita** | 30 días | 45 días |

## Características de Seguridad

| Característica de Seguridad | GitHub Enterprise Cloud | GitHub Enterprise Server |
|----------------------------|-------------------------|--------------------------|
| **Control de infraestructura** | Limitado (gestionado por GitHub) | Total (infraestructura propia) |
| **Autenticación SAML** | Sí | Sí |
| **Autenticación LDAP** | No | Sí |
| **Autenticación CAS** | No | Sí |
| **Políticas de red** | Limitadas a las opciones disponibles | Totalmente personalizables |
| **Firewalls** | Gestionados por GitHub | Configurables según necesidades |
| **GitHub Advanced Security** | Disponible como complemento | Disponible como complemento |
| **Análisis de código** | Sí | Sí |
| **Escaneo de secretos** | Sí | Sí |
| **Alertas de Dependabot** | Sí | Sí |
| **Actualizaciones de seguridad de Dependabot** | Sí | Sí |
| **Gráfico de dependencias** | Sí | Sí |
| **Revisión de dependencias** | Sí | Sí |
| **IP whitelisting** | Sí | Sí |
| **Autenticación de dos factores** | Sí | Sí |
| **Reglas de protección de ramas** | Sí | Sí |
| **Auditoría de logs** | Sí | Sí |
| **Control de acceso basado en roles** | Sí | Sí |

## Cumplimiento Normativo y Residencia de Datos

| Aspecto | GitHub Enterprise Cloud | GitHub Enterprise Server |
|---------|-------------------------|--------------------------|
| **Residencia de datos** | Opción de UE o Australia | Donde se implemente la infraestructura |
| **Cumplimiento GDPR** | Sí, con opción de residencia en UE | Sí, si se implementa en la UE |
| **Control sobre transferencias internacionales** | Limitado a las opciones disponibles | Total |
| **Responsabilidad del tratamiento** | Compartida (GitHub como encargado) | Total (empresa como responsable y encargada) |
| **Auditorías de cumplimiento** | Informes proporcionados por GitHub | Personalizables según necesidades |
| **Aislamiento de datos** | Subdominio dedicado en GHE.com | Total en infraestructura aislada |
| **Evaluación de impacto (EIPD)** | Puede ser necesaria | Puede ser necesaria |

## Opciones de Implementación

| Opción | GitHub Enterprise Cloud | GitHub Enterprise Server |
|--------|-------------------------|--------------------------|
| **Hipervisores locales** | No aplicable | Microsoft Hyper-V, OpenStack KVM, VMware ESXi |
| **Servicios en la nube** | GitHub.com | AWS, GCP, Azure |
| **Réplicas activas** | No aplicable | Sí, para escalar y mejorar rendimiento |
| **Réplicas pasivas** | No aplicable | Sí, para alta disponibilidad |
| **Copias de seguridad** | Gestionadas por GitHub | Sistema Backup Utilities |

## Costos y Soporte

| Aspecto | GitHub Enterprise Cloud | GitHub Enterprise Server |
|---------|-------------------------|--------------------------|
| **Modelo de costos** | Suscripción por usuario | Licencia por usuario + costos de infraestructura |
| **Costos de infraestructura** | Incluidos | Adicionales (servidores, mantenimiento) |
| **Soporte técnico** | 24/7 con opciones premium | 24/7 con opciones premium |
| **Gestión de cuenta** | Gerente de cuenta dedicado | Gerente de cuenta dedicado |
| **Comunidad de soporte** | Sí | Sí |
