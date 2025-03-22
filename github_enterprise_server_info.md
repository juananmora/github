# GitHub Enterprise Server

## Características principales

GitHub Enterprise Server es una versión autohospedada de la plataforma GitHub. Su empresa puede beneficiarse de un mayor control y evitar problemas asociados con la nube pública, mientras que sus desarrolladores pueden beneficiarse de las características y flujos de trabajo familiares de GitHub.com.

GitHub Enterprise Server es adecuado para empresas que están sujetas a cumplimiento normativo. Se ejecuta en su infraestructura y se rige por los controles de acceso y seguridad que usted defina, como firewalls, políticas de red, IAM, monitoreo y VPNs.

## Implementación

GitHub Enterprise Server se distribuye como un dispositivo virtual autónomo. Después de aprovisionar una máquina virtual e instalar el dispositivo, la instancia ejecuta un sistema operativo Linux con una pila de aplicaciones personalizada.

Puede implementar GitHub Enterprise Server en:

### Hipervisores locales compatibles
- Microsoft Hyper-V
- OpenStack KVM
- VMware ESXi

### Servicios en la nube compatibles
- Amazon Web Services (AWS)
- Google Cloud Platform (GCP)
- Microsoft Azure

## Características opcionales

Puede configurar características opcionales en GitHub Enterprise Server para mejorar el ciclo de vida de desarrollo de software para su empresa:

- **GitHub Actions:** Automatice CI/CD y flujos de trabajo de desarrollo
- **GitHub Advanced Security:** Escanee código en busca de secretos y vulnerabilidades
- **GitHub Connect:** Benefíciese de datos y características en GitHub.com
- **GitHub Packages:** Aloje paquetes de software para su empresa

## Opciones administrativas

Los administradores pueden:
- Configurar y monitorear la instancia a través del navegador, acceso SSH administrativo y APIs REST o GraphQL
- Configurar autenticación externa usando CAS, LDAP o SAML
- Establecer políticas de uso para garantizar el cumplimiento de las reglas comerciales o restricciones regulatorias

## Copias de seguridad y disponibilidad

GitHub Enterprise Server proporciona opciones para protegerse contra la pérdida de datos o interrupciones del servicio:

- Para hacer copias de seguridad de la configuración y los datos de usuario, puede tomar instantáneas regulares de su instancia utilizando el sistema Backup Utilities.
- Para aumentar la fiabilidad, puede configurar una instancia de réplica pasiva para conmutar por error en caso de falla del sistema o de la red.
- Para mejorar el rendimiento, puede configurar réplicas activas para escalar la instancia para usuarios dispersos o alta demanda.

## Prueba gratuita

Puede registrarse para una prueba gratuita de 45 días de GitHub Enterprise Server.
