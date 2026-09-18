# Rice Ball Ninja — Browser Voice Studio

A personal browser-based voice cloning and dialogue generator.

- Runs in the browser with WebGPU/WASM.
- Voice cloning is local to the browser.
- Multiple saved voices are supported.
- Dialogue lines use `Voice 1 [Mike] ...` / `Voice 2 [Aru] ...`.
- Bracketed Chatterbox tags such as `[laugh]`, `[sigh]`, etc. can be passed through to the model.
- Generated audio is encoded to MP3 in the browser.
- No Python, desktop app, command line, or API key is required.

The first model load downloads the model files to the browser cache. Generated voice samples are processed in-browser.
