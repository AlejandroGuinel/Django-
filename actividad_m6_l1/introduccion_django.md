# Introducción a Django

## 1. ¿Qué es Django?

### ¿Qué tipo de framework es Django?

Django es un framework de desarrollo web de alto nivel creado en Python. Está diseñado para facilitar y acelerar la creación de aplicaciones web seguras, escalables y mantenibles.

Es un framework basado en el patrón MTV (Model - Template - View), inspirado en el modelo MVC.

### ¿Qué tipo de aplicaciones permite construir?

Django permite desarrollar distintos tipos de aplicaciones web, por ejemplo:

* Sistemas de gestión empresarial
* Tiendas online
* Redes sociales
* Blogs y portales de noticias
* APIs y servicios web
* Plataformas educativas
* Sistemas administrativos

### Ventajas de usar Django sobre Python puro para desarrollo web

1. **Desarrollo más rápido**
   Django incluye herramientas listas para usar, como autenticación, panel administrativo y manejo de bases de datos.

2. **Mayor seguridad**
   Protege automáticamente contra ataques comunes como SQL Injection y CSRF.

3. **Organización del proyecto**
   Utiliza una estructura clara que facilita el mantenimiento del código.

4. **Escalabilidad**
   Permite desarrollar proyectos pequeños y grandes de manera eficiente.

5. **Comunidad y documentación**
   Tiene una gran comunidad y abundante documentación oficial.

---

# 2. Entornos virtuales en Python

### ¿Qué es un entorno virtual en Python y para qué sirve?

Un entorno virtual es un espacio aislado dentro de Python que permite instalar librerías y dependencias sin afectar otros proyectos del sistema.

Sirve para mantener organizadas las dependencias de cada proyecto y evitar conflictos entre versiones.

### ¿Qué ventajas tiene crear un entorno virtual para un proyecto Django?

* Evita conflictos entre librerías.
* Permite trabajar con diferentes versiones de Django.
* Mantiene el proyecto más ordenado.
* Facilita compartir el proyecto con otros desarrolladores.
* Mejora la portabilidad del proyecto.

### Explica en tus palabras qué hace el siguiente comando:

```bash
python -m venv env
```

Este comando crea un entorno virtual llamado `env` usando el módulo `venv` de Python. Dentro de esa carpeta se almacenan los archivos necesarios para ejecutar un entorno independiente del sistema principal.

---

# 3. Estructura y diseño de Django

## ¿Qué es el patrón MVC y cómo se aplica en Django (MTV)?

El patrón MVC (Model - View - Controller) es una forma de organizar aplicaciones separando la lógica, la interfaz y el control de datos.

Django utiliza una variante llamada MTV (Model - Template - View).

| Concepto tradicional (MVC) | Nombre en Django (MTV) | Función                                      |
| -------------------------- | ---------------------- | -------------------------------------------- |
| Model                      | Model                  | Gestiona los datos y la base de datos        |
| View                       | Template               | Muestra la interfaz y el contenido visual    |
| Controller                 | View                   | Contiene la lógica y controla las peticiones |

## ¿Qué es el enrutador de Django y qué papel cumple en una aplicación web?

El enrutador de Django funciona mediante el archivo `urls.py`. Su función es dirigir las solicitudes del usuario hacia la vista correspondiente.

Por ejemplo, cuando un usuario entra a una URL específica, Django revisa las rutas definidas y ejecuta la función adecuada para responder a esa petición.

---

# 4. Principios del desarrollo con Django

## ¿Qué significa el principio DRY ("Don't Repeat Yourself") y cómo lo aplica Django?

El principio DRY significa “No te repitas”. Busca evitar duplicar código o información innecesariamente.

Django aplica este principio reutilizando componentes como modelos, templates y formularios, permitiendo escribir menos código y mantenerlo más fácilmente.

## ¿Qué significa que Django tenga una “estructura flexible y minimalista”?

Significa que Django entrega una estructura organizada pero adaptable. El desarrollador puede modificar o agregar componentes según las necesidades del proyecto sin perder orden ni simplicidad.

## ¿Qué son los Templates en Django y qué rol cumplen en la renderización de contenido?

Los Templates son archivos que contienen el diseño visual de una página web, normalmente escritos en HTML con sintaxis especial de Django.

Su función es mostrar información dinámica al usuario, permitiendo separar la lógica del programa de la presentación visual de la aplicación.
