# TTS Landscape 🗣️

A curated list of the latest and most influential tools, models, and resources in the Text-to-Speech sector.

## Current State of TTS (as of 2024) 📈

The field of Text-to-Speech (TTS) has matured significantly, with modern models generating voices that are nearly indistinguishable from human speech. Key trends include:

-   **Human-like and Natural Speech:** Innovations in neural network architectures and training data have led to highly natural and expressive synthetic voices. 🎤
-   **New Architectures:** State Space Models (SSMs) and other new architectures are offering better performance and efficiency. 🧠
-   **Real-time Capabilities:** Significant advancements have been made in reducing latency, making real-time conversational AI more natural and responsive. ⚡
-   **Voice Cloning and Style Transfer:** It is now possible to clone a voice from a short audio sample and transfer the style of one speaker to another. 🎭

## Commercial & Open Source TTS Landscape 🌐

| Service/Model | Organization | Key Features | Link |
| --- | --- | --- | --- |
| **OpenAI TTS** | OpenAI | High-quality, real-time streaming TTS models. | [OpenAI TTS](https://platform.openai.com/docs/guides/text-to-speech) |
| **ElevenLabs** | ElevenLabs | Realistic AI voices in numerous languages, with voice cloning and dubbing. | [ElevenLabs](https://elevenlabs.io/) |
| **Google Cloud TTS** | Google | Large variety of voices and languages, with customization options. | [Google Cloud TTS](https://cloud.google.com/text-to-speech) |
| **Deepgram Aura** | Deepgram | Low-latency TTS for real-time conversations. | [Deepgram Aura](https://deepgram.com/aura) |
| **NVIDIA NeMo** | NVIDIA | End-to-end platform for generative AI, including advanced TTS models. | [NVIDIA NeMo](https://developer.nvidia.com/nemo) |
| **🐸 Coqui TTS** | Coqui | Open-source toolkit with pretrained models for over 1100 languages. | [Coqui TTS on GitHub](https://github.com/coqui-ai/TTS) |
| **Chatterbox** | Resemble AI | Open-source voice models with emotion control and zero-shot voice cloning. | [Chatterbox on GitHub](https://github.com/resemble-ai/chatterbox) |
| **ESPnet-TTS** | Various | Open-source toolkit with implementations of popular TTS models. | [ESPnet on GitHub](https://github.com/espnet/espnet) |
| **Parler-TTS** | Hugging Face | Lightweight model for generating high-quality, natural-sounding speech. | [Parler-TTS on Hugging Face](https://huggingface.co/parler-tts) |
| **Mozilla TTS** | Mozilla | Open-source project for building speech-enabled applications. | [Mozilla TTS on GitHub](https://github.com/mozilla/TTS) |
| **MaryTTS** | DFKI | Open-source, Java-based TTS engine with multilingual support. | [MaryTTS on GitHub](https://github.com/marytts/marytts) |
| **eSpeak NG** | Various | Compact and efficient open-source TTS engine. | [eSpeak NG on GitHub](https://github.com/espeak-ng/espeak-ng) |
| **Piper** | Rhasspy | A fast, local neural text to speech system. | [Piper on GitHub](https://github.com/rhasspy/piper) |

## Voice Cloning  cloning

Voice cloning technology has made significant strides. Here are a few notable examples:

-   **XTTS-v2 by Coqui:** Can clone a voice from a 6-second audio clip and transfer emotion and speaking style.
-   **Resemble AI's Chatterbox:** Offers zero-shot voice cloning.
-   **ElevenLabs:** Provides tools for creating realistic voice clones.

## Hugging Face 🤗

[Hugging Face](https://huggingface.co/) has become a central hub for sharing and discovering TTS models. You can find a wide variety of pretrained models and tools for TTS on their platform.

-   [TTS Models on Hugging Face](https://huggingface.co/models?pipeline_tag=text-to-speech)

## Reddit Posts 📝

-   [[N] Baidu AI Can Clone Your Voice in Seconds](https://www.reddit.com/r/MachineLearning/comments/7zb2jm/n_baidu_ai_can_clone_your_voice_in_seconds/)
-   [[R] Expressive Speech Synthesis with Tacotron](https://www.reddit.com/r/MachineLearning/comments/87klvo/r_expressive_speech_synthesis_with_tacotron/)
-   [[D] Realtime Neural Voice Style Transfer Feasibility and Implications](https://www.reddit.com/r/MachineLearning/comments/8opn4c/d_realtime_neural_voice_style_transfer/)
-   [[D] Is there an implementation of Neural Voice Cloning?](https://www.reddit.com/r/MachineLearning/comments/8o7mkt/d_is_there_an_implementation_of_neural_voice/)
-   [[D] Are the hyper-realistic results of Tacotron-2 and Wavenet not reproducible?](https://www.reddit.com/r/MachineLearning/comments/845uji/d_are_the_hyperrealistic_results_of_tacotron2_and/)
-   [[P] Voice Style Transfer: Speaking like Kate Winslet](https://www.reddit.com/r/MachineLearning/comments/7a0wcv/p_voice_style_transfer_speaking_like_kate_winslet/)

## Samples from github 💻

| Samples | Pretrained Models | Code | Paper | Output Quality |
| --- | :---: | :---: | :---: | :---: |
| [Baidu's Deep Voice samples](https://audiodemos.github.io)(official)|--|--|--| D |
| [Baidu's Deep Voice 3 samples](http://research.baidu.com/Blog/index-view?id=91)(official)|--|--|[1710.07654](https://arxiv.org/pdf/1710.07654.pdf)| B |
| [Google Tacotron2 samples](https://google.github.io/tacotron/publications/tacotron2/index.html)(official) | -- | -- | [1712.05884](https://arxiv.org/abs/1712.05884) | A |
| [Google tacotron + style transfer sample](https://google.github.io/tacotron/publications/end_to_end_prosody_transfer/)(official)|--|--|[1803.09047](https://arxiv.org/abs/1803.09047)| A |
| [NVIDIA's waveglow](https://nv-adlr.github.io/WaveGlow)|[Download Model](https://drive.google.com/file/d/1cjKPHbtAMh_4HTHmuIGNkbOkPBD9qwhj/view?usp=sharing)|[Code](https://github.com/NVIDIA/waveglow)|[1811.00002](https://arxiv.org/abs/1811.00002)| A |
| [NVIDIA's tacotron2 + waveglow](https://nv-adlr.github.io/WaveGlow)|[Download Model](https://drive.google.com/file/d/1c5ZTuT7J08wLUoVZ2KkUs_VdZuJ86ZqA/view?usp=sharing)|[Code](https://github.com/NVIDIA/tacotron2)|--| A |
| [Griffin-Lim](https://nv-adlr.github.io/WaveGlow)|--|--|--| A |
|[Deepmind Neural Discrete Representation Learning samples](https://avdnoord.github.io/homepage/vqvae/)(official)|--|--|[1711.00937](https://arxiv.org/abs/1711.00937)| B |
| [r9y9's wavenet vocoder Tacotron2(189k iterations)](https://r9y9.github.io/wavenet_vocoder/)|[(Download Tacotron2 model)](https://www.dropbox.com/s/vx7y4qqs732sqgg/pretrained.tar.gz?dl=0) - [(Download wavenet model(1000k iterations))](https://www.dropbox.com/s/zdbfprugbagfp2w/20180510_mixture_lj_checkpoint_step000320000_ema.pth?dl=0) - [(Get models)](https://github.com/r9y9/wavenet_vocoder#pre-trained-models)|--| [1712.05884](https://arxiv.org/abs/1712.05884) and [1611.09482](https://arxiv.org/abs/1611.09482)| B |
|[dhgrs's implementation of Neural Discrete Representation Learning samples](https://nana-music.com/playlists/2276008/)|[Download Model](https://drive.google.com/file/d/1Ayy9NbpBoZCj1WVmwHGnUTG_jB2eonVU/view)|[Code](https://github.com/dhgrs/chainer-VQ-VAE)|[1711.00937](https://arxiv.org/abs/1711.00937)| D |
|[mazzzystar's Tacotron-WaveRNN samples](https://github.com/mazzzystar/Tacotron-WaveRNN#samples)(730k iterations)|[Get Model](https://github.com/mazzzystar/Tacotron-WaveRNN#pretrained-model)|[Code](https://github.com/mazzzystar/Tacotron-WaveRNN)|--| A |
| [syang1993's tacotron + style transfer samples](https://syang1993.github.io/gst-tacotron/)(200k iterations)|[Model ErnstTmp(232k iter)](https://www.dropbox.com/s/fl1vqfz6611s8zw/checkpoint234000.tar?dl=0)|--|[1803.09047](https://arxiv.org/abs/1803.09047) and [1803.09017](https://arxiv.org/abs/1803.09017)| C |
| [keithito's tacotron samples(414k iterations)](https://keithito.github.io/audio-samples/)|[Get model](https://github.com/keithito/tacotron#using-a-pre-trained-model)|--|--| D |
| [rayhane's Tacotron2 samples(6k4 steps(whatever that means))](https://rayhane-mamah.github.io/Tacotron-2_audio_samples/)|--|--|--| D |
| [Kyubyong's tacotron on LJ dataset(200k iterations)](https://soundcloud.com/kyubyong-park/sets/tacotron_lj_200k)|[Download model](https://www.dropbox.com/s/8kxa3xh2vfna3s9/LJ_logdir.zip?dl=0)|--|--| D |
| [Kyubyong's tacotron on nick dataset(215k iterations)](https://soundcloud.com/kyubyong-park/sets/tacotron_nick_215k)|--|--|--| D |
| [Kyubyong's tacotron on web dataset(183k iterations)](https://soundcloud.com/kyubyong-park/sets/tacotron_web_183k)|[Download model](https://www.dropbox.com/s/g7m6xhd350ozkz7/WEB_logdir.zip?dl=0)|--|--| D |
| [Kyubyong's expressive tacotron(420k iterations)](https://soundcloud.com/kyubyong-park/sets/expressive_tacotron_420k)|--|[Code](https://github.com/Kyubyong/expressive_tacotron)|[1803.09047](https://arxiv.org/abs/1803.09047)| D |
| [Kyubyong's dc-tts on LJ dataset(800k iterations)](https://soundcloud.com/kyubyong-park/sets/dc_tts_lj_800k)|[Get model](https://github.com/Kyubyong/dc_tts#pretrained-model-for-lj)|--|--| D |
| [Kyubyong's dc-tts on nick dataset(800k iterations)](https://soundcloud.com/kyubyong-park/sets/dc_tts_nick_800k)|--|--|--| D |
| [Kyubyong's dc-tts kate(800k iterations)](https://soundcloud.com/kyubyong-park/sets/dc_tts_kate_800k)|--|--|--| D |
| [andabi's deep voice conversion](https://soundcloud.com/andabi/sets/voice-style-transfer-to-kate-winslet-with-deep-neural-networks)|--|--|--| D |
| [Facebook Loop samples](https://ytaigman.github.io/loop/)(official)|[Get model](https://github.com/facebookresearch/loop#pretrained-models)|--|--| D |
| [mazzzystar's randomCNN voice transfer](https://soundcloud.com/mazzzystar/sets/speech-conversion-sample)|--|--|[1712.08363](https://arxiv.org/abs/1712.08363)| D |

## Work in progress 🚧

-   https://github.com/ErnstTmp is implementing https://arxiv.org/abs/1807.06736
-   https://github.com/nii-yamagishilab/self-attention-tacotron
-   https://github.com/nii-yamagishilab/tacotron2

If I missed your output sample/demo in this consolidation, just add and send a pull request. I will be more than happy to add it. Thanks!

## Codelabs 🧪

-   https://github.com/tugstugi/dl-colab-notebooks

## Product Demos 🎥

-   [Lyrebird samples](https://lyrebird.ai/g/vWI8bJTl)(official)
-   [Lyrebird Demo](https://youtu.be/YfU_sWHT8mo)(official)
-   [Google Duplex Demo](https://www.youtube.com/watch?v=D5VN56jQMWM&t=66s)(official)
-   [Adobe Voco Demo](https://youtu.be/I3l4XLZ59iw)(official)
-   [Voice Cloning Toolbox](https://www.youtube.com/watch?v=-O_hYhToKoA)(official)

## Related Works 📚

-   https://github.com/tensorflow/magenta

## Arxiv-sanity  sanity

-   http://www.arxiv-sanity.com/1705.08947v1
-   http://arxiv-sanity.com/1703.10135v2

### ✨ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=ishandutta2007/Text-to-Speech-Landscape&type=date&legend=top-left)](https://www.star-history.com/#ishandutta2007/Text-to-Speech-Landscape&type=date&legend=top-left)

## 💬 Community & Support

-   **📚 [Documentation](https://docs.open-workflows.com):** Check out our official documentation for detailed guides and tutorials.
-   **🗣️ [Forum](https://community.open-workflows.com):** Join our community forum to ask questions, share your projects, and connect with other users.
-   **💬 [Discord](https://discord.com/invite/jc4xtF58Ve):** Chat with us on Discord for real-time support and discussions.
-   **🐦 [Twitter](https://twitter.com/ishandutta2007):** Follow us on Twitter for the latest news and updates.
-   **🐦 [Github](https://github.com/ishandutta2007):** Follow me on Github for the latest commits and updates.

## 💖 Support & Sponsorship

If you find this project helpful or if it has saved you time and resources, please consider sponsoring the development. Your support helps maintain the project, develop new features, and keep the initiative open-source.

**[Sponsor @ishandutta2007 on GitHub](https://github.com/sponsors/ishandutta2007)**

-   [PAYPAL](https.paypal.me/ishandutta2007)
-   [BITCOIN ADDRESS: 3LZazKXG18Hxa3LLNAeKYZNtLzCxpv1LyD](https://www.coinbase.com/join/5a8e4a045b02c403bc3a9c0c)

Every contribution, no matter how small, makes a huge difference! 🙏
