# 🐟 Koi_Os Project

Welcome to the official home of **Koi_Os**—an independent operating system built from scratch for legacy mobile hardware. 

> 🚫 **Android is NOT Linux.** Modern Android has become a heavy, telemetry-bloated container packed with invasive AI models that exhaust device hardware and harvest user data. 
> 
> **Koi_Os is the antidote:** A stripped-down, ultra-optimized, mainline Linux kernel decoupled from Google and Samsung ecosystems. Our core engineering directive is to guarantee a **25+ year functional hardware lifecycle**.

---

## 📱 LIVE DEVICE SUPPORT LIST

To maintain strict hardware optimization and prevent bootloader bricking risks, Koi_Os only supports unlocked international hardware variations. 

### Supported Platforms:
* **Samsung Galaxy Note Edge (SM-N915FY)** — *Active Primary Testbed*
* **Samsung Galaxy Note Edge (SM-N915F)** — *Fully Compatible (International Platform)*

> ⚠️ **CRITICAL WARNING:** This system **DOES NOT** support and will **NEVER** support North American carrier variants (such as SM-N915A, SM-N915T, or SM-N915V). Attempting to flash this kernel onto these devices will result in a hard brick due to permanently locked carrier bootloaders.

---

## 📊 PROTOTYPE DEVELOPMENT STATUS (v0.0.0)

**Current Milestone:** Initial host configuration under Arch Linux and core kernel compilation.
[████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░] 6% / 100%
---

## 💡 CP (CORE PHILOSOPHY): NO EXTRA FLOUR

The structural engineering of Koi_Os follows a strict, unyielding law: **Do not add 10kg of flour to a car if you want it to run fast and last forever.** 

Modern smartphone companies use planned obsolescence to kill perfectly good hardware. They force heavy background tracking, continuous telemetry, and unoptimized cloud AI tasks into the system core. This cooks the silicon, degrades the battery, and chokes the GPU on basic tasks. 

Koi_Os strips out the "flour" using three technical pillars:
1. **Zero Data Harvesting:** No background analytics, no telemetry, and no AI tracking. Your private data is never packaged or sold to advertisers. This keeps the CPU completely cold to the touch.
2. **RAM-Based Execution:** To prevent the internal flash storage (eMMC chip) from wearing out over 25 years, the OS operates out of a memory-based filesystem (`tmpfs`). Storage is read only once at boot, extending the physical life of the chip indefinitely.
3. **Static Dependency Control:** Critical binaries (like BusyBox) are compiled statically. They carry their own code internally. This mathematically guarantees that a command executed in the year 2051 will run exactly as fast as it does today, unaffected by external software updates.

---

## 🎏 SYSTEM ARCHITECTURE & EDITIONS

Koi_Os uses a multi-tier distribution model named after legendary varieties of Koi fish, balancing raw hardware endurance with deep user customization.

### 🚀 1. Koi_Os Shiro (White Koi)
Shiro is designed for absolute minimalism, stripped down to essential system utilities.
* **Advantages (+):** Hyper-lightweight system footprint with zero background processing overhead. The CPU spends 99% of its runtime in a deep sleep state. Legacy hardware like a Samsung Galaxy S1 can realistically achieve 10+ years of active maintenance because the hardware operates under near-zero thermal or mechanical stress.
* **Disadvantages (-):** No graphical desktop manager or advanced layout customization. It provides a pure text-based shell and shell script automation infrastructure built exclusively for runtime longevity.

### 🎨 2. Koi_Os Utsuri (Patterned Koi)
Utsuri is engineered for complete cosmetic freedom and total user expression, drawing heavy visual inspiration from the mid-2000s **Frutiger Aero** aesthetic (glossy glass textures, water bubbles, and 3D iconography). It operates like a jailbroken mobile operating system on maximum overdrive.
* **Advantages (+):** A humongous open-source configuration engine. Every layout property is exposed to the user. You can modify system names, core iconography, search bar geometry, battery display visuals (such as animated fluids), and boot melodies natively. It offers 5x the customization density of stock smartphone frameworks.
* **Disadvantages (-):** High storage and memory overhead. Storing high-fidelity graphic assets and rendering custom compositing layers requires active CPU work. On older hardware like the Galaxy S1, this edition yields a shorter ~5 year optimal lifecycle before asset expansion creates visible lag, requiring a fallback to the Shiro edition.

### 💎 3. Limited Edition: Koi_Os Shiro Utsuri (Hyper-Optimized Hybrid)
The ultimate synthesis of both philosophies. Shiro Utsuri applies the unyielding, optimized base framework of Shiro and layers it with the rich customization capabilities of Utsuri.
* **Optimization Framework:** Customization without software bloat. The user interface logic is compiled in native C, and graphic assets are pre-rendered into fixed sizes on storage. This prevents the CPU from wasting clock cycles on real-time image scaling and layout calculations during menu navigation.
* **Hardware Ceiling Safeguard:** To fulfill the 10+ year lifecycle target on legacy hardware, Shiro Utsuri features a firm configuration freeze lock. When local system telemetry detects that modern UI customizability limits threaten hardware resource thresholds, the automatic update engine locks the core layer into a peak-performance state, preventing intentional or accidental software slowdown.

> 📝 **A PERSONAL NOTE FROM THE DEVELOPER**
>
> I would be very happy if this project was left unmodified by third parties. If you want to see Koi_Os running on a different device, please do not fork and alter the project blindly—simply request your target device model to be officially added. Keep in mind that Koi_Os is dedicated **ONLY to Samsung hardware** to keep its original development roots and engineering focus alive. 
> 
> Furthermore, let's keep the open-source community honest. Taking this code, cloning it, or stealing it without credit from a single, independent **12/13-year-old developer** who built this ecosystem from scratch would be incredibly low. Respect the origin, respect the licensing, and let's build something great together.

---
*Koi_Os is an open-source development project fighting planned obsolescence through pure, high-performance embedded systems engineering.*
