# Ejercicio Huellitas
Taller 10 - Fundamentos de bases de datos

La red de clínicas veterinarias Huellitas tiene varias sedes en el país y necesita una base de datos para registrar a los propietarios y sus mascotas, los veterinarios y los turnos que cumplen en cada sede, las consultas que
se atienden, los medicamentos que se formulan en cada consulta y las vacunas que se aplican a cada mascota.
Reglas del negocio:
Un propietario puede tener varias mascotas; cada mascota pertenece a un solo propietario.
Un veterinario puede trabajar en varias sedes y en distintos días; en una misma sede y un mismo día
solo tiene un turno.
Toda consulta se atiende dentro de un turno existente (veterinario + sede + día).
En una consulta se pueden formular varios medicamentos, pero cada medicamento aparece una sola
vez por consulta.
Una mascota puede recibir la misma vacuna varias veces(refuerzos), pero no dos veces el mismo día
