# Programmeerimise_projekt_Ussimang
# Kood programeerimise projekti jaoks nimega "Ussimäng".

import pygame, random
from pygame.locals import *

#Värvid
valge=(255,255,255)
must=(0,0,0)
punane=(255,0,0)
roheline=(0,155,0)
algpikkus=4

#Ekraani mõõtmed
ekraani_laius=800
ekraani_korgus=600

pygame.init()
ekraan=pygame.display.set_mode((ekraani_laius,ekraani_korgus))
ekraan.fill(valge)
pygame.display.update()

def algus():
  while True:
    for event in pygame.event.get():
      if event.type==pygame.QUIT:
        pygame.quit()
        quit()
      if event.type==pygame.KEYDOWN:
        if event.key==pygame.K_s:
          False
        if event.key==pygame.K_q:
          pygame.quit()
          quit()
    gameDisplay.fill(valge)
    tekst_ekraanil("Ussimäng",roheline, size="")
    tekst_ekraanil("Alustamiseks vajuta s-klahvi",must)
    tekst_ekraanil("")
    tekst_ekraanil("")
    tekst_ekraanil("")

def tekst_ekraanil(tekst,värv,suurus):
  tekst=font.render(tekst,)


















pygame.quit
