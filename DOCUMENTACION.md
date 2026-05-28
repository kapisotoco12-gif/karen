# SISTEMA DE REGISTRO DE ESTUDIANTES

## 👥 NOMBRE DE ESTUDIANTES
- Karen Paola Medina (kapisotoco12-gif)
- [Nombre Segundo Estudiante]
- [Nombre Tercer Estudiante]

---

## 📋 PLANTEAMIENTO DEL PROBLEMA

La institución educativa requiere un sistema eficiente para gestionar el registro de estudiantes. Actualmente, los datos se manejan de forma manual o en archivos desorganizados, lo que genera:

- **Pérdida de información**: Datos incompletos o desactualizados
- **Búsqueda ineficiente**: Dificultad para localizar estudiantes por nombre o curso
- **Errores de duplicidad**: Registros duplicados o inconsistentes
- **Falta de actualización**: Imposibilidad de editar información de forma rápida
- **Problemas de integridad**: Eliminación accidental o sin control de datos

Se necesita una aplicación web que permita centralizar, organizar y gestionar eficientemente toda la información de los estudiantes.

---

## 🎯 OBJETIVOS

### Objetivo General
Desarrollar un sistema web de registro de estudiantes que permita gestionar eficientemente la información académica de los alumnos de la institución.

### Objetivos Específicos
1. **Registrar estudiantes**: Crear nuevos registros con información completa (nombre, cédula, curso, email, teléfono)
2. **Consultar información**: Búsqueda rápida por nombre o curso
3. **Actualizar datos**: Editar información de estudiantes existentes
4. **Eliminar registros**: Remover estudiantes del sistema de forma segura
5. **Persistencia de datos**: Almacenar toda la información en base de datos MySQL
6. **Interfaz amigable**: Diseñar una interfaz intuitiva y fácil de usar

---

## 💡 JUSTIFICACIÓN

### Por qué es necesario este sistema:

1. **Eficiencia Operativa**
   - Automatiza tareas repetitivas y tediosas
   - Reduce tiempo de búsqueda y procesamiento
   - Minimiza errores humanos

2. **Organización y Control**
   - Centraliza toda la información en una base de datos
   - Permite auditoría y trazabilidad
   - Mantiene integridad referencial

3. **Escalabilidad**
   - Permite crecer el número de estudiantes sin problemas
   - Sistema preparado para futuras expansiones
   - Fácil mantenimiento y actualizaciones

4. **Seguridad**
   - Datos protegidos en servidor seguro
   - Control de acceso (potencial para autenticación)
   - Backups y recuperación de datos

5. **Mejora en Experiencia del Usuario**
   - Interfaz moderna y responsiva
   - Acceso desde cualquier navegador
   - Validaciones en tiempo real

---

## 🛠️ SOFTWARE A UTILIZAR

| Componente | Tecnología | Versión | Función |
|-----------|-----------|---------|----------|
| **Frontend** | HTML5 | 5.0 | Estructura y maquetación |
| | CSS3 | 3.0 | Estilos y diseño responsivo |
| **Backend** | PHP | 7.4+ | Lógica de servidor |
| **Base de Datos** | MySQL | 5.7+ | Almacenamiento de datos |
| **Servidor** | Apache (XAMPP/WAMP) | 2.4+ | Servidor web |
| **Navegador** | Chrome/Firefox/Edge | - | Cliente web |

### Características Técnicas

**HTML5**: Elementos semánticos modernos, formularios con validación

**CSS3**: Diseño responsivo, flexbox/grid, animaciones suaves

**PHP**: 
- Procesamiento de formularios
- Conexión a base de datos
- Operaciones CRUD (Create, Read, Update, Delete)
- Gestión de sesiones

**MySQL**:
- Almacenamiento relacional
- Consultas SQL optimizadas
- Integridad de datos

---

## 📂 ESTRUCTURA DEL PROYECTO

```
sistema-registro-estudiantes/
├── index.php                 # Página principal
├── crear.php                 # Formulario de registro
├── buscar.php                # Búsqueda de estudiantes
├── editar.php                # Editar estudiante
├── eliminar.php              # Eliminar estudiante
├── procesar.php              # Procesar operaciones
├── conexion.php              # Conexión a BD
├── css/
│   └── estilos.css          # Estilos principales
├── js/
│   └── validacion.js        # Validaciones JavaScript
└── bd/
    └── estudiantes.sql      # Script de base de datos
```

---

## 🔧 FUNCIONALIDADES PRINCIPALES

1. **Registrar Estudiantes**
   - Formulario completo con validación
   - Datos: Nombre, Cédula, Curso, Email, Teléfono

2. **Buscar Estudiantes**
   - Búsqueda por nombre
   - Filtro por curso
   - Resultados dinámicos

3. **Editar Datos**
   - Modificar información existente
   - Confirmación antes de guardar

4. **Eliminar Registros**
   - Eliminación con confirmación
   - Integridad referencial

5. **Listado General**
   - Vista de todos los estudiantes
   - Paginación
   - Ordenamiento

---

## 📅 FECHAS IMPORTANTES

- **Creación**: 28 de Mayo de 2026
- **Entrega Esperada**: [Fecha a definir]
- **Estado**: En Desarrollo

---

**Versión**: 1.0  
**Última Actualización**: 28/05/2026
