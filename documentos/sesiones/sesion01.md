# Minuta de Sesión de Requisitado

**Proyecto / Sistema:** Por resolver

**Fecha:** 2026-10-29 | **Hora Inicio:** 10:03 | **Hora Fin:** 10:54

**Lugar :** Aula 1.9

---

## 1. Asistentes
**Cliente:**
*   Mar Pacheco


**Equipo:**
*   Carlos Alvarado
*   Gabriel Béjar
*   Jimena Calderón
*   Nicolás Navas
*   Miguel Rivas
*   Chao Zhen

## 2. Objetivo de la Sesión
*   Obtener datos mediante interacción con el cliente donde se descubran las problemáticas que tiene actualmente, la solución que espera acerca de dicha problemática y el cómo la quiere. Comprender también su contexto específico para plantear una solución para el sistema esperado por el cliente.

---

## 3. Desarrollo

### 3.1. Contexto y Procesos de Negocio
*   El contexto del cliente se halla en OTRI (Oficina de Transferencia de Resultados de Investigación). Se trata de una oficina en el dominio de la universidad que actúa como puente y facilita la gestión entre la investigación que desarrolla o busca desarrollar el personal docente e investigador (PDI) de la propia institución y la entidad financiadora.
*   Existen diversas organizaciones de distinto alcance que mediante las convocatorias entablan comunicación con los investigadores y pueden llegar a un acuerdo mediante la OTRI. Se definen como entidades.
*   En la mencionada oficina se presentan propuestas de investigación. Las cuales pueden luego de ser evaluadas por los interesados se informa si son concedidas o no concedidas. En caso de ser concedidas pasa a considerarse un proyecto de investigación, en caso contrario existe la opción de trabajar en la propuesta para buscar su aprobación o mantenerse archivada.
*   En una propuesta/proyecto se distingue entre dos responsabilidades: Gestor de Propuesta y Gestor de Proyecto. El gestor de propuesta se encarga de exponer la misma a la entidad interesada. Por contraparte cuando la propuesta es aprobada y pasa a ser proyecto, su gestor se encarga de administrar y asegurar que se complete el mismo.
*   Para presentar una propuesta las entidades financiadoras abren convocatorias, allí es donde se las propuestas se presentan ante las mismas para su posterior valoración. Las mencionadas convocatorias se distinguen como Internacionales, Nacionales y Regionales.
*   Existe la figura de un auditor, el cual se trata de un sujeto externo al departamento encargado de revisar el proyecto y su documentación.
*   Tanto las entidades financiadoras como los organismos de evaluación, acreditación y estadística pueden solicitar informes y justificaciones relativas a los proyectos. La OTRI es responsable de buscar, organizar, y dar formato según lo que haya pedido la entidad. Dichos informes pueden contener información básica, datos de progreso, estados, resultados entre otras cosas.
*  El almacenamiento y gestión de los datos de propuestas/proyectos se realiza actualmente en un Excel, el cual contiene en sus filas los campos necesarios para su registro y también elementos visuales que ayudan a distinguir entre los estados de las propuestas.
*   En el escenario vigente el acceso está limitado a un grupo reducido de personas que cuentan con un nivel de permisos idéntico.

### 3.2. Problemas Identificados
*   Las entidades pueden solicitar información acerca de un conjunto de proyectos, lo cual se dificulta a causa de la herramienta utilizada en la gestión de los datos de las propuestas/proyectos, se presenta una alta dificultad a la hora del cribado de registros al momento de solicitar datos de una cantidad considerable, ya que debido a la naturaleza de la herramienta se requiere realizar una búsqueda manual para hallar los registros deseados. Dicha búsqueda manual puede conllevar errores humanos tales como omisión de proyectos o un mal conteo.
*   Casos explícitos de búsqueda serían hallar los que se llevaron a cabo entre 2022 hasta 2025 o un conteo de los proyectos donde el investigador principal sea una persona específica.

### 3.3. Necesidades y Expectativas
*   Un sistema que permita gestionar la información de propuestas/proyectos de investigación con todos los apartados pertinentes así como obtención de elementos. Permitiendo las acciones de leer los registros, agregar nuevos registros, rastrear registros y editar los existentes. Mediante interacción directa, obviando el uso de formularios intermedios y manteniendo una estructura similar a la utilizada actualmente.
*   Es un requerimiento crítico que la solución ofrezca búsquedas y filtrado, permitiendo al usuario localizar la información utilizando cualquier dato del registro.
*   Garantizar trazabilidad de la manipulación de datos.
*   Generar informes de registros individuales utilizando los datos presentes, informes los cuales puedan ser editados a posterior para agregar información adicional no correspondiente al dominio del sistema.
*   Se debe permitir la ampliación, modificación y reducción de apartados de registro.

### 3.4. Reglas de Negocio
*   Una propuesta de investigación se convierte en proyecto al momento en que se aprueba por la entidad interesada.
*   Si una propuesta es rechazada, permanece cerrada para siempre. En caso de buscar su aprobación en otra oportunidad, se registra como una propuesta nueva.
*   No se contemplan casos donde se eliminen registros existentes. Quedan almacenados por siempre.
*   Los usuarios del sistema deben acceder al mismo utilizando sus credenciales regulares de la universidad.
*   La propuesta tiene elementos definidos como son: nombre, código, convocatoria, carácter, financiación, curso/área, fecha de entrega de propuesta, fecha de concesión de propuesta, entidad financiadora, nacional, internacional o regional, dinero que conceden, investigadores que llevarán a cabo esa propuesta (pueden ser participantes que justifican únicamente la propuesta o ejecutores) y descripción.

### 3.5. Restricciones y Entorno
*   El alcance del sistema se encuentra delimitado al almacenamiento de los registros de propuestas/proyectos, es decir, no almacena información del trabajo realizado en los ellos, únicamente de sus datos identificativos y de control que faciliten su ubicación y comprensión de ámbito.

---

## 4. Acuerdos y Decisiones Tomadas
*   **Aprobado:** Nivel de detalle en la manipulación de campos de datos de registro.
*   **Descartado:** La necesidad de una variedad de perfiles en el sistema. Pues los usuarios tendrán una capacidad casi homogénea en el sistema.

---

## 5. Anexos y Evidencias
*   [Registro de propuestas/proyectos (CSV)](./../../evidencias/sesion01/registro-propuestas-proyectos.csv) - Archivo de visualización rápida de la estructura de registro.
*   [Registro de propuestas/proyectos (XLSX)](./../../evidencias/sesion01/registro-propuestas-proyectos.xlsx) - Archivo original de muestra del formato de registro proveído por el cliente.
*   [Departamento de proyectos](./../../evidencias/sesion01/esquema_dpto_proyectos.png) - Foto tomada de las anotaciones en la pizarra del cliente sobre el departamento de proyectos.