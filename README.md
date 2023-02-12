
<h1 align="center">

<img src="https://img.shields.io/static/v1?label=morseTranslate%20POR&message=Bates&color=7159c1&style=flat-square&logo=ghost"/>

<h3> <p align="center">Morse Translate </p> </h3>

<h3> <p align="center"> ================= </p> </h3>

>> <h3> Resume </h3>

<p> Morse Code is a system of representing letters, numbers and punctuation marks through a coded signal sent intermittently.
In the <i> 'morseTranslate' </i> project we use a system developed in python that translates morse code to text and text to morse.
Although there are many translators on the internet, which this project is inspired by, a study was necessary to understand the grammar involved in segmentation of dots and dashes.
This project aims to help a more accurate translation of morse code for cryptography in generation. </p>

>> <h3> How install </h3> 

```

pip install morseTranslate

```

>> <h3> How Works </h3>

```
from morseTranslate import morseTranslate

morseTranslate = morseTranslate()
print(morseTranslate.to_text(".... . .-.. .-.. ---   .-- --- .-. .-.. -.."))
print(morseTranslate.to_morse("Hello World"))

```
>> <h3> Output </h3>

```
HELLO  WORLD
.... . .-.. .-.. ---   .-- --- .-. .-.. -..

```