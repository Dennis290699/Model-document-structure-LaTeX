# 📄 Plantilla Base de Documento en LaTeX

Este repositorio contiene una **estructura base modular en LaTeX**, pensada para facilitar la creación de documentos académicos o técnicos en español. Está diseñada para ser fácilmente modificable y extensible según las necesidades del proyecto.

## 🧱 Características principales

- Configuración completa de:
  - Márgenes y formato de página (`geometry`)
  - Encabezados y pies de página (`fancyhdr`)
  - Índice con estilo personalizado (`tocloft`)
  - Títulos jerarquizados (`titlesec`)
  - Estilo para código fuente (`listings`)
- Soporte para idioma español y codificación UTF-8
- Estructura por módulos (`\input` / `\include`)
- Compatible con Overleaf, TeX Live, MikTeX, etc.

## 🗂 Estructura del repositorio

```
Model-document-structure-LaTeX/
├── pages/
│   ├── portada.tex
│   ├── resumen.tex
│   ├── introduccion.tex
│   ├── conclusiones.tex
│   ├── bibliografia.tex
│   └── anexos.tex
├── assets/
│   └── icons/ (para logotipos u otras imágenes)
├── main.tex
```

## 🚀 Cómo usar

1. Clona el repositorio:

```bash
git clone --branch Aplicaciones-Criptograficas --single-branch https://github.com/Dennis290699/Model-document-structure-LaTeX.git
```

2. Abre y edita los archivos dentro del directorio `pages/` para construir tu documento.
3. Compila `main.tex` con tu herramienta LaTeX preferida.

> Esta plantilla está diseñada para ser **ligera, ordenada y profesional**, lista para adaptarse a cualquier tipo de informe, artículo o trabajo universitario.
