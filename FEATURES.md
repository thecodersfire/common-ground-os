# Built-in features for common-ground-os

Purpose: community coordination

1. **organize a personal routine** — run common-ground-os-workspace. It creates ~/Documents/common-ground-os-workspace/ with Plans, Journal, Reference folders.
2. **plan a personal session** — run common-ground-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/common-ground-os-session-plans/.
3. **check routine readiness** — run common-ground-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/common-ground-os-workspace features/common-ground-os-plan features/common-ground-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for community coordination:

1. **GNOME Calendar** — org.gnome.Calendar
2. **Audacity** — org.audacityteam.Audacity
3. **Foliate** — com.github.johnfactotum.Foliate

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
