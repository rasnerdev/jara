  # NPAE: IS-H: Datos maestros del paciente (rel.con centro sanitario)
  Esta tabla guarda la relación entre pacientes y centros sanitarios.
  
  ## Campos de la tabla
| Campo | Clave | Descripción |
| --- | --- | --- |
| MANDT | X |	Mandante |
| EINRI | X | IS-H: Centro sanitario |
| PATNR | X |	IS-H: Número de paciente |
| PFORT |  |	IS-H: El paciente ha pedido protección de sus datos personal |
| PFAKZ |  |	IS-H: indicador Voluntades Anticipadas |
| PFARR |  |	IS-H: Parroquia |
| STATU |  |	IS-H: status de paciente |
| SZVOR |  |	IS-H: el indicador sociedad para particular M/A existe |
| STORN |  |	IS-H: Indicador de anulación |
| STUSR |  |	IS-H: Nombre del responsable de la anulación |
| STDAT |  |	IS-H: fecha de anulación |
| ERDAT |  |	IS-H: Fecha en la que se ha creado el registro |
| ERUSR |  |	IS-H: nombre del responsable que ha creado el registro |
| UPDAT |  |	IS-H: Fecha de la modificación |
| UPUSR |  |	IS-H: Nombre del responsable de la modificación |

## Módulos de funciones relacionados: 
- **[ZAS_BAPI_PATIENT_UPD_NPAE](../modulos-de-funciones/zas_bapi_patient_upd_npae.md)**: Añade a la NPAE todas las áreas que no tenga el paciente.
<hr />

### [```ÍNDICE```](../indice.md) > [```TABLAS```](./indice.md)