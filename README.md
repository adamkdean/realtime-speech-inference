```
Note: this is written ahead of building it.
```

# Realtime Speech Inference

Based on https://twitter.com/imdsm/status/1681654618609033221

![image](https://github.com/adamkdean/realtime-speech-inference/assets/1639527/a4cf3fe6-66ba-4b0d-bacf-f441bb6db8d5)

Realtime Speech Inference is a proof of concept prototype for revolutionizing speech technology.

## Project Overview

I have combined the power of three key technologies: OpenAI's Whisper ASR system for speech-to-text, GPT-4 for text-to-text translation, and a text-to-speech system that is yet to be determined.

Traditionally, speech technology relies on processing complete inputs, leading to delays and interruptions in conversational interactions. Realtime Speech Inference challenges this approach by introducing a real-time, cyclical solution for processing and generating speech.

In this project, I have implemented a mechanism where speech is continuously decoded into text using the Whisper ASR system, even while the user is still speaking. Simultaneously, the available speech is analyzed, and responses are generated in real time using the cutting-edge GPT-4 language model developed by OpenAI. The inferred text is then converted into speech using a chosen text-to-speech system.

By detecting pauses in speech, the system is able to respond seamlessly and naturally. This real-time processing allows for a fluid and dynamic interaction, closely resembling the ebb and flow of human conversation.

## Core Features

- **Real-time Speech-to-Text**: Convert spoken language into written text in real time, without waiting for the entire input to finish.

- **Real-time Text-to-Text Inference**: Utilize GPT-4 for generating responses in real time as the input is being processed.

- **Real-time Text-to-Speech**: Convert generated text into spoken language, ready to be delivered as soon as the user stops speaking.

These core features ensure a more natural and interactive experience with speech technology. As a solo developer and the originator of the idea, I am continuously working on finalizing the text-to-speech system and optimizing the overall approach.

## Tech Stack

- Speech to Text: Whisper ASR by OpenAI
- Text to Text: GPT-4 by OpenAI
- Text to Speech: To be determined

This project serves as a proof of concept and prototype for real-time speech inference. I invite developers interested in exploring the cutting edge of speech technology and end users seeking a seamless interaction with their devices to join me on this journey. Together, let's move towards real-time, natural language processing.

Stay tuned for updates as I continue to innovate and build upon this project inspired by my original tweet.

## Thanks

Note: GPT-4 mostly write this readme.
