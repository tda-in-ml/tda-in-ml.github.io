---
layout: default
title: Accepted Papers
---

This is the list of all accepted papers. You can find more information
about each submission by following either the *Forum* link or by
visiting the [OpenReview Workshop Website](https://openreview.net/group?id=NeurIPS.cc/2020/Workshop/TDA_and_Beyond).

# Statistics

We received 53 submissions in total, of which we accepted 10 spotlights
and 29 poster presentations. All submissions received at least two
reviews, which were afterwards weighted, read, and considered by members
of the organisation committee independently.

Congratulations to all authors!

# Spotlights

**$k$-simplex2vec: a simplicial extension of node2vec** (Spotlight presentation)<br />
Celia Hacker<br />
<abstract>We present a novel method of associating Euclidean features to simplicial complexes, providing a way to use them as input to statistical and machine learning tools. This method extends the node2vec algorithm to simplices of higher dimensions, providing insight into the structure of a simplicial complex, or into the higher-order interactions in a graph. </abstract>

[PDF](https://openreview.net/pdf?id=Aw9DUXPjq55) &bull;
[Poster](https://openreview.net/attachment?id=Aw9DUXPjq55&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=Aw9DUXPjq55)

<div id="presentation-embed-38941577"></div>
<script src='https://slideslive.com/embed_presentation.js'></script>
<script>
    embed = new SlidesLiveEmbed('presentation-embed-38941577', {
        presentationId: '38941577',
        autoPlay: false, // change to true to autoplay the embedded presentation
        verticalEnabled: true
    });
</script>

<div style="text-align:center">
&#10086;
</div>

**Characterizing the Latent Space of Molecular Deep Generative Models with Persistent Homology Metrics** (Spotlight presentation)<br />
Yair Schiff &bull; Payel Das &bull; Vijil Chenthamarakshan &bull; Karthikeyan Natesan Ramamurthy<br />
<abstract>Deep generative models are increasingly becoming integral parts of the in silico molecule design pipeline and have dual goals of learning the chemical and structural features that render candidate molecules viable while also being flexible enough to generate novel designs. Specifically, Variational Auto Encoders (VAEs) are generative models in which encoder-decoder network pairs are trained to reconstruct training data distributions in such a way that the latent space of the encoder network is smooth. Therefore, novel candidates can be found by sampling from this latent space. However, the scope of architectures and hyperparameters is vast and choosing the best combination for in silico discovery has important implications for downstream success. Therefore, it is important to develop a principled methodology for distinguishing how well a given generative model is able to learn salient molecular features. In this work, we propose a method for measuring how well the latent space of deep generative models is able to encode structural and chemical features of molecular datasets by correlating latent space metrics with metrics from the field of topological data analysis (TDA). We apply our evaluation methodology to a VAE trained on SMILES strings and show that 3D topology information is consistently encoded throughout the latent space of the model.</abstract>

[PDF](https://openreview.net/pdf?id=AN6v6MkWG__) &bull;
[Poster](https://openreview.net/attachment?id=AN6v6MkWG__&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=AN6v6MkWG__)

<div id="presentation-embed-38941579"></div>
<script src='https://slideslive.com/embed_presentation.js'></script>
<script>
    embed = new SlidesLiveEmbed('presentation-embed-38941579', {
        presentationId: '38941579',
        autoPlay: false, // change to true to autoplay the embedded presentation
        verticalEnabled: true
    });
</script>

<div style="text-align:center">
&#10086;
</div>

**giotto-tda: A Topological Data Analysis Toolkit for Machine Learning and Data Exploration** (Spotlight presentation)<br />
Guillaume Tauzin &bull; Umberto Lupo &bull; Lewis Tunstall &bull; Julian Burella Perez &bull; Matteo Caorsi &bull; Wojciech Reise &bull; Anibal Maximiliano Medina-Mardones &bull; Alberto Dassatti &bull; Kathryn Hess<br />
<abstract>We introduce giotto-tda, a Python library that integrates high-performance topological data analysis with machine learning via a scikit-learn-compatible API and state-of-the-art C++ implementations. The library's ability to handle various types of data is rooted in a wide range of preprocessing techniques, and its strong focus on data exploration and interpretability is aided by an intuitive plotting API. Source code, binaries, examples, and documentation can be found at https://github.com/giotto-ai/giotto-tda</abstract>

[PDF](https://openreview.net/pdf?id=fjQtZJOCTXf) &bull;
[Poster](https://openreview.net/attachment?id=fjQtZJOCTXf&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=fjQtZJOCTXf)

<div id="presentation-embed-38941576"></div>
<script src='https://slideslive.com/embed_presentation.js'></script>
<script>
    embed = new SlidesLiveEmbed('presentation-embed-38941576', {
        presentationId: '38941576',
        autoPlay: false, // change to true to autoplay the embedded presentation
        verticalEnabled: true
    });
</script>

<div style="text-align:center">
&#10086;
</div>

**Hypothesis classes with a unique persistence diagram are nonuniformly learnable** (Spotlight presentation)<br />
Nicholas Bishop &bull; Thomas Davies &bull; Long Tran-Thanh<br />
<abstract>Persistence-based summaries are increasingly integrated into deep learning through topological loss functions or regularisers. The implicit role of a topological term in a loss function is to restrict the class of functions in which we are learning (the hypothesis class) to those with a specific topology. Although doing so has had empirical success, to the best of our knowledge there exists no result in the literature that theoretically justifies this restriction. Given a binary classifier in the plane with a Morse-like decision boundary, we prove that the hypothesis class defined by restricting the topology of the possible decision boundaries to those with a unique persistence diagram results in a nonuniformly learnable class of functions. In doing so, we provide a statistical learning theoretic justification for the use of persistence-based summaries in loss functions.</abstract>

[PDF](https://openreview.net/pdf?id=Ay-RgChnje) &bull;
[Poster](https://openreview.net/attachment?id=Ay-RgChnje&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=Ay-RgChnje)

<div id="presentation-embed-38941574"></div>
<script src='https://slideslive.com/embed_presentation.js'></script>
<script>
    embed = new SlidesLiveEmbed('presentation-embed-38941574', {
        presentationId: '38941574',
        autoPlay: false, // change to true to autoplay the embedded presentation
        verticalEnabled: true
    });
</script>

<div style="text-align:center">
&#10086;
</div>

**Multidimensional Persistence Module Classification via Lattice-Theoretic Convolutions** (Spotlight presentation)<br />
Hans Matthew Riess &bull; Jakob Hansen<br />
<abstract>Multiparameter persistent homology has been largely neglected as an input to machine learning algorithms. We consider the use of lattice-based convolutional neural network layers as a tool for the analysis of features arising from multiparameter persistence  modules. We find that these show promise as an alternative to convolutions for the classification of multidimensional persistence modules.</abstract>

[PDF](https://openreview.net/pdf?id=CqFcRp-_mUD) &bull;
[Poster](https://openreview.net/attachment?id=CqFcRp-_mUD&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=CqFcRp-_mUD)

<div id="presentation-embed-38941581"></div>
<script src='https://slideslive.com/embed_presentation.js'></script>
<script>
    embed = new SlidesLiveEmbed('presentation-embed-38941581', {
        presentationId: '38941581',
        autoPlay: false, // change to true to autoplay the embedded presentation
        verticalEnabled: true
    });
</script>

<div style="text-align:center">
&#10086;
</div>

**Permutation invariant networks to learn Wasserstein metrics** (Spotlight presentation)<br />
Arijit Sehanobish &bull; Neal G Ravindra &bull; David van Dijk<br />
<abstract>Understanding the space of probability measures on a metric space equipped with a Wasserstein distance is one of the fundamental questions in mathematical analysis. The Wasserstein metric has received a lot of attention in the machine learning community especially for its principled way of comparing distributions. In this work, we use a permutation invariant network to map samples from probability measures into a low-dimensional space such that the Euclidean distance between the encoded samples reflects the Wasserstein distance between probability measures. We show that our network can generalize to correctly compute distances between unseen densities. We also show that these networks can learn the first and the second moments of probability distributions. </abstract>

[PDF](https://openreview.net/pdf?id=VFP81oXIxeh) &bull;
[Poster](https://openreview.net/attachment?id=VFP81oXIxeh&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=VFP81oXIxeh)

<div id="presentation-embed-38941580"></div>
<script src='https://slideslive.com/embed_presentation.js'></script>
<script>
    embed = new SlidesLiveEmbed('presentation-embed-38941580', {
        presentationId: '38941580',
        autoPlay: false, // change to true to autoplay the embedded presentation
        verticalEnabled: true
    });
</script>

<div style="text-align:center">
&#10086;
</div>

**Quantifying barley morphology using the Euler characteristic transform** (Spotlight presentation)<br />
Erik J Amezquita &bull; Michelle Quigley &bull; Tim Ophelders &bull; Jacob Landis &bull; Elizabeth Munch &bull; Daniel Chitwood &bull; Daniel Koenig<br />
<abstract>Shape is foundational to biology. Observing and documenting shape has fueled biological understanding, and from this perspective, it is also a type of data.  The vision of topological data analysis, that data is shape and shape is data, will be relevant as biology transitions into a data-driven era where meaningful interpretation of large data sets is a limiting factor. We focus first on quantifying the morphology of barley spikes and seeds using topological descriptors based on the Euler characteristic. We then successfully train a support vector machine to classify 28 different varieties of barley based solely on the shape of their grains.</abstract>

[PDF](https://openreview.net/pdf?id=cIRwkIETJBs) &bull;
[Poster](https://openreview.net/attachment?id=cIRwkIETJBs&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=cIRwkIETJBs)

<div id="presentation-embed-38941575"></div>
<script src='https://slideslive.com/embed_presentation.js'></script>
<script>
    embed = new SlidesLiveEmbed('presentation-embed-38941575', {
        presentationId: '38941575',
        autoPlay: false, // change to true to autoplay the embedded presentation
        verticalEnabled: true
    });
</script>

<div style="text-align:center">
&#10086;
</div>

**Sheaf Neural Networks** (Spotlight presentation)<br />
Jakob Hansen &bull; Thomas Gebhart<br />
<abstract>We present a generalization of graph convolutional networks by generalizing the diffusion operation underlying this class of graph neural networks. These \emph{sheaf neural networks} are based on the \emph{sheaf Laplacian}, a generalization of the graph Laplacian that encodes additional relational structure parameterized by the underlying graph. The sheaf Laplacian and associated matrices provide an extended version of the diffusion operation in graph convolutional networks, providing a proper generalization for domains where relations between nodes are non-constant, asymmetric, and varying in dimension. We show that the resulting sheaf neural networks can outperform graph convolutional networks in domains where relations between nodes are asymmetric and signed.</abstract>

[PDF](https://openreview.net/pdf?id=GgcgIJsT8HD) &bull;
[Poster](https://openreview.net/attachment?id=GgcgIJsT8HD&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=GgcgIJsT8HD)

<div id="presentation-embed-38941578"></div>
<script src='https://slideslive.com/embed_presentation.js'></script>
<script>
    embed = new SlidesLiveEmbed('presentation-embed-38941578', {
        presentationId: '38941578',
        autoPlay: false, // change to true to autoplay the embedded presentation
        verticalEnabled: true
    });
</script>

<div style="text-align:center">
&#10086;
</div>

**Topo Sampler: A Topology Constrained Noise Sampling for GANs** (Spotlight presentation)<br />
Adrish Dey &bull; Sayantan Das<br />
<abstract>This work studies disconnected manifold learning in generative models in the light of point-set topology and persistent homology. Under this formalism, the topological similarity of latent space in generative models with the underlying manifold of data distribution facilitates better generalization. To achieve this, we introduce a topology-constrained noise sampler, responsible for mapping the samples from Gaussian spheres to a latent embedding space, which in turn is constrained to be topologically similar to the manifold underlying the data distribution. We study the effectiveness of this method in GANs for learning disconnected manifolds. This is ongoing research, with the current report containing preliminary empirical experiments.</abstract>

[PDF](https://openreview.net/pdf?id=OTxZfmVFlTO) &bull;
[Poster](https://openreview.net/attachment?id=OTxZfmVFlTO&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=OTxZfmVFlTO)

<div id="presentation-embed-38941572"></div>
<script src='https://slideslive.com/embed_presentation.js'></script>
<script>
    embed = new SlidesLiveEmbed('presentation-embed-38941572', {
        presentationId: '38941572',
        autoPlay: false, // change to true to autoplay the embedded presentation
        verticalEnabled: true
    });
</script>

<div style="text-align:center">
&#10086;
</div>

**Weighting vectors for machine learning: numerical harmonic analysis applied to boundary detection** (Spotlight presentation)<br />
Eric Bunch &bull; Daniel Dickinson &bull; Jeffery Kline &bull; Glenn Fung<br />
<abstract>Metric space magnitude, an active subject of research in algebraic topology, aims to quantify the effective number of distinct points in a space. The contribution of each point to a metric space’s global magnitude, which is encoded by the {\em weighting vector}, captures much of the underlying geometry of the original metric space. When the metric space is Euclidean, the weighting vector also serves as an effective tool for boundary detection. This allows the weighting vector to serve as the foundation of novel algorithms for classic machine learning tasks such as classification, outlier detection and active learning.   We demonstrate, using experiments and comparisons on classic benchmark datasets, the promise of the proposed magnitude and weighting vector-based approaches.</abstract>

[PDF](https://openreview.net/pdf?id=AwBwKEzfaXG) &bull;
[Forum](https://openreview.net/forum?id=AwBwKEzfaXG)

<div id="presentation-embed-38941573"></div>
<script src='https://slideslive.com/embed_presentation.js'></script>
<script>
    embed = new SlidesLiveEmbed('presentation-embed-38941573', {
        presentationId: '38941573',
        autoPlay: false, // change to true to autoplay the embedded presentation
        verticalEnabled: true
    });
</script>

# Accepted Posters

**0-dimensional Homology Preserving Dimensionality Reduction with TopoMap** <br />
Harish Doraiswamy &bull; Julien Tierny &bull; Paulo J.S. Silva &bull; Luis Gustavo Nonato &bull; Cláudio Silva<br />
<abstract>This note presents TopoMap, a novel dimensionality reduction technique which provides topological guarantees during the mapping process. In particular, TopoMap performs the mapping from a high-dimensional space to a visual space, while preserving the 0-dimensional persistence diagram of the Rips filtration of the high-dimensional data, ensuring that the filtrations generate the same connected components when applied to the original as well as projected data. The presented case studies show that the topological guarantee provided by TopoMap not only brings confidence to the visual analytic process but also can be used to assist in the assessment of other projection methods.
</abstract>

[PDF](https://openreview.net/pdf?id=zrDNDWjOGwH) &bull;
[Poster](https://openreview.net/attachment?id=zrDNDWjOGwH&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=zrDNDWjOGwH)

<div style="text-align:center">
&#10086;
</div>

**Application of Topological Data Analysis to Delirium Detection** <br />
Mari Kajitani &bull; Ken Kobayashi &bull; Yuichi Ike &bull; Takehiko Yamanashi &bull; Yuhei Umeda &bull; Yoshimasa Kadooka &bull; Gen Shinozaki<br />
<abstract>We propose a new scoring algorithm for detecting delirium from one-channel EEG, based on topological data analysis.  Numerical experiments demonstrated that our method achieved high predictive performance than the other existing methods. </abstract>

[PDF](https://openreview.net/pdf?id=szTsSnY3EaT) &bull;
[Poster](https://openreview.net/attachment?id=szTsSnY3EaT&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=szTsSnY3EaT)

<div style="text-align:center">
&#10086;
</div>

**Bifurcation Analysis using Zigzag Persistence** <br />
Sarah Tymochko &bull; Elizabeth Munch &bull; Firas Khasawneh<br />
<abstract>As bifurcations in a dynamical system are drastic behavioral changes, being able to detect when these bifurcations occur can be essential to understanding the system overall. While persistent homology has successfully been used in the field of dynamical systems, the most commonly used approaches have their limitations. Using zigzag persistence, we can simplify the methodology and capture topological changes through a collection of time series, rather that studying the topology of individual time series separately. Here we present Bifurcations using ZigZag (BuZZ), a method to detect Hopf bifurcations in dynamical systems.</abstract>

[PDF](https://openreview.net/pdf?id=QjlNs8ymHNc) &bull;
[Poster](https://openreview.net/attachment?id=QjlNs8ymHNc&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=QjlNs8ymHNc)

<div style="text-align:center">
&#10086;
</div>

**Can neural networks learn persistent homology features?** <br />
Guido Montufar &bull; Nina Otter &bull; Yu Guang Wang<br />
<abstract>Topological data analysis uses tools from topology — the mathematical area that studies shapes — to create representations of data. In particular, in persistent homology, one studies one-parameter families of spaces associated with data, and persistence diagrams describe the lifetime of topological invariants, such as connected components or holes, across the one-parameter family. In many applications, one is interested in working with features associated with persistence diagrams rather than the diagrams themselves. In our work, we explore the possibility of learning several types of features extracted from persistence diagrams using neural networks.</abstract>

[PDF](https://openreview.net/pdf?id=pqpXM1Wjsxe) &bull;
[Poster](https://openreview.net/attachment?id=pqpXM1Wjsxe&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=pqpXM1Wjsxe)

<div style="text-align:center">
&#10086;
</div>

**Cell Complex Neural Networks** <br />
Mustafa Hajij &bull; Kyle Istvan &bull; Ghada Zamzmi<br />
<abstract>Cell complexes are topological spaces constructed from simple blocks called cells. They generalize graphs, simplicial complexes, and polyhedral complexes that form important domains for practical applications. They also provide a combinatorial formalism that allows the inclusion of complicated relationships of restrictive structures such as graphs and meshes. In this paper, we propose \textbf{cell complexes neural networks (CXNs)} a general, combinatorial, and unifying construction for performing neural network-type computations on cell complexes. We introduce an inter-cellular message passing scheme on cell complexes that takes the topology of the underlying space into account and generalizes message passing scheme to graphs. Finally, we introduce a unified cell complex encoder-decoder framework that enables learning representation of cells for a given complex inside the Euclidean spaces.  In particular, we show how our cell complex autoencoder construction can give in the special case \textbf{cell2vec}, a generalization for node2vec.</abstract>

[PDF](https://openreview.net/pdf?id=6Tq18ySFpGU) &bull;
[Poster](https://openreview.net/attachment?id=6Tq18ySFpGU&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=6Tq18ySFpGU)

<div style="text-align:center">
&#10086;
</div>

**Challenging Euclidean Topological Autoencoders** <br />
Michael Moor &bull; Max Horn &bull; Karsten Borgwardt &bull; Bastian Rieck<br />
<abstract> Topological autoencoders (TopoAE) have demonstrated their capabilities for performing dimensionality reduction while at the same time preserving topological information of the input space. In its original formulation, this method relies on a Vietoris--Rips filtration of the data space, using the Euclidean metric as the base distance. It is commonly assumed that this distance is not sufficiently powerful to capture salient features of image data sets. We therefore investigate alternative choices of distances in the data space, which are generally considered to be more faithful for image data in comparison to the pixel distance. In our experiments on real-world image datasets, we find that the Euclidean formulation of TopoAE is surprisingly competitive with more elaborate, perceptually-inspired image distances.</abstract>

[PDF](https://openreview.net/pdf?id=P3dZuOUnyEY) &bull;
[Poster](https://openreview.net/attachment?id=P3dZuOUnyEY&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=P3dZuOUnyEY)

<div style="text-align:center">
&#10086;
</div>

**Comparing Distance Metrics on Vectorized Persistence Summaries** <br />
Brittany Fasy &bull; Yu Qin &bull; Brian Summa &bull; Carola Wenk<br />
<abstract>The persistence diagram (PD) is an important tool in topological data analysis for encoding an abstract representation of the homology of a shape at different scales. Different vectorizations of PD summary are commonly used in machine learning applications, however distances between vectorized persistence summaries may differ greatly from the distances between the original PDs. Surprisingly, no research has been carried out in this area before. In this work we compare distances between PDs and between different commonly used vectorizations. Our results give new insights into comparing vectorized persistence summaries and can be used to design better feature-based learning models based on PDs.</abstract>

[PDF](https://openreview.net/pdf?id=X1bxKJo5_qL) &bull;
[Poster](https://openreview.net/attachment?id=X1bxKJo5_qL&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=X1bxKJo5_qL)

<div style="text-align:center">
&#10086;
</div>

**Deep Graph Mapper: Seeing Graphs Through the Neural Lens** <br />
Cristian Bodnar &bull; Cătălina Cangea &bull; Pietro Liò<br />
<abstract>Graph summarisation has received much attention lately, with various works tackling the challenge of defining pooling operators on data regions with arbitrary structures. These contrast the grid-like ones encountered in image inputs, where techniques such as max-pooling have been enough to show empirical success. In this work, we merge the Mapper algorithm with the expressive power of graph neural networks to produce topologically-grounded graph summaries. We demonstrate the suitability of Mapper as a topological framework for graph pooling by proving that Mapper is a generalisation of pooling methods based on soft cluster assignments. Building upon this, we show how easy it is to design novel pooling algorithms that obtain competitive results with other state-of-the-art methods.</abstract>

[PDF](https://openreview.net/pdf?id=IYX38fl5sTh) &bull;
[Poster](https://openreview.net/attachment?id=IYX38fl5sTh&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=IYX38fl5sTh)

<div style="text-align:center">
&#10086;
</div>

**Functorial Clustering via Simplicial Complexes** <br />
Dan Shiebler<br />
<abstract>We adapt previous research on topological unsupervised learning to characterize hierarchical overlapping clustering algorithms as functors that factor through a category of simplicial complexes. We first develop a pair of adjoint functors that map between simplicial complexes and the outputs of clustering algorithms. Next, we introduce the maximal and single linkage clustering algorithms as the respective composition of the flagification and connected components functors with McInnes et al's finite singular set functor. We then adapt a theorem by Culbertson et al to demonstrate that all other hierarchical overlapping clustering functors are refined by maximal linkage and refine single linkage.</abstract>

[PDF](https://openreview.net/pdf?id=ZkDLcXCP5sV) &bull;
[Poster](https://openreview.net/attachment?id=ZkDLcXCP5sV&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=ZkDLcXCP5sV)

<div style="text-align:center">
&#10086;
</div>

**Fuzzy c-Means Clustering for Persistence Diagrams** <br />
Thomas Davies &bull; Jack Aspinall &bull; Bryan Wilder &bull; Long Tran-Thanh<br />
<abstract>Persistence diagrams concisely represent the topology of a point cloud whilst having strong theoretical guarantees. Most current approaches to integrating topological information into machine learning implicitly map persistence diagrams to a Hilbert space, resulting in deformation of the underlying metric structure whilst also generally requiring prior knowledge about the true topology of the space. In this paper we give an algorithm for Fuzzy c-Means (FCM) clustering directly on the space of persistence diagrams, enabling unsupervised learning that automatically captures the topological structure of data, with no prior knowledge or additional processing of persistence diagrams. We prove the same convergence guarantees as traditional FCM clustering: every convergent subsequence of iterates tends to a local minimum or saddle point. We end by presenting experiments where the fuzzy nature of our topological clustering is capitalised on: lattice structure classification in materials science and pre-trained model selection in machine learning.</abstract>

[PDF](https://openreview.net/pdf?id=I49l3mLYXl6) &bull;
[Poster](https://openreview.net/attachment?id=I49l3mLYXl6&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=I49l3mLYXl6)

<div style="text-align:center">
&#10086;
</div>

**Hotspot identification for Mapper graphs** <br />
Ciara Frances Loughrey &bull; Anna Jurek-Loughrey &bull; Nick Orr &bull; Pawel Dlotko<br />
<abstract>Mapper algorithm can be used to build graph-based representations of high-dimensional data capturing structurally interesting features such as loops, flares or clusters. The graph can be further annotated with additional colouring of vertices allowing location of regions of special interest. For instance, in many applications, such as precision medicine, Mapper graph has been used to identify unknown compactly localized subareas within the dataset demonstrating unique or unusual behaviours. This task, performed so far by a researcher, can be automatized using hotspot analysis. In this work we propose a new algorithm for detecting hotspots in Mapper graphs. It allows automatizing of the hotspot detection process. We demonstrate the performance of the algorithm on a number of artificial and real world datasets. We further demonstrate how our algorithm can be used for the automatic selection of the Mapper lens functions. </abstract>

[PDF](https://openreview.net/pdf?id=reLv5jl2adC) &bull;
[Poster](https://openreview.net/attachment?id=reLv5jl2adC&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=reLv5jl2adC)

<div style="text-align:center">
&#10086;
</div>

**Interpretable Phase Detection and Classification with Persistent Homology** <br />
Gregory Loges &bull; Alex Cole &bull; Gary Shiu<br />
<abstract>We apply persistent homology to the task of discovering and characterizing phase transitions, using lattice spin models from statistical physics for working examples. Persistence images provide a useful representation of the homological data for conducting statistical tasks. To identify the phase transitions, a simple logistic regression on these images is sufficient for the models we consider, and interpretable order parameters are then read from the weights of the regression. Magnetization, frustration and vortex-antivortex structure are identified as relevant features for characterizing phase transitions.</abstract>

[PDF](https://openreview.net/pdf?id=Ls8WYFSRxDq) &bull;
[Poster](https://openreview.net/attachment?id=Ls8WYFSRxDq&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=Ls8WYFSRxDq)

<div style="text-align:center">
&#10086;
</div>

**Learning a manifold from a teacher’s demonstrations** <br />
PEI WANG &bull; Arash Givchi &bull; Patrick Shafto<br />
<abstract>We consider the problem of learning a manifold from a teacher's demonstration. Extending existing approaches of learning from randomly sampled data points, we consider contexts where data may be chosen by a teacher. 
 We analyze learning from teachers who can provide structured data such as individual examples (isolated data points) and demonstrations (sequences of points). Our analysis shows that for the purpose of teaching the topology of a manifold, demonstrations can yield remarkable decreases in the amount of data points required in comparison to teaching with randomly sampled points.</abstract>

[PDF](https://openreview.net/pdf?id=jj-x_DG5G84) &bull;
[Poster](https://openreview.net/attachment?id=jj-x_DG5G84&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=jj-x_DG5G84)

<div style="text-align:center">
&#10086;
</div>

**LUMAWIG: Un-bottling the bottleneck distance for zero dimensional persistence diagrams at scale** <br />
Paul Samuel Ignacio &bull; Jay-Anne Bulauan &bull; David Uminsky<br />
<abstract>We present LUMÁWIG, a novel efficient algorithm to compute dimension zero bottleneck distance between two persistence diagrams of a specific kind which outperforms all other publicly available algorithm in runtime and accuracy.  We bypass the overwhelming matching problem in previous implementations of the bottleneck distance, and prove that the zero dimensional bottleneck distance can be recovered from a very small number of matching cases. LUMÁWIG also generally enjoys linear complexity as shown by empirical tests.  This allows us to scaleTDA to data sets of sizes encountered in machine learning and utilize persistence diagrams in a manner that goes beyond the simple use of the most persistent components.</abstract>

[PDF](https://openreview.net/pdf?id=E4k5yX1GH63) &bull;
[Poster](https://openreview.net/attachment?id=E4k5yX1GH63&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=E4k5yX1GH63)

<div style="text-align:center">
&#10086;
</div>

**Multi-parameter hierarchical clustering and beyond** <br />
Alexander Rolle<br />
<abstract>We survey recent progress on multi-parameter hierarchical clustering, which has developed in several directions since it was introduced by Carlsson--M\'{e}moli in 2010. These lines of research show that tools originally developed in the setting of multi-parameter persistent homology can be applied more broadly, without linearizing via homology.</abstract>

[PDF](https://openreview.net/pdf?id=g0-tBxQTPRy) &bull;
[Poster](https://openreview.net/attachment?id=g0-tBxQTPRy&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=g0-tBxQTPRy)

<div style="text-align:center">
&#10086;
</div>

**Multi-Parameter Persistent Homology is Practical (Extended Abstract)** <br />
Michael Kerber<br />
<abstract>Multi-parameter persistent homology is a branch of topological data analysis that is notorious for being more difficult than the standard (one-parameter) version, both in theory and for algorithmic problems. We report on three ongoing projects that demonstrates that multi-parameter method are applicable to large data sets. For instance, natural bi-filtrations generalizing Vietoris-Rips or alpha filtrations for hundred of thousands of points can be decomposed within seconds in their indecomposable parts.</abstract>

[PDF](https://openreview.net/pdf?id=TDU6UycGYxR) &bull;
[Poster](https://openreview.net/attachment?id=TDU6UycGYxR&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=TDU6UycGYxR)

<div style="text-align:center">
&#10086;
</div>

**Multiple Hypothesis Testing with Persistent Homology** <br />
Mikael Vejdemo-Johansson &bull; Sayan Mukherjee<br />
<abstract>Multiple hypothesis testing requires a control procedure.
Simply increasing simulations or permutations to meet a Bonferroni-style threshold is prohibitively expensive.
In this paper we propose a null model based approach to testing for acyclicity, coupled with a Family-Wise Error Rate (FWER) control method that does not suffer from these computational costs.
</abstract>

[PDF](https://openreview.net/pdf?id=rHaiOtGdRS) &bull;
[Poster](https://openreview.net/attachment?id=rHaiOtGdRS&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=rHaiOtGdRS)

<div style="text-align:center">
&#10086;
</div>

**Novel Topological Shapes of Model Interpretability** <br />
Hendrik Jacob van Veen<br />
<abstract>The most accurate models can be the most challenging to interpret. This paper advances interpretability analysis by combining insights from $\texttt{Mapper}$ with recent interpretable machine-learning research. Enforcing new visualization constraints on $\texttt{Mapper}$, we produce a globally - to locally interpretable visualization of the Explainable Boosting Machine. We demonstrate the usefulness of our approach to three data sets: cervical cancer risk, propaganda Tweets, and a loan default data set that was artificially hardened with severe concept drift.</abstract>

[PDF](https://openreview.net/pdf?id=G-kWQ9WvBMq) &bull;
[Poster](https://openreview.net/attachment?id=G-kWQ9WvBMq&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=G-kWQ9WvBMq)

<div style="text-align:center">
&#10086;
</div>

**On The Topological Expressive Power of Neural Networks** <br />
Giovanni Petri &bull; António Leitão<br />
<abstract>We propose a topological description of neural network expressive power. 
We adopt the topology of the space of decision boundaries realized by a neural architecture as a measure of its intrinsic expressive power. 
By sampling a large number of neural architectures with different sizes and design, we show how such measure of expressive power depends on the properties of the architectures, like depth, width and other related quantities. </abstract>

[PDF](https://openreview.net/pdf?id=I44kJPuvqPD) &bull;
[Poster](https://openreview.net/attachment?id=I44kJPuvqPD&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=I44kJPuvqPD)

<div style="text-align:center">
&#10086;
</div>

**Passive Encrypted IoT Device Fingerprinting with Persistent Homology** <br />
Joe Collins &bull; Michaela Iorga &bull; Dmitry Cousin &bull; David Chapman<br />
<abstract>Internet of things (IoT) devices are becoming increasingly prevalent. These devices can improve quality of life,  but often present significant security risks to end users. In this work we present a novel persistent homology based method for the fingerprinting of IoT traffic.  Traditional passive device fingerprinting methods directly inspect the packet attributes or contents within the captured traffic. Buttechniques to fingerprint devices based on inter-packet arrival time (IAT) are an important area of research, as this feature is available even in encrypted traffic.We demonstrate that Topological Data Analysis (TDA) using persistent homology over IAT packet windows is a viable approach to obtain discriminative features for device fingerprinting. The clique complex construction and weighting function we present are efficient to compute and robust to shifts of the packet window. The1-dimensional homology is calculated over the resulting filtered clique complex.We obtain competitive accuracy of 95.34% on the UNSW IoT dataset by using a convolutional neural network to classify over the corresponding persistence images.</abstract>

[PDF](https://openreview.net/pdf?id=BXGqPm6nKgP) &bull;
[Poster](https://openreview.net/attachment?id=BXGqPm6nKgP&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=BXGqPm6nKgP)

<div style="text-align:center">
&#10086;
</div>

**Regularization of Persistent Homology Gradient Computation** <br />
Padraig Corcoran &bull; Bailin Deng<br />
<abstract>Persistent homology is a method for computing the topological features present in a given data. Recently, there has been much interest in the integration of persistent homology as a computational step in neural networks or deep learning. In order for a given computation to be integrated in such a way, the computation in question must be differentiable. Computing the gradients of persistent homology is an ill-posed inverse problem with infinitely many solutions. Consequently, it is important to perform regularization so that the solution obtained agrees with known priors. In this work we propose a novel method for regularizing persistent homology gradient computation through the addition of a grouping term. This has the effect of helping to ensure gradients are defined with respect to larger entities and not individual points.</abstract>

[PDF](https://openreview.net/pdf?id=MOpuZ5GtoAJ) &bull;
[Poster](https://openreview.net/attachment?id=MOpuZ5GtoAJ&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=MOpuZ5GtoAJ)

<div style="text-align:center">
&#10086;
</div>

**Research Directions to Validate Topological Models of Multi-Dimensional Data** <br />
Nello Blaser &bull; Michael Aupetit<br />
<abstract>Various topological models of multi-dimensional data have been proposed for different applications. One of the main issues is to evaluate how correct these models are given the stochastic nature of the data source typical of exploratory data analysis and machine learning settings. We propose research directions to validate the quality of the Mapper and the Generative Simplicial Complex, two models that compute simplicial complexes from multi-dimensional data.</abstract>

[PDF](https://openreview.net/references/pdf?id=XDCElDa9Qn) &bull;
[Poster](https://openreview.net/attachment?id=3iVbgfPMZtU&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=3iVbgfPMZtU)

<div style="text-align:center">
&#10086;
</div>

**Simplicial 2-Complex Convolutional Neural Networks** <br />
Eric Bunch &bull; Qian You &bull; Glenn Fung &bull; Vikas Singh<br />
<abstract>Recently, neural network architectures have been developed to accommodate when the data has the structure of a graph or, more generally, a hypergraph. While useful, graph structures can be potentially limiting. Hypergraph structures in general do not account for higher order relations between their hyperedges. Simplicial complexes offer a middle ground, with a rich theory to draw on. We develop a convolutional neural network layer on simplicial 2-complexes.</abstract>

[PDF](https://openreview.net/pdf?id=TLbnsKrt6J-) &bull;
[Poster](https://openreview.net/attachment?id=TLbnsKrt6J-&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=TLbnsKrt6J-)

<div style="text-align:center">
&#10086;
</div>

**Simplicial Neural Networks** <br />
Stefania Ebli &bull; Michaël Defferrard &bull; Gard Spreemann<br />
<abstract>We present simplicial neural networks (SNNs), a generalization of graph neural networks to data that live on a class of topological spaces called simplicial complexes. These are natural multi-dimensional extensions of graphs that encode not only pairwise relationships but also higher-order interactions between vertices—allowing us to consider richer data, including vector fields and $n$-fold collaboration networks. We define an appropriate notion of convolution that we leverage to construct the desired convolutional neural networks. We test the SNNs on the task of imputing missing data on coauthorship complexes. Code and data are available at https://github.com/stefaniaebli/simplicial_neural_networks.</abstract>

[PDF](https://openreview.net/pdf?id=nPCt39DVIfk) &bull;
[Poster](https://openreview.net/attachment?id=nPCt39DVIfk&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=nPCt39DVIfk)

<div style="text-align:center">
&#10086;
</div>

**Teaspoon: A comprehensive python package for topological signal processing** <br />
Audun D Myers &bull; Melih Yesilli &bull; Sarah Tymochko &bull; Firas Khasawneh &bull; Elizabeth Munch<br />
<abstract>The emerging field of  topological signal processing brings methods from Topological Data Analysis (TDA) to create new tools for signal processing by incorporating aspects of shape. In this paper, we present an overview of the python package teaspoon, which brings together available software for computing persistent homology, the main workhorse of TDA, with modules that expand the functionality of teaspoon as a state-of-the-art topological signal processing tool. These modules include methods for incorporating tools from machine learning, complex networks,  information, and parameter selection along with a dynamical systems library to streamline the creation and benchmarking of new methods. All code is open source with up to date documentation, making the code easy to use, in particular for signal processing experts with limited experience in topological methods.</abstract>

[PDF](https://openreview.net/pdf?id=qUoVqrIcy2P) &bull;
[Poster](https://openreview.net/attachment?id=qUoVqrIcy2P&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=qUoVqrIcy2P)

<div style="text-align:center">
&#10086;
</div>

**Topological Convolutional Neural Networks** <br />
Ephy Love &bull; Benjamin Filippenko &bull; Vasileios Maroulas &bull; Gunnar E. Carlsson<br />
<abstract>There is considerable interest in making convolutional neural networks (CNNs) that learn on less data, are better at generalizing, and are more easily interpreted. This work introduces the Topological CNN (TCNN), which encompasses several topologically defined convolutional methods. Manifolds with important relationships to the natural image space are used to parameterize image filters which are used as convolutional weights in a TCNN. These manifolds also parameterize slices in layers of a TCNN across which the weights are localized. We show evidence that TCNNs learn faster, on less data, with fewer learned parameters, and with greater generalizability and interpretability than conventional CNNs.</abstract>

[PDF](https://openreview.net/pdf?id=hntbh8Zo1V) &bull;
[Poster](https://openreview.net/attachment?id=hntbh8Zo1V&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=hntbh8Zo1V)

<div style="text-align:center">
&#10086;
</div>

**Topological Echoes of Primordial Physics in the Universe at Large Scales** <br />
Alex Cole &bull; Matteo Biagetti &bull; Gary Shiu<br />
<abstract>We present a pipeline for characterizing and constraining initial conditions in cosmology via persistent homology. The cosmological observable of interest is the cosmic web of large scale structure, and the initial conditions in question are non-Gaussianities (NG) of primordial density perturbations. We compute persistence diagrams and derived statistics for simulations of dark matter halos with Gaussian and non-Gaussian initial conditions. For computational reasons and to make contact with experimental observations, our pipeline computes persistence in sub-boxes of full simulations and simulations are subsampled to uniform halo number. We use simulations with large NG ($f_{\rm NL}^{\rm loc}=250$) as templates for identifying data with mild NG ($f_{\rm NL}^{\rm loc}=10$), and running the pipeline on several cubic volumes of size $40~(\textrm{Gpc/h})^{3}$, we detect $f_{\rm NL}^{\rm loc}=10$ at $97.5\%$ confidence on $\sim 85\%$ of the volumes for our best single statistic. Throughout we benefit from the interpretability of topological features as input for statistical inference, which allows us to make contact with previous first-principles calculations and make new predictions.</abstract>

[PDF](https://openreview.net/pdf?id=Uuga2BsQ2CR) &bull;
[Poster](https://openreview.net/attachment?id=Uuga2BsQ2CR&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=Uuga2BsQ2CR)

<div style="text-align:center">
&#10086;
</div>

**TOTOPO: Classifying univariate and multivariate time series with Topological Data Analysis** <br />
Pilyugina Polina &bull; Rodrigo Rivera-Castro &bull; Evgeny Burnaev<br />
<abstract>This work is devoted to a comprehensive analysis of topological data analysis for time series classification. Previous works have significant shortcomings, such as lack of large-scale benchmarking or missing state-of-the-art methods. In this work, we propose TOTOPO for extracting topological descriptors from different types of persistence diagrams. The results suggest that TOTOPO significantly outperforms existing baselines in terms of accuracy. TOTOPO is also competitive with the state-of-the-art, being the best on 20\% of univariate and 40\% of multivariate time series datasets. This work validates the hypothesis that TDA-based approaches are robust to small perturbations in data and are useful for cases where periodicity and shape help discriminate between classes.</abstract>

[PDF](https://openreview.net/pdf?id=Rl8UZsKEhwF) &bull;
[Poster](https://openreview.net/attachment?id=Rl8UZsKEhwF&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=Rl8UZsKEhwF)

<div style="text-align:center">
&#10086;
</div>

**Using topological autoencoders as a filtering function for global and local topology** <br />
Filip Cornell<br />
<abstract>Choosing a suitable filtering function for the Mapper algorithm can be difficult due to its arbitrariness and domain-specific requirements. Finding a general filtering function that can be applied across domains is therefore of interest, since it would improve the representation of manifolds in higher dimensions. In this extended abstract, we propose that topological autoencoders is a suitable candidate for this and report initial results strengthening this hypothesis for one set of high-dimensional manifolds. The results indicate a potential for an easier choice of filtering function when using the Mapper algorithm, allowing for a more general and descriptive representation of high-dimensional data. </abstract>

[PDF](https://openreview.net/pdf?id=0V6WLosuIfJ) &bull;
[Poster](https://openreview.net/attachment?id=0V6WLosuIfJ&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=0V6WLosuIfJ)

<div style="text-align:center">
&#10086;
</div>

**Witness Autoencoder: Shaping the Latent Space with Witness Complexes** <br />
Simon Till Schönenberger &bull; Anastasiia Varava &bull; Vladislav Polianskii &bull; Jen Jen Chung &bull; Danica Kragic &bull; Roland Siegwart<br />
<abstract>We present a Witness Autoencoder (W-AE) – an autoencoder that captures geodesic distances of the data in the latent space. Our algorithm uses witness complexes to compute geodesic distance approximations on a mini-batch level, and leverages topological information from the entire dataset while performing batch-wise approximations. This way, our method allows to capture the global structure of the data even with a small batch size, which is beneficial for large-scale real-world data. We show that our method captures the structure of the manifold more accurately than the recently introduced topological autoencoder (TopoAE).</abstract>

[PDF](https://openreview.net/pdf?id=1gQfXt_U5a-) &bull;
[Poster](https://openreview.net/attachment?id=1gQfXt_U5a-&name=Poster) &bull;
[Forum](https://openreview.net/forum?id=1gQfXt_U5a-)

<div style="text-align:center">
&#10086;
</div>

