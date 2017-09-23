# some awesome image retrieval papers

> 1、Deep Learning for Content-Based Image Retrieval

> 2、Online Multimodal Deep Similarity Learning with Application to Image Retrieval

> 3、Neural Codes for Image Retrieval

> 4、A practical guide to CNNs and Fisher Vectors for image instance retrieval

> 5、Convolutional Neural Codes for Image Retrieval

> 6、Deep Convolutional Features for Image Based Retrieval and Scene Categorization

> 7、Deep Hashing for Compact Binary Codes Learning

> 8、Deep Learning of Binary Hash Codes for Fast Image Retrieval

> 9、Deep Semantic Ranking Based Hashing for Multi-Label Image Retrieval

> 10、Efficient Manifold Ranking for Image Retrieval

> 11、Iterative Quantization A Procrustean Approach to Learning Binary Codes

> 12、Large Scale Online Learning of Image Similarity Through Ranking

> 13、Learning Hash Functions Using Sparse Reconstruction

> 14、Using Very Deep Autoencoders for Content-Based Image Retrieval

> 15、Supervised Learning of Semantics-Preserving Hashing via Deep Neural Networks for Large-Scale Image Search


-----------------update-------------------

## Awesome image retrieval papers

#### Local Feature Based

- [Object retrieval with large vocabularies and fast spatial matching](https://www.robots.ox.ac.uk/~vgg/publications/papers/philbin07.pdf)
- [Improving the Fisher Kernel for Large-Scale Image Classification](https://www.robots.ox.ac.uk/~vgg/rg/papers/peronnin_etal_ECCV10.pdf)
- [Visual Categorization with Bags of Keypoints](http://www.cs.princeton.edu/courses/archive/fall09/cos429/papers/csurka-eccv-04.pdf)
- [ORB: an efficient alternative to SIFT or SURF](https://www.willowgarage.com/sites/default/files/orb_final.pdf)
- [Object Recognition from Local Scale-Invariant Features](http://www.cs.ubc.ca/~lowe/papers/iccv99.pdf)
- [Total Recall: Automatic Query Expansion with a Generative Feature Model for Object Retrieval](https://www.robots.ox.ac.uk/~vgg/publications/papers/philbin07.pdf)
- [Three things everyone should know to improve object retrieval](https://www.robots.ox.ac.uk/~vgg/publications/2012/Arandjelovic12/arandjelovic12.pdf)
- [On-the-fly learning for visual search of large-scale image and video datasets](https://www.robots.ox.ac.uk/~vgg/publications/2015/Chatfield15/chatfield15.pdf)

#### Deep Learning Feature Based

- [Deep Image Retrieval:Learning Global Representations for Image earch](https://arxiv.org/abs/1604.01325)
- [End-to-end Learning of Deep Visual Representations for Image retrieval](), DIR更详细的论文说明
- [What Is the Best Practice for CNNs Applied to Visual Instance Retrieval?](), 关于layer选取的问题
- [Bags of Local Convolutional Features for Scalable Instance Search](https://arxiv.org/abs/1604.01325)
- [Faster R-CNN Features for Instance Search](https://github.com/imatge-upc/retrieval-2016-deepvision)
- [Cross-dimensional Weighting for Aggregated Deep Convolutional Features](https://arxiv.org/abs/1512.04065), [project](https://github.com/yahoo/crow)
- [Class-Weighted Convolutional Features for Image Retrieval](https://github.com/imatge-upc/retrieval-2017-cam)
- [Multi-Scale Orderless Pooling of Deep Convolutional Activation Features](), VLAD coding
- [Aggregating Deep Convolutional Features for Image Retrieval](https://arxiv.org/abs/1510.07493), [论文笔记](https://zhuanlan.zhihu.com/p/23136747), [基于深度学习的视觉实例搜索研究进展](https://zhuanlan.zhihu.com/p/22265265).
- [Particular object retrieval with integral max-pooling of CNN activations](https://arxiv.org/abs/1511.05879), [project](http://cmp.felk.cvut.cz/~toliageo/soft.html)
- [Particular object retrieval using CNN](https://github.com/AaltoVision/Object-Retrieval)
- [Learning to Match Aerial Images with Deep Attentive Architectures](https://vision.cornell.edu/se3/wp-content/uploads/2016/04/1204.pdf).
- [Siamese Network of Deep Fisher-Vector Descriptors for Image Retrieval](https://arxiv.org/pdf/1702.00338v1.pdf)
- [Combining Fisher Vector and Convolutional Neural Networks for Image Retrieval](http://ceur-ws.org/Vol-1653/paper_19.pdf), fv和cnn特征融合提升
- [Selective Deep Convolutional Features for Image Retrieval](https://arxiv.org/pdf/1707.00809v1.pdf)
- [Class-Weighted Convolutional Features for Image Retrieval](https://github.com/imatge-upc/retrieval-2017-cam)

#### ANN search

- [Practical and Optimal LSH for Angular Distance](chrome-extension://ikhdkkncnoglghljlkmcimlnlhkeamad/pdf-viewer/web/viewer.html?file=http%3A%2F%2Fpapers.nips.cc%2Fpaper%2F5893-practical-and-optimal-lsh-for-angular-distance.pdf)
- [pq-fast-scan](https://github.com/technicolor-research/pq-fast-scan)
- [faiss](https://github.com/facebookresearch/faiss). A library for efficient similarity search and clustering of dense vectors.
- [lopq](https://github.com/yahoo/lopq). Training of Locally Optimized Product Quantization (LOPQ) models for approximate nearest neighbor search of high dimensional data in Python and Spark.
- [nns_benchmark](https://github.com/DBWangGroupUNSW/nns_benchmark). Benchmark of Nearest Neighbor Search on High Dimensional Data.
- [Optimized Product Quantization](http://kaiminghe.com/cvpr13/index.html)
- [Falconn](https://github.com/FALCONN-LIB/FALCONN). FAst Lookups of Cosine and Other Nearest Neighbors.
- [Annoy](https://github.com/spotify/annoy). Approximate Nearest Neighbors in C++/Python optimized for memory usage and loading/saving to disk 
- [NMSLIB](https://github.com/searchivarius/nmslib). Non-Metric Space Library (NMSLIB): A similarity search library and a toolkit for evaluation of k-NN methods for generic non-metric spaces.

#### Industry CBIR

- [Visual Search at Pinterest]()
- [Visual Discovery at Pinterest]()
- [Visual Search at ebay]()

#### feature fusion

- [Feature fusion using Canonical Correlation Analysis](https://github.com/mhaghighat/ccaFuse)

#### Feature Matching

- [Image Matching Benchmark](https://arxiv.org/pdf/1709.03917.pdf)
- [GMS: Grid-based Motion Statistics for Fast, Ultra-robust Feature Correspondence]()
- [A Vote-and-Verify Strategy for Fast Spatial Verification in Image Retrieval](https://github.com/vote-and-verify/vote-and-verify)
- [CODE: Coherence Based Decision Boundaries for Feature Correspondence]()
- [Robust feature matching in 2.3µs](https://www.edwardrosten.com/work/taylor_2009_robust.pdf)
- [PopSift is an implementation of the SIFT algorithm in CUDA](https://github.com/alicevision/popsift)
- [openMVG robust_estimation](https://github.com/openMVG/openMVG/tree/e3a0bde5e9c676d1cb663a38f7e74c771324d69a/src/openMVG/robust_estimation)

#### Plan to read

- [VisualRank: Applying PageRank to Large-Scale Image Search]()

### Tutorials

- [Recent Image Search Techniques](http://cvpr2016.thecvf.com/program/tutorials)
- [Compact Features for Visual Search](http://cvpr2016.thecvf.com/program/tutorials)
- [multimedia-indexing](https://github.com/MKLab-ITI/multimedia-indexing). A framework for large-scale feature extraction, indexing and retrieval.


## Awesome multiclass classification

### papers

- [Loss Functions for Top-k Error: Analysis and Insights]() and [Top-k Multiclass SVM](), [code](https://github.com/mlapin/libsdca)

### Tutorials

- [Linear Classification](http://cs231n.github.io/linear-classify/), [中文版](http://blog.csdn.net/elaine_bao/article/details/50519970), [demo](http://vision.stanford.edu/teaching/cs231n/linear-classify-demo/)

---

## Logo Detection and Classification

### Papers

- [LOGO-Net: Large-scale Deep Logo Detection and Brand Recognition with Deep Region-based Convolutional Networks](https://arxiv.org/abs/1511.02462)

---

## Object Detection and Recognition

### Papers

- [SSD: Single Shot MultiBox Detector](www.cs.unc.edu/~wliu/papers/ssd.pdf), [code](https://github.com/weiliu89/caffe/tree/ssd)
- [A Closer Look: Small Object Detection in Faster R-CNN]()

---

## Video Classification

### Papers

- [Large-scale Video Classification with Convolutional Neural Networks](vision.stanford.edu/pdf/karpathy14.pdf)
- [Learning Spatiotemporal Features With 3D Convolutional Networks](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Tran_Learning_Spatiotemporal_Features_ICCV_2015_paper.pdf), [code](https://github.com/Lasagne/Recipes/blob/master/examples/Video%20features%20with%20C3D.ipynb), [doc](https://docs.google.com/document/d/1-QqZ3JHd76JfimY4QKqOojcEaf5g3JS0lNh-FHTxLag/edit), [project](http://vlg.cs.dartmouth.edu/c3d/)
- [ActionVLAD: Learning spatio-temporal aggregation for action classification](https://rohitgirdhar.github.io/ActionVLAD/)

---

## ROS for Robotics

- [Learning_ROS_for_Robotics_Programming_2nd_edition](https://github.com/AaronMR/Learning_ROS_for_Robotics_Programming_2nd_edition)

---

## Image Fingerprinting

- [Video fingerprinting tool. Finding duplicate movies in a large dataset](https://github.com/funzoneq/video_fingerprinting)
