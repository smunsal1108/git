# Comandos de Git Esenciales

Este repositorio sirve como una guía rápida y un recordatorio de los comandos más importantes de Git que se utilizan regularmente en el desarrollo de software y el control de versiones.

## Configuración Inicial

- **Configurar Usuario y Correo Electrónico**
  ```bash
  git config --global user.name "Tu Nombre"
  git config --global user.email "tuemail@example.com"
   ```

## Crear y Clonar Repositorios

- **Inicializar un Nuevo Repositorio**
   ```bash
  git init
   ```

- **Clonar un Repositorio Existente**
  ```bash
git clone [URL]
   ```

## Cambios en los Archivos

- **Verificar el Estado del Repositorio**
  ```bash
git status
   ```
- **Agregar Archivos al Área de Staging**
  ```bash
git add [archivo]
git add .

   ```

- **Realizar un Commit de los Cambios**
  ```bash
git commit -m "Mensaje del commit"
   ```


  ## Trabajar con Ramas

- **Listar todas las Ramas**
  ```bash
git branch -a
   ```

- **Crear una Nueva Rama**
  ```bash
git branch [nombre-rama]
   ```
  - **Cambiar a Otra Rama**
  ```bash
git checkout [nombre-rama]
   ```
  - **Fusionar Ramas**
  ```bash
git merge [nombre-rama]
   ```
  ## Sincronización con Repositorios Remotos

- **Subir Cambios al Repositorio Remoto**
  ```bash
git push [alias] [rama]

  ```
- **Actualizar el Repositorio Local con Cambios Remotos**
  ```bash
git pull [alias] [rama]

  ```

  ## Historial de Commits

- **Configurar Usuario y Correo Electrónico**
  ```bash
git log
   ```
  ## Ejemplo de ALIAS
- **ALIAS :: git tree**
- **Configurar Usuario y Correo Electrónico**
  ```bash
git config --global alias.tree "log --graph --decorate --all --oneline"

   ```


## Configuración repositorio
- **Cambiar**
  ```bash
git remote set-url origin git@github.com:[tu_usuario]/[tu_repositorio].git
   ```
- **Nuevo**
  ```bash
git remote add origin git@github.com:<tu_usuario>/<tu_repositorio>.git
   ```

 ## Comandos Adicionales

- **Diferencias entre Archivos**
  ```bash
git diff   
```


- **Reestablecer Archivos del Área de Staging**
  ```bash
git reset [archivo]
```

