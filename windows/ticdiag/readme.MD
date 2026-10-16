# TicDiag 🔍🛠️

> **Parte da suite de ferramentas de [TIC Galicia](https://www.ticgalicia.com)**

![Static Badge](https://img.shields.io/badge/Plataforma-Windows-0078D4?style=for-the-badge&logo=windows)
![Static Badge](https://img.shields.io/badge/Mantenedor-TIC_Galicia-1E3A8A?style=for-the-badge)

**TicDiag** é unha ferramenta de diagnóstico avanzado de compoñentes e xestor do Visor de Eventos de Windows, deseñada por **TIC Galicia** para identificar rapidamente fallos de hardware, erros de controladores e problemas do sistema.

---

## 🚀 Funcionalidades Principais

- **Escaneo e Agrupación de Eventos:** 
  - Analiza rexistros clave do sistema (`System`, `Application`, `Setup`, `WHEA-Logger`, `Disk` e `Kernel-PnP`).
  - Agrupa incidencias repetidas indicando a súa frecuencia e a última data detectada.
  - Colorimetría por severidade (Errores en vermello, Advertencias en laranxa e Información en verde).
  
- **Búsqueda Web Integrada:** 
  - Con só facer dobre clic sobre calquera evento, a aplicación abre automaticamente o navegador para buscar a solución ao código de erro ou orixe.

- **Filtros e Ordenación Dinámica:** 
  - Permite filtrar en tempo real por nivel de erro e ordenar as columnas con só pulsar no encabezado.

- **Ferramentas de Reparación do Sistema:**
  - Botóns de acceso rápido para a execución directa de **SFC** (`sfc /scannow`) e **DISM** (`RestoreHealth`) sen mostrar consolas molestas.
  - Detección automática e dinámica de todas as unidades de disco conectadas (C:, D:, etc.) con botóns individuais para a comprobación de erros mediante **CHKDSK**.

- **Execución Silenciosa e Áxil:**
  - Consultas asíncronas para non bloquear a interface gráfica en ningún momento.
  - Execución de procesos en segundo plano sen pestanexo de consolas PowerShell.

---

## 📥 Descarga Directa

Podes obter a última versión lista para usar aquí:

👉 **[Descargar ticdiag.exe](https://github.com/ticgalicia/ferramentas/raw/main/windows/ticdiag/ticdiag.exe)**

---

## 🛠️ Instrucións de Uso

1. Descarga o executable `ticdiag.exe`.
2. Executa a aplicación **con permisos de Administrador** para permitir o acceso aos rexistros protexidos e ás ferramentas de reparación (SFC, DISM e CHKDSK).
3. Pulsa en **Escanear Eventos** para analizar o estado do sistema ou utiliza os botóns de reparación directa.

---

## 🏢 Sobre TIC Galicia

TIC Galicia é un grupo de profesionais de varios sectores que traballan para a dinamización tecnolóxica de Galicia:

🌐 [www.ticgalicia.com](https://www.ticgalicia.com)

---

*Desenvolvido con ❤️ polo equipo de TIC Galicia.*
