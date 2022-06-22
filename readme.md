## crea el proyecto

1. ENTRA AL DIRECTORIO, 
2. INICIALIZALO EN GIT,
3.  CREA EL ARCHIVO INDEX, 
4. PREPARALO EN GIT,
5.  CONFIRMALO EN GIT, 
6. ASOCIA A REMOTO, 
7. MANDA A REMOTO

```bash
# 1 ENTRA AL DIRECTORIO, 2 INICIALIZALO EN GIT, CREA EL ARCHIVO INDEX, PREPARALO EN GIT, CONFIRMALO EN GIT, ASOCIA A REMOTO, MANDA A REMOTO

cd ejemplo_1/matcha #1
git init #2
touch index.html #3
git add * #4
git commit -m "Primer commit" #5
git remote add master https://github.com/gsanroman/matcha.git #6
git push master #7
```

Crea el contenido del sitio y despliega en un cuenta [NETLIFY](https://app.netlify.com/) asociada a gitHub

el contenido està [aqui](https://clever-fox-91388a.netlify.app/)