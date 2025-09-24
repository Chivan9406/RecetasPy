# 🍳 RecetasPy - Administrador Digital de Recetas

Un sistema completo de gestión de recetas desarrollado en Python que permite organizar, crear, leer y administrar tu colección personal de recetas culinarias de forma intuitiva y eficiente.

---

## 🚀 Características Principales

- ✨ **Interfaz de consola interactiva** con menú intuitivo
- 📁 **Organización por categorías** (Carnes, Ensaladas, Pastas, Postres)
- 📖 **Lectura de recetas** con navegación fácil
- ➕ **Creación de nuevas recetas** con validación
- 🆕 **Gestión de categorías** dinámicas
- 🗑️ **Eliminación segura** de recetas y categorías
- 📊 **Contador automático** de recetas disponibles
- 🔄 **Compatibilidad multiplataforma** (Windows/Linux/Mac)

---

## 🛠️ Tecnologías Utilizadas

- **Python 3.x** - Lenguaje principal
- **Pathlib** - Manejo moderno de rutas y archivos
- **OS** - Operaciones del sistema operativo

---

## 📦 Instalación

### Requisitos Previos
- Python 3.6 o superior instalado en tu sistema
- Sistema operativo: Windows, Linux o macOS

### Pasos de Instalación

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/Chivan9406/RecetasPy.git
   cd RecetasPy
   ```

2. **Verifica la instalación de Python:**
   ```bash
   python --version
   ```

3. **Ejecuta el programa:**
   ```bash
   python Mis_recetas.py
   ```

---

## 🏗️ Estructura del Proyecto

```
RecetasPy/
├── 📄 Mis_recetas.py          # Script principal del administrador
├── 📄 README.md               # Documentación del proyecto
└── 📁 Recetas/                # Directorio principal de recetas
    ├── 🥩 Carnes/             # Categoría de recetas de carnes
    │   ├── Entrecot al Malbec.txt
    │   └── Matambre a la Pizza.txt
    ├── 🥗 Ensaladas/          # Categoría de ensaladas
    │   ├── Ensalada Griega.txt
    │   └── Ensalada Mediterranea.txt
    ├── 🍝 Pastas/             # Categoría de pastas
    │   ├── Canelones de Espinaca.txt
    │   └── Ravioles de Ricotta.txt
    └── 🍰 Postres/            # Categoría de postres
        ├── Compota de Manzana.txt
        └── Tarta de Frambuesa.txt
```

---

## 🎯 Funcionalidades del Sistema

### 📖 **Leer Recetas**
- Navega por categorías disponibles
- Selecciona y visualiza recetas completas
- Interfaz numerada para fácil selección

### ➕ **Crear Nuevas Recetas**
- Selecciona la categoría deseada
- Ingresa nombre y contenido de la receta
- Validación automática para evitar duplicados

### 🆕 **Gestión de Categorías**
- Crea nuevas categorías dinámicamente
- Organización automática de archivos
- Validación de nombres únicos

### 🗑️ **Eliminación Segura**
- Elimina recetas específicas por categoría
- Elimina categorías completas
- Confirmación antes de acciones destructivas

---

## 🎨 Componentes Principales

### `inicio()`
Función principal que maneja la interfaz del menú y las opciones del usuario.

```python
def inicio():
    # Limpia pantalla según el SO
    # Muestra información del sistema
    # Presenta menú interactivo
    return int(eleccion_menu)
```

### `mostrar_categorias(ruta)`
Lista todas las categorías disponibles de forma numerada.

### `leer_receta(receta)`
Muestra el contenido completo de una receta seleccionada.

### `crear_receta(ruta)` / `crear_categoria(ruta)`
Funciones para la creación de nuevos elementos con validación.

---

## 🔧 Uso del Sistema

### Ejecución Principal
```bash
python Mis_recetas.py
```

### Menú de Opciones
```
[1] - Leer receta
[2] - Crear receta nueva
[3] - Crear categoría nueva
[4] - Eliminar receta
[5] - Eliminar categoría
[6] - Terminar el programa
```

### Ejemplo de Uso
1. Ejecuta el programa
2. Selecciona opción `[1]` para leer una receta
3. Elige una categoría (ej: `[1]` para Carnes)
4. Selecciona una receta específica
5. Visualiza el contenido completo

---

## 🌟 Características Técnicas Destacadas

- **🔄 Bucle Principal Persistente:** El programa mantiene la sesión activa hasta que el usuario decide salir
- **🛡️ Validación Robusta:** Control de entrada para evitar errores y duplicados
- **📁 Gestión Dinámica de Archivos:** Uso de `pathlib` para operaciones modernas con archivos
- **🖥️ Compatibilidad Multiplataforma:** Detección automática del sistema operativo
- **🔍 Búsqueda Recursiva:** Localización automática de archivos `.txt` en subdirectorios
- **🧹 Interfaz Limpia:** Limpieza automática de pantalla para mejor experiencia

---

## 📊 Estadísticas del Proyecto

- **8 recetas incluidas** distribuidas en 4 categorías
- **Arquitectura modular** con funciones especializadas
- **Gestión completa CRUD** (Create, Read, Update, Delete)
- **Código limpio** siguiendo buenas prácticas de Python

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.

---

## 👨‍💻 Autor

**Iván** - [Chivan9406](https://github.com/Chivan9406)

¿Te gusta el proyecto? ¡Dale una ⭐ en GitHub!

---

*Desarrollado con ❤️ para amantes de la cocina y la programación*

