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
⌨️ Atalhos de Teclado (Principais)
A tecla Super (Mod4) é o modificador principal.

Geral
Mod + Enter : Abrir Terminal (Kitty)

Mod + D : Abrir Menu de Apps (Wofi)

Mod + N : Central de Notificações (SwayNC)

Mod + Shift + Q : Fechar Janela focada

Mod + P : Esconder/Mostrar Waybar

Mod + E : Abrir editor Geany

Navegação e Layout
Mod + Setas ou H J K L : Mover foco

Mod + Shift + Setas : Mover janela

Mod + F : Tela cheia (Fullscreen)

Mod + Shift + Espaço : Alternar modo flutuante

Mod + R : Entrar no Modo Redimensionar

Multimídia e Sistema
F8 / F9 : Controle de Volume

Print : Screenshot da tela inteira

Mod + Print : Selecionar área para Screenshot

Mod + Shift + E : Sair do Sway

🔧 Notas Técnicas
Teclado: Configurado para layout brasileiro (br).

Integração GTK: O tema de cursor é forçado via gsettings para que aplicativos como Firefox sigam a estética do sistema.

Wallpaper: Atualmente configurado para ler de ~/Downloads/wllll.jpeg.

Configurado com foco em produtividade por [Seu Nome]
