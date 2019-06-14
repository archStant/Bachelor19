Udpak cullpdb+profile_5926.npy.gz i './data' før koden køres.

I './code' ligger fire filer:
- main.ipynb:		Single-task secondary structure model
- solvent_main.ipynb:	Single-task solvent accessibility model
- multi_main.ipynb:	Multi-task secondary structure model
- visualization.ipynb:	Peak performance og grafer

Alle kodefiler kan køres fra toppen.
Koden er CPU/GPU-agnostisk, men vælger at køre på GPU hvis der er en til stede og CUDA er installeret.
Hvis 'savefile' er slået til i visualization.ipynb bliver graferne gemt i './graphs'.
