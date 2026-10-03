# LegoControlPanel
Panel de control para tienda de lego/ tienda de exhibicion de LEGOS

## Prioridad 1, Pantalla Principal y Monitoreo en Tiempo Real 
Ubicación: Parte superior y central de la interfaz.
# 1.	Sección de Proyectos y Tareas en Ejecución (Área de Enfoque):
Tarjeta / Listado de Tarea Activa:
Nombre de la exhibición LEGO y cantidad de unidades a construir.
Fecha/Hora de inicio y fecha/hora estimada de finalización.
Barra de Progreso: Elemento HTML <progress> o <div> para la animación del porcentaje de avance.
Personal asignado con su costo por hora.
Materiales asignados (sets LEGO, unidades y costo unitario).
Botón de acción para Marcar como Concluida (lo que fijará el costo real).

# 2.	Dashboard General de Métricas (Resumen global):
Indicador de costo total vs. costo real ejecutado.
Indicadores de costos acumulados de personal, materiales (sets LEGO) y otros gastos.
Alerta o indicador visual de sobreutilización de personal (> 8 horas diarias).
##Prioridad 2: Modulos de Alta y Registro (Creación de Recursos y Tareas)
Ubicación: Panel lateral o secciones secundarias mediante pestañas/formularios.
# 1.	Formulario de Registro de Personal:
Campo de texto: Nombre del encargado de construcción.
Campo numérico: Costo por hora.
Botón: "Guardar Personal".
# 2.	Formulario de Registro de Tareas (Nuevas Exhibiciones):
Selección de personal a asignar (de la lista de empleados creados).
Definición del tiempo estimado de ejecución (en horas/días).
Selección y asignación de sets de LEGO (materiales) y cantidad requerida.
Costos adicionales y cantidad.
Definición del número de construcciones de un mismo tipo a realizar.
Botón: "Crear Exhibición / Tarea".
# 3.	Formulario de Inventario / Materiales y Otros Costos:
Registro de sets LEGO / Materiales con su precio/costo por unidad.
Registro de otros gastos operativos por unidad.
## Prioridad 3: Histórico y Restricciones de Integridad
Ubicación: Sección inferior o tab de consulta.
# 1.	Tabla / Historial de Exhibiciones Concluidas:
historial con la comparación de costo presupuestado vs. costo real finalizado.
# 2.	Regla de Borrado / Estado:
Los elementos (personal, sets LEGO, tareas) incluirán en la interfaz estados de desactivación o bloqueo para asegurar que ningún elemento asignado o con historial pueda ser eliminado.

