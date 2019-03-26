# Text2Gloss

This repo contains the models for the Text2Gloss proposed in "Sign Language Production using Neural Machine Translation and Generative Adversarial Networks (BMVC 2018)".

The models were trained using [an earlier version of Luong et al.'s Neural Machine Translation Tutorial](https://github.com/tensorflow/nmt/tree/tf-1.2). 

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
      author = {[Stephanie Stoll and Necati Cihan Camgoz and Simon Hadfield and Richard Bowden](http://www.cihancamgoz.com/pub/stoll2018bmvc.pdf)},
      title = {Sign Language Production using Neural Machine Translation and Generative Adversarial Networks},
      booktitle = {British Machine Vision Conference (BMVC)},
      year = {2018}
    }

## Other Research:

[Neural Sign Language Translation](https://github.com/neccam/nslt)
