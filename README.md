# speech-to-text-conversion

decode/convert "speech-to-text" using SpeechReconition library/package
- each Recognizer instandce has several methods for recognizing speech from an audio source using various APIs.
= recognize_bing(): Microsoft Bing Search
- recognize_google() : Google Web Speech API
- recognize_google_cloud(): -require installation of G-cloud speech package
- recognize_houndity()
- recognize_ibm(): IBM Speech to Text
- recognize_sphinx(): require installing PocketSphinx
- recognize_wit()

* $pip install SpeechRecogniiton if not installed
* read voice data in
* apply recognizer-google( ) method to convert the voice file into text output
