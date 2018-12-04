# Text to Speech(TTS) Landscape

## Reddit Posts:

- [[N] Baidu AI Can Clone Your Voice in Seconds](https://www.reddit.com/r/MachineLearning/comments/7zb2jm/n_baidu_ai_can_clone_your_voice_in_seconds/)
- [[R] Expressive Speech Synthesis with Tacotron
](https://www.reddit.com/r/MachineLearning/comments/87klvo/r_expressive_speech_synthesis_with_tacotron/)
- [[D] Realtime Neural Voice Style Transfer Feasibility and Implications
](https://www.reddit.com/r/MachineLearning/comments/8opn4c/d_realtime_neural_voice_style_transfer/)
- [[D] Is there an implementation of Neural Voice Cloning?
](https://www.reddit.com/r/MachineLearning/comments/8o7mkt/d_is_there_an_implementation_of_neural_voice/)
- [[D] Are the hyper-realistic results of Tacotron-2 and Wavenet not reproducible?](https://www.reddit.com/r/MachineLearning/comments/845uji/d_are_the_hyperrealistic_results_of_tacotron2_and/) 
- [[P] Voice Style Transfer: Speaking like Kate Winslet](https://www.reddit.com/r/MachineLearning/comments/7a0wcv/p_voice_style_transfer_speaking_like_kate_winslet/)

## Samples from github:

| Samples       | Pretrained Models           | Code  | Paper  | Output Quality
| ------------- |:---------------------------:| -----:| ------:|------:|
| [Baidu's Deep Voice samples](https://audiodemos.github.io)(official)|--|--|--| D |
| [Baidu's Deep Voice 3 samples](http://research.baidu.com/Blog/index-view?id=91)(official)|--|--|[1710.07654](https://arxiv.org/pdf/1710.07654.pdf)| B |
| [Google Tacotron2 samples](https://google.github.io/tacotron/publications/tacotron2/index.html)(official) | -- | -- | [1712.05884](https://arxiv.org/abs/1712.05884) | A |
| [Google tacotron + style transfer sample](https://google.github.io/tacotron/publications/end_to_end_prosody_transfer/)(official)|--|--|[1803.09047](https://arxiv.org/abs/1803.09047)| A |
| [r9y9's wavenet vocoder Tacotron2(189k iterations)](https://r9y9.github.io/wavenet_vocoder/)|[(Download Tacotron2 model)](https://www.dropbox.com/s/vx7y4qqs732sqgg/pretrained.tar.gz?dl=0) - [(Download wavenet model(1000k iterations))](https://www.dropbox.com/s/zdbfprugbagfp2w/20180510_mixture_lj_checkpoint_step000320000_ema.pth?dl=0) - [(Get models)](https://github.com/r9y9/wavenet_vocoder#pre-trained-models)|--| [1712.05884](https://arxiv.org/abs/1712.05884) and [1611.09482](https://arxiv.org/abs/1611.09482)| B |
|[Deepmind's Neural Discrete Representation Learning samples](https://arxiv.org/abs/1711.00937)|--|[Code by dhgrs](https://github.com/dhgrs/chainer-VQ-VAE)|[1711.00937](https://arxiv.org/abs/1711.00937)| B |
|[mazzzystar's Tacotron-WaveRNN samples](https://github.com/mazzzystar/Tacotron-WaveRNN#samples)(730k iterations)|[Get Model](https://github.com/mazzzystar/Tacotron-WaveRNN#pretrained-model)|[Code](https://github.com/mazzzystar/Tacotron-WaveRNN)|--| A |
| [syang1993's tacotron + style transfer samples](https://syang1993.github.io/gst-tacotron/)(200k iterations)|--|--|[1803.09047](https://arxiv.org/abs/1803.09047) and [1803.09017](https://arxiv.org/abs/1803.09017)| C |
| [keithito's tacotron samples(414k iterations)](https://keithito.github.io/audio-samples/)|[(Get model)](https://github.com/keithito/tacotron#using-a-pre-trained-model)|--|--| D |
| [rayhane's Tacotron2 samples(6k4 steps(whatever that means))](https://rayhane-mamah.github.io/Tacotron-2_audio_samples/)|--|--|--| D |
| [Kyubyong's tacotron on LJ dataset(200k iterations)](https://soundcloud.com/kyubyong-park/sets/tacotron_lj_200k)|[(Download model)](https://www.dropbox.com/s/8kxa3xh2vfna3s9/LJ_logdir.zip?dl=0)|--|--| D |
| [Kyubyong's tacotron on nick dataset(215k iterations)](https://soundcloud.com/kyubyong-park/sets/tacotron_nick_215k)|--|--|--| D |
| [Kyubyong's tacotron on web dataset(183k iterations)](https://soundcloud.com/kyubyong-park/sets/tacotron_web_183k)|[(Download model)](https://www.dropbox.com/s/g7m6xhd350ozkz7/WEB_logdir.zip?dl=0)|--|--| D |
| [Kyubyong's expressive tacotron(420k iterations)](https://soundcloud.com/kyubyong-park/sets/expressive_tacotron_420k)|--|--|[1803.09047](https://arxiv.org/abs/1803.09047)| D |
| [Kyubyong's dc-tts on LJ dataset(800k iterations)](https://soundcloud.com/kyubyong-park/sets/dc_tts_lj_800k)|[(Get model)](https://github.com/Kyubyong/dc_tts#pretrained-model-for-lj)|--|--| D |
| [Kyubyong's dc-tts on nick dataset(800k iterations)](https://soundcloud.com/kyubyong-park/sets/dc_tts_nick_800k)|--|--|--| D |
| [Kyubyong's dc-tts kate(800k iterations)](https://soundcloud.com/kyubyong-park/sets/dc_tts_kate_800k)|--|--|--| D |
| [andabi's deep voice conversion](https://soundcloud.com/andabi/sets/voice-style-transfer-to-kate-winslet-with-deep-neural-networks)|--|--|--| D |
| [Facebook Loop samples](https://ytaigman.github.io/loop/)(official)|[(Get pretrained model)](https://github.com/facebookresearch/loop#pretrained-models)|--|--| D |
| [mazzzystar's randomCNN voice transfer](https://soundcloud.com/mazzzystar/sets/speech-conversion-sample)|--|--|[1712.08363](https://arxiv.org/abs/1712.08363)| D |


## Product Demos:

- [Lyrebird samples](https://lyrebird.ai/g/vWI8bJTl)(official)
- [Lyrebird Demo](https://youtu.be/YfU_sWHT8mo)(official)
- [Google Duplex Demo](https://www.youtube.com/watch?v=D5VN56jQMWM&t=66s)(official)
- [Deep Fakes demo](https://www.youtube.com/watch?v=VXZlq70jHvw) [(Download Pretrained model)](https://anonfile.com/p7w3m0d5be/face-swap.zip)
- [Adobe Voco Demo](https://youtu.be/I3l4XLZ59iw)(official)

## Arxiv-sanity

- http://www.arxiv-sanity.com/1705.08947v1
- http://arxiv-sanity.com/1703.10135v2

