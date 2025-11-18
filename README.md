# Sega-CD-Stamper

# Features

-   **Interactive stamp editor**
    
    -   Load, view and edit stamp maps (binary `.bin` / `.unc`).
        
    -   Active-stamp preview with H-flip and rotation controls.
        
    -   Click-to-paint and right-click-to-clear cells on the main map.
        
-   **Map editing tools**
    
    -   New map / Clear map / Fill options.
          
    -   Grid overlay toggle.
    
    -   Pan and zoom for large maps.
        
-   **Export & saving**
    
    -   Export visible canvas (map) to PNG.
        
    -   Export tile atlas or stamp map palette to PNG.
        
    -   Save edited stamp map as binary `.bin`.
        
    -   Generate 68K assembly (`.asm`) with configurable formatting (labels, words/line, comments).
        
----------

# Controls

## Mouse / Pointer

-   **Left click (stamp selector)** — select a stamp to make it active.
    
-   **Left click (main canvas)** — place the active stamp into the clicked cell.
    
-   **Right click (main canvas)** — clear the stamp at the clicked cell (erase).
    
-   **Mouse wheel** — zoom in / out (cursor-centered zoom).
    
-   **Click + drag (canvas container)** — pan the view while zoomed.
    
-   **Double-click (canvas container)** — reset pan and zoom to default (100%).
    
-   **Click + drag (stamp selector)** — scroll/pan the stamp selector if content overflows.
    

## Keyboard

-   **Arrow keys** — move selection in stamp selector (when focused).
    
-   **Space** — toggle H-flip on the active stamp.
    
-   **R** — rotate the active stamp (cycles 0° → 90° → 180° → 270°).
    
-   **Delete / Backspace** — clear the currently selected cell (when editing).
    
-   **Ctrl/Cmd + Z** — undo last edit (if undo is implemented).
    
-   **Ctrl/Cmd + Y** — redo (if redo is implemented).
    
-   **Enter** — confirm dialogs or apply current edit tool (context-dependent).
    
----------
