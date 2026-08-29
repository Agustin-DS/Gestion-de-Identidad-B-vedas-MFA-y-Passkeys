# Práctica de Gestión de Identidad y Cifrado

Este repositorio contiene la documentación técnica, estructura de archivos y evidencias gráficas de la práctica sobre gestión de credenciales y cifrado de datos en reposo.
---
#Propósito de las Herramientas Utilizadas

* **KeePassXC:** Gestor de contraseñas local y de código abierto utilizado para almacenar credenciales de forma centralizada y cifrada sin depender de servidores en la nube.
* **Key File (Archivo Llave):** Mecanismo de seguridad adicional que funciona como un segundo factor de autenticación (MFA local). Es necesario poseer este archivo específico junto con la contraseña maestra para lograr el desbloqueo de la bóveda.
* **VeraCrypt:** Software de cifrado de disco de código abierto empleado para crear un volumen virtual cifrado (contenedor) en el sistema de archivos local, protegiendo los datos en reposo contra accesos no autorizados.

---

## 📁 Estructura del Repositorio

```text
.
├── evidencias/
│   ├── Archivo key funcionando.png
│   ├── Mi Boveda - KeePass.png
│   └── Unidad Z creada.png
├── aprendizajes.txt
└── README.md
