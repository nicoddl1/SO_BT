# SO_BT
Material Sistemas operativos BT

Para ejecutar el script desde el server:

# Laboratorio de Auditoría y Remediación en Linux de usuarios y permisos

Este laboratorio simula un escenario real de administración de sistemas en una institución educativa. 
El servidor contiene inconsistencias y fallas de seguridad en la configuración de usuarios, grupos y permisos de archivos que deben ser auditados y remediados.

---

## 💻 Requisitos Previos

* acceso al servidor con usuario administrador

---

## 🚀 Despliegue del Entorno

Abre una terminal en tu servidor Ubuntu y ejecuta el siguiente comando para desplegar el escenario de prueba:

```bash
curl -sSL https://raw.githubusercontent.com/nicoddl1/SO_BT/main/escuela.sh | sudo bash
'''

## ℹ️** Información del Entorno**
Directorio de trabajo   /opt/escuela
Usuarios a auditar:     prof_ana, est_juan, dir_carlos
Grupos a auditar:       profesores, estudiantes, directivos

## 📝 **Consigna de la Tarea**
Auditoría del Sistema: Explora la estructura creada bajo /opt/escuela, los usuarios del sistema y la pertenencia a sus grupos utilizando exclusivamente comandos de terminal.

Identificación de Errores: Localiza los problemas de configuración en permisos de archivos/carpetas y asignación de grupos primarios/secundarios de los tres usuarios.

Análisis de Riesgo: Justifica el impacto que tiene cada falla encontrada respecto a la seguridad y la funcionalidad de la institución.

Remediación: Determina y aplica los comandos exactos de Linux necesarios para corregir cada problema. Te sugiero crear una tabla.

## 📂 **Entregable y Formato del Informe**
Debes entregar un informe que contenga la siguiente estructura estructurada por cada hallazgo detectado:

Elemento Auditado: Nombre del usuario, grupo, directorio o archivo analizado.

Estado Actual Detectado: Descripción detallada del error encontrado con los comandos de auditoría empleados.

Análisis de Riesgo: Explicación técnica del problema de operatividad que genera la falla.

Comando de Remediación: Comando(s) exacto(s) de Linux ejecutados para solucionar la inconsistencia.
