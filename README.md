# Diversifying Inference Path Selection: Moving-Mobile-Network for Landmark Recognition

## Environment

* python 2.7
* pytorch 0.3.1

## Datasets
We construct two landmark classification datasets: Landmark-420 and Landmark-732, which are available in link

![dataset samples](https://github.com/hfutqian/Diversifying-Inference-Path-Selection-Moving-Mobile-Network-for-Landmark-Recognition/blob/main/images/dataset_samples.png)

## Training process

In the pre-training phase, the policy network is first trained based on both the landmark images and geographic locations. Then the policy network and the pre-trained recognition network are jointly finetuned in the finetuning phase.

(1) Pre-training phase

Run the python file ./Landmark-732/pre-training phase/training_policy_network.py

(2) Finetuning phase

Run the python file ./Landmark-732/finetuning phase/finetune.py


## Citation

    @ARTICLE{9423528,
      author={Qian, Biao and Wang, Yang and Hong, Richang and Wang, Meng and Shao, Ling},
      journal={IEEE Transactions on Image Processing}, 
      title={Diversifying Inference Path Selection: Moving-Mobile-Network for Landmark Recognition}, 
      year={2021},
      volume={30},
      number={},
      pages={4894-4904},
      doi={10.1109/TIP.2021.3076275}
    }
