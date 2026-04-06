## 🛠️ KIT DE HERRAMIENTAS | SECCIÓN 2

### 🔑 TestDisk & PhotoRec: La suite esencial de recuperación y diagnóstico de discos

![release](https://img.shields.io/github/v/release/cgsecurity/testdisk?label=release%20v7.2&color=blue) ![Plataformas](https://img.shields.io/badge/Plataformas-Windows%20%7C%20Linux%20%7C%20macOS-blue) ![Licencia](https://img.shields.io/badge/Licencia-GPLv2-green)

TestDisk & PhotoRec es una potente suite de herramientas de código abierto líder en el sector, esencial para el diagnóstico y la recuperación de discos. TestDisk se especializa en la recuperación de particiones de disco perdidas y la reparación de sectores de arranque. PhotoRec se centra en la recuperación de archivos borrados o de discos con fallos físicos graves.

🔗 [Sitio Web Oficial](https://www.cgsecurity.org/wiki/TestDisk_ES) • 💻 [Código Fuente](https://github.com/cgsecurity/testdisk) • 📖 [Documentación](https://www.cgsecurity.org/wiki/PhotoRec_ES)

---

### 💎 ¿Por qué TestDisk & PhotoRec es la herramienta definitiva de disco?

> **[!] Important**
> **Prevención de Desastres:** TestDisk es fundamental para reparar tablas de particiones dañadas y sectores de arranque, lo que permite que el sistema operativo vuelva a arrancar. PhotoRec ignora el sistema de archivos para recuperar archivos directamente de los datos brutos, ideal para discos con fallos físicos graves.

| ⚡ RECUPERACIÓN | 🛠️ REPARACIÓN | 🛡️ FORENSE |
| :--- | :--- | :--- |
| Recupera particiones NTFS, FAT, ext2/ext3/ext4 perdidas. | Repara tablas de particiones dañadas y sectores de arranque. | Herramienta potente para análisis forense de datos. |

---

### 🛠️ Capacidades Técnicas Resumidas

| Función | Descripción Técnica |
| :--- | :--- |
| **Multi-Plataforma** | Funciona en casi todos los sistemas operativos comunes (Windows, Linux, macOS, BSD, etc.). |
| **Soporte de Sistemas de Archivos** | Cubre casi todos los sistemas de archivos comunes (NTFS, FAT, ext2/3/4, HFS+, Btrfs, etc.). |
| **Recuperación de Archivos** | PhotoRec soporta cientos de formatos de archivo para la recuperación de medios digitales. |
| **Análisis de Disco** | Capacidad para analizar y reportar sobre la salud de la tabla de particiones del disco. |

---

### 🚀 Guía de Despliegue Rápido

1.  **Ejecución:** Lanza `testdisk` o `photorec` con privilegios de administrador.
2.  **Selección de Disco:** Elige la unidad física que deseas analizar de la lista proporcionada.
3.  **Tipo de Partición:** Selecciona el tipo de tabla de particiones del disco (ej: Intel para MBR o EFI GPT para sistemas modernos).
4.  **Análisis:** Permite que la herramienta busque particiones perdidas o archivos borrados.
5.  **Guardado:** Escribe la nueva tabla de particiones o copia los archivos recuperados a un disco seguro.

---

### 📥 Recursos de Descarga Directa

| Sistema Operativo | Enlace de Instalación |
| :--- | :--- |
| 🪟 Windows | `testdisk-7.2.win.zip` |
| 🐧 Linux | `apt install testdisk` / `pacman -S testdisk` |
| 🍎 macOS | `brew install testdisk` |

---

> **Tip**
> ⚠️ **Recordatorio Crítico:** Cuando recuperes archivos con PhotoRec, asegúrate de guardarlos en un disco físico DIFERENTE al que estás analizando. De lo contrario, podrías sobrescribir los datos que intentas recuperar.
