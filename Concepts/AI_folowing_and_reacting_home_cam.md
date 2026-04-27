# Spidercam System
## Contactless Spatial AI for Proactive Assistance

**Tagline:** *It never touches the ceiling. It doesn't have to.*

### 1. Core Concept
AI systems should not remain static — spatial adaptability improves interaction quality. 
Spidercam is a ceiling-mounted, magnetically levitating sensor unit that follows context 
and initiates interaction without user prompts.

### 2. Key Insight
Existing AI: box on table. Human: moves. Result: 50% blindness.
Solution: Move the sensors, not the human.

### 3. Technical Approach
- **Levitation**: Active magnetic suspension, 5-10cm clearance. No contact, no wear.
- **Docking**: Inductive charging nest in ceiling panel. Fail-safe drop to dock on power loss.
- **Stabilization**: IMU + Optical flow + PID @ 1000Hz. Target <2mm jitter.
- **Sensing**: 
    - Cheap tier: 60GHz mmWave + ToF. Gesture/pose only.
    - Pro tier: ToF + Global shutter IR + Edge NPU. Emotion via local face mesh.
- **Shielding**: Mu-metal foil layer. Contains field, prevents interference, ±2mm precision.
- **Power**: ~20-30W levitation + 10W compute. Inductive dock or thin tether.

### 4. Killer Use-Case
User nods at coffee machine. Spidercam checks: cup present? 
- Yes → "Brew coffee, Dariau?" 
- No → Laser pointer at machine + "Padėk puodelį".
Proactive, context-aware, no apps.

### 5. Market
Early adopters, accessibility, maker spaces. B2C 600€, B2B contracts.
Ecosystem lock-in: Spidercam + smart appliances.

### 6. Status
Concept. Awaiting technical validation. Next: 1D levitation PoC.

### 7. Principles
- Clarity over noise
- Logic over assumptions  
- Systems over isolated features
- Privacy: local processing, no cloud video