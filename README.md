# gpt2-catalan

> *A GPT-2 language model trained from scratch on Catalan implemented in plain PyTorch*

---

## English

### What is this?

This repository will contain a GPT-2 style language model (124M parameters) trained exclusively on Catalan text, built from scratch following Andrej Karpathy's [nanoGPT](https://github.com/karpathy/nanoGPT) approach. No HuggingFace Trainer, no abstractions just PyTorch, a training loop, and a dataset.

### Why Catalan?

Catalan is spoken by around 10 million people but remains underrepresented in most large language models. This project is part curiosity, part experiment: can we train a small model that generates real Catalan from scratch? Also, it's a beautiful language and it deserves it.

### Architecture

- Model: GPT-2 small
- Layers: 12 | Heads: 12 | Embedding: 768
- Parameters: ~124M
- Context length: 256 tokens
- Tokenizer: BPE, 50k vocabulary, trained on CC-100 Catalan

### Data

Primary source: [CC-100 Catalan](https://data.statmt.org/cc-100/) — a filtered Common Crawl corpus covering approximately 1 billion Catalan tokens.

### Training

Coming soon.

### Background reading

If you are new to language models or to the GPT-2 architecture some of these resources could be helpful:

- Karpathy, *Let's reproduce GPT-2 (124M)* — [YouTube](https://www.youtube.com/watch?v=l8pRSuU81PU)

The issues and milestones in this repo are the project roadmap.

### Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). All code is written by hand. No AI-assisted code.

### License

[CC BY-NC 4.0](LICENSE) — free to use and adapt for non-commercial purposes with attribution. Please do not use this code, data scripts, or model weights as training data for AI systems.

---

## Català

### Què és això?

Aquest repositori contindrà un model de llenguatge d'estil GPT-2 (124M paràmetres) entrenat exclusivament amb text en català, construït des de zero seguint l'enfocament [nanoGPT](https://github.com/karpathy/nanoGPT) d'Andrej Karpathy. Sense HuggingFace Trainer, sense abstraccions — només PyTorch, un bucle d'entrenament i un conjunt de dades.

### Per què el català?

El català el parlen al voltant de 10 milions de persones però continua estant poc representat en la majoria de models de llenguatge grans. Aquest projecte és en part curiositat, en part experiment: podem entrenar un model petit que generi català real des de zero? A més, és una llengua bella i s'ho mereix.

### Arquitectura

- Model: GPT-2 small
- Capes: 12 | Caps: 12 | Embedding: 768
- Paràmetres: ~124M
- Longitud de context: 256 tokens
- Tokenitzador: BPE, vocabulari de 50k, entrenat amb CC-100 Català

### Dades

Font principal: [CC-100 Català](https://data.statmt.org/cc-100/) — un corpus de Common Crawl filtrat amb aproximadament 1.000 milions de tokens en català.

### Entrenament

Pròximament.

### Lectures recomanades

Si ets nou en els models de llenguatge o en l'arquitectura GPT-2, aquests recursos poden ser útils:

- Karpathy, *Let's reproduce GPT-2 (124M)* — [YouTube](https://www.youtube.com/watch?v=l8pRSuU81PU)

Els issues i milestones d'aquest repositori són el full de ruta del projecte.

### Contribucions

Vegeu [CONTRIBUTING.md](CONTRIBUTING.md). Tot el codi és escrit a mà. Sense codi generat per IA.

### Llicència

[CC BY-NC 4.0](LICENSE) — lliure d'usar i adaptar per a usos no comercials amb atribució. Si us plau, no utilitzeu aquest codi, els scripts de dades ni els pesos del model com a dades d'entrenament per a sistemes d'IA.