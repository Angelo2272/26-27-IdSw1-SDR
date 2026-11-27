<div align=right>

|[![](https://img.shields.io/badge/-Inicio-24292e?style=flat&logo=Emlakjet&logoColor=white)](/README.md) [![](https://img.shields.io/badge/-RUP-24292e?style=flat&logo=Elsevier&logoColor=white)](/RUP/README.md) [![](https://img.shields.io/badge/-Modelo_del_dominio-24292e?style=flat&logo=freedesktop.org&logoColor=white)](/RUP/00-modelo-del-dominio/README.md) [![](https://img.shields.io/badge/-Actores_&_Casos_de_Uso-24292e?style=flat&logo=crewunited&logoColor=white)](/RUP/01-actores-casos-uso/README.md) [![](https://img.shields.io/badge/-Sesiones-24292e?style=flat&logo=buffer&logoColor=white)](/documentos/sesiones/README.md) [![](https://img.shields.io/badge/-Evidencias-24292e?style=flat&logo=googlesheets&logoColor=white)](/evidencias/sesion01/)
|-:

</div>

# Actores y casos de uso

## Información del artefacto
* **Proyecto:** 26-27-IdSw1-SDR · Gestión OTRI
* **Fase RUP:** Inicio (Inception) / Requisitos — Actores y casos de uso
* **Estado:** En curso (Actividad 1)

---

<div align=center>

|Propuestas y Convocatorias|Filtrado e Informes|
|:-:|:-:|
|![Actores y Casos de Uso — Dimensión Propuesta](/images/01-actores-casos-uso/dimension-propuesta/actores-casos-uso.svg)|![Actores y Casos de Uso — Dimensión Filtrado e Informes](/images/01-actores-casos-uso/dimension-filtrado-informe/actores-casos-uso.svg)|
|<div align=right><sup><i>[Código fuente](/modelosUML/01-actores-casos-uso/dimension-propuesta/actores-casos-uso.puml)</i></sup></div>|<div align=right><sup><i>[Código fuente](/modelosUML/01-actores-casos-uso/dimension-filtrado-informe/actores-casos-uso.puml)</i></sup></div>|

|Proyectos|
|:-:|
|![Actores y Casos de Uso — Dimensión Proyecto](/images/01-actores-casos-uso/dimension-proyecto/actores-casos-uso.svg)|
|<div align=right><sup><i>[Código fuente](/modelosUML/01-actores-casos-uso/dimension-proyecto/actores-casos-uso.puml)</i></sup></div>|

</div>

---

## Diagrama de Contexto

*(En elaboración).*

---

## Inventario por dimensión

| Dimensión | Actores | Paquetes | Casos de uso |
| :--- | :--- | :--- | :--- |
| **Convocatorias y Propuestas** | `UsuarioNoLogueado`<br>`Administrador` | Acceso al Sistema | `iniciarSesion()`, `cerrarSesion()` |
| | `Administrador` | Gestión de Convocatorias | `abrirConvocatoria()`, `abrirConvocatorias()`, `crearConvocatoria()`, `editarConvocatoria()`, `eliminarConvocatoria()` |
| | `Administrador` | Gestión de Propuestas | `abrirPropuesta()`, `abrirPropuestas()`, `crearPropuesta()`, `editarPropuesta()`, `asignarPersonal()`, `desasignarPersonal()`, `concederPropuesta()`, `descartarPropuesta()`, `rechazarPropuesta()`, `entregarPropuesta()` |
| | `Administrador` | Gestión de Persona | `abrirPersona()`, `abrirPersonas()`, `crearPersona()`, `editarPersona()`, `eliminarPersona()` |
| **Proyectos** | `Administrador` | Gestión de Proyectos | `abrirProyecto()`, `abrirProyectos()`, `editarProyecto()`, `finalizarProyecto()`, `abrirHistorial()`, `asignarPersonal()`, `desasignarPersonal()` |
| **Filtrado e Informes** | `Administrador` | Gestión de Organismos Externos | `crearOrganismoExterno()`, `abrirOrganismoExterno()`, `abrirOrganismosExternos()`, `editarOrganismoExterno()`, `eliminarOrganismoExterno()` |
| | `Administrador` | Gestión de Informes | `abrirInformes()`, `abrirInforme()`, `generarInforme()`, `editarInforme()`, `eliminarInforme()`, `descargarInforme()`, `filtrarRegistros()` |

---

## Delimitación de Actores del Sistema

| Actor | Tipo | Descripción y Alcance |
| :--- | :---: | :--- |
| **`UsuarioNoLogueado`** | Humano (Iniciador) | Usuario que accede a la plataforma sin credenciales activas. Su única acción permitida es `iniciarSesion()`. |
| **`Administrador`** | Humano (Principal) | Técnico o gestor de la OTRI autenticado. Tiene el control operativo integral sobre convocatorias, propuestas, proyectos, organismos, informes y directorio de personal. |
