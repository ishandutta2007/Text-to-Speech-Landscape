# Awesome Text-to-Speech (TTS): Models, Tools, and Resources for AI Voice Generation 🗣️

A meticulously curated and continuously updated list of the most influential tools, cutting-edge models, and essential resources in the Text-to-Speech (TTS) and AI Voice Generation sector. Discover everything from commercial AI voice platforms to open-source speech synthesis libraries, real-time TTS solutions, and advanced voice cloning techniques.

-   **[voicetoinstrument.com](https://voicetoinstrument.com):** Convert voice recordings into instrumental tracks using AI — useful for music production and audio content repurposing.

## Why Explore Text-to-Speech?

Text-to-Speech technology has revolutionized how we interact with digital content, creating opportunities for:
*   **Enhanced Accessibility:** Providing screen readers and voice interfaces for visually impaired users.
*   **Content Creation:** Generating realistic voiceovers for YouTube videos, podcasts, audiobooks, and e-learning modules.
*   **Virtual Assistants & Chatbots:** Powering natural-sounding conversational AI experiences.
*   **Language Learning:** Offering pronunciation guides and interactive speech exercises.
*   **Creative Arts:** Crafting unique character voices for games and animations.

This repository aims to be your go-to guide for navigating the dynamic world of synthetic speech.

## Current State of Text-to-Speech (as of 2024) 📈

The field of Text-to-Speech (TTS) and AI voice synthesis has matured significantly, with modern neural voice models generating audio that is nearly indistinguishable from human speech. Key trends and advancements include:

-   **Hyper-realistic and Natural Speech Synthesis:** Innovations in deep learning and neural network architectures have led to highly natural, expressive, and emotionally nuanced synthetic voices. 🎤
-   **Next-Generation Architectures:** The adoption of State Space Models (SSMs), Diffusion Models, and advanced transformer-based architectures is offering superior performance, efficiency, and voice quality in speech generation. 🧠
-   **Real-time Conversational AI:** Significant advancements in reducing latency now enable real-time TTS, making conversational AI, virtual assistants, and live dubbing more natural and responsive. ⚡
-   **Advanced Voice Cloning and Style Transfer:** Cutting-edge techniques allow for high-fidelity voice cloning from minimal audio samples and the transfer of speaking style and emotion across different voices. 🎭
-   **Multilingual and Cross-Lingual TTS:** Models are increasingly capable of generating speech in numerous languages with accurate pronunciation and intonation, breaking down language barriers.

## Comprehensive List of Text-to-Speech (TTS) Resources 🌐

### Cloud-based & Commercial AI Voice Generation Platforms

Leading platforms offering robust, scalable, and high-quality Text-to-Speech APIs and services for various applications.

| Service/Model | Organization | Key Features | Link |
| --- | --- | --- | --- |
| **OpenAI TTS** | OpenAI | High-quality, real-time streaming TTS models for applications requiring natural AI voices. | [OpenAI TTS](https://platform.openai.com/docs/guides/text-to-speech) |
| **PHANTOM VOICES** | PHANTOM VOICES | 10 free professional AI voice clones via public REST API. Zero cost, commercial rights cleared. 29 platform configs (Vapi, Retell AI, etc). Multilingual (9+ languages). AI-powered recommendation. | [PHANTOM VOICES](https://auto-business-agent.replit.app/portfolio) |
| **ElevenLabs** | ElevenLabs | State-of-the-art AI voice generator offering realistic voices, voice cloning, and AI dubbing in numerous languages. Ideal for content creators and businesses. | [ElevenLabs](https://elevenlabs.io/) |
| **Spokio** | Spokio | Offline macOS text-to-speech app with local voice cloning, batch export, and no cloud uploads. | [Spokio](https://spokio.pro/) |
| **Google Cloud Text-to-Speech** | Google | A powerful TTS API providing a large variety of natural-sounding voices and languages, with extensive customization options for pitch, speaking rate, and voice profiles. | [Google Cloud TTS](https://cloud.google.com/text-to-speech) |
| **Deepgram Aura** | Deepgram | Specializing in low-latency TTS designed for real-time conversational AI, making virtual interactions seamless and natural. | [Deepgram Aura](https://deepgram.com/aura) |
| **NVIDIA NeMo** | NVIDIA | An end-to-end platform for building, training, and deploying generative AI models, including advanced Text-to-Speech and Automatic Speech Recognition (ASR). | [NVIDIA NeMo](https://developer.nvidia.com/nemo) |

### Open-Source Text-to-Speech Libraries & Projects

Explore powerful open-source toolkits and projects for local deployment, research, and custom TTS development.

| Service/Model | Organization | Key Features | Link |
| --- | --- | --- | --- |
| **🐸 Coqui TTS** | Coqui | A versatile open-source deep learning toolkit for Text-to-Speech, featuring pretrained models for over 1100 languages, voice cloning, and model training capabilities. | [Coqui TTS on GitHub](https://github.com/coqui-ai/TTS) |
| **Chatterbox** | Resemble AI | An open-source collection of voice models offering advanced features like emotion control and zero-shot voice cloning, perfect for expressive speech synthesis. | [Chatterbox on GitHub](https://github.com/resemble-ai/chatterbox) |
| **ESPnet-TTS** | Various | A comprehensive open-source toolkit providing implementations of popular and state-of-the-art TTS models, ideal for speech research and development. | [ESPnet on GitHub](https://github.com/espnet/espnet) |
| **Parler-TTS** | Hugging Face | A lightweight and efficient model capable of generating high-quality, natural-sounding speech. Available through the Hugging Face ecosystem. | [Parler-TTS on Hugging Face](https://huggingface.co/parler-tts) |
| **KittenTTS** | KittenML | A lightweight ONNX text-to-speech library with 15M-80M parameter models, built-in voices, and CPU inference without requiring a GPU. | [KittenTTS on GitHub](https://github.com/KittenML/KittenTTS) |
| **Mozilla TTS** | Mozilla | An open-source project focused on building speech-enabled applications, providing tools and resources for developers. | [Mozilla TTS on GitHub](https://github.com/mozilla/TTS) |
| **MaryTTS** | DFKI | An open-source, Java-based Text-to-Speech engine offering robust multilingual support and various voice customization options. | [MaryTTS on GitHub](https://github.com/marytts/marytts) |
| **eSpeak NG** | Various | A compact and efficient open-source TTS engine, known for its small footprint and broad language support, suitable for embedded systems. | [eSpeak NG on GitHub](https://github.com/espeak-ng/espeak-ng) |
| **Piper** | Rhasspy | A fast, entirely local neural text-to-speech system that prioritizes privacy and on-device inference, ideal for offline applications. | [Piper on GitHub](https://github.com/rhasspy/piper) |

### Advanced Voice Cloning & Neural Voice Synthesis 🧬

Dedicated resources and examples focusing on the latest in voice replication and advanced synthetic voice generation.

-   **XTTS-v2 by Coqui:** A breakthrough in voice cloning, capable of replicating a voice from just a 6-second audio clip, preserving emotion and speaking style.
-   **Resemble AI's Chatterbox:** Offers advanced zero-shot voice cloning capabilities, enabling instant voice replication without extensive training data.
-   **ElevenLabs Voice Cloning:** Provides robust tools for creating highly realistic voice clones, suitable for personalized audio content.
-   **Suno Bark:** A transformer-based text-to-audio model that generates highly naturalistic, multilingual speech, music, and sound effects. It excels at expressive speech with nuances like laughter, sighs, and crying.
    *   [Bark on GitHub](https://github.com/suno-ai/bark)
-   **MeloTTS:** A multi-language, multi-speaker Text-to-Speech model capable of generating high-quality audio.
    *   [MeloTTS on GitHub](https://github.com/myshell-ai/MeloTTS)

### Hugging Face 🤗 - The Hub for TTS Models

[Hugging Face](https://huggingface.co/) has emerged as a central ecosystem for sharing, discovering, and experimenting with a vast array of pretrained Text-to-Speech models. Explore their extensive collection for diverse applications and research.

-   [Browse TTS Models on Hugging Face](https://huggingface.co/models?pipeline_tag=text-to-speech)

### Notable Research Papers & Community Discussions 📝

Stay updated with the latest breakthroughs and discussions in the TTS community.

-   [[N] Baidu AI Can Clone Your Voice in Seconds](https://www.reddit.com/r/MachineLearning/comments/7zb2jm/n_baidu_ai_can_clone_your_voice_in_seconds/) (Reddit discussion on voice cloning technology)
-   [[R] Expressive Speech Synthesis with Tacotron](https://www.reddit.com/r/MachineLearning/comments/87klvo/r_expressive_speech_synthesiss_with_tacotron/) (Reddit discussion on making TTS more human-like)
-   [[D] Realtime Neural Voice Style Transfer Feasibility and Implications](https://www.reddit.com/r/MachineLearning/comments/8opn4c/d_realtime_neural_voice_transfer/) (Discussion on the challenges and potential of real-time voice style transfer)
-   [[D] Is there an implementation of Neural Voice Cloning?](https://www.reddit.com/r/MachineLearning/comments/8o7mkt/d_is_there_an_implementation_of_neural_voice/) (Community quest for neural voice cloning implementations)
-   [[D] Are the hyper-realistic results of Tacotron-2 and Wavenet not reproducible?](https://www.reddit.com/r/MachineLearning/comments/845uji/d_are_the_hyperrealistic_results_of_tacotron2_and/) (Discussion on reproducibility in advanced TTS models)
-   [[P] Voice Style Transfer: Speaking like Kate Winslet](https://www.reddit.com/r/MachineLearning/comments/7a0wcv/p_voice_transfer_speaking_like_kate_winslet/) (Showcase of voice style transfer examples)

### Exemplary Code Samples & Project Demos 💻

A collection of influential code repositories and product demonstrations showcasing various Text-to-Speech implementations and their output quality.

| Project/Samples | Pretrained Models | Code Link | Paper/Arxiv ID | Output Quality | Year of Launch | Description |
| --- | :---: | :---: | :---: | :---: | :---: | --- |
| [MeloTTS Samples](https://github.com/myshell-ai/MeloTTS) | -- | [Code](https://github.com/myshell-ai/MeloTTS) | [Codebase](https://github.com/myshell-ai/MeloTTS) | B | 2024 | Multilingual, multi-speaker TTS model for high-quality audio generation. |
| [Parler-TTS Samples](https://github.com/huggingface/parler-tts) | -- | [Code](https://github.com/huggingface/parler-tts) | [2402.01912](https://arxiv.org/abs/2402.01912) | B | 2024 | Samples from a lightweight model producing natural-sounding speech. |
| [XTTS-v2 Samples](https://coqui.ai/xtts-v2-demo) | -- | [Code](https://github.com/idiap/coqui-ai-TTS) | [2309.02055](https://arxiv.org/abs/2309.02055) | A | 2023 | Demonstrations of Coqui's advanced voice cloning with emotion transfer. |
| [Bark Samples (Suno.ai)](https://suno.ai/) | -- | [Code](https://github.com/suno-ai/bark) | -- | A | 2023 | Samples from Suno's expressive text-to-audio model, including non-speech sounds. |
| [rayhane's Tacotron2 Samples](https://rayhane-mamah.github.io/Tacotron-2_audio_samples/) | -- | -- | -- | D | 2019 | Audio samples from an early Tacotron 2 implementation. |
| [Google Tacotron + Style Transfer Sample](https://google.github.io/tacotron/publications/end_to_end_prosody_transfer/) (Official) | -- | -- | [1803.09047](https://arxiv.org/abs/1803.09047) | A | 2018 | Official samples showcasing prosody and style transfer with Tacotron. |
| [NVIDIA's WaveGlow Samples](https://nv-adlr.github.io/WaveGlow) | [Download Model](https://drive.google.com/file/d/1cjKPHbtAMh_4HTHmuIGNkbOkPBD9qwhj/view?usp=sharing) | [Code](https://github.com/NVIDIA/waveglow) | [1811.00002](https://arxiv.org/abs/1811.00002) | A | 2018 | High-fidelity audio generated by NVIDIA's WaveGlow vocoder. |
| [NVIDIA's Tacotron2 + WaveGlow Samples](https://nv-adlr.github.io/WaveGlow) | [Download Model](https://drive.google.com/file/d/1c5ZTuT7J08wLUoVZ2KkUs_VdZuJ86ZqA/view?usp=sharing) | [Code](https://github.com/NVIDIA/tacotron2) | -- | A | 2018 | Combined high-quality speech synthesis from Tacotron 2 and WaveGlow. |
| [mazzzystar's Tacotron-WaveRNN Samples](https://github.com/mazzzystar/Tacotron-WaveRNN#samples) | [Get Model](https://github.com/mazzzystar/Tacotron-WaveRNN#pretrained-model) | [Code](https://github.com/mazzzystar/Tacotron-WaveRNN) | -- | A | 2018 | Demonstrations from a Tacotron and WaveRNN hybrid model. |
| [syang1993's Tacotron + Style Transfer Samples](https://syang1993.github.io/gst-tacotron/) | [Model ErnstTmp (232k iter)](https://www.dropbox.com/s/fl1vqfz6611s8zw/checkpoint234000.tar?dl=0) | -- | [1803.09047](https://arxiv.org/abs/1803.09047) and [1803.09017](https://arxiv.org/abs/1803.09017) | C | 2018 | Samples demonstrating Tacotron with global style tokens for voice style transfer. |
| [Kyubyong's Tacotron on LJ Dataset Samples](https://soundcloud.com/kyubyong-park/sets/tacotron_lj_200k) | [Download model](https://www.dropbox.com/s/8kxa3xh2vfna3s9/LJ_logdir.zip?dl=0) | -- | -- | D | 2018 | Audio generated from Tacotron trained on the LJSpeech dataset. |
| [Kyubyong's Tacotron on Nick Dataset Samples](https://soundcloud.com/kyubyong-park/sets/tacotron_nick_215k) | -- | -- | -- | D | 2018 | Tacotron samples from the Nick dataset. |
| [Kyubyong's Tacotron on Web Dataset Samples](https://soundcloud.com/kyubyong-park/sets/tacotron_web_183k) | [Download model](https://www.dropbox.com/s/g7m6xhd350ozkz7/WEB_logdir.zip?dl=0) | -- | -- | D | 2018 | Tacotron speech output from the Web dataset. |
| [Kyubyong's Expressive Tacotron Samples](https://soundcloud.com/kyubyong-park/sets/expressive_tacotron_420k) | -- | [Code](https://github.com/Kyubyong/expressive_tacotron) | [1803.09047](https://arxiv.org/abs/1803.09047) | D | 2018 | Samples demonstrating expressive speech synthesis with Tacotron. |
| [Kyubyong's DC-TTS on Nick Dataset Samples](https://soundcloud.com/kyubyong-park/sets/dc_tts_nick_800k) | -- | -- | -- | D | 2018 | DC-TTS samples generated from the Nick dataset. |
| [Baidu's Deep Voice Samples](https://audiodemos.github.io) (Official) | -- | -- | -- | D | 2017 | Official audio demonstrations from Baidu's Deep Voice project. |
| [Baidu's Deep Voice 3 Samples](http://research.baidu.com/Blog/index-view?id=91) (Official) | -- | -- | [1710.07654](https://arxiv.org/pdf/1710.07654.pdf) | B | 2017 | Official samples from Deep Voice 3, showcasing advanced speech synthesis. |
| [Google Tacotron2 Samples](https://google.github.io/tacotron/publications/tacotron2/index.html) (Official) | -- | -- | [1712.05884](https://arxiv.org/abs/1712.05884) | A | 2017 | Official, high-quality audio samples from the groundbreaking Tacotron 2 model. |
| [DeepMind Neural Discrete Representation Learning Samples](https://avdnoord.github.io/homepage/vqvae/) (Official) | -- | -- | [1711.00937](https://arxiv.org/abs/1711.00937) | B | 2017 | Samples demonstrating speech generated using VQ-VAE for neural discrete representation learning. |
| [r9y9's Wavenet Vocoder Tacotron2 Samples](https://r9y9.github.io/wavenet_vocoder/) | [Download Tacotron2 model](https://www.dropbox.com/s/vx7y4qqs732sqgg/pretrained.tar.gz?dl=0) - [Download Wavenet model](https://www.dropbox.com/s/zdbfprugbagfp2w/20180510_mixture_lj_checkpoint_step000320000_ema.pth?dl=0) - [Get models](https://github.com/r9y9/wavenet_vocoder#pre-trained-models) | -- | [1712.05884](https://arxiv.org/abs/1712.05884) and [1611.09482](https://arxiv.org/abs/1611.09482) | B | 2017 | Samples from a Tacotron 2 and WaveNet vocoder combination. |
| [dhgrs's Implementation of Neural Discrete Representation Learning Samples](https://nana-music.com/playlists/2276008/) | [Download Model](https://drive.google.com/file/d/1Ayy9NbpBoZCj1WVmwHGnUTG_jB2eonVU/view) | [Code](https://github.com/dhgrs/chainer-VQ-VAE) | [1711.00937](https://arxiv.org/abs/1711.00937) | D | 2017 | Audio generated using a Chainer implementation of VQ-VAE for speech. |
| [keithito's Tacotron Samples](https://keithito.github.io/audio-samples/) | [Get model](https://github.com/keithito/tacotron#using-a-pre-trained-model) | -- | -- | D | 2017 | Audio samples from keithito's Tacotron implementation. |
| [Kyubyong's DC-TTS on LJ Dataset Samples](https://soundcloud.com/kyubyong-park/sets/dc_tts_lj_800k) | [Get model](https://github.com/Kyubyong/dc_tts#pretrained-model-for-lj) | -- | -- | D | 2017 | DC-TTS generated speech from the LJSpeech dataset. |
| [Kyubyong's DC-TTS Kate Samples](https://soundcloud.com/kyubyong-park/sets/dc_tts_kate_800k) | -- | -- | -- | D | 2017 | DC-TTS samples featuring the "Kate" voice. |
| [andabi's Deep Voice Conversion](https://soundcloud.com/andabi/sets/voice-style-transfer-to-kate-winslet-with-deep-neural-networks) | -- | -- | -- | D | 2017 | Demonstrations of deep voice conversion techniques. |
| [Facebook Loop Samples](https://ytaigman.github.io/loop/) (Official) | [Get model](https://github.com/facebookresearch/loop#pretrained-models) | -- | -- | D | 2017 | Official audio samples from Facebook's Loop project. |
| [mazzzystar's RandomCNN Voice Transfer](https://soundcloud.com/mazzzystar/sets/speech-conversion-sample) | -- | -- | [1712.08363](https://arxiv.org/abs/1712.08363) | D | 2017 | Speech conversion samples using Random CNNs. |
| [Griffin-Lim Samples](https://nv-adlr.github.io/WaveGlow) | -- | -- | -- | A | 1984 | Classic samples from the Griffin-Lim algorithm for spectrogram inversion. |

## Work in Progress & Future of Text-to-Speech 🚧

Ongoing projects and cutting-edge research shaping the next generation of AI voice synthesis.

-   https://github.com/ErnstTmp is implementing https://arxiv.org/abs/1807.06736
-   https://github.com/nii-yamagishilab/self-attention-tacotron
-   https://github.com/nii-yamagishilab/tacotron2

If I missed your output sample/demo in this consolidation, just add and send a pull request. I will be more than happy to add it. Thanks!

## Codelabs & Interactive Tutorials 🧪

Practical guides and interactive notebooks for experimenting with Text-to-Speech models.

-   https://github.com/tugstugi/dl-colab-notebooks

## Product Demos & Showcase Videos 🎥

Visual demonstrations of advanced Text-to-Speech and voice cloning in action.

-   [Lyrebird samples](https://lyrebird.ai/g/vWI8bJTl)(official)
-   [Lyrebird Demo](https://youtu.be/YfU_sWHT8mo)(official)
-   [Google Duplex Demo](https://www.youtube.com/watch?v=D5VN56jQMWM&t=66s)(official)
-   [Adobe Voco Demo](https://youtu.be/I3l4XLZ59iw)(official)
-   [Voice Cloning Toolbox](https://www.youtube.com/watch?v=-O_hYhToKoA)(official)

## Related Works & Foundational Research 📚

Broader projects and research efforts that contribute to the Text-to-Speech ecosystem.

-   https://github.com/tensorflow/magenta

## Arxiv Sanity Preserver - Key Papers in Speech Synthesis 📄

Explore influential academic papers and preprints in the field of Text-to-Speech and voice AI.

-   http://www.arxiv-sanity.com/1705.08947v1
-   http://arxiv-sanity.com/1703.10135v2

### ✨ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=ishandutta2007/Text-to-Speech-Landscape&type=date&legend=top-left)](https://www.star-history.com/#ishandutta2007/Text-to-Speech-Landscape&type=date&legend=top-left)

## 💬 Community & Support for Text-to-Speech Enthusiasts

Connect with the community, get support, and stay informed about the latest in TTS.

-   **📚 [Documentation](https://docs.open-workflows.com):** Check out our official documentation for detailed guides and tutorials on utilizing TTS technologies.
-   **🗣️ [Forum](https://community.open-workflows.com):** Join our community forum to ask questions, share your Text-to-Speech projects, and connect with other users and developers.
-   **💬 [Discord](https://discord.com/invite/jc4xtF58Ve):** Chat with us on Discord for real-time support and discussions on AI voice generation.
-   **🐦 [Twitter](https://twitter.com/ishandutta2007):** Follow us on Twitter for the latest news, updates, and insights into the world of synthetic speech.
-   **🐦 [Github](https://github.com/ishandutta2007):** Follow me on Github for the latest commits and updates on this and other AI projects.

## 💖 Support & Sponsorship

If you find this collection of Text-to-Speech resources helpful, or if it has saved you time and effort in your AI voice generation endeavors, please consider sponsoring the development. Your support helps maintain the project, add new cutting-edge models and tools, and keep this initiative open-source and accessible to everyone.

**[Sponsor @ishandutta2007 on GitHub](https://github.com/sponsors/ishandutta2007)**

-   [PAYPAL](https://paypal.me/ishandutta2007)
-   [BITCOIN ADDRESS: 3LZazKXG18Hxa3LLNAeKYZNtLzCxpv1LyD](https://www.coinbase.com/join/5a8e4a045b02c403bc3a9c0c)

Every contribution, no matter how small, makes a huge difference in advancing the Text-to-Speech landscape! 🙏
