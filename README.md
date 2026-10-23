# Models Hub

Models Hub is a small static website introducing compact language models and ways to run them locally. It includes model pages, a comparison table, setup notes, and topic guides.

## Website for the teacher

**Live website:** [https://mingshenhk.github.io/model-hub/](https://mingshenhk.github.io/model-hub/)

Open the link above to view the published site. The homepage is `index.html`.

## Run the site locally

Open `index.html` in a browser, or start a simple static server from this folder. For example, with Python:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Images

The runtime logos and llama.cpp interface screenshot are stored in `images/`, so the published pages do not need to fetch them from another site when they load.

- Ollama logo: [ollama/ollama](https://github.com/ollama/ollama/blob/main/docs/ollama-logo.svg)
- vLLM logo: [vllm-project/media-kit](https://github.com/vllm-project/media-kit)
- llama.cpp interface screenshot: [ggml-org/llama.cpp README](https://github.com/ggml-org/llama.cpp#readme)

The logos identify their respective projects. Product names and logos belong to their owners.
