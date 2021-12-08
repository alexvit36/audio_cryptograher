# audio_cryptograher
The project has been created for Information Protection subject
# Description
In this project we implement the process of steganography in audio file. 
We use Blum Blum Shub pseudorandom number generator to select bites, which are selected for encrypting our message.
In Steganographer.py encrypting and decoding processes are implemented.
In Audio.py audio file is divided into frames, so our message can be encrypted.
In generate_keys.py private and public keys are generated with RSA algorithm.
Interface file encoder.py use written methods to encrypt message into audio file and create new audio file, aurally the same with the source audio.
Interface file decoder.py use tten methods to decode message from created audio file.
# How to build and run
```
./setup.sh
./generate_keys.py
./encoder.py
./decoder.py
```
# Note
Parser is available by adding -h to end of running command: ./encoder.py -h and ./decoder.py -h. In the following message available operations are showed.
