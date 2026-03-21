![Project Diablo Banner](https://github.com/ByRafaelSystem/Project-Diablo/blob/main/IMG_20260321_100205.jpg?raw=true)

# 😈 Project Diablo Pro

### By_Rafael System

**Motor de rendimiento avanzado para Android — Performance Engine**


---

## 🌍 Idiomas / Languages

- 🇪🇸 [Español](#-español)
- 🇺🇸 [English](#-english)
- 🇧🇷 [Português](#-português)
- 🇮🇩 [Indonesia](#-indonesia)
- 🇷🇺 [Русский](#-русский)

---

## 🇪🇸 Español

### ¿Qué es Project Diablo Pro?

Project Diablo Pro es un motor de rendimiento avanzado para Android que optimiza CPU, GPU, memoria y touch para maximizar FPS y reducir lag. La versión **Pro v2.0** introduce **DiabloAI v2** — un sistema de inteligencia automática con 6 reglas configurables que se adapta solo según lo que estás haciendo en el teléfono.

---

### 📱 App de Control — Diablo Pro App

A partir de v2.0, el módulo incluye una **app nativa de Android** que se instala automáticamente al flashear. Ya no necesitás KernelSU WebUI para controlar el módulo.

| Característica | Detalle |
|---|---|
| 🔧 **Instalación automática** | Se instala sola al flashear el módulo — sin pasos extra |
| 📱 **App nativa** | Funciona desde el cajón de aplicaciones como cualquier app |
| 😈 **Ícono propio** | Demonio morado con lentes negros de sol |
| ⚡ **Sin lag** | WebView nativo dedicado — sin el lag del WebUI de KSU |
| 🌐 **Compatible con todo** | Magisk, KernelSU y APatch — cualquier gestor de root |
| 🔑 **Bridge root directo** | Ejecuta comandos con `su` sin pasar por capas del gestor |
| 💾 **Banner personalizable** | Cambiá el banner desde la app con tu propia imagen |
| 📲 **Android 5.0+** | Compatible con cualquier Android rooteado moderno |

> 💡 Si preferís el WebUI de KernelSU, sigue funcionando igual que antes. La app es una alternativa más fluida y universal.

---

### ✨ Novedades en v2.0 PRO

| Característica | Descripción |
|---|---|
| 📱 **App de Control** | App nativa incluida en el módulo — se instala automáticamente |
| 🤖 **DiabloAI v2** | 6 reglas configurables — detecta apps, temperatura, batería baja, idle y más |
| 🎮 **Gamelist inteligente** | Asignás un modo específico a cada app. No solo juegos — cualquier app |
| 📱 **Página AI dedicada** | Control total de DiabloAI con estado en tiempo real |
| 🔒 **Sistema de bloqueo por app** | Cuando detecta una app de la gamelist la bloquea hasta que termine |
| 🔔 **Notificaciones dinámicas** | La notificación muestra el modo exacto que aplicó según la app |
| 😈 **Diablo 3D animado** | El ícono de DiabloAI tiene dos estados — activo con fuego y dormido con Zzz |
| 🔊 **Sonido de bienvenida** | Efecto Portal al abrir (Web Audio API, 0 KB extra) |
| 🔊 **Sonidos de AI** | Sonido al activar y desactivar DiabloAI |
| 🎨 **Nuevo diseño PRO** | Colores púrpura + dorado, banner 3D, 5 pestañas de navegación |
| ❓ **Botones de ayuda ?** | 3 botones contextuales en página AI, traducidos en 5 idiomas |
| 🔋 **Niveles de Battery** | 3 niveles de ahorro seleccionables con slider |
| 🔧 **Selección de chip manual** | Corregí el chip detectado desde la tarjeta de estado — se guarda permanentemente |
| ℹ️ **Info ? en Status** | Explicación de DiabloAI, chip, Battery y prioridades en 5 idiomas |
| 🌐 **Gaming Pro — Red integrada** | WiFi baja latencia, TCP gaming, buffers 4MB, RPS — automático al jugar |
| 👹 **Diablesa** | Segundo personaje seleccionable — tocá el demonio en la página AI |
| ⚡ **Loop AI optimizado** | Config en memoria — de hasta 20s por ciclo a menos de 1s |

---

### 😈 DiabloAI v2 — Motor automático

DiabloAI detecta el contexto del teléfono y aplica el modo correcto sin que el usuario tenga que hacer nada.

**Sistema de bloqueo por app:**
Cuando detecta una app de la gamelist en primer plano (`oom_score_adj ≤ 0`), aplica el modo asignado y bloquea. Solo libera cuando la app desaparece completamente de memoria.

**6 Reglas automáticas configurables:**

| Regla | Comportamiento | Ajustable |
|---|---|---|
| 🎮 App del gamelist | Aplica el modo asignado a esa app | Modo por app |
| 📴 Pantalla apagada | Aplica Battery automáticamente | ON/OFF |
| 🔌 Cargando | Aplica el modo por defecto | ON/OFF |
| 💤 Sin actividad | Battery tras X minutos de idle | Slider 2–15 min |
| 🪫 Batería baja | Battery cuando baja de X% | Slider 10–30% |
| 🌡️ Temperatura alta | Battery al superar X°C, restaura al enfriarse | Slider 40–55°C |

**Prioridad de reglas:**
```
1° Temperatura     → seguridad del hardware primero
2° App del gamelist
3° Pantalla apagada
4° Batería baja
5° Cargando
6° Idle
7° Activo normal   → modo por defecto
```

---

### 🌐 Gaming Pro — Red integrada

| Optimización | Detalle |
|---|---|
| WiFi baja latencia | Prioriza latencia sobre ahorro de energía |
| Sin escaneos de fondo | El chip WiFi no interrumpe la conexión buscando otras redes |
| TCP sin frenos de idle | No frena entre ráfagas de paquetes del juego |
| Buffers TCP a 4MB | `rmem_max/wmem_max` elevados para que el kernel no los trunque |
| Cola WiFi 3000 | Aguanta ráfagas sin descartar paquetes |
| RPS en 4 cores | Interrupciones de red distribuidas — siempre hay un core libre |
| Sin diagnósticos | Para `cnss_diag` y `tcpdump` que roban CPU durante el juego |

> 💡 Activá **Diablo Boost** desde la app para sumar `netdev_max_backlog`, `tcp_fastopen` y WiFi sin power save encima de Gaming Pro.

---

### 🔋 Niveles de Battery

| Nivel | Governor | CPU | Ideal para |
|---|---|---|---|
| 🌿 **Suave** | schedutil | 50% máx | Uso cotidiano con ahorro moderado |
| ⚡ **Moderado** | powersave | 25% máx | Buen ahorro sin sacrificar la usabilidad |
| 💀 **Agresivo** | powersave | Mínimo | Reposo total, máxima autonomía |

---

### 👹 Diablesa — Segundo personaje

Tocá el demonio animado en la página AI para abrir el selector de personaje. Elegí entre **Diablo** (púrpura) y **Diablesa** (rosa). La selección se guarda automáticamente.

---

### 🔧 Selección de chip manual

En la tarjeta de estado hay un botón **CHIP ▾**. Si la detección falló, tocá para elegir manualmente entre MediaTek · Snapdragon · Exynos · Unisoc · Google Tensor · Kirin. Se guarda permanentemente.

---

### 🎮 Gamelist inteligente

Formato: `package|nombre|modo`

```
com.dts.freefireth|Free Fire|4          → Gaming Pro
com.miHoYo.GenshinImpact|Genshin|4      → Gaming Pro
com.google.android.camera|Cámara|1      → Performance
com.instagram.android|Instagram|3       → Battery
com.spotify.music|Spotify|2             → Balance
```

---

### 😈 Modos disponibles

| Modo | CPU | GPU | Ideal para |
|---|---|---|---|
| 🔥 Performance | Governor máximo | Frecuencia máxima | Rendimiento sostenido |
| ⚖️ Balance | Governor inteligente | Frecuencia media | Uso diario |
| 🔋 Battery | Ahorro (nivel elegido) | Frecuencia mínima | Máxima autonomía |
| 😈 Gaming Pro | Máximo absoluto | Máximo + FPSGO | Juegos competitivos |

---

### 🔧 Chipsets soportados

| Chipset | Soporte | Detalles |
|---|---|---|
| MediaTek (MTK) | ✅ Máximo | `sugov_ext` · `gpufreqv2` · `dvfsrc` · `FPSGO` · Mali dinámico |
| Snapdragon (QCOM) | ✅ Completo | `schedutil` · DCVS bus boost · KGSL GPU |
| Exynos (Samsung) | ✅ Completo | `performance` governor · GPU devfreq |
| Google Tensor | ✅ Completo | Detección via sysfs |
| Unisoc | ✅ Base | Tweaks genéricos CPU/GPU |
| Kirin (Huawei) | ✅ Base | Tweaks genéricos CPU/GPU |

---

### 📱 Compatibilidad de dispositivos

| Dispositivo | Compatibilidad | Notas |
|---|---|---|
| Xiaomi / Redmi / POCO | ✅ Máxima | Optimizado para HyperOS · DiabloAI verificado |
| Samsung | ✅ Parcial | Exynos soportado |
| OnePlus / OPPO | ✅ Parcial | Tweaks genéricos |
| Google Pixel | ✅ Parcial | Tensor soportado |
| Otros Android 5.0+ | ✅ Base | Tweaks genéricos activos |
| **Helio G99 (MT6789)** | ✅ **Verificado** | Redmi Note 14 4G — hardware real |

---

### ⚙️ Gestores de root compatibles

| Gestor | Versión mínima | App de Control | WebUI |
|---|---|---|---|
| Magisk | v20.4+ | ✅ Incluida en el módulo | ❌ No disponible |
| KernelSU | Cualquiera | ✅ Incluida en el módulo | ✅ Disponible |
| APatch | Cualquiera | ✅ Incluida en el módulo | ✅ Disponible |

---

### ⚡ FastCharge Next

- Corriente ajustable: 500 mA a 3000 mA
- Temperatura máxima: slider 35°C–48°C
- Temperatura de recuperación: slider 30°C–47°C
- ⚠️ La compatibilidad depende del kernel y ROM del dispositivo

---

### 👆 Touch Engine

| Perfil | Descripción |
|---|---|
| Normal | Configuración estándar optimizada |
| Gaming | 1000Hz · 0ms latencia · PowerHAL boost |
| iPhone | Scroll estilo iOS · fling 16000 |
| Sistema | Restaura valores originales |

---

### 🛡️ Diablo Protect

Sistema anti-bootloop integrado. Si el boot anterior no completó, suma un fallo al contador. Al llegar a 3 fallos consecutivos, desactiva el módulo automáticamente. El contador se resetea al completar un boot exitoso.

---

### 📲 Instalación

1. Descargá el ZIP desde [Releases](https://github.com/ByRafaelSystem/Project-Diablo/releases)
2. Abrí Magisk / KernelSU / APatch
3. Instalá desde ZIP
4. Reiniciá el dispositivo
5. Buscá **Diablo Pro** en el cajón de aplicaciones — se instaló automáticamente
6. Configurá DiabloAI, el gamelist y las reglas desde la app

> 💡 Si usás KernelSU también podés acceder desde **KSU → Project Diablo Pro → WebUI**

---

### ❓ Preguntas frecuentes

**¿Necesito KernelSU para usar la interfaz?**
No. La app de control se instala automáticamente con el módulo y funciona con Magisk, KernelSU y APatch. KernelSU WebUI sigue disponible como alternativa.

**¿Funciona en mi chipset?**
Project Diablo detecta automáticamente tu SoC. Si la detección falla, usá el botón CHIP ▾ en la tarjeta de estado.

**¿Qué modo recomendás para jugar?**
Con DiabloAI activado no necesitás elegir — agregá tu juego al gamelist con Gaming Pro y lo aplica solo.

**¿Puedo cambiar de modo sin reiniciar?**
Sí. Desde la app el cambio se aplica en 1–2 segundos.

**¿DiabloAI consume batería?**
El loop corre cada 1 segundo con lectura en memoria. Durante gaming la lectura de disco se reduce a cada 5 segundos. El consumo es negligible.

**¿Qué pasa si uso otro módulo de rendimiento?**
No se recomienda combinar con otros módulos de rendimiento.

---

### 📋 Changelog

#### v2.0 PRO — 2026
- **Nuevo**: App de Control nativa — se instala automáticamente al flashear el módulo
- **Nuevo**: Compatible con Magisk sin necesidad de KernelSU WebUI
- **Nuevo**: DiabloAI v2 con 6 reglas configurables
- **Nuevo**: Gamelist con modo individual por app
- **Nuevo**: Página AI dedicada con estado en tiempo real
- **Nuevo**: Sistema de bloqueo por app
- **Nuevo**: Modo por defecto configurable
- **Nuevo**: Sonido Portal de bienvenida (Web Audio API, 0 KB extra)
- **Nuevo**: Diablo 3D animado — activo con fuego / dormido con Zzz
- **Nuevo**: 5 pestañas de navegación
- **Nuevo**: Notificaciones dinámicas por modo
- **Nuevo**: Botones ? de ayuda en 5 idiomas
- **Nuevo**: Selección de chip manual (CHIP ▾)
- **Nuevo**: 3 niveles de Battery con slider
- **Nuevo**: Gaming Pro — red integrada (WiFi baja latencia, TCP gaming, buffers 4MB, RPS)
- **Nuevo**: Personaje Diablesa seleccionable
- **Nuevo**: Diablo Boost — parámetros de red exclusivos opcionales
- **Mejorado**: VM tweaks por perfil
- **Mejorado**: DiabloAI — cache de config cada 5s durante gaming
- **Mejorado**: DiabloAI — protección OOM del proceso del juego
- **Mejorado**: Touch Engine — todos los tweaks ahora se aplican correctamente
- **Mejorado**: Ciclo DiabloAI 4s → 1s
- **Mejorado**: Loop AI — lectura de config en memoria, de hasta 20s a menos de 1s
- **Corregido**: IDLE_TIMER acumula correctamente
- **Corregido**: Boot fluido — primer arranque ya no bloquea la inicialización

#### v1.3 UNIVERSAL — 2026
- DiabloAI con detección de juegos
- FastCharge Next con protección térmica
- Touch Engine con 4 perfiles
- Soporte universal Magisk/KSU/APatch
- 5 idiomas en WebUI

#### v1.1 — 2025
- Primera versión pública
- 4 modos de rendimiento
- KSU WebUI
- Soporte MTK/Snapdragon/Exynos

---

## 🇺🇸 English

### What is Project Diablo Pro?

Project Diablo Pro is an advanced performance engine for Android that optimizes CPU, GPU, memory and touch to maximize FPS and reduce lag. Version **Pro v2.0** introduces **DiabloAI v2** — an automatic intelligence system with 6 configurable rules that adapts on its own based on what you're doing.

---

### 📱 Control App — Diablo Pro App

Starting with v2.0, the module includes a **native Android app** that installs automatically when flashing. You no longer need KernelSU WebUI to control the module.

| Feature | Detail |
|---|---|
| 🔧 **Auto install** | Installs itself when flashing the module — no extra steps |
| 📱 **Native app** | Works from the app drawer like any regular app |
| 😈 **Custom icon** | Purple devil with black sunglasses |
| ⚡ **No lag** | Dedicated native WebView — none of the KSU WebUI lag |
| 🌐 **Universal** | Magisk, KernelSU and APatch — any root manager |
| 🔑 **Direct root bridge** | Runs commands with `su` without going through manager layers |
| 💾 **Custom banner** | Change the banner from the app with your own image |
| 📲 **Android 5.0+** | Compatible with any modern rooted Android |

> 💡 If you prefer KernelSU WebUI, it still works exactly the same. The app is a smoother, universal alternative.

---

### ✨ What's new in v2.0 PRO

| Feature | Description |
|---|---|
| 📱 **Control App** | Native app included in module — auto-installs on flash |
| 🤖 **DiabloAI v2** | 6 configurable rules — detects apps, temperature, low battery, idle and more |
| 🎮 **Smart Gamelist** | Assign a specific mode to each app. Not just games — any app |
| 📱 **Dedicated AI page** | Full DiabloAI control with real-time status |
| 🔒 **App lock system** | Locks the mode until the app closes completely |
| 🔔 **Dynamic notifications** | Shows the exact mode applied for each app |
| 😈 **Animated 3D Diablo** | Active with fire and sleeping with Zzz |
| 🔊 **Welcome sound** | Portal effect when opening (0 KB extra) |
| 🔊 **AI sounds** | Sound when activating/deactivating DiabloAI |
| 🎨 **New PRO design** | Purple + gold, 3D banner, 5 navigation tabs |
| ❓ **Help ? buttons** | 3 contextual buttons, translated in 5 languages |
| 🔋 **Battery levels** | 3 saving levels selectable via slider |
| 🔧 **Manual chip selection** | Fix the detected chipset from the status card |
| ℹ️ **Info ? in Status** | DiabloAI explanation, chip, Battery and priorities in 5 languages |
| 🌐 **Gaming Pro — Integrated network** | WiFi low-latency, gaming TCP, 4MB buffers, RPS — automatic |
| 👹 **Diablesa** | Second selectable character — tap the demon on the AI page |
| ⚡ **Optimized AI loop** | Config in memory — from up to 20s per cycle to under 1s |

---

### 🌐 Gaming Pro — Integrated network

| Optimization | Detail |
|---|---|
| WiFi low-latency | Prioritizes latency over power saving |
| No background scans | WiFi chip stops scanning for other networks during gameplay |
| TCP no idle slow-start | No speed reduction between packet bursts |
| TCP buffers at 4MB | `rmem_max/wmem_max` raised to avoid kernel truncation |
| WiFi queue 3000 | Handles burst traffic without dropping packets |
| RPS on 4 cores | Network interrupts distributed — always a free core available |
| No diagnostics | Stops `cnss_diag` and `tcpdump` that steal CPU during gameplay |

> 💡 Enable **Diablo Boost** from the app to add `netdev_max_backlog`, `tcp_fastopen` and WiFi no power save on top of Gaming Pro.

---

### 🔋 Battery levels

| Level | Governor | CPU | Best for |
|---|---|---|---|
| 🌿 **Soft** | schedutil | 50% max | Daily use with moderate saving |
| ⚡ **Moderate** | powersave | 25% max | Good saving without losing usability |
| 💀 **Aggressive** | powersave | Minimum | Full idle, maximum battery life |

---

### 😈 Available modes

| Mode | CPU | GPU | Best for |
|---|---|---|---|
| 🔥 Performance | Max governor | Max frequency | Sustained performance |
| ⚖️ Balance | Smart governor | Mid frequency | Daily use |
| 🔋 Battery | Saving (chosen level) | Min frequency | Maximum battery life |
| 😈 Gaming Pro | Absolute max | Max + FPSGO | Competitive gaming |

---

### ⚙️ Compatible root managers

| Manager | Min version | Control App | WebUI |
|---|---|---|---|
| Magisk | v20.4+ | ✅ Included in module | ❌ Not available |
| KernelSU | Any | ✅ Included in module | ✅ Available |
| APatch | Any | ✅ Included in module | ✅ Available |

---

### 🛡️ Diablo Protect

Built-in anti-bootloop system. After 3 consecutive failed boots, automatically disables the module so the phone can boot normally. Resets on successful boot.

---

### 📲 Installation

1. Download the ZIP from [Releases](https://github.com/ByRafaelSystem/Project-Diablo/releases)
2. Open Magisk / KernelSU / APatch
3. Install from ZIP
4. Reboot your device
5. Find **Diablo Pro** in your app drawer — installed automatically
6. Configure DiabloAI, gamelist and rules from the app

> 💡 If you use KernelSU you can also access from **KSU → Project Diablo Pro → WebUI**

---

### ❓ FAQ

**Do I need KernelSU to use the interface?**
No. The control app installs automatically with the module and works with Magisk, KernelSU and APatch. KernelSU WebUI is still available as an alternative.

**Does it work on my chipset?**
Project Diablo auto-detects your SoC. If detection fails, use the CHIP ▾ button in the status card.

**Which mode for gaming?**
With DiabloAI on you don't need to choose — add your game to the gamelist with Gaming Pro and it applies automatically.

**Can I switch modes without rebooting?**
Yes. From the app changes apply in 1–2 seconds.

**Does DiabloAI drain battery?**
Loop runs every 1 second with in-memory config. During gaming disk reads drop to every 5 seconds. Consumption is negligible.

---

## 🇧🇷 Português

### O que é Project Diablo Pro?

Project Diablo Pro é um motor de desempenho avançado para Android. A versão **Pro v2.0** apresenta o **DiabloAI v2** e agora inclui um **app nativo de controle** que se instala automaticamente ao flashear o módulo.

---

### 📱 App de Controle — Diablo Pro App

| Recurso | Detalhe |
|---|---|
| 🔧 **Instalação automática** | Se instala ao flashear o módulo — sem passos extras |
| 📱 **App nativo** | Funciona na gaveta de apps como qualquer app |
| 😈 **Ícone próprio** | Demônio roxo com óculos escuros |
| ⚡ **Sem lag** | WebView nativo dedicado — sem o lag do WebUI do KSU |
| 🌐 **Universal** | Magisk, KernelSU e APatch — qualquer gerenciador root |

---

### ✨ Novidades na v2.0 PRO

- 📱 **App de Controle** — App nativo incluído, se instala automaticamente
- 🤖 **DiabloAI v2** — 6 regras configuráveis
- 🎮 **Gamelist inteligente** — Modo específico para cada app
- 🔒 **Bloqueio por app** — Mantém o modo enquanto a app estiver na memória
- 😈 **Diablo 3D animado** — Ativo com fogo e dormindo com Zzz
- 🎨 **Design PRO** — Roxo + dourado, banner 3D, 5 abas
- 🔋 **Níveis de Battery** — 3 níveis de economia com slider
- 🔧 **Seleção de chip manual** — Corrija o chip direto na tela de status
- 🌐 **Gaming Pro — Rede integrada** — WiFi baixa latência, TCP gaming, buffers 4MB
- 👹 **D
