## Pre-Reqs
```
https://github.com/01-ai/Yi?tab=readme-ov-file#quick-start---llamacpp
```


### LLama
- Convert formats
```
# Convert from safetensors to gguf
cd llama.cpp
python3 ./convert.py ../Yi-34B-Chat
```

- CLI
```
cd llama.cpp
tmodel="../yi-6b/yi-chat-6b.Q4_K_M.gguf"
make -j4 && ./main -m ${tmodel} -p "Write a sample shell script"
```

- Web

```
cd llama.cpp

# This model is quite good
tmodel="../yi-6b/yi-chat-6b.Q5_K_M.gguf"
./server --ctx-size 2048 --host 0.0.0.0 --n-gpu-layers 64 --model ${tmodel}

http://0.0.0.0:8080
```