# awesome-dp
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of resources dedicated to Differential Privacy

## Contents

* [Books](#books)
* [Courses](#courses)
* [Blogs](#blogs)
* [Libraries](#libraries)
* [Papers](#papers)

## Books
* [The Algorithmic Foundations of Differential Privacy](https://www.cis.upenn.edu/~aaroth/Papers/privacybook.pdf) - Book from creators of Differential Privacy, Cynthia Dwork and Aaron Roth. Wouldn't recommend as an introductory resource.
* [Programming Differential Privacy](https://programming-dp.com/) - Book by Joseph P. Near  and  Chiké Abuah. Created for a course at University of Vermont. Full of examples and Python code.
* [Differential Privacy: A Primer for a Non-Technical Audience](https://salil.seas.harvard.edu/files/salil/files/differential_privacy_primer_nontechnical_audience.pdf) - Book by Wood et al. (including Kobbi Nissim), also analyzes legal aspects.
## Courses
* [CS 860 - Algorithms for Private Data Analysis](http://www.gautamkamath.com/CS860-fa2020.html) - Course taught by Gautam Kamath at University of Waterloo. Course has lecture videos (as a [YouTube playlist](https://www.youtube.com/playlist?list=PLmd_zeMNzSvRRNpoEWkVo6QY_6rR3SHjp)), lecture notes and additional reading. More theoretical, but an **excellent introductory** course to Differential Privacy.
* [CS211: Data Privacy](https://jnear.github.io/cs211-data-privacy/) - Course taught by Joe Near and Protiva Sen at University of Vermont. Exclusively lecture slides (no videos), homework and weekly assignments via Jupyter Notebooks. 
* [Privacy Preserving Machine Learning](http://researchers.lille.inria.fr/abellet/teaching/private_machine_learning_course.html) - Course taught by Aurélien Bellet at University of Lille. Exclusively lecture slides (no videos), practical sessions in Jupyter Notebooks. Definitely more of an advanced course.

## Blogs
* [Damien Desfontaines' Personal Blog](https://desfontain.es/privacy/friendly-intro-to-differential-privacy.html) - His personal curated list of blogs which serve as a friendly introduction to differential privacy.
* [differentialprivacy.org](https://differentialprivacy.org/) - Resource for the differential privacy research community and all of those who want to learn more about it. Also has a mailing list.
* [gretel.ai Blog](https://gretel.ai/blog) - [Gretel.ai]()'s blog about privacy in machine learning, differential privacy and data sharing. More focused on creating sythetic data.
* [OpenMined Blog](https://blog.openmined.org/tag/differential-privacy/) - All OpenMined blogs on differential privacy topic.
* [PyTorch Blog](https://pytorch.medium.com/) - Differential Privacy Series currently consisting of [two](https://medium.com/pytorch/differential-privacy-series-part-1-dp-sgd-algorithm-explained-12512c3959a3) [parts](https://medium.com/pytorch/differential-privacy-series-part-2-efficient-per-sample-gradient-computation-in-opacus-5bf4031d9e22) explaining concepts like differential privacy, DP-SGD and their inner-workings in Opacus.

## Libraries
* [opacus](https://github.com/pytorch/opacus) - PyTorch based library for Differential Privacy. You can read the whitepaper [here](https://arxiv.org/abs/2109.12298).
* [tensorflow-privacy](https://github.com/tensorflow/privacy) - TensorFlow library for Differential Privacy.
* [PyDP](https://github.com/OpenMined/PyDP) - OpenMined's Python wrapper library of Google's differential privacy library.
* [PrivacyRaven](https://github.com/trailofbits/PrivacyRaven) - Privacy testing Python library for deep learning systems.

## Papers
* [Deep Learning with Differential Privacy](https://arxiv.org/abs/1607.00133) - Paper that introduced Differentially Private SGD optimizator that enabled private deep learning.
* [Learning Differentially Private Recurrent Language Models](https://arxiv.org/abs/1710.06963) - Paper that introduced training of large recurrent language models with user-level differential privacy guarantees with only a negligible cost in predictive accuracy.
* [Privacy Regularization: Joint Privacy-Utility Optimization in Language Models](https://cseweb.ucsd.edu//~fmireshg/naacl_2021_private_text_gen.pdf) - Paper that introduced privacy regularization of LMs in order to try to preserve model utility and uniform treatment of under-represented subgroups.
* [Removing Disparate Impact of DP-SGD on Model Accuracy](https://arxiv.org/abs/2003.03699) - Paper that introduced changes of regular DP-SGD optimizator in order to make it fair. You can view my paper summary (presentation) here.
