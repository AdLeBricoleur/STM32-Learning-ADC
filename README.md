# STM32-Learning-ADC
Ce dépôt correspond à mon apprentissage de l'ADC et de l'UART TX sur STM32L476RG.

Je travaille sur un Nucleo-L476RG.

Pour connaître la configuration des Horloges et des Pinouts, il faut afficher le fichier .ioc sur CubeMX.

Ensuite, j'ai codé dans le fichier Core/Src/main.c. J'utilise l'IDE CubeIDE.

J'ai noté mes observations dans le Dossier Compte_Rendu.

J'avais plusieurs objectifs :
- utiliser l'ADC en mode polling
- Utiliser l'UART TX en DMA pour renvoyer les valeurs de l'ADC
- utiliser l'ADC avec un DMA
