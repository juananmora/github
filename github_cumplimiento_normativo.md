# Residencia de datos y cumplimiento normativo en GitHub Enterprise

## GitHub Enterprise Cloud con residencia de datos

GitHub Enterprise Cloud ofrece una característica de residencia de datos que permite a las empresas elegir dónde se almacenan sus datos y código. Esta característica es especialmente relevante para empresas españolas que deben cumplir con normativas europeas como el GDPR.

### Regiones disponibles para residencia de datos
- La Unión Europea (UE)
- Australia

GitHub planea ofrecer residencia de datos en más regiones en el futuro.

### Ventajas de la residencia de datos en la UE
- Permite a las organizaciones cumplir con regulaciones locales como el Reglamento General de Protección de Datos (GDPR)
- Los datos y el código se almacenan en la UE, no en EE.UU.
- La empresa se aloja en un subdominio dedicado de GHE.com
- Mayor control sobre los datos sin necesidad de alojar su propia plataforma

### Características de seguridad y cumplimiento
- Gestión de autenticación y ciclo de vida de usuarios desde un sistema externo de gestión de identidades
- SCIM para aprovisionamiento
- SAML o OIDC para autenticación
- Usuarios gestionados que solo pueden interactuar con recursos de la empresa
- Aislamiento de la comunidad más amplia de GitHub.com
- Centralización de facturación, administración, gobernanza y auditoría

## GitHub Enterprise Server y cumplimiento normativo

GitHub Enterprise Server ofrece ventajas específicas para el cumplimiento normativo:

- Control total de la infraestructura: se ejecuta en la infraestructura propia de la empresa
- Firewalls y políticas de red personalizadas
- Integración con sistemas existentes de gestión de identidad y acceso
- Restricción de acceso a través de VPN corporativa
- Adecuado para empresas sujetas a requisitos específicos de cumplimiento normativo
- Aislamiento completo de datos: los datos permanecen dentro de la infraestructura de la empresa

## Consideraciones para empresas españolas

Para empresas españolas que deben cumplir con el GDPR y otras normativas europeas:

1. **GitHub Enterprise Cloud con residencia de datos en la UE**:
   - Permite cumplir con GDPR manteniendo los datos en la UE
   - Ofrece las últimas características de GitHub.com, como GitHub Copilot
   - No requiere programar tiempo de inactividad para mantenimiento o actualizaciones
   - Experiencia administrativa simplificada

2. **GitHub Enterprise Server**:
   - Ofrece el máximo control sobre los datos y la infraestructura
   - Puede implementarse en centros de datos dentro de España
   - Permite políticas de seguridad más estrictas y personalizadas
   - Requiere más recursos para mantenimiento y actualizaciones

La elección entre ambas opciones dependerá de los requisitos específicos de cumplimiento normativo de la empresa española, sus recursos de TI disponibles y sus necesidades de control de datos.
