# Programmeerimise_projekt_Ussimang
#Kood programeerimise projekti jaoks nimega "Ussimäng".
import pygame, random
from pygame.locals import *

#Värvid
valge=(255,255,255)
must=(0,0,0)
punane=(255,0,0)

ekraani_laius=800
ekraani_korgus=600

pygame.init()
ekraan=pygame.display.set_mode((ekraani_laius,ekraani_korgus))
ekraan.fill(valge)
