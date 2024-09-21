[![Compile Sketch](https://github.com/pixelEDI/GitHubAction_ArduinoR4/actions/workflows/compile-sketch.yaml/badge.svg)](https://github.com/pixelEDI/GitHubAction_ArduinoR4/actions/workflows/compile-sketch.yaml)

# GitHub Actions
Eine kurze Einführung mit Arduino und ESP32 Codes.  Wir verwenden dafür vordefinierte Aktionen, die das Kompilieren von Sketches ermöglichen und wie du deine CI/CD-Pipeline so einrichtest, 
dass deine Arduino- und ESP32-Codes automatisch überprüft werden

## Videos
Playlist: https://www.youtube.com/playlist?list=PLluslK6uBf4tOir-zkFXTTtdfZk6BK0MW

## Alle Repos zur Serie
- https://github.com/pixelEDI/GitHubAction_ArduinoR4
- https://github.com/pixelEDI/GitHubAction_ESP32XIAO
- https://github.com/pixelEDI/GiteaAction_ArduinoR4
- https://github.com/pixelEDI/GIiteaAciton_pio_ESP32XIAO

## übersicht
```mermaid
graph TD

    A[GitHub] -->|Video 1| BB[GitHub Actions]
    BB --> BB2[CI/CD bei MCU]
    BB2 --> B[Action arduino/compile-sketches]
    B -->|Video 1| B1[Arduino CLI im Hintergrund]
    B1 --> B2[Verwendung vorgefertigter Action]
    B2 --> B3[Kompilierung eines Arduino R4 Sketches]
    B3 --> B4[Mit Libraries]
    
    B --> |Video 2| C[ESP32 Plattform]
    C --> C1[ESP32 Kompilierungen]
    C1 --> C2[Mit Libraries]
    C2 --> C3[Matrixfunktion für Mehrfachkompilierung C3/S3/C6]

    D[Gitea] --> |Video 3| D1[Self-hosted Runner Installation]
    D1 --> D2[Nachbau einer Aktion mit Bash]
    D2 --> D3[Arduino Sketch Kompilierung]
    
    D --> |Video 4| E1[Self-hosted Runner mit PlatformIO]
    E1 --> E2[Bash Kompilierung von ESP32-Dateien]
    E2 --> E3[Mit Libraries]

    style A stroke:#f96,stroke-width:2px
    style BB stroke:#f96,stroke-width:2px
    style BB2 stroke:#f96,stroke-width:2px
    style B stroke:#f96,stroke-width:2px
    style B1 stroke:#f96,stroke-width:2px
    style B2 stroke:#f96,stroke-width:2px
    style B3 stroke:#f96,stroke-width:2px
    style B4 stroke:#f96,stroke-width:2px
```
