# [Rpi]Security_System
Author: Andrea Santeramo
mail: andreasanteramo@gmail.com
# Description_project:

Con questo progetto ho voluto realizzare un piccolo sistema di domotica e videosorveglianza tramite una interfaccia web user-friendly ad il sistema di multipresa domotica su cui è presente anche un articolo nel sito.

Componenti utilizzati:
- raspberry-pi
- webcam USB
- Domotic_Multiple_Socket

Streaming video:
Lo streaming video è fornito dal programma mjpg-streamer che permette di avere una buona fluidità con poco utilizzo di risorse.

Communication:
La comunicazione tra pagine HTML e GPIO è stata realizzata tramite linguaggio PHP che all'occorrenza esegue specifiti script collocati nella memoria interna del raspberry.
