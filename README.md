# Recommender Systems in Production
It is a part of my investidation of existing recommenders for our production needs. Hope it might help to others make a right choose.
Why not just contribute into existing lists available on Github? Most of them just list existing libraries w/o enought evidance to use them on production.

# Work in progress!
This article isn't yet finilized.

TODO:
1. [ ] Desrcibe each provided link more deeply. 
2. [ ] Comparision table with existing solutions.
3. [ ] Add a list with proofs that particular library is used in production.

# Some existing lists of Recommenders
1. List of ready recommenders: https://github.com/grahamjenson/list_of_recommender_systems
2. List of papers: 
    1. https://github.com/robi56/Deep-Learning-for-Recommendation-Systems
    2. https://github.com/daicoolb/RecommenderSystem-Paper
    3. https://github.com/OnYuKang/Recommendation-systems-paperlist
3. List of datasets: https://github.com/caserec/Datasets-for-Recommender-Systems

# Solutions
Most popular libraries based on matrix factorization are:
1. https://github.com/benfred/implicit
2. https://github.com/lyst/lightfm

LightFM author later have started to use neural network approach and created:
https://github.com/maciejkula/spotlight
Currently, he is working in Google and develops:
https://github.com/tensorflow/recommenders
https://github.com/tensorflow/recommenders-addons
Before Tensorflow has only library to train rankers:
https://github.com/tensorflow/ranking

Another popular library which employes ANN approach:
https://github.com/jfkirk/tensorrec

Popular implementation of session-based approach using ANN:
https://github.com/hidasib/GRU4Rec

Attention is hot topic in ANN. Here is one implementaion:
https://github.com/kang205/SASRec

Reinforment learning another hot topic. It is usually not so easy to train models. Here are some solutions:
1. https://github.com/criteo-research/reco-gym
2. https://scitator.medium.com/rl-in-recsys-an-overview-e02815019a8f

Graph based solutions:
1. https://github.com/cnclabs/smore

Microsoft's large repostitory about Recommenders. It contains a lot of different solutions like ANN and MF based models:
https://github.com/microsoft/recommenders
Also, they provide implementation using C# and Azure Recommender:
https://github.com/microsoft/Product-Recommendations

Others large companies also has been envolved:
1. Facebook - https://github.com/facebookresearch/dlrm
2. Nvidia - https://github.com/NVIDIA/DeepRecommender
3. IBM - https://github.com/IBM/elasticsearch-spark-recommender

Create yout own RecSys solution is complicated task. In some cases it is easer and cheaper to use SaaS solutions:
1. https://cloud.google.com/retail/recommendations-ai/docs
2. https://retailrocket.net/
1. https://www.recombee.com/

# Need to review
1. https://github.com/NicolasHug/Surprise 
1. https://github.com/DeepGraphLearning/RecommenderSystems
1. https://github.com/shenweichen/DeepCTR
1. https://github.com/shenweichen/DeepMatch
1. https://github.com/evfro/polara
1. https://github.com/mquad/hgru4rec
1. https://github.com/rexyai/rsparse
1. https://github.com/khanhnamle1994/MetaRec
1. https://github.com/etlundquist/rankfm
1. https://github.com/jangmino/HGRU4Rec
1. https://github.com/evfro/HyperbolicRecommenders
1. https://github.com/that-recsys-lab/librec-auto
1. https://github.com/dmitryhd/lightfm
