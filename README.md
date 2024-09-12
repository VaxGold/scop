# OpenGL .OBJ Model Renderer

Este proyecto es una aplicación simple que carga y renderiza modelos 3D en formato `.obj` utilizando **OpenGL**. El objetivo principal es demostrar cómo cargar archivos `.obj`, procesar los datos de vértices y renderizarlos en una ventana OpenGL.

## Características

- Carga de archivos `.obj` para representar modelos 3D.
- Renderizado de geometría utilizando **VBO** (Vertex Buffer Objects), **VAO** (Vertex Array Objects), y **EBO** (Element Buffer Objects).
- Aplicación de shaders para manejar transformaciones y colorear el modelo.
- Soporte para transformaciones de cámara (modelo, vista, proyección).

## Requisitos

Para ejecutar este proyecto, necesitas las siguientes dependencias:

- [GLFW](https://www.glfw.org/) (para la creación de ventanas y manejo de entradas).
- [GLAD](https://glad.dav1d.de/) (para la carga de funciones de OpenGL).
- [GLM](https://github.com/g-truc/glm) (para manejar matemáticas 3D).
- Un compilador compatible con **C++11** o superior.

Opcionalmente, puedes usar una librería como [Assimp](http://www.assimp.org/) para manejar la carga de modelos `.obj`, pero en este ejemplo se describe cómo hacerlo manualmente.

## Instalación y uso

1. **Clonar el repositorio**
2. **En la carpeta raíz ejecutar `make` + ruta del archivo `.obj`**


##

<p align="center">
  <img src="https://w7.pngwing.com/pngs/1014/68/png-transparent-opengl-es-khronos-group-webgl-vulkan-2-joints-logo-blue-3d-computer-graphics-text.png" alt="OpenGL Logo" width="200"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/1/18/ISO_C%2B%2B_Logo.svg" alt="OpenGL Logo" width="200"/>
</p>
