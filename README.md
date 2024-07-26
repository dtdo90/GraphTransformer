# Graph Transformer

Implementation of the Graph Transformer structure in https://arxiv.org/pdf/2012.09699. 

In this elmentation, the usual matrix multiplication QK.T is used to compute the attention coefficients. This is different from the official implementation that uses element-wise multiplication Q*K.

Refer to the official implementation https://github.com/graphdeeplearning/graphtransformer.

# Install DGL for MacOs
1. Dependencies: pydantic, PyYAML, numpy==1.26.4 (version 2 doesn't work)
2. Install pytorch version: pip install torch==2.1.2 torchvision==0.16.2 torchaudio==2.1.2
3. Install dgl: pip install dgl -f https://data.dgl.ai/wheels/repo.html
