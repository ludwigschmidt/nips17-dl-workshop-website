# Workshop Abstract
The past five years have seen a huge increase in the capabilities of deep neural networks. Maintaining this rate of progress however, faces some steep challenges, and awaits fundamental insights. As our models become more complex, and venture into areas such as unsupervised learning or reinforcement learning, designing improvements becomes more laborious, and success can be brittle and hard to transfer to new settings.

This workshop seeks to highlight recent works that use theory as well as systematic experiments to isolate the fundamental questions that need to be addressed in deep learning. These have helped flesh out core questions on topics such as generalization, adversarial robustness, large batch training, generative adversarial nets, and optimization, and point towards elements of the theory of deep learning that is expected to emerge in the future.

The workshop aims to enhance this confluence of theory and practice, highlighting influential work with these methods, future open directions, and core fundamental problems. There will be an emphasis on discussion, via panels and round tables, to identify future research directions that are promising and tractable.

# Confirmed Speakers
- [Peter Bartlett](https://www.stat.berkeley.edu/~bartlett/) (UC Berkeley)
- [Yoshua Bengio](http://www.iro.umontreal.ca/~bengioy/yoshua_en/) (University of Montreal)
- [Ian Goodfellow](http://www.iangoodfellow.com/) (Google Brain)
- [Sham Kakade](https://homes.cs.washington.edu/~sham/) (University of Washington)
- [Percy Liang](https://cs.stanford.edu/~pliang/) (Stanford University)
- [Doina Precup](http://cs.mcgill.ca/~dprecup/) (McGill University)


# Schedule

| Time | Event |
| --- | --- |
| 8:35 - 8:45 | Opening Remarks |
| 8:45 - 9:15 | Yoshua Bengio: *Generalization, Memorization and SGD* |
| 9:15 - 9:45 | Ian Goodfellow: *Bridging Theory and Practice of GANs* |
| 9:45 - 10:00 | Spotlights 1 |
| 10:00 - 10:30 | Peter Bartlett: *Generalization in Deep Networks* |
| 10:30 - 11:00 | Coffee |
| 11:00 - 11:30 | Doina Precup: *Experimental design in Deep Reinforcement Learning* |
| 11:30 - 11:45 | Spotlights 2 |
| 11:45 - 1:30 | Lunch + first poster session |
| 1:30 - 2:00 | Percy Liang: *Fighting Black Boxes, Adversaries, and Bugs in Deep Learning* |
| 2:00 - 3:00 | Contributed talks |
| 3:00 - 4:00 |  Coffee + second poster session |
| 4:00 - 4:30 | Sham Kakade: *Towards Bridging Theory and Practice in DeepRL* |
| 4:30 - 5:30 | Panel: Peter Bartlett, Yoshua Bengio, Sham Kakade, Percy Liang, Ruslan Salakhutdinov |

## Spotlights 1  (9:45 - 10:00)
1. Generalization in Deep Networks: The Role of Distance from Initialization    
*Vaishnavh Nagarajan and Zico Kolter*  
2.  Entropy-SG(L)D optimizes the prior of a (valid) PAC-Bayes bound  
*Gintare Karolina Dziugaite and Daniel Roy*  
3. Large Batch Training of Deep Neural Networks with Layer-wise Adaptive Rate Scaling    
*Boris Ginsburg, Yang You, and Igor Gitman*  

## Spotlights 2  (11:30 - 11:45)
1. Measuring the Robustness of Neural Networks via Minimal Adversarial Examples  
*Sumanth Dathathri, Stephan Zheng, Sicun Gao, and Richard M. Murray*  
2. [A Classification-Based Perspective on GAN Distributions](https://arxiv.org/abs/1711.00970)    
*Shibani Santurkar, Ludwig Schmidt, and Aleksander Madry*  
3. Learning One-hidden-layer Neural Networks with Landscape Design  
*Rong Ge, Jason Lee, and Tengyu Ma* 

## Contributed talks (2:00 - 3:00)
1. Don't Decay the Learning Rate, Increase the Batch Size  
*Samuel L. Smith, Pieter-Jan Kindermans, and Quoc V. Le*  
2. [Meta-Learning and Universality: Deep Representations and Gradient Descent Can Approximate Any Learning Algorithm](https://arxiv.org/abs/1710.11622)  
*Chelsea Finn and Sergey Levine*  
3. Hyperparameter Optimization: A Spectral Approach  
*Elad Hazan, Adam Klivans, and Yang Yuan*  
4. Learning Implicit Generative Models with Method of Learned Moments  
*Suman Ravuri, Shakir Mohamed, Mihaela Rosca, and Oriol Vinyals* 

## Posters (11:45 - 1:30 and 3:00 - 4:00)
The posters are listed in order of submission.

- Rethinking Feature Discrimination and Polymerization for Large-scale Recognition  
*Yu Liu, Hongyang Li, and Xiaogang Wang*
- [High dimensional dynamics of generalization error in neural networks](https://arxiv.org/abs/1710.03667)  
*Madhu Advani and Andrew Saxe*
- [On the importance of single directions for generalization](https://github.com/ludwigschmidt/nips17-dl-workshop-website/blob/master/papers/morcos_barrett_rabinowitz_botvinick.pdf)  
*Ari S. Morcos, David G.T. Barrett, Neil C. Rabinowitz, and Matthew Botvinick*
- [When is a Convolutional Filter Easy to Learn?](http://www.cs.cmu.edu/~ssdu/publications/filter.pdf)  
*Simon Du, Jason Lee, and Yuandong Tian*
- [A Pitfall of Unsupervised Pre-Training](https://arxiv.org/abs/1703.04332)  
*Michele Alberti, Mathias Seuret, Rolf Ingold, and Marcus Liwicki*
- Competitive Learning Enriches Learning Representation and Accelerates the Fine-tuning of CNNs  
*Takashi Shinozaki*
- [Reducing Duplicate Filters in Deep Neural Networks](http://people.cs.umass.edu/~arunirc/downloads/pubs/redundant_filter_dltp2017.pdf)  
*Aruni Roychowdhury, Prakhar Sharma, and Erik Learned-Miller*
- [Generalization Bounds of SGLD for Non-convex Learning: Two Theoretical Viewpoints](https://arxiv.org/abs/1707.05947)  
*Wenlong Mou, Liwei Wang, Xiyu Zhai, and Kai Zheng*
- [Towards Provable Learning of Polynomial Neural Networks Using Low-Rank Matrix Estimation](https://github.com/ludwigschmidt/nips17-dl-workshop-website/blob/master/papers/soltani_hegde.pdf)  
*Mohammadreza Soltani and Chinmay Hegde*
- Learning Depth-Three Neural Networks in Polynomial Time  
*Surbhi Goel and Adam Klivans*
- Analyzing GANs with Generative Scattering Networks  
*Tomas Angles and Stephane Mallat*
- On Characterizing the Capacity of Neural Networks Using Algebraic Topology  
*William Guss and Ruslan Salakhutdinov*
- Deep Learning is Robust to Massive Label Noise  
*David Rolnick, Andreas Veit, Serge Belongie, and Nir Shavit*
- [Network Approximation using Tensor Sketching](https://arxiv.org/abs/1710.07850)  
*Shiva Kasiviswanathan, Nina Narodytska, and Hongxia Jin*
- Evaluation of Random Neural Layers in Deep Neural Networks  
*Corentin Hardy, Erwan Le Merrer, Gerardo Rubino, and Bruno Sericola*
- Training GANs with Optimism  
*Constantinos Daskalakis, Andrew Ilyas, Vasilis Syrgkanis, and Haoyang Zeng*
- GAN Connoisseur: Can GANs Learn Simple 1D Parametric Distributions?  
*Manzil Zaheer, Chun-Liang Li, Barnabas Poczos, and Ruslan Salakhutdinov*
- LSH Softmax: Sub-Linear Learning and Inference of the Softmax Layer in Deep Architectures  
*Daniel Levy, Danlu Chen, and Stefano Ermon*
- Global optimality conditions for deep neural networks  
*Chulhee Yun, Suvrit Sra, and Ali Jadbabaie*
- Visualizing the Loss Landscape of Neural Nets  
*Hao Li, Zheng Xu, Gavin Taylor, and Tom Goldstein*
- Semi-Supervised Learning with IPM-based GANs: an Empirical Study  
*Tom Sercu and Youssef Mroueh*
- Theoretical limitations of Encoder-Decoder GAN architectures  
*Sanjeev Arora, Andrej Risteski, and Yi Zhang*
- An Online Learning Approach to Generative Adversarial Networks  
*Paulina Grnarova, Kfir Levy, Aurelien Lucchi, Thomas Hofmann, and Andreas Krause*
- [mixup: Beyond Empirical Risk Minimization](https://arxiv.org/abs/1710.09412)  
*Hongyi Zhang, Moustapha Cisse, Yann Dauphin, and David Lopez-Paz*
- An Empirical Study of the Generalization Behavior of Generative Adversarial Networks  
*Hongyu Ren, Shengjia Zhao, Jiaming Song, Lijie Fan, and Stefano Ermon*
- [Towards a testable notion of generalization for generative adversarial networks](http://www.robots.ox.ac.uk/~rcornish/assets/bib/workshop/cornish2017towards.pdf)  
*Robert Cornish, Hongseok Yang, and Frank Wood*
- Sparse Coding and Autoencoders  
*Akshay Rangamani, Anirbit Mukherjee, Ashish Arora, Amitabh Basu, Tejaswini Ganapathi, Peter Chin, and Trac Tran*
- Investigating the working of text classifiers  
*Devendra Singh Sachan, Manzil Zaheer, and Russ Salakhutdinov*
- Intriguing Properties of Adversarial Examples  
*Ekin Dogus Cubuk, Barret Zoph, Samuel S. Schoenholz, and Quoc V. Le*
- Sparse-Gen: Combining Sparse Recovery and Generative Modeling for Compressed Sensing  
*Manik Dhar, Aditya Grover, and Stefano Ermon*
- Experiments & non-convex theory for sign-based methods in stochastic optimisation  
*Jeremy Bernstein, Kamyar Azizzadenesheli, Yu-Xiang Wang, and Anima Anandkumar*
- Exactly solvable nonlinear recurrent networks for finite state computation  
*Christopher Stock and Surya Ganguli*
- Training ultra-deep CNNs with critical initialization  
*Lechao Xiao, Yasaman Bahri, Sam Schoenholz, and Jeffrey Pennington*


# Call for Papers and Submission Instructions
We invite researchers to submit anonymous extended abstracts of up to 4 pages (excluding references). No specific formatting is required. Authors may use the NIPS style file, or any other style as long as they have standard font size (11pt) and margins (1in).

Submit on [https://easychair.org/conferences/?conf=dltp2017](https://easychair.org/conferences/?conf=dltp2017).


# Important Dates
- Submission Deadline: (EXTENDED) Wednesday November 1st
- Notification: Saturday November 25th
- Workshop: Saturday December 9th

# Organizers
- [Sanjeev Arora](https://www.cs.princeton.edu/~arora/) (Princeton University)
- [Maithra Raghu](http://maithraraghu.com/) (Cornell University and Google Brain)
- [Ruslan Salakhutdinov](http://www.cs.cmu.edu/~rsalakhu/) (Carnegie Mellon University)
- [Ludwig Schmidt](http://people.csail.mit.edu/ludwigs/) (MIT)
- [Oriol Vinyals](https://research.google.com/pubs/OriolVinyals.html) (DeepMind)

Please email [nips2017deeplearning@gmail.com](mailto:nips2017deeplearning@gmail.com) with any questions.
