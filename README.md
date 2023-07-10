# Electron Assistant

Boilerplate of whisper.cpp + chatGPT + Electron.


## Instructions

- Expose OPENAI_API_KEY env variable in your shell
- Copy .env.sample to .env
- create `bin` folder in root directory and add required binaries :
  - whisper -> main program from whisper.cpp
  - sox
  - at least one ggml whisper model
- [Mac M1 binaries](https://www.dropbox.com/sh/ncxavljogsb6xch/AACzK0t2zWpZTT0EahDWDz-0a?dl=0) at your own risk
- Expect many bugs and hacks
- `pnpm i`
- `pnpm dev`
