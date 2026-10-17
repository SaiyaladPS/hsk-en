English speech recognition assets for English Quest

The speech check runs locally in the browser with Vosk Browser 0.0.8 and the
Vosk small US English model vosk-model-small-en-us-0.15. It does not upload
recorded microphone audio to an online speech service.

The language model is about 40 MB. Keep model.tar.gz beside vosk.js so the
offline speech recognizer can load it from this folder.

Vosk Browser source: https://github.com/ccoreilly/vosk-browser
Vosk English model source: https://alphacephei.com/vosk/models
Both are distributed under Apache License 2.0. See VOSK-BROWSER-COPYING.txt.
