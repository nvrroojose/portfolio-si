# Herramientas Ofimáticas

Documentación sobre las principales suites ofimáticas multiplataforma, sus formatos nativos y su instalación automatizada mediante gestor de paquetes.

## Comparativa de suites ofimáticas

| Suite | Licencia | Formatos nativos | Sistemas soportados |
| :--- | :--- | :--- | :--- |
| **LibreOffice** | MPL 2.0 (Libre) | `.odt`, `.ods`, `.odp` | Windows, Linux, macOS |
| **Microsoft 365** | Propietaria | `.docx`, `.xlsx`, `.pptx` | Windows, macOS, Web |
| **OnlyOffice** | AGPL v3 (Libre) | `.docx`, `.xlsx`, `.pptx` | Windows, Linux, macOS |

## Instalación por terminal en Linux

Para desplegar **LibreOffice** completo con paquete de idioma en español desde la terminal en sistemas Debian/Ubuntu:

```bash
sudo apt update
sudo apt install -y libreoffice libreoffice-l10n-es