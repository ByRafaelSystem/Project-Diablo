<div align="center">

# 😈 Project Diablo
### By_Rafael System

**Motor de rendimiento avanzado para Android — Performance Engine**

[![Version](https://img.shields.io/badge/Version-v1.1-red?style=flat-square)]()
[![Android](https://img.shields.io/badge/Android-9%2B-green?style=flat-square)]()
[![Root](https://img.shields.io/badge/Root-Magisk%20%7C%20KSU%20%7C%20APatch-blue?style=flat-square)]()
[![Chips](https://img.shields.io/badge/Chips-MTK%20%7C%20SD%20%7C%20Exynos%20%7C%20Tensor%20%7C%20más-purple?style=flat-square)]()
[![License](https://img.shields.io/badge/License-Apache%202.0-orange?style=flat-square)]()
[![Author](https://img.shields.io/badge/Author-By__Rafael_System-red?style=flat-square)]()

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

### ✨ Características

- 😈 **4 modos de rendimiento** — Performance · Balance · Battery · Gaming Pro
- 🔥 **CPU Engine** — Governor dinámico por chip: `sugov_ext` MTK, `schedutil` Snapdragon, `performance` Exynos
- 🎮 **GPU Engine** — Frecuencia máxima con anti-reversión, soporte `gpufreqv2` y legacy MTK, Mali dinámico
- 👆 **Touch Profiles** — Normal · Gaming 1000Hz · iPhone Style · Sistema
- 🧠 **Gaming Keeper** — Combate las reversiones de HyperOS cada 5 segundos en modo Gaming Pro
- 🌐 **Network Boost** — BBR, TCP optimizado, latencia reducida
- 📦 **Asset Preloader** — Precarga librerías de juegos en RAM con `vmtouch`
- 🎨 **KSU WebUI** — Panel de control completo
- 🔍 **Detección automática de chipset** — via sysfs + getprop, guardada para próximos boots

### 😈 Modos disponibles

| Modo | CPU | GPU | Ideal para |
|---|---|---|---|
| ⚡ Performance | Governor máximo | Frecuencia máxima | Rendimiento sostenido |
| ⚖️ Balance | Governor inteligente | Frecuencia media | Uso diario con buena duración |
| 🔋 Battery | Ahorro agresivo | Frecuencia mínima | Máxima autonomía |
| 🎮 Gaming Pro | Máximo + anti-reversión | Máximo + keeper | Juegos competitivos |

### 🔧 Chipsets soportados

| Chipset | Soporte | Detalles |
|---|---|---|
| MediaTek (MTK) | ✅ Máximo | `sugov_ext` · `gpufreqv2` · `dvfsrc` · `FPSGO` · Mali dinámico |
| Snapdragon (QCOM) | ✅ Completo | `schedutil` · DCVS bus boost · KGSL GPU |
| Exynos (Samsung) | ✅ Completo | `performance` governor · GPU devfreq |
| Google Tensor | ✅ Completo | Detección via sysfs tegra |
| Unisoc | ✅ Base | Tweaks genéricos CPU/GPU |
| Kirin (Huawei) | ✅ Base | Tweaks genéricos CPU/GPU |

### 📱 Compatibilidad de dispositivos

| Dispositivo | Compatibilidad | Notas |
|---|---|---|
| Xiaomi / Redmi / POCO | ✅ Máxima | Optimizado para HyperOS 2 · Gaming Keeper activo |
| Samsung | ✅ Parcial | Exynos soportado · Sin tweaks OneUI específicos |
| OnePlus / OPPO | ✅ Parcial | Sin tweaks ColorOS específicos |
| Google Pixel | ✅ Parcial | Tensor soportado |
| Otros Android 9+ | ✅ Base | Tweaks genéricos activos |
| **Helio G99 (MTK)** | ✅ **Máxima** | Nodos verificados en hardware real |

### ⚙️ Gestores de root compatibles

| Gestor | Versión mínima | Estado |
|---|---|---|
| Magisk | v20.4+ | ✅ Soportado |
| KernelSU | Cualquiera | ✅ Soportado |
| APatch | Cualquiera | ✅ Soportado |

### 📲 Instalación

1. Descargá el ZIP desde la página oficial
2. Abrí Magisk / KSU / APatch
3. Instalá desde ZIP
4. Reiniciá el dispositivo
5. Abrí **KSU WebUI** → seleccioná el modo y perfil de touch

### ❓ Preguntas frecuentes

**¿Funciona en mi chipset?**
Project Diablo detecta automáticamente tu SoC al instalar. Si es MTK, Snapdragon, Exynos, Tensor, Unisoc o Kirin va a funcionar. Para otros chips aplica tweaks genéricos.

**¿Qué modo recomendás para jugar?**
Gaming Pro — activa el máximo rendimiento de CPU y GPU y encima tiene el Gaming Keeper que evita que HyperOS revierta los ajustes mientras jugás.

**¿Puedo cambiar de modo sin reiniciar?**
Sí. Desde KSU WebUI el cambio se aplica en segundos sin reiniciar.

**¿Es compatible con VisorX y ARG X9?**
Sí, los tres módulos del mismo autor son totalmente compatibles entre sí.

**¿Qué es el Gaming Keeper?**
Es un proceso que corre en segundo plano durante Gaming Pro y re-aplica los tweaks de GPU y CPU cada 5 segundos para contrarrestar las reversiones automáticas de HyperOS 2.

**¿Afecta la temperatura del dispositivo?**
En modo Performance y Gaming Pro el dispositivo puede calentar más de lo normal ya que el hardware trabaja al máximo. Es normal y esperado.

---

## 🇺🇸 English

### What is Project Diablo?

Project Diablo is an advanced performance engine that optimizes CPU, GPU, memory and touch on your Android to maximize FPS and reduce gaming lag. It automatically detects your chipset during installation and applies specific tweaks for each manufacturer.

### ✨ Features

- 😈 **4 performance modes** — Performance · Balance · Battery · Gaming Pro
- 🔥 **CPU Engine** — Dynamic governor per chip: `sugov_ext` MTK, `schedutil` Snapdragon, `performance` Exynos
- 🎮 **GPU Engine** — Max frequency with anti-revert, `gpufreqv2` and legacy MTK support, dynamic Mali
- 👆 **Touch Profiles** — Normal · Gaming 1000Hz · iPhone Style · Stock
- 🧠 **Gaming Keeper** — Fights HyperOS governor reversions every 5 seconds in Gaming Pro mode
- 🌐 **Network Boost** — BBR, optimized TCP, reduced latency
- 📦 **Asset Preloader** — Preloads game libraries into RAM via `vmtouch`
- 🎨 **KSU WebUI** — Full control panel
- 🔍 **Automatic chipset detection** — via sysfs + getprop, saved for subsequent boots

### 😈 Available modes

| Mode | CPU | GPU | Best for |
|---|---|---|---|
| ⚡ Performance | Max governor | Max frequency | Sustained performance |
| ⚖️ Balance | Smart governor | Mid frequency | Daily use with good battery |
| 🔋 Battery | Aggressive saving | Min frequency | Maximum battery life |
| 🎮 Gaming Pro | Max + anti-revert | Max + keeper | Competitive gaming |

### 🔧 Supported chipsets

| Chipset | Support | Details |
|---|---|---|
| MediaTek (MTK) | ✅ Maximum | `sugov_ext` · `gpufreqv2` · `dvfsrc` · `FPSGO` · dynamic Mali |
| Snapdragon (QCOM) | ✅ Full | `schedutil` · DCVS bus boost · KGSL GPU |
| Exynos (Samsung) | ✅ Full | `performance` governor · GPU devfreq |
| Google Tensor | ✅ Full | Detection via tegra sysfs |
| Unisoc | ✅ Base | Generic CPU/GPU tweaks |
| Kirin (Huawei) | ✅ Base | Generic CPU/GPU tweaks |

### 📱 Device compatibility

| Device | Compatibility | Notes |
|---|---|---|
| Xiaomi / Redmi / POCO | ✅ Maximum | Optimized for HyperOS 2 · Gaming Keeper active |
| Samsung | ✅ Partial | Exynos supported · No OneUI-specific tweaks |
| OnePlus / OPPO | ✅ Partial | No ColorOS-specific tweaks |
| Google Pixel | ✅ Partial | Tensor supported |
| Other Android 9+ | ✅ Base | Generic tweaks active |
| **Helio G99 (MTK)** | ✅ **Maximum** | Nodes verified on real hardware |

### ⚙️ Supported root managers

| Manager | Min version | Status |
|---|---|---|
| Magisk | v20.4+ | ✅ Supported |
| KernelSU | Any | ✅ Supported |
| APatch | Any | ✅ Supported |

### 📲 Installation

1. Download the ZIP from the official page
2. Open Magisk / KSU / APatch
3. Install from ZIP
4. Reboot your device
5. Open **KSU WebUI** → select mode and touch profile

### ❓ FAQ

**Does it work on my chipset?**
Project Diablo automatically detects your SoC on install. MTK, Snapdragon, Exynos, Tensor, Unisoc and Kirin are all supported. Other chips get generic tweaks.

**Which mode is best for gaming?**
Gaming Pro — it maxes out CPU and GPU and the Gaming Keeper prevents HyperOS from reverting the settings while you play.

**Can I switch modes without rebooting?**
Yes. From KSU WebUI the change applies in seconds without rebooting.

**Is it compatible with VisorX and ARG X9?**
Yes, all three modules from the same author are fully compatible with each other.

**What is the Gaming Keeper?**
A background process that runs during Gaming Pro mode and re-applies GPU and CPU tweaks every 5 seconds to counter HyperOS 2 automatic reversions.

---

## 🇧🇷 Português

### O que é Project Diablo?

Project Diablo é um motor de desempenho avançado que otimiza CPU, GPU, memória e touch do seu Android para maximizar FPS e reduzir lag nos jogos. Detecta automaticamente seu chipset na instalação.

### 😈 Modos disponíveis

| Modo | Ideal para |
|---|---|
| ⚡ Performance | Desempenho sustentado |
| ⚖️ Balance | Uso diário com boa bateria |
| 🔋 Battery | Máxima autonomia |
| 🎮 Gaming Pro | Jogos competitivos |

### 🔧 Chipsets suportados

MTK · Snapdragon · Exynos · Tensor · Unisoc · Kirin

### 📱 Compatibilidade

| Dispositivo | Compatibilidade |
|---|---|
| Xiaomi / Redmi / POCO | ✅ Máxima |
| Samsung / OnePlus | ✅ Parcial |
| Android 9+ qualquer | ✅ Base |

### 📲 Instalação

1. Baixe o ZIP na página oficial
2. Abra o Magisk / KSU / APatch
3. Instale pelo ZIP
4. Reinicie
5. Abra o **KSU WebUI** → selecione o modo

---

## 🇮🇩 Indonesia

### Apa itu Project Diablo?

Project Diablo adalah mesin performa canggih yang mengoptimalkan CPU, GPU, memori, dan sentuhan Android untuk memaksimalkan FPS dan mengurangi lag saat bermain game. Mendeteksi chipset secara otomatis saat instalasi.

### 😈 Mode tersedia

| Mode | Terbaik untuk |
|---|---|
| ⚡ Performance | Performa berkelanjutan |
| ⚖️ Balance | Penggunaan harian |
| 🔋 Battery | Baterai maksimal |
| 🎮 Gaming Pro | Game kompetitif |

### 🔧 Chipset didukung

MTK · Snapdragon · Exynos · Tensor · Unisoc · Kirin

### 📱 Kompatibilitas

| Perangkat | Kompatibilitas |
|---|---|
| Xiaomi / Redmi / POCO | ✅ Maksimal |
| Samsung / OnePlus | ✅ Sebagian |
| Android 9+ manapun | ✅ Dasar |

### 📲 Instalasi

1. Unduh ZIP dari halaman resmi
2. Buka Magisk / KSU / APatch
3. Pasang dari ZIP
4. Reboot
5. Buka **KSU WebUI** → pilih mode

---

## 🇷🇺 Русский

### Что такое Project Diablo?

Project Diablo — продвинутый движок производительности, оптимизирующий CPU, GPU, память и сенсорный экран Android для максимальных FPS и минимального лага в играх. Автоматически определяет чипсет при установке.

### 😈 Доступные режимы

| Режим | Лучше всего для |
|---|---|
| ⚡ Performance | Стабильная производительность |
| ⚖️ Balance | Ежедневное использование |
| 🔋 Battery | Максимальный заряд |
| 🎮 Gaming Pro | Соревновательные игры |

### 🔧 Поддерживаемые чипсеты

MTK · Snapdragon · Exynos · Tensor · Unisoc · Kirin

### 📱 Совместимость

| Устройство | Совместимость |
|---|---|
| Xiaomi / Redmi / POCO | ✅ Максимальная |
| Samsung / OnePlus | ✅ Частичная |
| Android 9+ любой | ✅ Базовая |

### 📲 Установка

1. Скачайте ZIP с официальной страницы
2. Откройте Magisk / KSU / APatch
3. Установите из ZIP
4. Перезагрузите устройство
5. Откройте **KSU WebUI** → выберите режим

---

## 📄 Licencia / License

Apache License 2.0 — By_Rafael System © 2026
