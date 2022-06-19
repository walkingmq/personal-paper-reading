# Benchmark Tracking: Models, Tasks and Datasets

## Code Pre-Training

| Model         | #Model Size   | Training Corpus      | PL |
| ------------- |  :-----  | -----                  |  :-----: |
| CodeBERT      |  50k(50,265)- 768D-12L -0L-12H-3072FF-124M(124,645,632) | CodeSearchNet          | - |
| CodeGPT-adapted| 50k(50,260)- 768D-12L -0L-12H-124M(124,442,112) | CodeSearchNet          | - |
| GraphCodeBERT |  50k(50,265)- 768D-12L -0L-12H-3072FF-124M(124,645,632) | CodeSearchNet          | - |
| Unixcoder     |  50k(51,416)- 768D-12L -0L-12H-3072FF-126M(125,929,728) | CodeSearchNet          | - |
| TransCoder    |  64k(63,961)-1024D- 6L- 6L- 8H-4096FF-312M(311,681,970) | Github           | Python/Java/Cpp | 
| PLBART        |  50k(50,005)- 768D- 6L- 6L-12H-3072FF-139M(139,220,736) | github & stackoverflow | Java/Python/English |
| CodeT5-base   |  32k(32,100)- 768D-12L-12L-12H-3072FF-223M(222,882,048) | CodeSearchNet          | - |
| CODE-MVP      |  - | CodeSearchNet          | Python |
