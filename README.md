# jetson-orin-nano
Repo of code and wiki, setting-up Jetson Orin Nano Super

## Where to buy:
+ https://www.amazon.com/dp/B0BZJTQ5YP?th=1
+ You'll need storage and the best is NVMe
+ https://www.amazon.com/dp/B0B217LZBG?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1
+ If setting-up with Ubuntu host, a female jumper for pins number 9 & 10 is required
+ https://www.amazon.com/dp/B0DSZWFS1V?ref=ppx_yo2ov_dt_b_fed_asin_title

## SDK Manager procedure using Ubuntu host:
+ I have an Ubuntu 22.04 computer, so I'll be using this route. Should take over an hour, depending on your selection
+ https://www.jetson-ai-lab.com/tutorials/initial-setup-jetson-orin-nano/

## Docker setup:
+ https://www.jetson-ai-lab.com/tutorials/ssd-docker-setup/

## Start using:
+ You can pick any models to use and download
+ Here's the most popular according to search
+ TensorRT - anything based on this will be much more optimized
+ CUDA - this is base
+ https://www.nomic.ai/gpt4all
+ https://github.com/nomic-ai/gpt4all
+ https://openclaw.ai/
+ https://clawhub.ai/https://clawhub.ai/
+ https://openrouter.ai/
+ https://openrouter.ai/models?order=most-popular
+ https://www.jetson-ai-lab.com/tutorials/#all-tutorials
  
## Ollama:
+ I will go with the easiest, which is Ollama as locally installed (not containerized)
+ Plus the WebUI to run as container
+ https://www.jetson-ai-lab.com/tutorials/ollama/
+ The following is highly optimized for NVIDIA's Ampere architecture and run very fast in Ollama
+ Llama 3.2 1B & 3B: These are the current "gold standard" for small edge devices

## Frigate NVR:
+ https://wiki.seeedstudio.com/deploy_frigate_on_jetson/
