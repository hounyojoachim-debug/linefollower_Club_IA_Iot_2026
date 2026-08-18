# linefollower_Club_IA_Iot_2026
[![Arduino Uno](https://img.shields.io/badge/Arduino-UNO-blue?style=for-the-badge)](https://circuitdigest.com/microcontroller-projects/arduino-uno-line-follower-robot)
[![Embeded C](https://img.shields.io/badge/Language-EmbeddedC-orange?style=for-the-badge)]()
![Club_IA_Iot_IFRI 2026](https://img.shields.io/badge/Club_IA__Iot-red?style=for-the-badge&logo=ifri-uac&logoColor=red&logoSize=auto&label=IFRI&labelColor=555555&color=blue&cacheSeconds=300&link=http%3A%2F%2Fwww.ifri-uac.bj%2F
)

Ce projet est un robot suiveur de ligne réalisé pour le compte du Club IA_Iot de l'IFRI au tire de l'année 2026. Ce robot, intègre un **Arduino Uno**; des **Capteurs Infrarouge(IR)**; un **shield L293D**; des **moteurs de 12V 25GA370**
Le principe de fonctionnement du robot repose sur la détection d'une ligne noire sur un fond blanc par les capteurs IR grace au phénomène de refraction de l'infra-rouge.

 ! [Fonctionnement du robot suiveur de ligne]()

<!--Démo-->

- Détection d'une ligne blanche sur un fond noir;
- Traitement de la réflexion de l'infra rouge par les trois capteurs situé aux extrémités et au milieu du chassis;
- Possiblités de mouvement dans trois directions: droite, gauche et en ligne droite;
- Controle de la direction des  moteurs par le **shield L293D**;
- Controle de tout le système par les cerveaux moteurs **Arduino Uno**

---

## 🛠️ Composants Matériels

| Composants             | Nombre   |Rôle(s)                                       |
|------------------------|----------|----------------------------------------------|
| Arduino UNO            | 1        | Cerveau du Robot                             |
|Shield L293D            | 1        | Contrôle des moteurs                         |
| Capteurs Infrarouge    | 3        | Distinction de la ligne noire sur le fond blanc                                                                              |
| moteurs de 12V 25GA370 | 2        | Rotation des roues                           |
| Chasis                 | 1        | Support de tout les composants               |
| Piles de 4,5 V         | 3        | Amimentation du circuit en électricité                                                                        |
|Roues                   | 2        |  Mobilité du robot  

---





---

## 💻 Composants Logiciels

| Composants             | Source      |Rôle(s)                                       |
|------------------------|----------   |----------------------------------------------|
| test.uno               |site /////// | Vérification du fonctionnement des moteurs   |
|Dimensions_Chasis       |            | Impression en 3D de la chasis                |
| code.uno               | -           | Fonctionnement logique du robot              |
---




## ⚙️ Fonctionnement détaillé

Le robot  a pour tache de suivre une ligne noire sur un fond blanc quelque soit sa trajoctoire.
Pour ce faire, le robot se sert de trois capteurs infra-rouge. En réflétant la IR, les capteurs collectent en temps réels les informations nécesaires au controle du robot. 
Par la suite, ces informations sont envoyés au micro controleur(Arduino Uno) qui procède à un traitement de l'informations et en sort les données sur les mouvements à effectuer. Ces données sont transférer au Shield qui fait tourner les moteurs dans un sens et à une vitesse précise pour permettre au robot se suivre toujours la ligne.



## 🧭 Logique de Navigation













## 🔌 Schématisation du Circuit

