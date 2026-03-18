```
                            ██████╗ ██╗ █████╗ ██████╗ ██╗      ██████╗ 
                            ██╔══██╗██║██╔══██╗██╔══██╗██║     ██╔═══██╗
                            ██║  ██║██║███████║██████╔╝██║     ██║   ██║
                            ██║  ██║██║██╔══██║██╔══██╗██║     ██║   ██║
                            ██████╔╝██║██║  ██║██████╔╝███████╗╚██████╔╝
                            ╚═════╝ ╚═╝╚═╝  ╚═╝╚═════╝ ╚══════╝ ╚═════╝ 
```

![Project Diablo](https://github.com/ByRafaelSystem/Project-Diablo/blob/main/IMG_20260317_235340.jpg?raw=true)

<div align="center">

# 😈 Project Diablo

### By\_Rafael System

**Motor de rendimiento avanzado para Android — Performance Engine**

[![Version](https://img.shields.io/badge/Versión-v1.3-red?style=flat-square)](https://github.com/ByRafaelSystem/Project-Diablo/releases)
[![Android](https://img.shields.io/badge/Android-9%2B-green?style=flat-square)](https://github.com/ByRafaelSystem/Project-Diablo)
[![Root](https://img.shields.io/badge/Root-Magisk%20%7C%20KSU%20%7C%20APatch-blue?style=flat-square)](https://github.com/ByRafaelSystem/Project-Diablo)
[![Chips](https://img.shields.io/badge/Chips-MTK%20%7C%20SD%20%7C%20Exynos%20%7C%20Tensor%20%7C%20más-purple?style=flat-square)](https://github.com/ByRafaelSystem/Project-Diablo)
[![License](https://img.shields.io/badge/License-Apache%202.0-orange?style=flat-square)](https://github.com/ByRafaelSystem/Project-Diablo/blob/main/LICENSE)
[![Telegram](https://img.shields.io/badge/Telegram-Canal%20Oficial-blue?style=flat-square&logo=telegram)](https://t.me/proyect_diablo)

</div>

---

## 🌍 Idiomas / Languages

- 🇪🇸 [Español](#español)
- 🇺🇸 [English](#english)
- 🇧🇷 [Português](#português)
- 🇮🇩 [Indonesia](#indonesia)
- 🇷🇺 [Русский](#русский)

---

## 🇪🇸 Español

### ¿Qué es Project Diablo?

Project Diablo es un motor de rendimiento avanzado que optimiza CPU, GPU, memoria y touch de tu Android para maximizar FPS y reducir lag en juegos. Detecta automáticamente tu chipset al instalar y aplica tweaks específicos para cada fabricante.

A partir de la **v1.3**, incluye **DiabloAI** — un motor de detección automática que aplica el modo correcto según lo que estés haciendo: gaming, cargando, idle o pantalla apagada. Se controla desde el **KSU WebUI**, la interfaz gráfica integrada en KernelSU.

---

### ✨ Características

- 😈 **4 modos de rendimiento** — Performance · Balance · Battery · Gaming Pro
- 🤖 **DiabloAI** — Detección automática de contexto: gaming · balance · idle · carga
- 🔥 **CPU Engine** — Governor dinámico por chip: `sugov_ext` MTK · `schedutil` Snapdragon · `performance` Exynos
- 🎮 **GPU Engine** — Frecuencia máxima con anti-reversión, soporte `gpufreqv2` y legacy MTK, Mali dinámico
- 👆 **Touch Profiles** — Normal · Gaming 1000Hz · iPhone Style · Sistema
- 🎮 **Gamelist** — 522+ juegos reconocidos para activación automática de Gaming Pro
- ⚡ **FastCharge** — Carga más rápida con protección térmica automática
- 🧠 **Gaming Keeper** — Combate las reversiones de HyperOS cada 5 segundos en modo Gaming Pro
- 🌐 **Network Boost** — TCP optimizado y latencia reducida
- 🎨 **KSU WebUI** — Panel de control completo, sin apps externas
- 🔍 **Detección automática de chipset** — via sysfs + getprop, guardada para próximos boots

---

### 😈 Modos disponibles

| Modo | CPU | GPU | Ideal para |
|------|-----|-----|------------|
| ⚡ Performance | Governor máximo | Frecuencia máxima | Rendimiento sostenido |
| ⚖️ Balance | Governor inteligente | Frecuencia media | Uso diario con buena duración |
| 🔋 Battery | Ahorro agresivo | Frecuencia mínima | Máxima autonomía |
| 😈 Gaming Pro | Máximo + anti-reversión | Máximo + keeper | Juegos competitivos |

---

### 🤖 DiabloAI — Modo Automático

DiabloAI es el motor de inteligencia del módulo. Cuando está activado, decide el modo automáticamente:

| Situación detectada | Modo aplicado |
|---------------------|---------------|
| Juego de la gamelist en ejecución | 😈 Gaming Pro |
| Pantalla apagada | 🔋 Battery |
| Cargando | ⚖️ Balance |
| Uso normal activo | ⚖️ Balance |
| Sin actividad por 5 minutos | 🔋 Battery |

> **Importante:** cuando DiabloAI está **activado**, los botones de modo del WebUI quedan en modo informativo — el AI tiene el control. Para aplicar un modo manualmente, desactivá DiabloAI primero.

---

### 🔧 Chipsets soportados

| Chipset | Soporte | Detalles |
|---------|---------|---------- |
| MediaTek (MTK) | ✅ Máximo | `sugov_ext` · `gpufreqv2` · `dvfsrc` · `FPSGO` · Mali dinámico |
| Snapdragon (QCOM) | ✅ Completo | `schedutil` · DCVS bus boost · KGSL GPU |
| Exynos (Samsung) | ✅ Completo | `performance` governor · GPU devfreq |
| Google Tensor | ✅ Completo | Detección via sysfs |
| Unisoc | ✅ Base | Tweaks genéricos CPU/GPU |
| Kirin (Huawei) | ✅ Base | Tweaks genéricos CPU/GPU |

---

### 📱 Compatibilidad de dispositivos

| Dispositivo | Compatibilidad | Notas |
|-------------|----------------|-------|
| Xiaomi / Redmi / POCO | ✅ Máxima | Optimizado para HyperOS 2 · Gaming Keeper activo |
| Samsung | ✅ Parcial | Exynos soportado · Sin tweaks OneUI específicos |
| OnePlus / OPPO | ✅ Parcial | Sin tweaks ColorOS específicos |
| Google Pixel | ✅ Parcial | Tensor soportado |
| Otros Android 9+ | ✅ Base | Tweaks genéricos activos |
| **Helio G99 (MTK)** | ✅ **Máxima** | Nodos verificados en hardware real |

---

### ⚙️ Gestores de root compatibles

| Gestor | Versión mínima | Estado |
|--------|----------------|--------|
| Magisk | v20.4+ | ✅ Soportado |
| KernelSU (KSU) | Cualquiera | ✅ Soportado + WebUI |
| APatch | Cualquiera | ✅ Soportado |

---

### 🖥️ KSU WebUI — Panel de Control

Project Diablo incluye una interfaz gráfica completa integrada con **KernelSU WebUI**. No necesitás ninguna app externa.

**¿Cómo acceder?**
1. Abrí KernelSU
2. Tocá el módulo Project Diablo
3. Tocá **Abrir WebUI**

**Qué podés hacer desde el WebUI:**

| Sección | Funciones |
|---------|-----------|
| 😈 Inicio | Estado del sistema · Toggle DiabloAI · Gamelist · Modos |
| 👆 Touch | Perfil de touch · Extras (iPhone scroll · Gaming Mode · Sin animaciones) |
| ⚙️ Ajustes | Zeta · AmeRender · FastCharge · Cool Down · Limpiar RAM |
| 📋 Log | Log del motor · Log de touch · Info del dispositivo |

---

### 📲 Instalación

1. Descargá el ZIP desde [Releases](https://github.com/ByRafaelSystem/Project-Diablo/releases)
2. Abrí **Magisk / KSU / APatch**
3. Instalá desde ZIP
4. Reiniciá el dispositivo
5. Abrí **KSU WebUI** desde KernelSU → seleccioná modo y perfil de touch

---

### ❓ Preguntas frecuentes

**¿Funciona en mi chipset?**  
Project Diablo detecta automáticamente tu SoC al instalar. Si es MTK, Snapdragon, Exynos, Tensor, Unisoc o Kirin va a funcionar. Para otros chips aplica tweaks genéricos.

**¿Qué modo recomendás para jugar?**  
Con DiabloAI activado no hace falta hacer nada — detecta automáticamente cuando abrís un juego y aplica Gaming Pro. Si preferís control manual, desactivá el AI y seleccioná Gaming Pro desde el WebUI.

**¿Puedo cambiar de modo sin reiniciar?**  
Sí. Desde KSU WebUI el cambio se aplica en segundos sin reiniciar.

**¿Por qué el teléfono arranca siempre en Balance?**  
Es intencional. Si DiabloAI está activo, al reiniciar siempre arranca en Balance y el AI toma el control inmediatamente según el contexto. Si está desactivado, arranca en el último modo guardado.

**¿Qué es el Gaming Keeper?**  
Un proceso en segundo plano que corre durante Gaming Pro y re-aplica los tweaks de GPU y CPU cada 5 segundos para contrarrestar las reversiones automáticas de HyperOS 2.

**¿Afecta la temperatura del dispositivo?**  
En modo Performance y Gaming Pro el dispositivo puede calentar más de lo normal ya que el hardware trabaja al máximo. Podés usar el **Cool Down** del WebUI para bajar la temperatura rápidamente.

---

### 📋 Changelog

#### v1.3 — UNIVERSAL (Marzo 2026)
- ✅ DiabloAI: detección automática de gaming/balance/idle/carga
- ✅ Gamelist con 522+ juegos reconocidos
- ✅ FastCharge integrado con protección térmica y sliders configurables
- ✅ Boot siempre en Balance cuando DiabloAI está activo
- ✅ Cambio manual respetado solo con DiabloAI desactivado
- ✅ KSU WebUI: gamelist expandible en inicio · botones de modo compactos
- ✅ Touch profiles: Normal · Gaming · iPhone · Sistema
- ✅ Botones Telegram y GitHub integrados
- ✅ ASCII art restaurado en instalación

#### v1.1 — UNIVERSAL
- ✅ Soporte universal: Magisk · KSU · APatch
- ✅ 4 modos de rendimiento
- ✅ Touch Engine con 4 perfiles
- ✅ KSU WebUI multilenguaje (ES · EN · PT · ID · RU)
- ✅ Detección automática de chipset
- ✅ Scripts Zeta y AmeRender

---

## 🇺🇸 English

### What is Project Diablo?

Project Diablo is an advanced performance engine that optimizes CPU, GPU, memory and touch on your Android to maximize FPS and reduce gaming lag. It automatically detects your chipset during installation and applies specific tweaks for each manufacturer.

As of **v1.3**, it includes **DiabloAI** — an automatic detection engine that applies the right mode based on what you're doing: gaming, charging, idle or screen off. It's controlled from the **KSU WebUI**, the graphical interface built into KernelSU.

---

### ✨ Features

- 😈 **4 performance modes** — Performance · Balance · Battery · Gaming Pro
- 🤖 **DiabloAI** — Automatic context detection: gaming · balance · idle · charging
- 🔥 **CPU Engine** — Dynamic governor per chip: `sugov_ext` MTK · `schedutil` Snapdragon · `performance` Exynos
- 🎮 **GPU Engine** — Max frequency with anti-revert, `gpufreqv2` and legacy MTK support, dynamic Mali
- 👆 **Touch Profiles** — Normal · Gaming 1000Hz · iPhone Style · Stock
- 🎮 **Gamelist** — 522+ recognized games for automatic Gaming Pro activation
- ⚡ **FastCharge** — Faster charging with automatic thermal protection
- 🧠 **Gaming Keeper** — Fights HyperOS governor reversions every 5 seconds in Gaming Pro
- 🌐 **Network Boost** — Optimized TCP and reduced latency
- 🎨 **KSU WebUI** — Full control panel, no external apps needed
- 🔍 **Automatic chipset detection** — via sysfs + getprop, saved for subsequent boots

---

### 😈 Available modes

| Mode | CPU | GPU | Best for |
|------|-----|-----|----------|
| ⚡ Performance | Max governor | Max frequency | Sustained performance |
| ⚖️ Balance | Smart governor | Mid frequency | Daily use with good battery |
| 🔋 Battery | Aggressive saving | Min frequency | Maximum battery life |
| 😈 Gaming Pro | Max + anti-revert | Max + keeper | Competitive gaming |

---

### 🤖 DiabloAI — Auto Mode

| Detected situation | Applied mode |
|--------------------|--------------|
| Game from gamelist running | 😈 Gaming Pro |
| Screen off | 🔋 Battery |
| Charging | ⚖️ Balance |
| Normal active use | ⚖️ Balance |
| No activity for 5 minutes | 🔋 Battery |

> **Note:** when DiabloAI is **enabled**, the mode buttons in WebUI are informational only — AI is in control. To apply a mode manually, disable DiabloAI first.

---

### 🔧 Supported chipsets

| Chipset | Support | Details |
|---------|---------|---------|
| MediaTek (MTK) | ✅ Maximum | `sugov_ext` · `gpufreqv2` · `dvfsrc` · `FPSGO` · dynamic Mali |
| Snapdragon (QCOM) | ✅ Full | `schedutil` · DCVS bus boost · KGSL GPU |
| Exynos (Samsung) | ✅ Full | `performance` governor · GPU devfreq |
| Google Tensor | ✅ Full | Detection via sysfs |
| Unisoc | ✅ Base | Generic CPU/GPU tweaks |
| Kirin (Huawei) | ✅ Base | Generic CPU/GPU tweaks |

---

### ⚙️ Supported root managers

| Manager | Min version | Status |
|---------|-------------|--------|
| Magisk | v20.4+ | ✅ Supported |
| KernelSU (KSU) | Any | ✅ Supported + WebUI |
| APatch | Any | ✅ Supported |

---

### 🖥️ KSU WebUI — Control Panel

Project Diablo includes a full graphical interface integrated with **KernelSU WebUI**. No external apps needed.

**How to access:**
1. Open KernelSU
2. Tap the Project Diablo module
3. Tap **Open WebUI**

---

### 📲 Installation

1. Download the ZIP from [Releases](https://github.com/ByRafaelSystem/Project-Diablo/releases)
2. Open **Magisk / KSU / APatch**
3. Install from ZIP
4. Reboot your device
5. Open **KSU WebUI** from KernelSU → select mode and touch profile

---

### ❓ FAQ

**Does it work on my chipset?**  
Project Diablo automatically detects your SoC on install. MTK, Snapdragon, Exynos, Tensor, Unisoc and Kirin are all supported. Other chips get generic tweaks.

**Which mode is best for gaming?**  
With DiabloAI active, no action needed — it automatically detects when you open a game and applies Gaming Pro. For manual control, disable AI and select Gaming Pro from WebUI.

**Can I switch modes without rebooting?**  
Yes. Changes from KSU WebUI apply in seconds without rebooting.

**Why does the phone always boot into Balance?**  
By design. If DiabloAI is active, it always boots to Balance and AI immediately takes control based on context. If AI is disabled, it boots into the last saved mode.

**What is the Gaming Keeper?**  
A background process that runs during Gaming Pro and re-applies GPU and CPU tweaks every 5 seconds to counter HyperOS 2 automatic reversions.

---

## 🇧🇷 Português

### O que é Project Diablo?

Motor de desempenho avançado que otimiza CPU, GPU, memória e touch do Android. A partir da v1.3 inclui **DiabloAI** para detecção automática de contexto e controle via **KSU WebUI**.

### 😈 Modos disponíveis

| Modo | Ideal para |
|------|------------|
| ⚡ Performance | Desempenho sustentado |
| ⚖️ Balance | Uso diário com boa bateria |
| 🔋 Battery | Máxima autonomia |
| 😈 Gaming Pro | Jogos competitivos |

### 🤖 DiabloAI

| Situação | Modo aplicado |
|----------|---------------|
| Jogo em execução | 😈 Gaming Pro |
| Tela desligada | 🔋 Battery |
| Carregando | ⚖️ Balance |
| Uso normal | ⚖️ Balance |
| Sem atividade 5 min | 🔋 Battery |

### 📲 Instalação

1. Baixe o ZIP em [Releases](https://github.com/ByRafaelSystem/Project-Diablo/releases)
2. Abra o Magisk / KSU / APatch → Instale pelo ZIP → Reinicie
3. Abra o **KSU WebUI** → selecione o modo

---

## 🇮🇩 Indonesia

### Apa itu Project Diablo?

Mesin performa canggih yang mengoptimalkan CPU, GPU, memori, dan sentuhan Android. Mulai v1.3 mencakup **DiabloAI** untuk deteksi konteks otomatis dan kontrol via **KSU WebUI**.

### 😈 Mode tersedia

| Mode | Terbaik untuk |
|------|---------------|
| ⚡ Performance | Performa berkelanjutan |
| ⚖️ Balance | Penggunaan harian |
| 🔋 Battery | Baterai maksimal |
| 😈 Gaming Pro | Game kompetitif |

### 🤖 DiabloAI

| Situasi terdeteksi | Mode diterapkan |
|--------------------|-----------------|
| Game dari daftar berjalan | 😈 Gaming Pro |
| Layar mati | 🔋 Battery |
| Mengisi daya | ⚖️ Balance |
| Penggunaan normal | ⚖️ Balance |
| Tidak aktif 5 menit | 🔋 Battery |

### 📲 Instalasi

1. Unduh ZIP dari [Releases](https://github.com/ByRafaelSystem/Project-Diablo/releases)
2. Buka Magisk / KSU / APatch → Pasang dari ZIP → Reboot
3. Buka **KSU WebUI** → pilih mode

---

## 🇷🇺 Русский

### Что такое Project Diablo?

Продвинутый движок производительности, оптимизирующий CPU, GPU, память и сенсорный экран Android. С версии v1.3 включает **DiabloAI** для автоматического определения контекста и управление через **KSU WebUI**.

### 😈 Доступные режимы

| Режим | Лучше всего для |
|-------|-----------------|
| ⚡ Performance | Стабильная производительность |
| ⚖️ Balance | Ежедневное использование |
| 🔋 Battery | Максимальный заряд |
| 😈 Gaming Pro | Соревновательные игры |

### 🤖 DiabloAI

| Ситуация | Применяемый режим |
|----------|-------------------|
| Игра из списка запущена | 😈 Gaming Pro |
| Экран выключен | 🔋 Battery |
| Зарядка | ⚖️ Balance |
| Обычное использование | ⚖️ Balance |
| Неактивность 5 минут | 🔋 Battery |

### 📲 Установка

1. Скачайте ZIP из [Releases](https://github.com/ByRafaelSystem/Project-Diablo/releases)
2. Откройте Magisk / KSU / APatch → Установите из ZIP → Перезагрузите
3. Откройте **KSU WebUI** → выберите режим

---

<div align="center">

## 📞 Contacto / Contact

[![Telegram](https://img.shields.io/badge/Telegram-@proyect__diablo-blue?style=for-the-badge&logo=telegram)](https://t.me/proyect_diablo)
[![GitHub](https://img.shields.io/badge/GitHub-ByRafaelSystem-black?style=for-the-badge&logo=github)](https://github.com/ByRafaelSystem)

---

**Apache License 2.0 — By_Rafael System © 2026**

*"No soy un módulo cualquiera."*

</div>
