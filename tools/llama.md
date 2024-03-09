## Pre-Reqs
```
https://github.com/01-ai/Yi?tab=readme-ov-file#quick-start---llamacpp
```


### LLama
- CLI
```
cd llama.cpp
tmodel="yi-chat-6b.Q4_K_M.gguf"
make -j4 && ./main -m ../yi-6b/${tmodel} -p "Write a sample shell script"
```

- Web
```
cd llama.cpp
tmodel="yi-chat-6b.Q4_K_M.gguf"
./server --ctx-size 2048 --host 0.0.0.0 --n-gpu-layers 64 --model ../yi-6b/${tmodel}

http://0.0.0.0:8080
```