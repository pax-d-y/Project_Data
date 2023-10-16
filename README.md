# Project

<p align="center">
  <img width="192" height="312" src="/images/cc12m_1.jpg">
  <img width="192" height="312" src="/images/cc12m_2.jpg">
</p>

We introduce the Conceptual 12M (CC12M), a dataset with ~12 million image-text pairs meant to be used for vision-and-language pre-training.
It is larger and covers a much more diverse set of visual concepts than [the Conceptual Captions](https://github.com/google-research-datasets/conceptual-captions) (CC3M), a dataset that is widely used for pre-training and end-to-end training of image captioning models.
Check our [paper](https://arxiv.org/abs/2102.08981) for further details.

## Download
Click [here](https://storage.googleapis.com/conceptual_12m/cc12m.tsv) to download (2.5GB)


**Format (.tsv)**
<div class="highlight highlight-source-shell"><pre>
[image_url_1]\t[caption_1]
[image_url_2]\t[caption_2]
[image_url_3]\t[caption_3]
…
[image_url_N]\t[caption_N]
</pre></div>

### Hashcodes
Click [here](https://storage.googleapis.com/cc_hashes/cc12m.tsv.gz) to download (2.12GB).
Credit: [Nicholas Carlini](https://nicholas.carlini.com/)

**Format (.tsv)**
<div class="highlight highlight-source-shell"><pre>
[image_url_1]\t[SHA256_1]\t[MD5_1]
[image_url_2]\t[SHA256_2]\t[MD5_2]
[image_url_3]\t[SHA256_3]\t[MD5_3]
…
[image_url_N]\t[SHA256_N]\t[MD5_N]
</pre></div>

## Cite

If you use this dataset in your research, please cite:

Soravit Changpinyo, Piyush Sharma, Nan Ding, Radu Soricut.
[Conceptual 12M: Pushing Web-Scale Image-Text Pre-Training To Recognize Long-Tail Visual Concepts](https://arxiv.org/abs/2102.08981).
CVPR 2021.

<div class="highlight highlight-source-shell"><pre>
@inproceedings{changpinyo2021cc12m,
  title = {{Conceptual 12M}: Pushing Web-Scale Image-Text Pre-Training To Recognize Long-Tail Visual Concepts},
  author = {Changpinyo, Soravit and Sharma, Piyush and Ding, Nan and Soricut, Radu},
  booktitle = {CVPR},
  year = {2021},
}
</pre></div>


