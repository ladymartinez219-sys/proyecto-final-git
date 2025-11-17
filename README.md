proyecto final git
Descripción general del trabajo realizado
Se desarrolló una contribución al proyecto colaborativo de gestión de paquetería utilizando Git como sistema de control de versiones. El trabajo incluyó la creación de una rama específica para el módulo asignado, la edición del archivo README.md, y el envío de un Pull Request al repositorio del compañero responsable de la integración. Se aplicó un flujo Git colaborativo que garantiza trazabilidad, organización y control de cambios.

🧩 Lista de comandos utilizados
# Inicializar repositorio local (si aplica)
git init

# Clonar repositorio remoto del compañero
git clone https://github.com/ladymartinez219-sys/proyecto-final-git.git

# Verificar remotos configurados
git remote -v

# Crear y cambiar a una nueva rama de trabajo
git checkout -b feature/manual-usuario

# Ver ramas locales y remotas
git branch
git branch -r
git branch -a

# Ver estado de archivos
git status

# Agregar cambios al área de staging
git add README.md

# Confirmar cambios con mensaje
git commit -m "Actualizo README con descripción del módulo manual de usuario"

# Subir rama al repositorio remoto
git push -u proyecto-final-git feature/manual-usuario

# Sincronizar cambios si el remoto tiene contenido previo
git pull proyecto-final-git main --rebase

# Resolver conflictos en README.md
# (edición manual + luego:)
git add README.md
git commit -m "Resuelvo conflicto en README.md"

# Enviar cambios finales
git push proyecto-final-git main




- Clonación del repositorio remoto para trabajar sobre una copia local.
- Creación de una rama específica para aislar los cambios del módulo asignado.
- Edición y commit de los archivos modificados, especialmente el README.md.
- Push de la rama al remoto, permitiendo que el compañero vea los cambios en GitHub.
- Pull Request desde la rama creada hacia la rama principal (main) del repositorio del compañero.
- Resolución de conflictos en caso de que el archivo README.md tuviera diferencias entre la versión local y remota.
- Integración final mediante la aceptación del Pull Request por parte del compañero.
Este flujo asegura que cada contribución esté bien documentada, aislada y revisable antes de integrarse al proyecto principal.



¿Te gustaría que convierta esto en una plantilla editable para tu manual de usuario o que lo adapte al formato APA si lo necesitas como parte del marco teórico?
