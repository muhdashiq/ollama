# README

Code to bring up Ollama using Docker (on GPU - Optionally)

## Pre-requisites
- Docker & docker-compose or Desktop app (bundled with both)
- GPU based machine, (NVIDIA GPU)
- Python version 3

## Installing

```
docker-compose up -d
```

## Downloading Model Images

```
docker-compose exec -it ollama bash
ollama pull llama3
ollama pull all-minilm
```

### Test

```
curl http://localhost:11434
```
```
In browser: http://localhost:3000 
```

## Building RAG locally with ollama
- https://medium.com/@vndee.huynh/build-your-own-rag-and-run-it-locally-langchain-ollama-streamlit-181d42805895


Refer the blog for more details - [https://medium.com/@srpillai/how-to-run-ollama-locally-on-gpu-with-docker-a1ebabe451e0](https://medium.com/@srpillai/how-to-run-ollama-locally-on-gpu-with-docker-a1ebabe451e0)
## References

* [https://ollama.com/](https://ollama.com/)
* [https://github.com/ollama/ollama](https://github.com/ollama/ollama)
* [https://streamlit.io/](https://streamlit.io/)
* [https://docs.docker.com/desktop/gpu/](https://docs.docker.com/desktop/gpu/)
* [https://github.com/sujithrpillai/ollama.git](https://github.com/sujithrpillai/ollama.git)
