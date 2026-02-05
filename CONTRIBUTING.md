# Guía de Contribución - CafeAngular

¡Gracias por tu interés en contribuir al proyecto CafeAngular! 🎉

## Cómo contribuir

### 1. Clonar el repositorio
```bash
git clone https://github.com/LexyJZ/CafeAngular.git
cd CafeAngular
npm install
```

### 2. Configurar el entorno de desarrollo
```bash
ng serve
```

La aplicación estará disponible en `http://localhost:4200/`

### 3. Crear una rama para tu trabajo

Antes de hacer cambios, crea una rama nueva:
```bash
git checkout -b feature/nombre-de-tu-feature
```

O para correcciones de bugs:
```bash
git checkout -b fix/descripcion-del-bug
```

### 4. Hacer cambios

- Escribe código limpio y comentado
- Sigue las convenciones de Angular
- Prueba tus cambios localmente antes de hacer commit

### 5. Hacer commit de tus cambios
```bash
git add .
git commit -m "Descripción clara de los cambios realizados"
```

**Convención de mensajes de commit:**
- `feat:` para nuevas funcionalidades
- `fix:` para corrección de bugs
- `docs:` para cambios en documentación
- `style:` para cambios de formato/estilo
- `refactor:` para refactorización de código
- `test:` para agregar o modificar tests

Ejemplos:
```bash
git commit -m "feat: añade módulo de gestión de inventario"
git commit -m "fix: corrige error en formulario de registro"
git commit -m "docs: actualiza README con instrucciones de instalación"
```

### 6. Sincronizar con la rama principal

Antes de subir tus cambios, asegúrate de tener lo último de main:
```bash
git checkout main
git pull origin main
git checkout feature/tu-rama
git merge main
```

Resuelve conflictos si los hay.

### 7. Subir tus cambios
```bash
git push origin feature/nombre-de-tu-feature
```

### 8. Crear un Pull Request

1. Ve a https://github.com/LexyJZ/CafeAngular
2. Verás un botón "Compare & pull request"
3. Describe claramente qué cambios hiciste y por qué
4. Espera la revisión del equipo

## Estándares de código

- **Indentación:** 2 espacios
- **Nombres de variables:** camelCase
- **Nombres de componentes:** PascalCase
- **Archivos:** kebab-case
- **Comentarios:** En español, claros y concisos

## Estructura del proyecto
```
src/
├── app/
│   ├── accesos/         # Módulo de accesos (home, login, etc.)
│   ├── procesos/        # Módulo de procesos del negocio
│   ├── recursos/        # Recursos compartidos
│   ├── servicios/       # Servicios
│   └── shared/          # Componentes compartidos
├── assets/              # Imágenes, iconos, etc.
└── styles.css           # Estilos globales
```

## Reportar problemas

Si encuentras un bug o tienes una sugerencia:

1. Ve a [Issues](https://github.com/LexyJZ/CafeAngular/issues)
2. Crea un nuevo issue
3. Describe claramente el problema o sugerencia
4. Incluye capturas de pantalla si es necesario

## Comunicación

- Usa nombres descriptivos en ramas y commits
- Comenta tu código cuando sea necesario
- Mantén conversaciones respetuosas en issues y PRs
- Pregunta si tienes dudas antes de hacer cambios grandes

## ¿Necesitas ayuda?

Si tienes dudas sobre cómo contribuir, contacta al equipo o abre un issue con la etiqueta `question`.

---

¡Gracias por contribuir a CafeAngular! 
