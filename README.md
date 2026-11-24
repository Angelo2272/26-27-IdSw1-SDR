<h1 align="center">26-27-IdSw1-SDR · Gestión OTRI</h1>

<p align="center">
  <b>Plataforma de Registro, Seguimiento y Cribado de Convocatorias, Propuestas y Proyectos de Investigación</b><br>
  <i>Oficina de Transferencia de Resultados de Investigación (OTRI) · UNEATLANTICO</i>
</p>

<div align="center">

[![](https://img.shields.io/badge/-Inicio-24292e?style=for-the-badge&logo=github&logoColor=white)](/README.md)
[![](https://img.shields.io/badge/-Modelo_del_Dominio-24292e?style=for-the-badge&logo=diagramsdotnet&logoColor=white)](/RUP/00-modelo-del-dominio/README.md)
[![](https://img.shields.io/badge/-Actores_&_Casos_de_Uso-24292e?style=for-the-badge&logo=crewunited&logoColor=white)](/RUP/01-actores-casos-uso/README.md)
[![](https://img.shields.io/badge/-Sesiones-24292e?style=for-the-badge&logo=googlemeet&logoColor=white)](/documentos/sesiones/README.md)
[![](https://img.shields.io/badge/-Evidencias-24292e?style=for-the-badge&logo=googlesheets&logoColor=white)](/evidencias/sesion01/)

</div>

---

## [Modelo del Dominio](/RUP/00-modelo-del-dominio/README.md)

Describe la estructura lógica del negocio, las entidades de datos y sus ciclos de vida.

* **[Diagrama de Clases](/modelosUML/00-modelo-del-dominio/diagrama-de-clases.puml)** 
* **[Diagrama de Estados — Propuesta](/modelosUML/00-modelo-del-dominio/diagrama-de-estados-propuesta.puml)**
* **[Diagrama de Estados — Informe](/modelosUML/00-modelo-del-dominio/diagrama-de-estados-informe.puml)**

---

## [Actores y Casos de Uso](/RUP/01-actores-casos-uso/README.md)

Describe las interacciones de los actores con el sistema y los requisitos funcionales organizados por dimensiones de negocio.

* **[Actores y Casos de Uso](/RUP/01-actores-casos-uso/README.md):** Identificación y justificación de roles y metas de usuario.
* **[Diagramas UML de Casos de Uso](/modelosUML/01-actores-casos-uso/):** Modelado modular por áreas de negocio.
* **Diagramas de Contexto:** Autómata de navegación de estados de interfaz.
* **Casos de Uso Detallados:** Detalle de flujos con autómatas PlantUML.
* **Prototipos de Interfaz:** Wireframes de interacción visual diseñados con PlantUML Salt.

---

## [Sesiones con el Cliente](/documentos/sesiones/README.md)

Apuntes oficiales, acuerdos de alcance y registros de campo de las reuniones con el cliente.

* **[Minuta Sesión 01 (2026-10-29)](/documentos/sesiones/sesion01.md):** Requisitos, reglas de negocio y problemáticas levantadas.

---

## Estructura del Repositorio

```text
26-27-IdSw1-SDR/
├── RUP/                                # Documentación formal del ciclo RUP
│   ├── 00-modelo-del-dominio/          # Fichas y justificaciones del Modelo del Dominio
│   └── 01-actores-casos-uso/           # Catálogo preliminar y detalle de Casos de Uso
├── modelosUML/                         # Fuentes PlantUML (.puml)
│   ├── 00-modelo-del-dominio/          # Clases y estados del dominio
│   └── 01-actores-casos-uso/           # Diagramas de casos de uso y navegación
├── images/                             # Exportaciones vectoriales (.svg)
│   ├── 00-modelo-del-dominio/          # Gráficos compilados del dominio
│   └── 01-actores-casos-uso/           # Gráficos compilados de requisitos
├── documentos/                         # Minutas oficiales de entrevistas
│   └── sesiones/                       # Registro de acuerdos con el cliente
├── evidencias/                         # Formatos originales provistos por el cliente
```
