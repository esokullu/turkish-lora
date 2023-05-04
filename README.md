# sokullu-lora

Nasil Kullanilir?

Bu projeyi kullanmak icin 
https://github.com/ggerganov/llama.cpp programina ihtiyaciniz olacak. Bunu indirip kurduktan sonra

```shell
./main -m models/13B/ggml-model-q4_0.bin --lora sokullu-lora/ggml-adapter-model.bin --lora-base models/13B/ggml-model-f16.bin --color -f sokullu-lora/turkish-prompt.txt -ins -b 256 --top_k 10000 --temp 0.2 --repeat_penalty 1 -t 7
```

komutu ile etkilesimli sohbet ekranini acabilirsiniz.

Keywords: Turkish, Lora, turkce, llama
