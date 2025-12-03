# 📱 Documentación del Prototipo UI – PelusasSpa

Este documento describe la interfaz de usuario del prototipo web desarrollado para la aplicación **PelusasSpa**, incluyendo su estructura, flujo de pantallas y capturas.

---

## 🔷 1. Tecnologías utilizadas

- **HTML5**
- **TailwindCSS CDN**
- **Google Fonts – Plus Jakarta Sans**
- **Material Symbols (Google Icons)**
- **Javascript simple para interacciones básicas**
- **Sin backend (prototipo funcional estático)**

---

## 🔷 2. Estructura del proyecto

/proyecto
├── index.html
├── iniciar_sesión/
│ └── code.html
├── registro/
│ └── code.html
├── mascotas/
│ └── agregar.html
├── citas/
│ └── agendar.html
└── docs/
├── ui_prototipo_stitch.md
├── pantalla_login.png
├── pantalla_registro.png
├── pantalla_agendar.png
├── pantalla_exito.png

yaml
Copiar código

---

## 🔷 3. Flujo del prototipo

1. **Pantalla de inicio → Registro**
2. **Registro → Iniciar sesión**
3. **Iniciar sesión → Menú principal**
4. **Menú principal → Agregar mascota**
5. **Agregar mascota → Confirmación**
6. **Menú principal → Agendar cita**
7. **Agendar cita → Mensaje de éxito**

---

## 🔷 4. Pantallas del prototipo

### 🖼️ **1. Pantalla de Registro**



Incluye:
- Nombre
- Correo
- Contraseña
- Confirmación
- Botón “Crear cuenta”
- Botón “Regresar”

---

### 🖼️ **2. Pantalla de Inicio de Sesión**



Campos:
- Correo
- Contraseña
- Iniciar sesión

---

### 🖼️ **3. Pantalla Agregar Mascota**


Formulario con:
- Nombre mascota  
- Tipo (perro, gato, etc.)  
- Raza  
- Edad  
- Dueño  
- Botón Guardar con **alerta bonita personalizada**

---

### 🖼️ **4. Pantalla Agendar Cita**


Campos:
- Mascota
- Servicio
- Fecha
- Hora

Incluye:
- Mensaje de éxito al confirmar la cita

---

### 🖼️ **5. Mensaje de éxito**



Se muestra cuando:
- Se guarda una mascota
- Se crea una cita

---
### 🖼️ **6. Listado de Mascotas**

- Muestra las mascotas disponibles
- Boton de agregar mas mascotas

### 🖼️ **7. Listado de Citas**  

-Listado de citas 
-Boton de agregar citas

### 🖼️ **8. Listado de citas para peluquero**

-Lista de citas para peluquero 


## 🔷 5. Navegación entre páginas

| Página | Va hacia |
|-------|----------|
| Registro | Iniciar sesión |
| Iniciar sesión | Página principal |
| Página principal | Agregar mascota / Agendar cita |
| Agregar mascota | Mensaje de éxito → regresar |
| Agendar cita | Mensaje de éxito |

---

## 🔷 6. Consideraciones

- Todo el prototipo es **estático** (sin base de datos).
- Funciona 100% en cualquier navegador.
- No requiere servidor, basta con **abrir los HTML**.
- Las rutas se manejan con `href="../carpeta/pagina.html"`.

---

## 🔷 7. Autora

**Lisbeth Estefanía Cale Bravo**  
Prototipo UI para la app PelusasSpa.

---
