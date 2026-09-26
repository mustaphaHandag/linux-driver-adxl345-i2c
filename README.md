# Driver Linux pour capteur ADXL345 (I2C)

## Objectif
Implementer un systeme Linux embarque et developper un driver noyau pour l'accelerometre ADXL345, en explorant toute la chaine : bootloader, kernel, device tree, systeme de fichiers racine, jusqu'a l'ecriture d'un module noyau communiquant en I2C avec le capteur.

## Contenu du depot

• adxl345.c : driver noyau Linux en C pour le capteur ADXL345 (bus I2C)

• Makefile : compilation du module noyau

• TP1-Embedded Linux.pdf, TP2.pdf, TP3.pdf : sujets des travaux pratiques (boot embarque, kernel, device drivers)

## Competences mises en oeuvre

• Mecanismes de boot embarque (bootloader vers kernel vers rootfs)

• Configuration du device tree

• Communication I2C entre le noyau Linux et un peripherique materiel

• Compilation d'un module noyau et tests sur environnement virtualise QEMU

## Compilation
make

## Tests
Le driver a ete developpe et teste sur un environnement Linux embarque virtualise avec QEMU.

## Contexte
Projet realise dans le cadre du Master 2 Systemes Embarques et Traitement de l'Information, Universite Paris-Saclay.
