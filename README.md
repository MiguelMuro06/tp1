# tp1
# Archivo .gitignore
## ¿Porque es conveniente incluirlo?
El archivo _.gitignore_ es útil porque permite excluir ciertos archivos y directorios del control de versiones en Git. Esto ayuda a evitar que archivos innecesarios, sensibles o específicos del entorno se suban al repositorio.
## ¿Cuando se debe hacer?
El archivo `.gitignore` debe configurarse desde el inicio del proyecto para evitar que archivos innecesarios sean rastreados por Git. Sin embargo, si un archivo ya ha sido añadido al repositorio antes de estar en `.gitignore`, se debe eliminar manualmente con _git rm --cached <archivo>_.