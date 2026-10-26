# Vocab Voice

Talk with Riddhi, a cheerful 3D tutor who helps you learn English words by voice.

**Live:** https://riddhigangbhoj.github.io/vocab-voice/

## How to use

1. Open the link in Chrome or Safari (desktop or phone).
2. Press **Start playing** and allow the microphone.
3. Talk when the pill under the reply box is green and says "Mic is on". You can also type.
4. Tell Riddhi what you want to learn. She adapts to your level, quizzes you, and gives points for right answers (5 for close ones).

If the mic pill is red, tap it to turn the mic back on.

## How it works

- 3D avatar with lip sync: [TalkingHead](https://github.com/met4citizen/TalkingHead) (three.js).
- Voice: ElevenLabs text to speech, and ElevenLabs Scribe for live speech to text.
- Brain: an Azure OpenAI model plays Riddhi.
- This repo is the static site only. A small backend on Google Cloud Run holds the API keys, so no key is in this code.

## Updating the site

Replace the files in this repo with the new build and commit. GitHub Pages republishes in about a minute
(Settings → Pages → Deploy from a branch → `main` / root).

## Credits

Avatar: Ready Player Me via TalkingHead, licensed CC BY-NC 4.0 (non-commercial use).
