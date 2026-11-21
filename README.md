# Laboratorio de Active Directory | Windows Server 2022 y Windows 11

## Descripción del proyecto

Laboratorio académico colaborativo desarrollado durante el Módulo 3 del Técnico en Ciberseguridad de la Universidad Latina de Costa Rica.

El objetivo fue implementar un entorno de administración centralizada de identidades mediante Active Directory Domain Services (AD DS), utilizando Windows Server 2022 como controlador de dominio y Windows 11 como equipo cliente.

## Objetivos

- Instalar y configurar Windows Server 2022.
- Implementar Active Directory Domain Services (AD DS) y DNS.
- Promover el servidor a controlador de dominio.
- Configurar Windows 11 para integrarlo al dominio.
- Crear usuarios y unidades organizativas (OU).
- Configurar y vincular una política de grupo (GPO).
- Documentar resultados y dificultades técnicas.

## Tecnologías utilizadas

- Windows Server 2022
- Windows 11
- Active Directory Domain Services (AD DS)
- DNS
- Group Policy Management (GPO)
- Oracle VirtualBox

## Desarrollo del laboratorio

### 1. Preparación del entorno

Se prepararon las máquinas virtuales y se instaló Windows Server 2022 con experiencia de escritorio. Se configuró la conectividad IPv4 necesaria para la comunicación entre el servidor y el cliente.

### 2. Instalación de Active Directory y DNS

Se instaló el rol AD DS y se promovió Windows Server 2022 a controlador de dominio de un bosque nuevo. Se configuró DNS para permitir que los equipos localizaran los servicios del dominio.

### 3. Integración de Windows 11 al dominio

Se configuró el DNS del equipo cliente para apuntar al servidor, se comprobó la resolución del dominio y se realizó la unión de Windows 11.

También se verificó el registro del equipo en Active Directory mediante la consola de administración de usuarios y equipos.

### 4. Administración de usuarios y OU

Se creó la unidad organizativa Usuarios_corporativos y se configuró una cuenta de usuario de dominio, incluyendo el cambio de contraseña inicial.

### 5. Configuración de políticas de grupo (GPO)

Se configuró y vinculó una GPO destinada a establecer un fondo de pantalla corporativo mediante un recurso compartido y una ruta UNC.

**Resultado documentado:** aunque se realizaron los pasos de configuración, el informe final registró que el fondo corporativo no se visualizó correctamente en el cliente Windows 11. Por tanto, no se considera una aplicación exitosa de la política.

## Dificultades encontradas

- Limitaciones de memoria RAM al ejecutar simultáneamente las máquinas virtuales.
- Necesidad de configurar correctamente DNS para la integración del cliente.
- Problemas con la visualización del fondo corporativo configurado mediante GPO.

## Aprendizajes

- Importancia de DNS para localizar controladores de dominio.
- Administración centralizada de usuarios y equipos.
- Organización de objetos mediante unidades organizativas.
- Funcionamiento y alcance de las políticas de grupo.
- Importancia de verificar los resultados y documentar los errores.

## Evidencias

Se incorporarán capturas seleccionadas del informe académico, correspondientes a la instalación del servidor, AD DS, DNS, unión al dominio, usuarios y GPO.

## Alcance y autoría

Proyecto académico realizado en colaboración con una compañera, con autorización del docente debido a limitaciones de recursos del equipo utilizado.

La documentación refleja una práctica de aprendizaje y no experiencia profesional administrando infraestructura empresarial.
