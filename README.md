# FedPartial: Privacy Preserving Collaborative Learning across Heterogeneous Clients

### Abstract

As healthcare applications involve the use of highly personal data, there has been a growing need for the development of privacy preserving techniques for applications involving large scale analytic and machine learning. Federated Learning has emerged out as one of the best techniques to enable the same. However, in some applications like healthcare, the data present at the clients (Hospitals) generally follow a heterogeneous structure because of heterogeneity among the data collection devices involved. Current approaches for federated learning require the clients to process/transform their data into a homogeneous manner across all clients. This creates an intrinsic requirement for data processing during inference at client side, which might result in data and utility loss. Additionally, current approaches result in a model which is generalised for all clients. FedPartial is a framework to handle heterogeneity among the clients which does not enforce any constraints like homogeneity among data structures. Additionally, the learned model is also personalized according to the data distribution present at the client side. With the proposed mechanism, on average MobileNet achieves 96% and VGG16 achieves 90% accuracy respectively. Our results on a [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) dataset indicate that our framework achieves similar utility to the baseline case of full model aggregation.
