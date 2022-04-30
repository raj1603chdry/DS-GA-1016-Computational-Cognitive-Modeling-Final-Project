# DS-GA-1016-Computational-Cognitive-Modeling-Final-Project

Group project for DS-GA 1016 - Computational Cognitive Modeling (taught by Prof.
Brenden Lake, [course website](https://brendenlake.github.io/CCM-site/) -
NYU Spring 2022)

## Group Members

* Alind Jain (aj2815)
* Raj Choudhary (rc4482)
* Tharangini Sankarnarayanan (ts4180)

## Topic: Neural Networks: Visual Representations

*Selected from [Course webpage](https://brendenlake.github.io/CCM-site/final_project_ideas.html)'s project section*

> **Comparing human and convolutional network representations for images**: With a visual domain of your choice (objects, animals, cars, etc.), use the Peterson et al. (2016) study design to compare the image similarity ratings between people and a pre-trained deep convolutional neural network trained on image recognition (as you did in Homework 1 Part D). Or, using a visual domain of your choice, use the Lake et al. (2015) study design compare typicality ratings between people and a pre-trained deep convolutional neural network trained on image recognition.

## Approved Proposal

> The Convolutional Neural Network was a breakthrough in Artificial Intelligence (CNN). CNN cut the error rate in the ImageNetChallenge, a benchmark for Visual Representation, in half in 2012. It signaled the start of the Deep Learning craze. CNN's have since revolutionized the field of Computer Vision and are now the industry standard for Object Recognition and Categorization. Categorization is an intriguing problem in cognitive psychology, and CNNs are the most widely used models to represent human brain categorization. Lake et al. [1] investigated how CNNs could predict category typicality ratings in a seminal paper, 'Deep Neural Networks Predict Category Typically Ratings,' and contributed to our understanding of categorization psychology. In 2017, Professor Hilton, one of Deep Learning's founding fathers, identified a major flaw in CNNs. CNNs, while detecting features in an image, do not
account for the spatial locality of the features. For example, operations like max-pooling which acts as an intermediate layer in most CNN architectures, lose spatial locality information. As a result, CNNs are prone to errors such as misclassifying a morphed facial image as a person. Furthermore, CNN has difficulty correctly classifying upside-down images. Humans, on the other hand, do not have such issues. As a result, CNN cannot be the pinnacle of representing categorization psychology. Interestingly, Prof. Hilton also proposed Capsule Networks, a radical new approach to Object Recognition [2]. Transformers were initially intended to perform text-based tasks. [3] proposes a vision model (Vision Transformer-ViT) that is as close to the Transformer architecture as possible. ViT represents an input image as a sequence of image patches, like how word embeddings are represented when using Transformers on the text and predicts class labels for the image directly. ViTs demonstrate excellent performance when trained on sufficient data, outperforming a comparable state-of-the-art CNN [3]. This project builds on the work of Lake et al. by evaluating the ability of models to predict category typicality with a performance analysis of GoogleNet, AlexNet, VGG, Capsule Networks, and Visual Transformers.

## Dataset sources

> **To Be Updated**

## Code Dependencies

> **To Be Updated**

## References

[1] Lake, B. M., Zaremba, W., Fergus, R. and Gureckis, T. M. Deep Neural Networks Predict Category Typicality Ratings for Images. In Proceedings of the 37th Annual Conference of the Cognitive Science Society, 2015.

[2] Sabour, S., Frosst, N., and Hinton, G. E. Dynamic Routing Between Capsules. arXiv:1710.09829, 2017.

[3] Dosovitskiy, A., Beyer, L., Kolesnikov, A., Weissenborn, D., Zhai, X., Unterthiner, T., ... & Houlsby, N. (2020). An image is worth 16x16 words: Transformers for image recognition at scale. arXiv preprint arXiv:2010.11929.

## General Guidelines (TBC)

* Do not commit to `main` branch directly. Use custom branches and make pull-requests.
* Each branch name should include its author's name, e.g., `raj-similarity-analysis`.
* After creating a PR, assign all other contributors to approve the PR. Only
merge the PR when it is approved by everyone.
* Only PR comment author may mark the comment as `Resolved`.
* Do not use `git push -f` / `git push --force`.
* `README.md` files for each folder will be updated when the project is
completed.
* All `*.py` and `*.ipynb` files should have the name and email of the author
indicated at the beginning of the file.
* Stick to the general PEP-8 coding style.
* **PLEASE** add comments and document your code.
* Update `.gitignore` with anything that is too large or doesn't need to be
in the Github repo.
* By default, except `README.md` from data, nothing would be pushed to Github. 
If something needs to be on Github, add exception in `.gitignore`.
