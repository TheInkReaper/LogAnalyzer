<div align="center">

# 🔍 Log Analyzer

**Herramienta de diagnóstico para analizar archivos de log y encontrar errores rápidamente.**

[![GitHub Pages](https://img.shields.io/badge/Demo-Online-blue?style=for-the-badge&logo=github)](https://theinkreaper.github.io/LogAnalyzer/)
[![Version](https://img.shields.io/badge/Versión-2.0-green?style=for-the-badge)](https://github.com/TheInkReaper/LogAnalyzer/releases)
[![License](https://img.shields.io/badge/Licencia-MIT-yellow?style=for-the-badge)](LICENSE)

<img src="https://raw.githubusercontent.com/TheInkReaper/LogAnalyzer/main/preview.png" alt="Preview de Log Analyzer" width="700">

</div>

---

## 📋 Descripción

Log Analyzer es una herramienta web que te ayuda a entender y solucionar problemas en tu PC analizando archivos de log. Detecta automáticamente errores, warnings y códigos de error, y te proporciona enlaces directos para buscar soluciones.

**Ideal para:**
- 🎮 Crashes de juegos
- 💻 Errores de Windows Update
- 🔧 Problemas de drivers
- 📦 Fallos de instalación

---

## 🚀 Cómo Usar

### Opción 1: Online (Recomendado)

Accede directamente desde tu navegador, sin descargar nada:

**👉 [theinkreaper.github.io/LogAnalyzer](https://theinkreaper.github.io/LogAnalyzer/)**

### Opción 2: Offline

Descarga el archivo HTML para usar sin conexión:

1. Ve a la sección [Releases](https://github.com/TheInkReaper/LogAnalyzer/releases)
2. Descarga `LogAnalyzer.html`
3. Ábrelo con cualquier navegador

---

## ✨ Características

| Función | Descripción |
|---------|-------------|
| **Análisis instantáneo** | Arrastra un archivo o pega texto para analizar al momento |
| **Detección inteligente** | Identifica códigos HRESULT (`0x8...`), NTSTATUS (`0xc...`), excepciones y más |
| **Búsqueda integrada** | Encuentra texto específico dentro del log con `Ctrl+F` |
| **Enlaces contextuales** | Genera búsquedas que incluyen el contexto del programa para resultados precisos |
| **Exportar análisis** | Guarda un informe con el resumen de errores encontrados |
| **Guías incluidas** | Aprende dónde encontrar logs de Windows, juegos y aplicaciones |
| **100% local** | Tu información nunca sale de tu navegador |

---

## 🎯 Tipos de Errores Detectados

```
✓ Códigos HRESULT     → 0x80070005, 0x80004005, etc.
✓ Códigos NTSTATUS    → 0xc0000005, 0xc0000135, etc.
✓ Excepciones         → ACCESS_VIOLATION, EXCEPTION_*, STATUS_*
✓ Errores COM/DirectX → E_OUTOFMEMORY, E_FAIL, E_INVALIDARG
✓ Códigos numéricos   → Error 1603, Error code 5
✓ Stack traces        → at Module.Function() in File.cpp:123
✓ Multilingüe         → error, fail, fallo, fehler, erreur
```

---

## 📁 Archivo de Ejemplo

¿Quieres probar la herramienta? Descarga el archivo de ejemplo:

1. Ve a [Releases](https://github.com/TheInkReaper/LogAnalyzer/releases)
2. Descarga `ejemplo_gaming_log.txt`
3. Arrástralo al analizador

Este archivo contiene ejemplos de todos los tipos de errores que detecta la herramienta.

---

## 🛠️ Otras Herramientas

Echa un vistazo a mis otros proyectos de mantenimiento y diagnóstico para Windows:

**👉 [github.com/TheInkReaper](https://github.com/TheInkReaper)**

---

## 📝 Changelog

### v2.0
- ✨ Nueva interfaz rediseñada
- 🔍 Búsqueda dentro del log (`Ctrl+F`)
- 📊 Estadísticas de análisis (líneas, errores, warnings)
- 💾 Exportar informe de análisis
- 🎯 Detección mejorada de códigos NTSTATUS y errores COM
- ♿ Mejoras de accesibilidad
- 🐛 Correcciones de bugs

### v1.0
- 🎉 Lanzamiento inicial

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Puedes usarlo, modificarlo y distribuirlo libremente.

---

<div align="center">

**Creado con ☕ por [TheInkReaper](https://github.com/TheInkReaper)**

*¿Te ha sido útil? ¡Dale una ⭐ al repositorio!*

</div>
