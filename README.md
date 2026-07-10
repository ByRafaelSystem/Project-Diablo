![Project Diablo Pro](https://github.com/ByRafaelSystem/Project-Diablo/raw/main/project_diablo_pro.jpg)



# 😈 Project Diablo Pro

### By_Rafael System

**Motor de rendimiento avanzado para Android — Performance Engine**

[![Version](https://img.shields.io/badge/Version-v3.0-red?style=flat-square)](https://github.com/ByRafaelSystem/Project-Diablo/releases)
[![Android](https://img.shields.io/badge/Android-9%2B-green?style=flat-square)](https://github.com/ByRafaelSystem/Project-Diablo)
[![Root](https://img.shields.io/badge/Root-Magisk%20%7C%20KSU%20%7C%20APatch-blue?style=flat-square)](https://github.com/ByRafaelSystem/Project-Diablo)
[![Chips](https://img.shields.io/badge/Chips-MTK%20%7C%20SD%20%7C%20Exynos%20%7C%20Tensor%20%7C%20m%C3%A1s-purple?style=flat-square)](https://github.com/ByRafaelSystem/Project-Diablo)
[![License](https://img.shields.io/badge/License-Apache%202.0-orange?style=flat-square)](https://github.com/ByRafaelSystem/Project-Diablo)
[![Author](https://img.shields.io/badge/Author-By__Rafael_System-red?style=flat-square)](https://github.com/ByRafaelSystem)

---

## 🌍 Idiomas / Languages

- 🇪🇸 [Español](#español)
- 🇺🇸 [English](#english)
- 🇧🇷 [Português](#português)
- 🇮🇩 [Indonesia](#indonesia)
- 🇷🇺 [Русский](#русский)

---

## 🇪🇸 Español

### ¿Qué es Project Diablo Pro?

Project Diablo Pro es un motor de rendimiento avanzado que optimiza CPU, GPU, memoria y touch de tu Android para maximizar FPS y eliminar el lag en juegos. Incluye una app nativa de control, inteligencia artificial para gestionar perfiles automáticamente y soporte universal para todos los chipsets principales.

### ✨ Características

- 😈 **4 modos de rendimiento** — Performance · Balance · Battery · Gaming Pro
- 🤖 **DiabloAI v2** — 6 reglas configurables: modo por app, pantalla apagada, carga, inactividad, batería baja, temperatura alta
- 📱 **Control App** — App nativa instalada automáticamente. Sin WebUI necesaria. Compatible con Magisk · KSU · APatch
- 🎮 **Smart Gamelist** — Asigna cualquier modo a cualquier app. Detección en 1s, protección OOM, restauración automática del modo
- 🔥 **CPU Engine** — Governor dinámico por chip: `sugov_ext` MTK, `schedutil` Snapdragon, `performance` Exynos
- 🎮 **GPU Engine** — Frecuencia máxima con anti-reversión, soporte `gpufreqv2` y legacy MTK, Mali dinámico
- 👆 **Touch Engine** — Normal · Gaming 1000Hz · iPhone Style · Sistema
- ⚡ **FastCharge Next** — Corriente ajustable 500–3000 mA con protección térmica
- 🔋 **Niveles de batería** — 3 niveles de ahorro: Suave · Moderado · Agresivo
- 🌐 **Gaming Pro Network** — WiFi baja latencia automático, TCP gaming, opción Diablo Boost
- 🛡️ **Diablo Protect** — Anti-bootloop: desactiva el módulo tras 3 arranques fallidos consecutivos
- 🧩 **Motor I/O y Scheduler** — Tweaks de bloque y planificador por modo y por chip
- 🎨 **Interfaz PRO** — Banner personalizable, personajes Diablo/Diablesa, sonido de bienvenida

### 😈 Modos disponibles

| Modo | CPU | GPU | Ideal para |
|---|---|---|---|
| ⚡ Performance | Governor máximo | Frecuencia máxima | Rendimiento sostenido |
| ⚖️ Balance | Governor inteligente | Frecuencia media | Uso diario con buena duración |
| 🔋 Battery | Ahorro agresivo | Frecuencia mínima | Máxima autonomía |
| 🎮 Gaming Pro | Máximo + scheduler gaming | Máximo + anti-reversión | Juegos competitivos |

### 🤖 DiabloAI v2 — Reglas configurables

| Regla | Descripción |
|---|---|
| 🎮 Modo por app | Aplica el modo asignado al abrir una app del gamelist |
| 🌙 Pantalla apagada | Cambia a Battery automáticamente |
| ⚡ Cargando | Aplica el modo predeterminado al conectar cargador |
| 😴 Inactividad | Cambia a Battery tras N minutos sin uso |
| 🔋 Batería baja | Activa Battery al bajar del % configurado |
| 🌡️ Temperatura alta | Activa Battery al superar la temperatura límite |

### 🔧 Chipsets soportados

| Chipset | Soporte | Detalles |
|---|---|---|
| MediaTek (MTK) | ✅ Máximo | `sugov_ext` · `gpufreqv2` · `dvfsrc` · `FPSGO` · Mali dinámico |
| Snapdragon (QCOM) | ✅ Completo | `schedutil` · DCVS bus boost · KGSL GPU · QCom Scheduler |
| Exynos (Samsung) | ✅ Completo | `performance` governor · GPU devfreq |
| Google Tensor | ✅ Completo | Detección via sysfs |
| Unisoc | ✅ Base | Tweaks genéricos CPU/GPU |
| Kirin (Huawei) | ✅ Base | Tweaks genéricos CPU/GPU |

### 📱 Compatibilidad de dispositivos

| Dispositivo | Compatibilidad | Notas |
|---|---|---|
| Xiaomi / Redmi / POCO | ✅ Máxima | Optimizado para HyperOS · Gaming Keeper activo |
| Samsung | ✅ Parcial | Exynos soportado · Sin tweaks OneUI específicos |
| OnePlus / OPPO | ✅ Parcial | Sin tweaks ColorOS específicos |
| Google Pixel | ✅ Parcial | Tensor soportado |
| Otros Android 9+ | ✅ Base | Tweaks genéricos activos |
| **Helio G85 / G99 (MTK)** | ✅ **Máxima** | Nodos verificados en hardware real |

### ⚙️ Gestores de root compatibles

| Gestor | Versión mínima | Estado |
|---|---|---|
| Magisk | v20.4+ | ✅ Soportado |
| KernelSU | Cualquiera | ✅ Soportado |
| APatch | Cualquiera | ✅ Soportado |

### 📲 Instalación

1. Descargá el ZIP desde la [página de releases](https://github.com/ByRafaelSystem/Project-Diablo/releases)
2. Abrí Magisk / KSU / APatch
3. Instalá desde ZIP
4. Reiniciá el dispositivo
5. La app **Project Diablo Pro** se instala automáticamente
6. Abrí la app → configurá DiabloAI y tu modo preferido

### ❓ Preguntas frecuentes

**¿Funciona en mi chipset?**
Project Diablo Pro detecta automáticamente tu SoC al instalar. MTK, Snapdragon, Exynos, Tensor, Unisoc y Kirin son soportados con tweaks específicos. Otros chips reciben tweaks genéricos.

**¿Qué modo recomendás para jugar?**
Gaming Pro — activa el máximo rendimiento de CPU y GPU con scheduler optimizado para gaming y red de baja latencia automática.

**¿Necesito WebUI / Termux?**
No. La app nativa se instala automáticamente con el módulo y no requiere ninguna interfaz externa.

**¿Puedo cambiar de modo sin reiniciar?**
Sí. Desde la app el cambio se aplica en segundos sin reiniciar.

**¿Qué hace DiabloAI?**
Monitorea tu dispositivo y cambia de perfil automáticamente según lo que estés haciendo: gaming, cargando, pantalla apagada, batería baja o temperatura alta. Cuando DiabloAI está activado, los botones de modo solo muestran información; la IA tiene el control. Para cambiar manualmente, desactivá primero DiabloAI.

**¿Es compatible con VisorX y ARG X9?**
Sí, los tres módulos del mismo autor son totalmente compatibles entre sí.

**¿Afecta la temperatura del dispositivo?**
En modo Performance y Gaming Pro el dispositivo puede calentar más de lo normal ya que el hardware trabaja al máximo. Es esperado. DiabloAI puede activar el modo Battery automáticamente si la temperatura supera el límite configurado.

---

## 🇺🇸 English

### What is Project Diablo Pro?

Project Diablo Pro is an advanced performance engine that optimizes CPU, GPU, memory and touch on your Android to maximize FPS and eliminate gaming lag. It includes a native control app, artificial intelligence to manage profiles automatically and universal support for all major chipsets.

### ✨ Features

- 😈 **4 performance modes** — Performance · Balance · Battery · Gaming Pro
- 🤖 **DiabloAI v2** — 6 configurable rules: per-app mode, screen off, charging, inactivity, low battery, high temperature
- 📱 **Control App** — Native app installed automatically. No WebUI needed. Compatible with Magisk · KSU · APatch
- 🎮 **Smart Gamelist** — Assign any mode to any app. 1s detection, OOM protection, auto mode restore
- 🔥 **CPU Engine** — Dynamic governor per chip: `sugov_ext` MTK, `schedutil` Snapdragon, `performance` Exynos
- 🎮 **GPU Engine** — Max frequency with anti-revert, `gpufreqv2` and legacy MTK support, dynamic Mali
- 👆 **Touch Engine** — Normal · Gaming 1000Hz · iPhone Style · Stock
- ⚡ **FastCharge Next** — Adjustable current 500–3000 mA with thermal protection
- 🔋 **Battery Levels** — 3 saving levels: Soft · Moderate · Aggressive
- 🌐 **Gaming Pro Network** — Auto low-latency WiFi, TCP gaming tweaks, Diablo Boost option
- 🛡️ **Diablo Protect** — Anti-bootloop: disables module after 3 consecutive boot failures
- 🧩 **I/O & Scheduler Engine** — Block and scheduler tweaks per mode and chip
- 🎨 **PRO Interface** — Custom banner, Diablo/Diablesa characters, welcome sound

### 😈 Available modes

| Mode | CPU | GPU | Best for |
|---|---|---|---|
| ⚡ Performance | Max governor | Max frequency | Sustained performance |
| ⚖️ Balance | Smart governor | Mid frequency | Daily use with good battery |
| 🔋 Battery | Aggressive saving | Min frequency | Maximum battery life |
| 🎮 Gaming Pro | Max + gaming scheduler | Max + anti-revert | Competitive gaming |

### 🤖 DiabloAI v2 — Configurable rules

| Rule | Description |
|---|---|
| 🎮 Per-app mode | Applies assigned mode when a gamelist app opens |
| 🌙 Screen off | Switches to Battery automatically |
| ⚡ Charging | Applies default mode when charger is connected |
| 😴 Inactivity | Switches to Battery after N minutes of no use |
| 🔋 Low battery | Activates Battery below the configured % |
| 🌡️ High temperature | Activates Battery above the temperature limit |

### 🔧 Supported chipsets

| Chipset | Support | Details |
|---|---|---|
| MediaTek (MTK) | ✅ Maximum | `sugov_ext` · `gpufreqv2` · `dvfsrc` · `FPSGO` · dynamic Mali |
| Snapdragon (QCOM) | ✅ Full | `schedutil` · DCVS bus boost · KGSL GPU · QCom Scheduler |
| Exynos (Samsung) | ✅ Full | `performance` governor · GPU devfreq |
| Google Tensor | ✅ Full | Detection via sysfs |
| Unisoc | ✅ Base | Generic CPU/GPU tweaks |
| Kirin (Huawei) | ✅ Base | Generic CPU/GPU tweaks |

### 📱 Device compatibility

| Device | Compatibility | Notes |
|---|---|---|
| Xiaomi / Redmi / POCO | ✅ Maximum | Optimized for HyperOS · Gaming Keeper active |
| Samsung | ✅ Partial | Exynos supported · No OneUI-specific tweaks |
| OnePlus / OPPO | ✅ Partial | No ColorOS-specific tweaks |
| Google Pixel | ✅ Partial | Tensor supported |
| Other Android 9+ | ✅ Base | Generic tweaks active |
| **Helio G85 / G99 (MTK)** | ✅ **Maximum** | Nodes verified on real hardware |

### ⚙️ Supported root managers

| Manager | Min version | Status |
|---|---|---|
| Magisk | v20.4+ | ✅ Supported |
| KernelSU | Any | ✅ Supported |
| APatch | Any | ✅ Supported |

### 📲 Installation

1. Download the ZIP from the [releases page](https://github.com/ByRafaelSystem/Project-Diablo/releases)
2. Open Magisk / KSU / APatch
3. Install from ZIP
4. Reboot your device
5. The **Project Diablo Pro** app installs automatically
6. Open the app → configure DiabloAI and your preferred mode

### ❓ FAQ

**Does it work on my chipset?**
Project Diablo Pro automatically detects your SoC on install. MTK, Snapdragon, Exynos, Tensor, Unisoc and Kirin all get specific tweaks. Other chips receive generic tweaks.

**Which mode is best for gaming?**
Gaming Pro — it maxes out CPU and GPU with a gaming-optimized scheduler and automatic low-latency network.

**Do I need WebUI / Termux?**
No. The native app installs automatically with the module and requires no external interface.

**Can I switch modes without rebooting?**
Yes. From the app the change applies in seconds without rebooting.

**What does DiabloAI do?**
It monitors your device and switches profiles automatically based on what you're doing: gaming, charging, screen off, low battery or high temperature. When DiabloAI is active, the mode buttons are informational only — the AI is in control. To switch manually, disable DiabloAI first.

---

## 🇧🇷 Português

### O que é Project Diablo Pro?

Project Diablo Pro é um motor de desempenho avançado que otimiza CPU, GPU, memória e touch do seu Android para maximizar FPS e eliminar o lag nos jogos. Inclui app nativa de controle e inteligência artificial para gerenciar perfis automaticamente.

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

1. Baixe o ZIP na [página de releases](https://github.com/ByRafaelSystem/Project-Diablo/releases)
2. Abra o Magisk / KSU / APatch
3. Instale pelo ZIP
4. Reinicie
5. Abra o app **Project Diablo Pro** → configure o modo e DiabloAI

---

## 🇮🇩 Indonesia

### Apa itu Project Diablo Pro?

Project Diablo Pro adalah mesin performa canggih yang mengoptimalkan CPU, GPU, memori, dan sentuhan Android untuk memaksimalkan FPS dan menghilangkan lag saat bermain game. Dilengkapi aplikasi kontrol native dan kecerdasan buatan untuk mengelola profil secara otomatis.

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

1. Unduh ZIP dari [halaman releases](https://github.com/ByRafaelSystem/Project-Diablo/releases)
2. Buka Magisk / KSU / APatch
3. Pasang dari ZIP
4. Reboot
5. Buka app **Project Diablo Pro** → atur mode dan DiabloAI

---

## 🇷🇺 Русский

### Что такое Project Diablo Pro?

Project Diablo Pro — продвинутый движок производительности, оптимизирующий CPU, GPU, память и сенсорный экран Android для максимальных FPS и минимального лага в играх. Включает нативное приложение управления и искусственный интеллект для автоматического управления профилями.

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

1. Скачайте ZIP со [страницы релизов](https://github.com/ByRafaelSystem/Project-Diablo/releases)
2. Откройте Magisk / KSU / APatch
3. Установите из ZIP
4. Перезагрузите устройство
5. Откройте приложение **Project Diablo Pro** → настройте режим и DiabloAI

---

## 📄 Licencia / License

Apache License 2.0 — By_Rafael System © 2026
