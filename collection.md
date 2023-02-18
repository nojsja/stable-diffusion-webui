# Collection

- Stable-diffusion主页：https://github.com/camenduru/stable-diffusion-webui
- 预训练模型网站：https://huggingface.co
- Chilloutmix civitai：https://civitai.com/models/6424/chilloutmix
- 谷歌colab脚本：https://github.com/camenduru/stable-diffusion-webui-colab

## Prompt

### demo01

prompt:

```sh
<lora:koreanDollLikeness_v10:0.3>(8k, best quality, masterpiece:1.2), (realistic, photo-realistic:1.37), ultra-detailed, 1 girl,cute, solo,beautiful detailed sky,detailed cafe,night,sitting,dating,(nose blush),(smile:1.15),(closed mouth) small breasts,beautiful detailed eyes,), night, wet, blazer, button T-shirt, black miniskirt, office, (short hair:1.2),floating hair NovaFrogStyle, cyber, makeup, future
```

nagative prompt:

```sh
paintings, sketches, (worst quality:2), (low quality:2), (normal quality:2), lowres, normal quality, ((monochrome)), ((grayscale)), skin spots, acnes, skin blemishes, age spot, (outdoor:1.6), manboobs, backlight,(ugly:1.331), (duplicate:1.331), (morbid:1.21), (mutilated:1.21), (tranny:1.331), mutated hands, (poorly drawn hands:1.331), blurry, (bad anatomy:1.21), (bad proportions:1.331), extra limbs, (disfigured:1.331), (more than 2 nipples:1.331), (missing arms:1.331), (extra legs:1.331), (fused fingers:1.61051), (too many fingers:1.61051), (unclear eyes:1.331), bad hands, missing fingers, extra digit, (futa:1.1), bad body, NG_DeepNegative_V1_75T,pubic hair, glans, naked
```

### demo02

prompt:

```sh
(RAW photo:1.2), ((photorealistic:1.4),(masterpiece:1.3),(best quality:1.4),ultra high res,(detailed facial features),(detailed clothes features),HDR,8k resolution, solo focus, bangs, skin tight, (shiny skin),(slender girl),dreamlike, (extreme detailed illustration),check commentary,commentary request,scenery,no text, white cat ear, white cat tail, white hair, long hair, twin_tail,bunches, medium breasts, dress, ribbon collar, smile.
```

nagative prompt:

```sh
((human ear)), (worst quality:2), (low quality:2), (normal quality:2), lowres, normal quality, ((monochrome)), ((grayscale)), skin spots, acnes, skin blemishes, age spot, (outdoor:1.6), manboobs, backlight,(ugly:1.331), (duplicate:1.331), (morbid:1.21), (mutilated:1.21), (tranny:1.331), mutated hands, (poorly drawn hands:1.331), blurry, (bad anatomy:1.21), (bad proportions:1.331), extra limbs, (disfigured:1.331), (more than 2 nipples:1.331), (missing arms:1.331), (extra legs:1.331), (fused fingers:1.61051), (too many fingers:1.61051), (unclear eyes:1.331), bad hands, missing fingers, extra digit, (futa:1.1), bad body, NG_DeepNegative_V1_75T,pubic hair, glans,nsfw,
```

config:

```sh
Size: 720x1080, Seed: 1787495593, Model: Chilloutmix-Ni-pruned-fp32-fix, Steps: 150, Sampler: DPM++ 2M Karras, CFG scale: 7, Clip skip: 2, Mask blur: 4, Model hash: fc2511737a, AddNet Enabled: True, AddNet Model 1: NyaaCaster_v1(ee4e4abd6390), AddNet Model 2: fantasyfactory_v1(2245d4d0eedc), AddNet Model 3: KasuganoSora_ksV1(5cee7ac7fc52), AddNet Module 1: LoRA, AddNet Module 2: LoRA, AddNet Module 3: LoRA, AddNet Weight A 1: 0.25, AddNet Weight A 2: 0.5, AddNet Weight A 3: 0.1, AddNet Weight B 1: 0.25, AddNet Weight B 2: 0.5, AddNet Weight B 3: 0.1, Denoising strength: 0.5
```