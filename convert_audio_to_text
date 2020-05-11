"""
Created on Sun May 10 18:36:20 2020

@author: john-
"""

import speech_recognition as sr
import time

r = sr.Recognizer()

with sr.AudioFile('arreglo2.wav') as source:
    audio = r.listen(source)
    try:
        print("Por favor, espere un momento...")
        text = r.recognize_google(audio, language='es-ES')
        time.sleep(1.5)
        print(text)
    except:
        print("¡Lo siento!, ¡No puedo entender!")
