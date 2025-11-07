# PwAirport - Mixed Reality Project

Progetto Unity di Mixed Reality sviluppato da Gruppo1 per **Meta Quest (Oculus)**.

## Informazioni Progetto

- **Nome:** MRProject (PwAirport)
- **Piattaforma:** Meta Quest / Oculus (Android-based)
- **Unity Version:** Compatible with Unity 2021.3+
- **Template:** Unity Mixed Reality Template v2.2.0

## Tecnologie Utilizzate

- **XR Interaction Toolkit** v3.2.1
- **XR Hands** v1.6.1 (Hand tracking per Meta Quest)
- **AR Foundation**
- **Unity Input System**

## Requisiti

- Unity 2021.3 o superiore
- Android SDK (API Level 32)
- Meta Quest 2/3/Pro con supporto MR
- Oculus Integration SDK (se necessario)

## Setup

1. Clonare il repository
2. Aprire il progetto con Unity
3. Attendere che Unity importi tutti i package necessari
4. Configurare le impostazioni Android in Build Settings

## Build per Meta Quest

Per buildare il progetto per Meta Quest:
1. File > Build Settings
2. Selezionare Android platform
3. Collegare il Meta Quest via USB (con Developer Mode attivo)
4. Cliccare su Build and Run per installare direttamente sul visore

**Note:** Il progetto è compilato per Android perché Meta Quest utilizza Android come sistema operativo.

## Struttura Progetto

```
Assets/
├── MRTemplateAssets/     # Asset personalizzati del progetto
│   └── Scripts/          # Script C# principali
├── Samples/              # Esempi da XR Toolkit e XR Hands
└── Scenes/               # Scene Unity
```

## Contributi

Progetto sviluppato da Gruppo1.
