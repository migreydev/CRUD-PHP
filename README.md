# Gestión de Alumnos

Hacer una pagina que liste todos los alumnos de la siguiente tabla. Añadirle botones para editar y borrar, asi como un formulario para insertar nuevos alumnos:

## Funcionalidad

1. **Listar Alumnos**
2. **Editar**
3. **Borrar**
4. **Insertar Nuevo Alumno**

## Tabla

La tabla `alumnos` se define de la siguiente manera:

```sql
CREATE TABLE `portfolio_projects`.`alumnos` (
  `idAlumnos` INT NOT NULL AUTO_INCREMENT,
  `nombreAlumnos` VARCHAR(45) NOT NULL,
  `edad` INT NULL,
  PRIMARY KEY (`idAlumnos`)
);
```
