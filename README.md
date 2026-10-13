Backend engineer, ten years, mostly consumer products at scale. Principal Software Engineer at [Turnip](https://zaps.design), looking after the platform behind 25M users and the AI infrastructure sitting on top of it.

The rest of the time I build my own things, from training the model to shipping the app.

### Models

- [**VoxLock**](https://huggingface.co/arbazsiddiqui/voxlock) · Keeps the caller's voice and removes the other voices in the room before speech-to-text hears them. The lowest word error rate on the Krisp Voice Isolation Benchmark of every model tested, paid or open. Streams on CPU, works as a Pipecat audio filter, and runs in your browser: [try it on your own voice](https://www.arbazsiddiqui.me/voxlock/#demo). [Code](https://github.com/arbazsiddiqui/voxlock) · `pip install voxlock`
- [**kev-0.6b-browser-use**](https://huggingface.co/arbazsiddiqui/kev-0.6b-browser-use) · A 0.6B decision model for browser agents that picks the element and the action in one forward pass. 32.2% step success on Mind2Web, level with Kev-9B at a fifteenth of the size, and it runs in the browser on WebGPU. [Code](https://github.com/arbazsiddiqui/kev-browser-use) · [Write-up](https://www.arbazsiddiqui.me/kev/)
- [**Ozan-v1-12B**](https://huggingface.co/arbazsiddiqui/Ozan-v1-12B) · An open creative-writing model fine-tuned from Mistral-Nemo on $40 of GPU. Lowest slop score of any 12B measured on EQ-Bench. #1 trending on Hugging Face, 3K+ downloads. Hosted on [Featherless](https://featherless.ai/models/arbazsiddiqui/Ozan-v1-12B), try it with no download. The [training recipe](https://github.com/arbazsiddiqui/Ozan) is public.

### Apps

- [**Iris**](https://apps.apple.com/in/app/iris-period-cycle-tracker/id6761134901) · A cycle tracker for iOS. Every feature free, twelve languages, health data never leaves the phone. 4.9 stars, 1,000+ downloads.
- [**Mercuro**](https://apps.apple.com/app/id6762402072) · Thermometer logic puzzles running on their own constraint solver. Native on iOS and Android. Featured in gaming newsletters.
- [**Glass Jar Garden**](https://glassjar.garden) · A terrarium simulator in the browser. Build a jar layer by layer, plant from 90 real species, seal it and watch it live day by day.

### Pipelines that run themselves

- [**The Footnote**](https://www.instagram.com/thefootnotemedia/) · A history channel that researches, scripts, voices and publishes itself. 500K+ monthly views.
- [**Iris growth pipeline**](https://www.instagram.com/iriscycletracker/) · The app markets itself. Posters generated, checked against a written creative contract, published daily. 100K+ monthly views driving organic traffic.
- [**Animated Hindi horror**](https://www.youtube.com/@AndheriDastak) · A model writes the screenplay, image models hold the cast across 25 shots, and Wan 2.2 animates it on rented GPUs. Under a dollar a film.

### Open source

- [**sqlite-sparse**](https://github.com/arbazsiddiqui/sqlite-sparse) · Semantic search inside a SQLite file. Documents are encoded once at insert; queries need no model and no server, and take 3.1 ms across a million passages. `pip install sqlite-sparse`
- [**lru-cache-node**](https://github.com/arbazsiddiqui/lru-cache-node) · O(1) LRU cache for Node, with expiry and stale reads.
- [**anabranch**](https://github.com/arbazsiddiqui/anabranch) · HTTP load balancer and reverse proxy in Go.

[arbazsiddiqui.me](https://www.arbazsiddiqui.me) · [Hugging Face](https://huggingface.co/arbazsiddiqui) · [LinkedIn](https://www.linkedin.com/in/arbazsiddiqui) · [Writing](https://www.arbazsiddiqui.me/blog)
