# Amadou Oury Diallo

**Élève ingénieur en dernière année (Bac+5) en instrumentation et systèmes embarqués — Sup Galilée**  
**Firmware C/C++ · STM32 · FPGA/VHDL · Temps réel · Traitement du signal**

Je développe des systèmes où le code doit fonctionner avec le matériel : acquisition de capteurs, commande, traitement du signal, communication et validation sur cible. Mes projets vont du firmware STM32 à la robotique, avec une place particulière pour l'intégration et les essais.

**Je recherche un stage de fin d'études de 6 mois, avec un démarrage en mars 2027, partout en France.**

## Trois projets, trois défis techniques

### 🚀 [FADEC Digital Twin — Réguler un moteur simulé et détecter une anomalie](https://github.com/DIALLOAmadouOury/FADEC-DigitalTwin)

**L'objectif :** réaliser sur STM32 un démonstrateur capable de **suivre une consigne de régime moteur**, puis de **repérer un changement de comportement lorsqu'une fuite de carburant est simulée**.

Un **correcteur PID** pilote le modèle moteur ; un petit réseau de neurones embarqué analyse son état. Les informations remontent vers un tableau de bord Python, où l'on peut déclencher une fuite simulée et observer l'alerte. Le tout associe **C embarqué, FreeRTOS, X-CUBE-AI et Wi-Fi/MQTT**.

**[Voir les captures : fonctionnement normal vs fuite simulée](https://github.com/DIALLOAmadouOury/FADEC-DigitalTwin#démonstration-de-la-supervision)** · **[Explorer le firmware STM32](https://github.com/DIALLOAmadouOury/FADEC-DigitalTwin/tree/main/Core/Src)**

*Il s'agit d'un moteur simulé et d'un prototype expérimental, pas d'un FADEC aéronautique certifié.*

### ✋ [Reconnaissance de gestes — Faire tourner l'IA directement sur STM32](https://github.com/DIALLOAmadouOury/STM32-gesture-recognition)

**L'objectif :** reconnaître un geste tracé dans l'air **sans envoyer les mesures à un serveur ou déléguer la reconnaissance au PC**.

Le STM32 relève les accélérations de la main via un capteur **LSM6DSL**, prépare les données en **C**, puis exécute localement un réseau de neurones **X-CUBE-AI**. Le prototype distingue **L, O, Z et BRUIT** ; une interface Python affiche seulement le résultat reçu par UART.

**[▶ Voir la démonstration vidéo](https://raw.githubusercontent.com/DIALLOAmadouOury/STM32-gesture-recognition/main/assets/video_demo.mp4)** · **[Lire le code d'acquisition et d'inférence](https://github.com/DIALLOAmadouOury/STM32-gesture-recognition/blob/main/stm32_firmware/Core/Src/gesture_ia.c)**

### 🤖 [Robot autonome — Passer de la conception à un robot sur le terrain](https://github.com/DIALLOAmadouOury/Robot-Autonome)

**L'objectif :** construire, en équipe, un robot autonome capable de **se déplacer avec précision et d'exécuter des actions sur le terrain** lors de la Coupe de France de Robotique 2025.

Le projet réunit motorisation, électronique, capteurs et programmation **Arduino/C++**. Pour corriger les écarts de déplacement entre moteurs, le robot utilise les **encodeurs et un asservissement PID**. Nous avons aussi conçu et intégré des **PAMIs**, petits robots complémentaires.

**[Voir le robot en compétition (photos et animation)](https://github.com/DIALLOAmadouOury/Robot-Autonome#le-robot-en-compétition)** · **[Consulter le code de l'asservissement](https://github.com/DIALLOAmadouOury/Robot-Autonome/blob/main/Software/Moteurs.cpp)**

*Projet collectif de six étudiants ; les contributions et les essais sont détaillés dans le dépôt.*

## Compétences mises en pratique

- **Développement embarqué :** C, C++, STM32, HAL, FreeRTOS, interruptions, DMA, UART, I²C, SPI
- **Électronique numérique et signal :** VHDL, FPGA Nexys A7, Vivado, acquisition, filtrage FIR/IIR
- **Commande et intégration :** PID, capteurs, motorisation, essais sur carte et mise au point
- **Outils et IA embarquée :** Python, Git, STM32CubeIDE, TensorFlow Lite, STM32 X-CUBE-AI

> Les dépôts documentent des prototypes et travaux de formation. Les limites de validation et les choix techniques sont précisés dans chaque README.
