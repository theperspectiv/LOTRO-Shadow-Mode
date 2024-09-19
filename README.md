# Shadow Mode
Ultra-Minimalist Dark Mode skin for LOTRO UI

## To-Do
### General

- delete redundant deps (SIM CORE)

- make distinct variants for buttons/selection indicators that currently use the same sprite
    - box_questJournal_entry_center_hightlight/box_questJournal_entry_center_pressed (quest_selection_highlight_center.tga)

- implement all toolbar options
    - Wide Skinned (uses default toolbar, no config edits neded, based on Azure Glass Wide universal)
    - Wide Minimal (based on _JRR Azure Glass Custom - Ultrawide Basic)
    - Short Skinned (based on SmallBar Reforged)
    - Short Minimal (based on JRR Azure Glass Custom short BGM)

- check for and clean up duplicate/redundant mapping entries
    - toolbar

- fix crafting panel width weirdness
    - currently fixed by reverting to vanilla layout (ie removing Adra's customized version). Works but could be better. 

### Elements

- titlebar
    - polish outline

- titlebar buttons
    - make buttons

- storage panel section hover outline 

- dropdown arrow
    - make wings shorter on hover & pressed state
    - make normal state slightly bigger and lighter, and add outline 

- slider handle and arrows
    - polish, test all

- textbutton
    - taller
    - AA corners

- innerpanel (crafting right panel)

- basepanel (tooltips)

- dropdown (options menus)

- silver (main window/panel bg)
    - semi-transparent?

- scrollbars
    - smoother outline gradient

## Maybe Do

- migrate custom-toolbar-compatible attunement config from JRR variants
- make distinct variants for silver assets that currently use the same sprite
    - (box_silver_bottom_left_noadorn_min, box_silver_bottom_left_light, etc)