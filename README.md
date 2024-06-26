# ACRM-for-moment-retrieval

This is the repository of our paper https://ieeexplore.ieee.org/abstract/document/9374685/. 


The pretrained models are provided for [Charades-STA](https://pan.baidu.com/s/1u_MvZA2yG7hI1VvAXmWLeA) which shall be stored in 'Home_path/checkpoints/charades_sta_train' and [TaCoS](https://pan.baidu.com/s/1S68-mba5M22YAX5XeOW6AQ) which shall be stored in 'Home_path/checkpoints/tacos_train'.

The extracted I3D features for [TaCoS](https://pan.baidu.com/s/1SyadxAp5gkst6rVP0RImLA) and for [Charades-STA](https://pan.baidu.com/s/1ATGRLtksAR5Y2hLBZvW5vw) are provided for both of them, which should be stored in 'Home_path/proposal_free/preprocessing/tacos' and 'Home_path/preprocessing/charades-sta', respectively.

The above models and features are stored in Baiduyun disk, where the extraction key is **th08** for all of them.

The pre-trained glove embedding that we use is [glove.840B.300d.zip](https://nlp.stanford.edu/projects/glove/) trained with the Common Crawl (840B tokens, 2.2M vocab, cased, 300d vectors, 2.03 GB download), which shall be unzipped and stored in 'Home_path/data/TMLGA'.

The code is based on https://github.com/crodriguezo/TMLGA. And thanks to their features.

run the program with ``python main.py --config-file experiments/tacos_train.yaml``

# Citing

If you find our paper useful in your research, please consider citing:

@Article{tang2021frame,
  author    = {Tang, Haoyu and Zhu, Jihua and Liu, Meng and Gao, Zan and Cheng, Zhiyong},
  title     = {Frame-wise Cross-modal Matching for Video Moment Retrieval},
  journal   = {IEEE Transactions on Multimedia},
  year      = {2021},
  publisher = {IEEE},
}

