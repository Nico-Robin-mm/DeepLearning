# CS583: Deep Learning


1. **Machine learning basics.**
This part briefly introduces the fundamental ML problems-- regression, classification, dimensionality reduction, and clustering-- and the traditional ML models and numerical algorithms for solving the problems.

    * ML basics. 
    [[slides-1](https://github.com/wangshusen/DeepLearning/blob/master/Slides/1_ML_Basics.pdf)]
    [[slides-2](https://github.com/wangshusen/DeepLearning/blob/master/Slides/1_Models.pdf)]

    
    * Regression. 
    [[slides-1](https://github.com/wangshusen/DeepLearning/blob/master/Slides/2_Regression_1.pdf)] 
    [[slides-2](https://github.com/wangshusen/DeepLearning/blob/master/Slides/2_Regression_2.pdf)]
    
    
    * Classification. 
    
        - Logistic regression: 
        [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/3_Classification_1.pdf)] 
        [[lecture note](https://github.com/wangshusen/DeepLearning/blob/master/LectureNotes/Logistic/paper/logistic.pdf)]
    
        - SVM: [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/3_Classification_2.pdf)] 
    
        - Softmax classifier: [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/3_Classification_3.pdf)] 
    
        - KNN classifier: [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/3_Classification_4.pdf)]
    
    * Regularizations. 
    [[slides-1](https://github.com/wangshusen/DeepLearning/blob/master/Slides/3_Optimization.pdf)]
    [[slides-2](https://github.com/wangshusen/DeepLearning/blob/master/Slides/3_Regularizations.pdf)]
    
    * Clustering. 
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/4_Clustering.pdf)] 
    
    * Dimensionality reduction. 
    [[slides-1](https://github.com/wangshusen/DeepLearning/blob/master/Slides/5_DR_1.pdf)] 
    [[slides-2](https://github.com/wangshusen/DeepLearning/blob/master/Slides/5_DR_2.pdf)] 
    [[lecture note](https://github.com/wangshusen/DeepLearning/blob/master/LectureNotes/SVD/svd.pdf)]
    
    * Scientific computing libraries.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/5_DR_3.pdf)]
    
    
2. **Neural network basics.**
This part covers the multilayer perceptron, backpropagation, and deep learning libraries, with focus on Keras.

    * Multilayer perceptron and backpropagation. 
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/6_NeuralNet_1.pdf)]
    [[lecture note](https://github.com/wangshusen/DeepLearning/blob/master/LectureNotes/BP/bp.pdf)]
    
    * Keras. 
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/6_NeuralNet_2.pdf)]
    
    * Further reading:
    
        - [[activation functions](https://adl1995.github.io/an-overview-of-activation-functions-used-in-neural-networks.html)]
        
        - [[parameter initialization](https://towardsdatascience.com/weight-initialization-in-neural-networks-a-journey-from-the-basics-to-kaiming-954fb9b47c79)]
    
        - [[optimization algorithms](http://ruder.io/optimizing-gradient-descent/)]
    
    
3. **Convolutional neural networks (CNNs).**
This part is focused on CNNs and its application to computer vision problems.

    * CNN basics.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/7_CNN_1.pdf)]
    
    * Tricks for improving test accuracy.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/7_CNN_2.pdf)]
    
    * Feature scaling and batch normalization.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/7_CNN_3.pdf)]
    
    * Advanced topics on CNNs. 
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/7_CNN_4.pdf)]
    
    * Popular CNN architectures.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/7_CNN_5.pdf)]
    
    * Face recognition.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/7_CNN_6.pdf)]
    
    * Further reading: 
    
        - [style transfer (Section 8.1, Chollet's book)]
        
        - [visualize CNN (Section 5.4, Chollet's book)]



4. **Recurrent neural networks (RNNs).**
This part introduces RNNs and its applications in natural language processing (NLP).

    * Text processing.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/9_RNN_1.pdf)] 
       
    * RNN basics and LSTM.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/9_RNN_2.pdf)]
    [[reference](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)]
   
    * Text generation.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/9_RNN_3.pdf)]
    
    * Machine translation. 
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/9_RNN_4.pdf)]
    
    * Image caption generation. 
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/9_RNN_5.pdf)]
    [[reference](https://machinelearningmastery.com/develop-a-deep-learning-caption-generation-model-in-python/)]
    
    * Attention. 
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/9_RNN_6.pdf)]
    [[reference-1](https://distill.pub/2016/augmented-rnns/)]
    [[reference-2](https://lilianweng.github.io/lil-log/2018/06/24/attention-attention.html)]
    
    * Transformer model: beyond RNNs. 
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/9_RNN_7.pdf)]
    [[reference](https://arxiv.org/pdf/1706.03762.pdf)]
    
    * Further reading: 
        
        - [[GloVe: Global Vectors for Word Representation](http://www.aclweb.org/anthology/D14-1162)]
        
        - [[Neural Word Embedding as Implicit Matrix Factorization](https://papers.nips.cc/paper/5477-neural-word-embedding-as-implicit-matrix-factorization.pdf)]


5. **Autoencoders.**
This part introduces autoencoders for dimensionality reduction and image generation.

    * Autoencoder for dimensionality reduction.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/8_AE_1.pdf)]
    
    * Variational Autoencoders (VAEs) for image generation. 
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/8_AE_2.pdf)]

    
6. **Generative Adversarial Networks (GANs).** 

    * DC-GAN [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/12_GAN.pdf)]



7. **Recommender system.** 
This part is focused on the collaborative filtering approach to recommendation based on the user-item rating data.
This part covers matrix completion methods and neural network approaches. 

    * Collaborative filtering. 
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/10_Recommender.pdf)]

    
8. **Deep Reinforcement Learning.** 

    * Reinforcement learning [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/13_RL_1.pdf)] [[lecture note](https://github.com/wangshusen/DeepLearning/blob/master/LectureNotes/DRL/DRL.pdf)]

    * Value-based learning [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/13_RL_2.pdf)]

    * Policy-based learning [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/13_RL_3.pdf)]

    * Actor-critic methods [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/13_RL_4.pdf)]

    * AlphaGo [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/13_RL_5.pdf)]


9. **Parallel Computing.** 

	* Basics and MapReduce. [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/14_Parallel_1.pdf)] [[lecture note](https://github.com/wangshusen/DeepLearning/blob/master/LectureNotes/Parallel/Parallel.pdf)]
	
	* Parameter Server and Decentralized Network. [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/14_Parallel_2.pdf)] 
	
	* Federated Learning. [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/14_Parallel_3.pdf)] 


10. **Adversarial Robustness.**
This part introduces how to attack neural networks using adversarial examples and how to defend from the attack.

	* Data evasion attack and defense.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/11_Adversarial.pdf)]
    [[lecture note](https://github.com/wangshusen/DeepLearning/blob/master/LectureNotes/Adversarial/DataAttacks.pdf)]
        
    * Further reading:
    [[Adversarial Robustness - Theory and Practice](https://adversarial-ml-tutorial.org/)]
    



