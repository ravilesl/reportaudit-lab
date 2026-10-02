🔗 Issue relacionado
<!-- Ponlo primero: el revisor necesita el contexto antes de leer el código. "Closes #123" cierra el Issue automáticamente al fusionar en la rama por defecto. Si el PR no termina el Issue, usa "Refs #123". --> 
Closes #

📝 Resumen
<!-- Qué problema resuelve y por qué. 2–3 frases. El "cómo" va en las secciones siguientes. --> 


🔄 Tipo de cambio
<!-- Debe coincidir con el prefijo Conventional Commits del título del PR (p. ej. "feat(ventas): ..."). --> 
•	[ ] fix — corrige un error
•	[ ] feat — nueva funcionalidad
•	[ ] refactor — mejora la estructura sin cambiar el comportamiento
•	[ ] perf — mejora de rendimiento
•	[ ] test — añade o modifica pruebas
•	[ ] docs — documentación
•	[ ] build / ci — dependencias, pipeline o configuración
•	[ ] ⚠️ BREAKING CHANGE — rompe compatibilidad (explica abajo cómo migrar)

📋 Cambios realizados
<!-- Los cambios técnicos más importantes, uno por línea. --> 
•	


🏗️ Decisiones de diseño
<!-- Lo que el revisor no puede deducir leyendo el diff. --> 
•	Enfoque elegido y por qué:
•	Alternativas descartadas:
•	Principios / patrones aplicados (si los hay): <!-- p. ej. SRP: se extrae PricingPolicy; Strategy para los transportistas -->
•	Deuda técnica conocida que este PR no resuelve: <!-- enlaza el Issue de deuda, si existe -->


👀 Cómo revisar este PR
<!-- Orden de lectura recomendado y en qué quieres que se fije el revisor. --> 
1.	

🧪 Pruebas y evidencias
•	[ ] Probado localmente: compila y se ejecuta sin errores.
•	[ ] Verificado contra los criterios de aceptación del Issue.
•	[ ] Pruebas automatizadas añadidas o actualizadas, y pasan en CI.
•	[ ] Evidencias adjuntas (capturas, salida de consola, SPOOL o script ejecutado).
<!-- Pega aquí las evidencias o enlázalas. --> 


⚠️ Riesgos e impacto
<!-- Borra lo que no aplique. --> 
•	Base de datos: ¿hay scripts DDL/DML? ¿Son reversibles? ¿Dónde está el script de rollback?
•	Configuración / secretos: ¿cambian variables de entorno? (nunca credenciales en el PR)
•	Cómo deshacerlo si falla:

✅ Checklist del autor
•	[ ] He hecho self-review del diff en GitHub antes de pedir revisión.
•	[ ] El PR es pequeño (idealmente < 400 líneas cambiadas) y trata un solo tema.
•	[ ] El Quality Gate de SonarQube está en verde y no hay avisos nuevos de linter/compilador.
•	[ ] Los nombres revelan la intención; no hay números mágicos ni código comentado.
•	[ ] Los comentarios explican el porqué, no el qué.
•	[ ] No hay secretos, contraseñas ni datos personales en el código o en los commits.
•	[ ] Si he usado asistentes de IA, he revisado y entiendo cada línea que entrego.

