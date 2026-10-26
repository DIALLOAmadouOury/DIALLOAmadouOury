# Amadou Oury Diallo

**Élève ingénieur en dernière année (Bac+5) en instrumentation et systèmes embarqués — Sup Galilée**  
**Firmware C/C++ · STM32 · FPGA/VHDL · Temps réel · Traitement du signal**

Je développe des systèmes où le code doit fonctionner avec le matériel : acquisition de capteurs, commande, traitement du signal, communication et validation sur cible. Mes projets vont du firmware STM32 à la robotique, avec une place particulière pour l'intégration et les essais.

**Je recherche un stage de fin d'études de 6 mois, avec un démarrage en mars 2027, partout en France.**

## Projets à découvrir

### [FADEC Digital Twin — commande, FreeRTOS et IA embarquée](https://github.com/DIALLOAmadouOury/FADEC-DigitalTwin)

Prototype sur **STM32L475** combinant un moteur **simulé**, une régulation **PID**, plusieurs tâches **FreeRTOS**, une détection expérimentale d'anomalies via **X-CUBE-AI** et une supervision **Python** par Wi-Fi/MQTT.

**Dans le code :** [régulation PID](https://github.com/DIALLOAmadouOury/FADEC-DigitalTwin/blob/main/Core/Src/fadec_core.c) · [tâches embarquées](https://github.com/DIALLOAmadouOury/FADEC-DigitalTwin/blob/main/Core/Src/main.c) · [README et démonstration](https://github.com/DIALLOAmadouOury/FADEC-DigitalTwin)

### [Reconnaissance de gestes — TinyML sur STM32](https://github.com/DIALLOAmadouOury/STM32-gesture-recognition)

Acquisition d'un accéléromètre **LSM6DSL en I²C**, traitement de fenêtres de données en **C**, inférence d'un réseau **Float32 directement sur STM32L475** avec X-CUBE-AI, puis affichage des résultats sur PC par **UART/Python**.

**À voir :** [firmware d'acquisition et d'inférence](https://github.com/DIALLOAmadouOury/STM32-gesture-recognition/blob/main/stm32_firmware/Core/Src/gesture_ia.c) · [vidéo de démonstration](https://raw.githubusercontent.com/DIALLOAmadouOury/STM32-gesture-recognition/main/assets/video_demo.mp4)

### [Robot autonome — Coupe de France de Robotique 2025](https://github.com/DIALLOAmadouOury/Robot-Autonome)

Projet **réalisé en équipe** : robot principal et PAMIs, intégration mécanique/électronique, programmation **Arduino/C++**, encodeurs, asservissement **PID**, capteurs ultrasoniques et essais sur le terrain.

**À voir :** [code de commande des moteurs](https://github.com/DIALLOAmadouOury/Robot-Autonome/blob/main/Software/Moteurs.cpp) · [photos et démonstrations](https://github.com/DIALLOAmadouOury/Robot-Autonome)

## Compétences mises en pratique

- **Développement embarqué :** C, C++, STM32, HAL, FreeRTOS, interruptions, DMA, UART, I²C, SPI
- **Électronique numérique et signal :** VHDL, FPGA Nexys A7, Vivado, acquisition, filtrage FIR/IIR
- **Commande et intégration :** PID, capteurs, motorisation, essais sur carte et mise au point
- **Outils et IA embarquée :** Python, Git, STM32CubeIDE, TensorFlow Lite, STM32 X-CUBE-AI

> Les dépôts documentent des prototypes et travaux de formation. Les limites de validation et les choix techniques sont précisés dans chaque README.
