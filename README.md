## Ziyaad Mallick

19, Karachi. CS at IBA.

Most of what I build runs without a network. Mobile data is metered here and the connection
drops most days, so local-first is just the default rather than a position I argue for.

**[voicenote](https://github.com/ziyaad-mallick/voicenote)** — offline voice notes in the
terminal. Vosk small-en does the ASR, a local Ollama model turns the transcript into a
titled, tagged Markdown note. No account, no API key, nothing on the network. There are
three swappable ASR backends, including one API path I keep only so I have something to
measure the local ones against.

**[ramble](https://github.com/ziyaad-mallick/ramble)** — the same idea on Android, in
Flutter, running on-device Gemma through `flutter_gemma` alongside the platform speech
recogniser. No backend to talk to.

**[nok](https://github.com/ziyaad-mallick/nok)** — a desktop agent you summon by knocking
on your laptop chassis. Two knocks for a screenshot or play/pause, three for an agent. Wake
detection is local audio under 200ms, the action layer is whitelisted, and it ships with no
UI at all by default. 321 tests.

**[ghostwriter](https://github.com/ziyaad-mallick/ghostwriter)** — a writing-style analyser
and rewriter that runs locally with no LLM in it anywhere.

**[mughal_shatranj](https://github.com/ziyaad-mallick/mughal_shatranj)** — a chess engine in
C++17 with an SFML interface and a minimax opponent with alpha-beta pruning.

Away from the terminal I co-found things. A street-food brand in Karachi, and a cafe loyalty
platform currently running paid pilots.

[LinkedIn](https://linkedin.com/in/ziyaadmallick) · zii.mallick@gmail.com
