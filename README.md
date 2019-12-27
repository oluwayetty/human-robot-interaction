# Human-robot-interaction
The task-oriented Spoken Dialogue System implemented in this homework is a restaurant waiter robot. The goal of this robot is to serve customers by taking their orders while giving them a list of the available types of menu based on Vegetarian and Non-Vegetarians, as the case may be), and provide them the requested meal in accordance to its availability.

## Tools used
All parts of this project was coded in python. The libraries used are highlighted below:
* Spacy: This is a python library that provides semantic analysis of text inputs. The text output from SpeechRecognition was supplied as input to this engine. It makes a total analysis of the supplied text from the user input, together with scenario parameters that we coded with it, then provides outputs, based on the scenario parameters. One of the outputs it provides is the dependency tree.

* gTTS: A python library and CLI tool to interface with Google Translate’s text-to-speech API. Writes spoken mp3 data to a file, a file-like object (bytestring) for further audio manipulation. This library was used to convert every text output from Spacy to a voice output for the user.

* SpeechRecognition: This is a python library for performing speech recognition, with support for several engines and APIs, online and offline. The API used for this work is the Google Cloud Speech API. It was responsible for accepting

* playsound: A pure Python, cross platform, single function module with no dependencies for playing sounds.

## Conclusion
The combination of Spacy, gTTS and SpeechRecognition makes a very powerful tool for Human Robot Interaction projects, allowing for a full speech-based interaction between robots and humans. We have modelled a few possibilities of what could happen during the interaction between the robot and human. A lot more things would happen in a real world scenario, hence, a lot of other considerations and tests would be considered for a production level system.
