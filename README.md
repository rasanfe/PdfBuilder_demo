# PdfBuilder_demo 📄

![PowerBuilder](https://img.shields.io/badge/PowerBuilder-2025-orange?style=flat-square&logo=appveyor&logoColor=white)
![Tecnología](https://img.shields.io/badge/PDFBuilder-PDF%20nativo-red?style=flat-square&logo=adobeacrobatreader&logoColor=white)
![Evento](https://img.shields.io/badge/PowerTalks-2024-blueviolet?style=flat-square)
![Blog](https://img.shields.io/badge/blog-rsrsystem-FF5722?style=flat-square&logo=blogger&logoColor=white)

> Manipular PDFs desde PowerBuilder sin librerías externas, usando el objeto **PDFBuilder** que llegó con PowerBuilder 2022 R2. Una auténtica bestia para el día a día.

---

## 📋 ¿Qué es esto?

Hace tiempo, preparando mi charla para el evento **PowerTalks 2024**, me puse a explorar una de esas funcionalidades que pasan desapercibidas y que, sin embargo, te ahorran muchísimo: el objeto **`PDFBuilder`** que Appeon incorporó en **PowerBuilder 2022 R2**.

Hasta entonces, para hacer cosas serias con PDFs en PowerBuilder casi siempre tocaba tirar de componentes de terceros. Con `PDFBuilder` tienes un montón de operaciones **directamente en el lenguaje**, sin frameworks ni instalaciones. Esto es un ejemplo ejecutable que recorre las operaciones más útiles.

## ✨ Cómo funciona

El proyecto es una galería de demos: cada botón ejecuta una operación de `PDFBuilder` y genera su PDF de salida (los tenéis incluidos en el repo para que veáis el resultado sin compilar nada). Lo que cubre:

| Demo | Qué hace |
|------|----------|
| **Import** | Importa/lee un PDF existente. |
| **Split** | Divide un PDF en varios. |
| **Merge** | Une varios PDFs en uno. |
| **WaterMark (imagen / texto)** | Añade marcas de agua, con imagen o con texto. |
| **AttachFile** | Adjunta ficheros dentro del PDF. |
| **Compress** | Comprime el PDF para reducir su tamaño. |
| **AddPage / InsertPage** | Añade o inserta páginas. |
| **AddImageQR** | Inserta una imagen de código **QR**. |
| **Settings** | Juega con los ajustes de generación. |

En la carpeta vienen también los recursos de ejemplo (imágenes, documentos `documentos/`, el CSV del gráfico, el QR…) y los **PDF de resultado numerados** para que compares de un vistazo.

## 🛠️ Requisitos

- **PowerBuilder 2025** (compilado con el Runtime `25.0.0.3711`). El objeto `PDFBuilder` está disponible desde **2022 R2** en adelante.
- **Windows 10/11**.
- Sin librerías de terceros: clonáis y compila.

## ▶️ Cómo probarlo

1. Clona el repositorio (viene **en modo solución**).
2. Abre `pdfbuilder_demo.pbsln` desde el IDE de PowerBuilder.
3. Compila y ejecuta (o lanza directamente el `pdfbuilder_demo.exe`).
4. Pulsa cada botón y abre el PDF generado para ver el resultado.

## 🔗 Repo PowerBuilder

Tenéis el ejemplo publicado en modo solución aquí:
👉 <https://github.com/rasanfe/PdfBuilder_demo>

## 🙌 Créditos

Este ejemplo está **basado en la presentación de Bruce Armstrong** titulada *"What's New in PowerBuilder 2022 R2 – Part 1"*:
- 🎥 <https://www.youtube.com/watch?v=Xv24Iz_M8rQ&t=1672s>

**Adaptado por Ramón San Félix** para su intervención del **jueves 8 de febrero de 2024, 19:00 (hora España)** en el evento **PowerTalks 2024**.

---

> ¡Nos vemos en el próximo artículo! Y recuerda: en PowerBuilder, los límites solo están en nuestra imaginación. 🚀

📨 **Blog:** <https://rsrsystem.blogspot.com/>
