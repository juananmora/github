# Requisitos de cumplimiento normativo para empresas españolas

## Normativa de protección de datos en España

La normativa de protección de datos en España se rige principalmente por:

1. **Reglamento General de Protección de Datos (RGPD/GDPR)** - Normativa europea aplicable desde mayo de 2018
2. **Ley Orgánica 3/2018 de Protección de Datos Personales y garantía de los derechos digitales (LOPDGDD)** - Adaptación española del RGPD

## Obligaciones principales para empresas españolas

Las empresas españolas que tratan datos personales deben cumplir con las siguientes obligaciones:

- Aplicar los principios de protección de datos desde el diseño y por defecto
- Mantener un registro de actividades de tratamiento
- Realizar evaluaciones de impacto para tratamientos de alto riesgo
- Implementar medidas de seguridad técnicas y organizativas adecuadas
- Notificar brechas de seguridad a la autoridad de control (AEPD)
- Designar un Delegado de Protección de Datos (DPD) en casos específicos
- Garantizar los derechos de los interesados (acceso, rectificación, supresión, etc.)
- Obtener consentimiento explícito para el tratamiento de datos cuando sea necesario

## Implicaciones para la elección entre GitHub Enterprise Cloud y Server

### Consideraciones para GitHub Enterprise Cloud

- **Residencia de datos en la UE**: GitHub Enterprise Cloud ofrece la opción de residencia de datos en la UE, lo que facilita el cumplimiento del RGPD para empresas españolas.
- **Transferencias internacionales**: Al elegir la residencia de datos en la UE, se evitan las transferencias internacionales de datos a EE.UU., simplificando el cumplimiento normativo tras la invalidación del Privacy Shield.
- **Responsabilidad compartida**: GitHub actúa como encargado del tratamiento, mientras que la empresa española sigue siendo responsable del tratamiento.
- **Medidas de seguridad**: GitHub implementa medidas de seguridad avanzadas, pero la empresa debe verificar que sean adecuadas según el RGPD.

### Consideraciones para GitHub Enterprise Server

- **Control total de los datos**: Al alojar la plataforma en infraestructura propia dentro de España o la UE, se garantiza que los datos no salen del territorio europeo.
- **Responsabilidad completa**: La empresa es totalmente responsable de implementar las medidas de seguridad adecuadas.
- **Evaluación de impacto**: Puede ser necesario realizar una evaluación de impacto relativa a la protección de datos (EIPD) para el despliegue.
- **Auditorías**: Mayor facilidad para realizar auditorías de cumplimiento al tener control total sobre la infraestructura.

## Recomendaciones para empresas españolas

1. **Para empresas con recursos limitados de TI y requisitos estándar de cumplimiento**:
   - GitHub Enterprise Cloud con residencia de datos en la UE puede ser suficiente, siempre que se documenten adecuadamente las medidas de seguridad implementadas por GitHub.

2. **Para empresas con requisitos estrictos de cumplimiento o en sectores altamente regulados**:
   - GitHub Enterprise Server alojado en infraestructura propia dentro de España o la UE proporciona el máximo control y facilita el cumplimiento de requisitos más estrictos.

3. **Documentación necesaria en ambos casos**:
   - Incluir el tratamiento en el registro de actividades
   - Actualizar la política de privacidad
   - Documentar las medidas de seguridad implementadas
   - Realizar una evaluación de impacto si es necesario
   - Establecer un procedimiento para gestionar los derechos de los interesados

La elección final dependerá del análisis de riesgos específico de cada organización, sus recursos disponibles y los requisitos particulares de su sector.
