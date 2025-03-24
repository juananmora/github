# Capacidades de GitHub Enterprise Server

## Descripción General

GitHub Enterprise Server es una versión autohospedada de la plataforma GitHub. Es adecuada para empresas que están sujetas a cumplimiento normativo, ya que se ejecuta en la infraestructura propia de la empresa y está gobernada por controles de acceso y seguridad definidos por la organización, como firewalls, políticas de red, IAM, monitorización y VPNs.

## Características Principales

GitHub Enterprise Server se distribuye como un dispositivo virtual autocontenido. Después de aprovisionar una máquina virtual e instalar el dispositivo, la instancia ejecuta un sistema operativo Linux con una pila de aplicaciones personalizada. No se admite la instalación de software de terceros ni la realización de cambios en el sistema operativo subyacente.

### Características Opcionales

GitHub Enterprise Server permite configurar características opcionales para mejorar el ciclo de vida del desarrollo de software:

- **GitHub Actions**: Automatización de CI/CD y flujos de trabajo de desarrollo
- **GitHub Advanced Security**: Escaneo de código para detectar secretos y vulnerabilidades
- **GitHub Connect**: Beneficiarse de datos y características en GitHub.com
- **GitHub Packages**: Alojamiento de paquetes de software para la empresa

## Opciones de Despliegue

GitHub Enterprise Server se puede desplegar en:

### Hipervisores on-premises soportados
- Microsoft Hyper-V
- OpenStack KVM
- VMware ESXi

### Servicios en la nube soportados
- Amazon Web Services (AWS)
- Google Cloud Platform (GCP)
- Microsoft Azure

## Opciones Administrativas

Los administradores pueden:

- Configurar y monitorizar la instancia a través del navegador, acceso SSH administrativo, y APIs REST o GraphQL
- Configurar autenticación externa usando CAS, LDAP o SAML
- Establecer políticas de uso para garantizar el cumplimiento de reglas de negocio o restricciones regulatorias

## Copias de Seguridad y Disponibilidad

GitHub Enterprise Server proporciona opciones para protegerse contra la pérdida de datos o interrupciones del servicio:

- Para respaldar la configuración y los datos de usuario, se pueden tomar instantáneas regulares de la instancia utilizando el sistema de Utilidades de Backup
- Para aumentar la fiabilidad, se puede configurar una instancia de réplica pasiva para conmutación por error en caso de fallo del sistema o de la red
- Para mejorar el rendimiento, se pueden configurar réplicas activas para escalar la instancia para usuarios dispersos o alta demanda

## Ventajas para Empresas con Requisitos de Cumplimiento

GitHub Enterprise Server es especialmente adecuado para empresas con requisitos estrictos de cumplimiento normativo:

- Control total sobre la infraestructura y los datos
- Capacidad para implementar políticas de seguridad específicas
- Posibilidad de mantener todos los datos dentro de la red corporativa
- Cumplimiento de requisitos regulatorios específicos de la industria o región

## Integración con Sistemas Existentes

GitHub Enterprise Server se puede integrar con:

- Sistemas de autenticación empresarial (LDAP, SAML, CAS)
- Herramientas de CI/CD existentes
- Sistemas de monitorización y alertas
- Soluciones de almacenamiento y respaldo corporativas

## Requisitos de Hardware

Los requisitos específicos dependen del tamaño de la organización y el número de usuarios, pero generalmente se necesitan servidores con:

- CPUs virtuales o físicas
- Memoria RAM suficiente
- Almacenamiento SSD para rendimiento óptimo
- Configuración de red adecuada

## Mantenimiento y Actualizaciones

A diferencia de GitHub Enterprise Cloud, con GitHub Enterprise Server:

- Se requiere planificar ventanas de mantenimiento para actualizaciones
- Los administradores son responsables de aplicar parches de seguridad
- Las nuevas características llegan después que a GitHub.com
- Se necesita gestionar la infraestructura subyacente

## Prueba y Adquisición

Se puede registrar para una prueba gratuita de 45 días de GitHub Enterprise Server. Después de la prueba, se requiere adquirir licencias para continuar utilizando el producto.
