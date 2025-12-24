# icons-looker-platform

Descripción
-----------
Repositorio con una colección de iconos y recursos pensados para integrarse en la plataforma Looker. Contiene archivos de iconos (SVG/PNG), ejemplos de uso y utilidades para exportar o previsualizar los assets.

Estructura (sugerida)
---------------------
- `icons/` — iconos en SVG/PNG
- `examples/` — ejemplos de integración y demostraciones
- `scripts/` — utilidades para generar o optimizar iconos
- `LICENSE` — fichero de licencia (añadir según corresponda)

Instalación
-----------
Clona el repositorio:

```
git clone <URL_DEL_REPOSITORIO>
cd icons-looker-platform
```

Para previsualizar los iconos localmente puedes usar un servidor estático:

- Con Python 3:

```
python -m http.server 8000
```

- Con Node (ej. `serve`):

```
npm install -g serve
serve .
```

Uso
---
- Coloca archivos SVG/PNG en la carpeta `icons/`.
- Añade ejemplos de uso en `examples/` (HTML, CSS, snippets de Looker si aplica).
- Usa los scripts en `scripts/` para optimizar o exportar formatos adicionales.

Contribuir
----------
1. Fork del repositorio.
2. Crea una rama con tu cambio: `git checkout -b feature/nombre`.
3. Haz commit de tus cambios y abre un Pull Request describiendo los cambios.

Licencia
--------
Añade un fichero `LICENSE` con la licencia que prefieras (MIT, Apache-2.0, etc.).

Contacto
--------
Abre un issue en el repositorio para reportar problemas o proponer mejoras.

---

Si quieres, puedo personalizar este README con información específica del proyecto (URL del repo, estructura real de carpetas, instrucciones de build o ejemplos concretos).