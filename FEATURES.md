# Built-in features for pressroom-os

Purpose: desktop publishing

1. **prepare a creative project** — run pressroom-os-workspace. It creates ~/Documents/pressroom-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run pressroom-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/pressroom-os-session-plans/.
3. **check project and export readiness** — run pressroom-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/pressroom-os-workspace features/pressroom-os-plan features/pressroom-os-check "$HOME/.local/bin/"
