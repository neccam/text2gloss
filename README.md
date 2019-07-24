# Text2Gloss

This repo contains the models for the Text2Gloss proposed in "[Sign Language Production using Neural Machine Translation and Generative Adversarial Networks (BMVC 2018)](http://www.cihancamgoz.com/pub/stoll2018bmvc.pdf)".

The models were trained using [an earlier version of Luong et al.'s Neural Machine Translation Code](https://github.com/tensorflow/nmt/tree/tf-1.2). 

## Requirements
* Download and extract [RWTH-PHOENIX-Weather 2014 T: Parallel Corpus of Sign Language Video, Gloss and Translation](https://www-i6.informatik.rwth-aachen.de/~koller/RWTH-PHOENIX-2014-T/)
* Download and install Tensorflow 1.3.0+ 
* Download [TensorFlow NMT](https://github.com/tensorflow/nmt/tree/tf-1.2) library.
* Python 2.7

### Inference Sample Usage

python -m nmt --out_dir=<your_model_dir> --inference_input_file=<input_video_paths.de> --inference_output_file=<predictions.gloss> --inference_ref_file=<ground_truth.gloss>


## Reference

Please cite the paper below if you use this model in your research:

    @inproceedings{stoll2018sign,
      author = {Stephanie Stoll and Necati Cihan Camgoz and Simon Hadfield and Richard Bowden},
      title = {Sign Language Production using Neural Machine Translation and Generative Adversarial Networks},
      booktitle = {British Machine Vision Conference (BMVC)},
      year = {2018}
    }


## Other Research:

[Neural Sign Language Translation](https://github.com/neccam/nslt)

#### Acknowledgement
<sub>This work was funded by the SNSF Sinergia project "Scalable Multimodal Sign Language Technology for Sign Language Learning and Assessment" (SMILE) grant agreement number CRSII2 160811 and the European Union’s Horizon2020 research and innovation programme under grant agreement no. 762021 (Content4All). This work reflects only the author’s view and the Commission is not responsible for any use that may be made of the information it contains. We would also like to thank NVIDIA Corporation for their GPU grant. </sub>
