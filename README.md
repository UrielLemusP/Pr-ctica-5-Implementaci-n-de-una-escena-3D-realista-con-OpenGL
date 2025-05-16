# Super Importante: 
Practica_5.zip es el codigo con la carpeta de texturas. Al darle click no aparecera nada, le tienes que dar en View Raw o Ver en bruto para que se descargue la carpeta. :D

# Visualizador 3D con PyOpenGL y Pygame

Este proyecto permite visualizar e interactuar con diferentes figuras 3D como cubo, pirámide, esfera, cilindro y superelipsoide, usando **Python**, **Pygame** y **PyOpenGL**. Las figuras pueden ser rotadas, escaladas, trasladadas, texturizadas e iluminadas dinámicamente mediante el teclado.

---

## ✨ Características

- Visualización de 5 figuras 3D: cubo, pirámide, esfera, cilindro, superelipsoide.
- Transformaciones: traslación, rotación y escalado.
- Opciones de iluminación y texturizado.
- Cambios entre proyección perspectiva y ortogonal.
- Interfaz interactiva desde consola y teclado.

---

## 📦 Dependencias

Instálalas con pip:
pip install pygame PyOpenGL PyOpenGL_accelerate

📁 Estructura del Proyecto
Practica_5/
├── proyecto_3D.py         # Código principal del visualizador
├── texturas/
│   ├── cubo.jpg
│   ├── piramide.jpg
│   ├── esfera.jpg
│   ├── cilindro.jpg
│   └── superelipsoide.jpg
└── README.md
⚠️ Asegúrate de colocar las texturas en la carpeta texturas/ con los nombres indicados. Son necesarias si usa_textura=True.

▶️ ¿Cómo ejecutar?
Ejecuta el programa desde la terminal:

python proyecto_3D.py
🎮 Controles del teclado
Menú principal
Presiona una tecla numérica para seleccionar una figura:

1: Cubo

2: Pirámide

3: Esfera

4: Cilindro

5: Superelipsoide

6: Salir

Interacción con la figura
Transformaciones:

← ↑ ↓ →: Mover figura en X/Y

W / S: Rotar sobre eje X

A / D: Rotar sobre eje Y

Q / E: Rotar sobre eje Z

+ / -: Escalar figura

Opciones visuales:

T: Activar/desactivar texturas

L: Activar/desactivar iluminación

P: Alternar entre proyección perspectiva y ortogonal

J / K: Mover fuente de luz en X

ESC: Volver al menú principal

⚙️ Notas técnicas
Las figuras usan OpenGL para renderizado.

Las transformaciones se aplican con glTranslatef, glRotatef, glScalef.

Las texturas deben estar en formato .jpg y llamarse como la figura (cubo.jpg, etc.).

El superelipsoide se genera con una fórmula paramétrica usando GL_POINTS.

👤 Autor
Desarrollado como parte de un proyecto educativo de visualización 3D en Python con OpenGL (Benemerita Universidad Autonoma de Puebla).

📄 Licencia
Este proyecto está licenciado bajo la MIT License.
