# List-of-Papers-that-use-Multimodal-LLMs-for-Recommendation
List of Papers that use (Multimodal) LLMs for (Micro Video) Recommendation

Each paper is listed with the paper title/Admission Conference/release date/summary/opinion/paper link.

# For reference（GREEN）:
- LLMRec: Large Language Models with Graph Augmentation for Recommendation [[PDF](https://dl.acm.org/doi/pdf/10.1145/3616855.3635853)]  
  WSDM2024 Mar-24  
  Use OpenAI's ADA and Davinci to enhance graph data, image and text encoders with clip-vit and sentence-BERT  
  The direction is the same, the problem is that the video modality is missing and the API is charged  
- Rec-GPT4V: Multimodal Recommendation with Large Vision-Language Models   [[PDF](https://arxiv.org/pdf/2402.08670.pdf)]  
  arxiv Feb-24  
  Use GPT and LLAVA as a recommender system  
  correlation，can refer to  
- Can Small Language Models be Good Reasoners for Sequential Recommendation [[PDF](https://arxiv.org/pdf/2403.04260.pdf)]  
  arxiv Mar-24  
  Knowledge distillation training LLaMA2-7B  
  The framework can be refer to, but it is not enough to take stepbystep to do novelty  
- Towards Efficient and Effective Unlearning of Large Language Models for Recommendation [[PDF](https://arxiv.org/pdf/2403.03536v1.pdf)]  
  arxiv Mar-24  
  After giving the LLM the recommendation capability, forget the specific data  
  Less parameter learning, can be reafer to  
- Visual instruction tuning [[PDF](https://proceedings.neurips.cc/paper_files/paper/2023/file/6dcf277ea32ce3288914faf369fe6de0-Paper-Conference.pdf)]  
  NeurIPS2023 Nov-23  
  LLAVA  
  Open-source multimodal large models   
- Multi-modal self-supervised learning for recommendation [[PDF](https://dl.acm.org/doi/pdf/10.1145/3543507.3583206)]  
  WWW2023 Apr-23  
  Adversarial perturbations, multimodal contrastive learning, and open source code  
  can take a look at the model, the encoder selection, the effect  
- ONCE: Boosting Content-based Recommendation with Both Open- and Closed-source Large Language Models [[PDF](https://dl.acm.org/doi/pdf/10.1145/3616855.3635845)]  
  WSDM2024 Mar-24  
  Explore the open-source closed-source LLMRec, and finetune parameters of LLaVa on one A100 (80G).  
  pipeline can be refer to     
- Repeated Padding as Data Augmentation for Sequential Recommendation [[PDF](https://arxiv.org/pdf/2403.06372v1.pdf)]  
  arxiv Mar-24  
  Filling the padding of the sequential rec with a repeating sequence has improved the effect a lot  
  It's very interesting, I feel like I can use it, think about it... Didn't he just repeat the short sequence and turn it into something like a duplicate purchase... Isn't that data fraud?  
- NineRec: A Benchmark Dataset Suite for Evaluating Transferable Recommendation [[PDF](https://arxiv.org/pdf/2309.07705.pdf)]  
  TPAMI Mar-24  
  The cove and title datasets of 500k and 2M user are from Bilibili and other platforms  
  After taking a look at the early version, in which Appendix Table 5 has a cost, you can pay attention to the cost part of the full version and the effect of PT  
- Self-Attentive Sequential Recommendation [[PDF](https://arxiv.org/pdf/1808.09781.pdf)]  
  IEEE2018 Nov-18  
  Self-attention is applied to the user interaction sequence of REC to shorten the relationship between embedding in the same sequence  
  Baseline, does that mean the initial embedding isn't important? Finally, embedding is all sequence information?  
- PromptMM: Multi-Modal Knowledge Distillation for Recommendation with Prompt-Tuning [[PDF](https://arxiv.org/pdf/2402.17188v1.pdf)]  
  WWW2024 Feb-24  
  Simplify the enhanced recommender system with knowledge distillation  
  There is no use of large language models, but it is a multimodal recommendation  

# expandable（YELLOW）  
- Mamba4Rec: Towards Efficient Sequential Recommendation with Selective State Space Models [[PDF](https://arxiv.org/pdf/2403.03900v1.pdf)]  
  arxiv Mar-24  
  Use MAMBA as a recommender system  
    
- Mamba: Linear-time sequence modeling with selective state spaces [[PDF](https://arxiv.org/ftp/arxiv/papers/2312/2312.00752.pdf)]  
  Mamba model  
  The related words are choice state machines and differential equations  

# not related/bad(RED)  
- Uncovering the Deep Filter Bubble: Narrow Exposure in Short-Video Recommendation [[PDF](https://arxiv.org/pdf/2403.04511.pdf)]  
  arxiv Mar-24  
  Research on the problem of depth filtering bubbles in short video recommendations  
  not related  
- Towards Open-World Recommendation with Knowledge Augmentation from Large Language Models [[PDF](https://arxiv.org/pdf/2306.10933v4.pdf)]  
  arxiv Dec-23  
  The LLM is used to generate open datasets for training  
  Lack of novelty      
- ReLLa: Retrieval-enhanced Large Language Models for Lifelong Sequential Behavior Comprehension in Recommendation [[PDF](https://arxiv.org/pdf/2308.11131.pdf)]  
  arxiv Aug-23  
  RAG, open source code  
  no novelty  
- KELLMRec: Knowledge-Enhanced Large Language Models for Recommendation [[PDF](https://arxiv.org/pdf/2403.06642.pdf)]  
  arxiv Mar-24  
  LLM does REC knowledge enhancement and contrasts learning frameworks  
  The work of Nanjing University and WeChat, the work recommended by the WeChat article, can be referenced, but it lacks novelty and is not open source    
- CoRAL: Collaborative Retrieval-Augmented Large Language Models Improve  Long-tail Recommendation [[PDF](https://arxiv.org/pdf/2403.06447v1.pdf)]  
  arxiv Mar-24  
  It is not open source, reinforcement learning framework, and directly uses LLM to do Recsys  
  I can't understand the methodology, and it is generally not good to use LLM to do Rec directly  
- Pre-Trained Model Recommendation for Downstream Fine-tuning [[PDF](https://arxiv.org/pdf/2403.06382v1.pdf)]  
  arxiv Mar-24  
  A framework for evaluating LLMs is proposed  
  Not related    
