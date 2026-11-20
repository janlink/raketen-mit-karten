# Explosion (Fehlstart) – Quellen

Alle Bilder in diesem Ordner stammen aus den „Free VFX Image Sequences & Flipbooks“ von Unity Labs:
https://unity.com/blog/engine-platform/free-vfx-image-sequences-flipbooks

Lizenz: CC0 1.0 (gemeinfrei), https://creativecommons.org/publicdomain/zero/1.0/
Zitat der Seite: „Here are some image sequences we want to share with you under CC0 license. Feel free to use them in your projects!“

| Datei          | Unity-Sequenz (Flipbook-Zip)                         | Raster | Zelle  | Mischung |
|----------------|------------------------------------------------------|--------|--------|----------|
| fireball.webp  | Explosion02HD (Explosion02HD-flipbooks.zip, 5x5)     | 5x5    | 320 px | Alpha    |
| blast.webp     | Explosion01 (Explosion01-flipbooks.zip, 5x5)         | 5x5    | 256 px | Alpha    |
| smoke.webp     | Explosion01-nofire (Explosion01-nofire-flipbooks.zip)| 5x5    | 256 px | Alpha    |
| fire.webp      | FireBall02 (FireBall02-flipbooks.zip, 8x8, Schleife) | 8x8    | 128 px | additiv (schwarzer Grund) |

Umgebaut (Zellen auf ganze Pixel neu gerastert, verkleinert, WebP) mit einem kleinen PIL-Skript; die Bilder selbst sind unverändert.
Layout: gleich große quadratische Zellen ohne Rand, Bild k liegt in Spalte k % cols, Zeile floor(k / cols), von oben links.
