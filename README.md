Temas puntuales:
	-Realizar backup a repos de Git
	-Subir repos a GitHub
	-Usar Github pages
	-Desplegar aplicación
	-Generar build de producción

-----------------------------------------

Comandos:
	-Generar el build: npm run build

-----------------------------------------

Recursos:
	-Despliegue: netlify.com
		-Sites 
		-Arrastrar la carpeta build previamente generada
		-Para actualizar el despliegue: deployments/arrastrar el nuevo build de producción

-----------------------------------------

Git:
	-git init: para inicializar el proyecto
	-igt add .
	    -git commit -m "Primer commit"
	    -git checkout -- . (revertir cambios)

-----------------------------------------

Repositorio GitHub:
	-git remote add origin https://github.com/ampv/react-gif-expert.git
	-git branch -M main
	-git push -u origin main

-----------------------------------------

GitHub pages:
    -Cambiar el nombre de la carpeta dist por docs
    -En el repo, seleccionar settings/pages y en branch seleccionar la main
    -Luego, seleccionar la carpeta /docs