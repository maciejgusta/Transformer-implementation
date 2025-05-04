# Transformer implementation

**Slightly modified Transformer implementaion** based on the [Attention Is All You Need](https://arxiv.org/pdf/1706.03762). 

### Changes to the architecture:
- Decided not to use shared weight matrix between the two embedding layers and the pre-softmax linear transformation - used two separate matrices instead (Section 3.4 of the paper)

This repository is purely educational and aims to get insight on the Transformer architecture rather than achieve the optimal implementation for maximum performance.
