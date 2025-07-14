# rpmspec-for-OpenaiWhisper

Whisper is OpenAI's speech-to-text model that achieves state-of-the-art results on
speech recognition benchmarks. It is a multi-language, multi-task model that can
perform speech recognition, translation, and language identification. The model is
trained on a large dataset of multilingual and multitask supervised data collected
from the web.

This package provides the command-line interface for using Whisper for speech-to-text
conversion, making it easy to transcribe audio files into text.


This is a RPM packaging around Whisper for a podman instance I am using for a partner, 
as this is something that can be useful for anyone, I decided to put it in the wild.


I am downloading this Python package from https://pypi.org/project/openai-whisper/#files 
and packagingng it using the following steps:

I am leaving here the source rpm and  binary for the current Fedora (42).

