# Forensic

## Ressources

* [Interpol Guidelines](https://www.interpol.int/content/download/16243/file/Guidelines_to_Digital_Forensics_First_Responders_V7.pdf)

## Avant intervention

1. Disposer du matériel adéquat : duplicateur (Hardware write blocker), appareil photo, softwares, etc.

2. Disposer des templates de document : timeline, rapport

3. Informer les parties prenantes et faire valider la méthodologie de conservation des preuves en vue d'un dépôt de plainte.

## Pendant intervention

1. Horodater chaque action sur la timeline.

2. Après collecte, toujours travailler sur les copies

## Si la machine allumée

1. Isolation réseau

2. Capture de la RAM et des artefacts

3. Déchiffrement ou récupération de la clé de chiffrement

4. Arrêt et copie du disque

## Si la machine est éteinte

1. Ne pas l'allumer.

2. Copier le disque.

## Copie du Disque

> privilégier la copie physique afin de garantir l'intégrité des preuves.

* **Device to Device (clone)** : This can be performed by obtaining an exact bit-by-bit replica of an original device in another - previously wiped - device with equal or greater capacity.

* **Device to File (image)** : This can be performed by generating one or more files that contain, linked together, an identical copy of the original device. The most widespread is `dd` (`raw`) or `E01` formats

## Collecte d'artefact

* [FASTIR](https://github.com/SekoiaLab/Fastir_Collector)

* [FIR](https://github.com/certsocietegenerale/FIR)

## Misc

### Montage read only :

```bash
mount  -o loop,ro,noexec img.dd  /mnt
```
> ne remplace pas duplicateur avec un bloqueur Hardware en écriture.


### dc3dd : 

fork de dd mais qui tolère les clusters défectueux

```bash
dc3dd if=/dev/sdb hof=/mnt/extdrive/WKS042.dd log=/mnt/extdrive/dd_WKS042.log
```

Pour le montage il faut determiner le secteur du début de partition (NTFS)

```bash
mmls WKS042.dd
```

