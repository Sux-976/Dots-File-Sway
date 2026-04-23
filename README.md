# 🌌 Sway Dotfiles | Debian Stable

Este repositório contém minhas configurações pessoais para o **Sway WM**, rodando sobre a base sólida do **Debian**. O foco deste setup é o minimalismo, performance e uma estética escura com acentos em roxo neon.

---

## 🎨 Design System

* **Cor Base:** `#11111B` (Deep Dark Blue)
* **Acentos:** `#313244` (Foco) e `#cdd6f4` (Texto)
* **Gaps:** `5px` (Interno) | `0px` (Externo)
* **Cursor:** `Moga-Neon-Purple` (24px)
* **Bordas:** Desativadas para um visual *clean*

---

## 🛠️ Software Stack

| Componente | Aplicação |
| :--- | :--- |
| **Window Manager** | [Sway](https://swaywm.org/) (Wayland) |
| **Terminal** | [Kitty](https://sw.kovidgoyal.net/kitty/) |
| **Barra de Status** | [Waybar](https://github.com/Alexays/Waybar) |
| **App Launcher** | [Wofi](https://hg.sr.ht/~scoopta/wofi) |
| **Notificações** | [SwayNC](https://github.com/ErikReider/SwayNotificationCenter) |
| **Logout Menu** | [wlogout](https://github.com/ArtsyFarcy/wlogout) |
| **Captura de Tela** | Grim + Slurp |
| **Polkit** | LXPolkit |

---

## 🚀 Instalação (Debian)

Como este setup roda no Debian, certifique-se de ter os pacotes necessários instalados:

```bash
# Instalação das dependências principais
sudo apt update && sudo apt install \
    sway waybar wofi kitty sway-notification-center \
    grim slurp brightnessctl pulseaudio-utils lxpolkit \
    fonts-font-awesome fonts-firacode
```

---

## ⌨️ Atalhos de Teclado (Principais)

A tecla **Super** (`Mod4`) é o modificador principal do sistema.

### 🚀 Sistema & Apps
* **`Mod + Enter`** : Abrir Terminal (**Kitty**)
* **`Mod + D`** : Abrir Menu de Apps (**Wofi**)
* **`Mod + N`** : Central de Notificações (**SwayNC**)
* **`Mod + Shift + Q`** : Fechar Janela focada
* **`Mod + E`** : Abrir editor Geany

### 📋 Navegação e Layout
* **`Mod + Setas`** (ou `H J K L`) : Mover foco entre janelas
* **`Mod + Shift + Setas`** : Mover janela de lugar
* **`Mod + F`** : Alternar Tela Cheia (Fullscreen)
* **`Mod + Shift + Espaço`** : Alternar modo flutuante
* **`Mod + R`** : Entrar no **Modo Redimensionar**

### 🎵 Multimídia & Captura
* **`F8` / `F9`** : Controle de Volume (Baixar/Elevar)
* **`Print`** : Screenshot da tela inteira
* **`Mod + Print`** : Selecionar área específica para Screenshot

---

## 🔧 Notas Técnicas

* **Teclado:** Configurado nativamente para layout brasileiro (`br`).
* **Integração GTK:** O tema de cursor é forçado via `gsettings` para garantir compatibilidade estética com apps GNOME e Firefox.
* **Wallpaper:** O sistema busca automaticamente a imagem em `~/Downloads/wllll.jpeg`.

---

*Configurado com foco em produtividade por Ramon*

<img width="1366" height="768" alt="2026-04-23_08-46-43" src="https://github.com/user-attachments/assets/6dc5829f-c25f-4a5d-8dcc-3b70da3427c0" />

<img width="1366" height="752" alt="2026-04-23_08-49-33" src="https://github.com/user-attachments/assets/8b2e7b93-8d87-4d99-be49-a99d10ea6f28" />


### WayBar Opções:

Opção 1
<img width="1366" height="61" alt="2026-04-23_08-54-23" src="https://github.com/user-attachments/assets/f21096c7-9436-4743-9cad-1ac8d0307adc" />

Opção 2
<img width="1366" height="54" alt="2026-04-23_08-56-06" src="https://github.com/user-attachments/assets/6a4b11f4-1fba-477c-a097-d609dd25546f" />

### Wlogout

<img width="1366" height="765" alt="2026-04-23_08-56-52" src="https://github.com/user-attachments/assets/cc147531-7df9-483c-a780-3a8d3b423aff" />


