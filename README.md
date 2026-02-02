# 🛡️ Infraestructura de Red y Seguridad Ofensiva - Grupo 6

Este proyecto documenta el diseño, implementación y análisis de seguridad de una infraestructura de red segmentada, desarrollado para la asignatura de **Criptografía y Seguridad de la Información**.

## 📖 Descripción del Proyecto

El objetivo principal es simular un entorno empresarial realista con segmentación de red y ejecutar pruebas de seguridad ofensiva (Ethical Hacking) en un entorno controlado.

### Infraestructura Implementada
- **Redes Segmentadas (VLANs)**:
  - **Red X1**: Pruebas de seguridad (Kali Linux + Access Point).
  - **Red X2**: Servidores (Windows Server).
  - **Red X3**: Usuarios finales (PCGX).
- **Interconexión**: Router y Switch Cisco configurados con enrutamiento Inter-VLAN (IEEE 802.1Q).
- **Direccionamiento**: Privado (`192.168.X.0/24`) y asignación dinámica por DHCP.

### ⚔️ Pruebas de Seguridad (Kali Linux)
El proyecto incluye la documentación detallada de las siguientes actividades ofensivas:
1.  **Monitoreo de Red**: Análisis de tráfico y detección de dispositivos.
2.  **Ataque DoS**: Denegación de servicio controlada.
3.  **Ataque Wireless**: Compromiso de credenciales en redes inalámbricas.
4.  **Ataque Avanzado/Opcional**: Explotación de vulnerabilidades específicas.

## 🗂 Estructura del Documento

El código fuente LaTeX está modularizado en el directorio `pages/`:

| Archivo | Contenido |
| :--- | :--- |
| `configuracion_rack.tex` | Configuración física y lógica de equipos Cisco. |
| `entorno.tex` | Descripción del escenario y topología. |
| `ataque_*.tex` | Documentación técnica de cada vector de ataque. |
| `resumen.tex` | Visión general del proyecto. |

## 🚀 Cómo contribuir

Si deseas proponer mejoras a la documentación:

1.  Lee nuestra [Guía de Contribución](CONTRIBUTING.md).
2.  Las **imágenes** nuevas deben ir obligatoriamente en `assets/images`.
3.  Al enviar un **Pull Request**, por favor detalla claramente los cambios realizados en la descripción.



1. Clona el repositorio:

```bash
git clone --branch project-final-crypto --single-branch https://github.com/Dennis290699/Model-document-structure-LaTeX.git
```

2. Abre y edita los archivos dentro del directorio `pages/` para construir tu documento.
3. Compila `main.tex` con tu herramienta LaTeX preferida.

> Esta plantilla está diseñada para ser **ligera, ordenada y profesional**, lista para adaptarse a cualquier tipo de informe, artículo o trabajo universitario.
