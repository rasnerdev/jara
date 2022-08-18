# Tablas

## PACIENTES
1. [**NPAT:**](./npat.md) IS-H: Dat.maestros paciente (gral.)
2. **NTMN:** IS-H: Citaciones por paciente (Tabla de cabecera en NAPP)
3. [**NPAE:**](./npae.md) IS-H: Datos maestros del paciente (rel.con centro sanitario)
4. [**ZAS_PAT_GROUP**](./zas_pat_group.md): Asignaciones de pacientes a colectivos
5. **ZASPATPUESTO**: IS-H: Asignación médicos-pacientes
6. **ZASEXITUS**: Situación de Pacientes Fallecidos
7. **ZASEXITUSPCC**: Situación de Pacientes Fallecidos


## DOCUMENTOS
1. [**NDOC:**](./ndoc.md) IS-H: Asignaciones de objetos IS-H y documentos en SGD
2. **TDWS:** Status del documento
3. **TDWST:** Texto para el status del documento. (Claves DOKST y CVLANG).
4. [**DRAW**](./draw.md): Registro info de documento
5. [**DRAT**](./drat.md): Textos breves para registros info de documentos
 

## INTERLOCUTORES
1. **N1MAPS:** ISHMED: Ocupación de empleado por posición
2. **NGPA:** IS-H: Interlocutores
3. [**NGUZ**](./nguz.md): IS-H: Asignación IC <-> usuario

## UNIDADES ORGANIZATIVAS Y ÁREAS
1. **TN10H:** IS-H: Jerarquía de unidades organizativas
2. **NORG:** IS-H: Unidades organizativas
3. **TN01:** IS-H: Centros sanitarios
4. **NBAU:** IS-H: Unidades edificio
5. **TN10A:** IS-H: Tipos de unidades org
6. **TN10S:** IS-H: Texto y palabra clave p.tipo de unidad org.

## ÓRDENES CLÍNICAS
1. **N1VKG:** IS-H: Posición de orden clínica (preadmisión)
2. **N1CORDER:** IS-H: Orden clínica
3. **[N1CORDTYPT](./n1cordtypt.md):** IS-H: Textos del tipo de orden clínica

## MEDICAMENTOS
1. **N1MEORDER:** IS-H\*MED: Medicación, prescripción medicamentos

## CITAS
1. **NTMN**: IS-H: Citaciones por paciente (tabla de cabecera en NAPP)
2. **NTPGK**: IS-H: Datos cabecera progr.diario p.planif.consul.externas
3. **NWPG**: IS_H: Programas semana p.planificación consultas externas
4. **TN10I**: IS-H: Ocupación interdepartamento de udad.org.por udad.org

## EPISODIOS Y MOVIMIENTOS
1. **NFAL:** IS-H: Episodios
2. [**NBEW:**](./nbew.md) IS-H: Mov. p. el episodio
3. **ZAS_MOV_RELACION**: IS-H: Asignación de un episodio a otro episodio

## TRATAMIENTOS
1. **TJ30T**: Estados tratamientos

## SMARTFORMS
1. **ISH_SMARTFORMS_GET:** 
2. **SSF_FUNCTION_MODULE_NAME:** 

## EMPLEADOS
1. [**NPER:**](./nper.md) IS-H: Personas
2. **NPEF:** IS-H: Asignación de personas a especialidades
3. **TNKFA:** IS-H: Codificación de especialidades
4. [**USR05:**](./usr05.md) Maestro de usuarios ID de parámetros
5. [**ZHR_M_CATEGORIAS:**](./zhr_m_categorias.md): Maestro de categorías

## ESTACIÓN DE IT
1. **VNREDO:** IS-H: Certificado; estructura de actualización
2. **VNWOINC:** IS-H: Documento - estructura de actualización para IT

## SISTEMA
- [**TN00S**](./tn00s.md): Tabla con parámetros del sistema
- [**TN006**](./tn006.md): Unidades de medida

## SAP
1. [**SMEN_BUFFC:**](./smen_buffc.md) Tabla para archivar favoritos
2. [**SYST:**](./syst.md) Variables de sistema
3. [**TSTC:**](./tstc.md) Códigos de transacción SAP

## CUESTIONARIOS
1. **ZAS_CUESTION:** Cuestionarios de enfermería
2. **ZAS_INTCUES:** Interpretación de los valores de cuestionarios de enfermería

## PRESTACIONES
1. **NLEM**: IS-H\*MED: Prestación médica
2. **NLEI**: IS-H: Prestac. realizadas

## ZAS_PETICIONES
1. **ZAS_CAB_PETICION:** Tabla de Cabecera de Peticiones. (Contiene las peticiones)
2. **ZAS_POS_PETICION:** Tabla de positiones de peticiones (Contiene las copias de las peticiones. 

## VISTAS
1. [**ZASVIEW**](./zasview.md): IS-H: Customizing de vistas en puesto de trabajo CWS
2. [**NWVIEW**](./nwview.md): Vistas en puestos de trabajo.
3. [**NWPLACE**](./nwplace.md): Entorno de trabajo

## LOG DE ERRORES
1. **BALHDR:** Log aplicación: Cabecera de log
### Relaciones
1. Obtener la especialidad de un trabajador

## PMD
- [**Y000006800000000**](./Y000006800000000.md): PMD: HEP_BAS - Documento de Hepatitis Crónica

## CTMAP
1. [**ZCONF_CTMAP**]: Tabla de configuración
2. [**ZBUSQ_CTMAP**]: Autoaprendizaje Diagnosticos CTMAPS

## NOTIFICACIONES TEAMS
1. [**ZAS_NOTIF_TEAMS**]():Información sobre las notificaciones Teams y su operación
2. [**ZLOG_NOTIF_TEAMS**]():Información sobre las notificaciones Teams y su operación
3. [**ZNOTIF_TEAMS_CU1**]():Maestro de características de tipos de notificaciones Teams
4. **ZAS_OPERA_TEAMS**: Tipos de operación en notificaciones Teams

### TIPS
1. [Modificar el contenido de una tabla de la SE16](https://github.com/rasnerdev/abap/blob/master/jara/sap/modificar_tabla_se16.md)

<hr>

[Volver al índice](https://github.com/rasnerdev/abap/blob/master/jara/indice.md)


<hr />

### [```ÍNDICE```](../indice.md)