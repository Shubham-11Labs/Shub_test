# Shub_test

This project uses the official ElevenLabs JavaScript SDK (`@elevenlabs/elevenlabs-js`).

```bash
npm install
```

```js
import { ElevenLabsClient } from "@elevenlabs/elevenlabs-js";

const client = new ElevenLabsClient();
```

Set `ELEVENLABS_API_KEY` in the environment, or pass `{ apiKey: "..." }` to the client constructor.
