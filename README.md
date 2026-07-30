# Grupo-Ademass

Landing page / plataforma web de la comunidad **Ademass**, desarrollada como proyecto colaborativo usando Git, GitHub y Gitflow como metodología de trabajo en equipo.

## 📋 Descripción del proyecto

<!-- Reemplaza esta sección con una descripción breve del proyecto: qué es, qué secciones tiene (Discord, Pilares de la Comunidad, etc.) y su propósito. -->

Este proyecto reúne las distintas secciones de la página de Ademass, incluyendo:

- Sección de bienvenida a Discord
- Sección "Los Pilares de Nuestra Comunidad"
- *(agregar más secciones a medida que se desarrollen)*

## 👥 Integrantes del equipo

| Nombre | Rol | GitHub |
|---|---|---|
| Juan Pablo Serna | Líder | [@juanpabloM-07](https://github.com/juanpabloM-07) |
| Juan José Mazo | Desarrollador/a | [@juanjosma241215-stack](https://github.com/juanjosma241215-stack) |
| Juan José Mira | Desarrollador/a | [@juanjomira12](https://github.com/juanjomira12) |
| Sebastián Lopez | Desarrollador/a | [@Sebastian787-max](https://github.com/Sebastian787-max) |
| Brayan Franco Gomez | Desarrollador/a | [@bry-07f-g](https://github.com/bry-07f-g) |

## 🛠️ Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript
<!-- Agrega o quita según lo que realmente uses -->

## 🌿 Flujo de trabajo (Gitflow)

Este proyecto sigue una metodología de trabajo colaborativo basada en Gitflow:

- **`main`** → rama de producción, contiene el proyecto estable.
- **`develop`** → rama de integración, donde se reúne el trabajo de todo el equipo.
- **`feature/nombre-rama`** → ramas temporales individuales, donde cada integrante desarrolla su parte.

### Reglas del equipo

1. Después de crear la rama `develop` en local, todos deben hacer `pull` a `develop`.
2. Antes de hacer `push` a la rama temporal, hay que hacer `pull` a `develop`.
3. Toda Pull Request se crea desde la rama temporal (`feature/...`) hacia `develop`, **nunca** directo a `main`.
4. Solo el líder del equipo aprueba, hace *merge* de las PR y elimina las ramas temporales tras integrarlas.
5. Al finalizar el sprint, el líder crea la PR de `develop` hacia `main` (sin eliminar `develop`).

## 🚀 Cómo clonar y trabajar en el proyecto

```bash
# 1. Clonar el repositorio
git clone https://github.com/juanpabloM-07/Grupo-Ademass.git
cd Grupo-Ademass

# 2. Crear y posicionarse en la rama develop
git checkout -b develop
git pull origin develop

# 3. Crear tu rama temporal de trabajo
git checkout -b feature/nombre-de-tu-rama

# 4. Al terminar tu desarrollo
git add .
git commit -m "feat: descripción del cambio"
git pull origin develop
git push -u origin feature/nombre-de-tu-rama
```

Luego crea tu Pull Request en GitHub: **base: `develop`** ← **compare: `feature/nombre-de-tu-rama`**.

## 📁 Estructura del proyecto

```
Grupo-Ademass/
├── public/
├── src/
├── Discord/
│   └── index.html
├── assets/
│   └── img/
├── .gitignore
└── index.html
```

## 📄 Licencia

<!-- Agrega la licencia si aplica, por ejemplo MIT -->
