  # Bytefixer Final Project Report
# Replication and robustness test of STRIP
Weixi Zhang wz2295	Tianzhe Fang tf2172	Dawang Shen ds6818

Our study is based on the STRIP system. First, we made a full comprehension of the STRIP paper and replicated the mentioned models with three datasets: MNIST, CIFAR10, and GTSRB. For each of them, we evaluated their accuracy on the clean dataset and the attack success rate with trojan inputs to verify the effectiveness of the trojan model.Then, we applied the method provided by the paper to calculate the entropy of each benign input and trojan input and get their distribution. By applying different FRRs of the distribution, we get the boundary of the entropy between benign and trojan input, thus verifying the STRIP system. Furthermore, we tried several attack methods to test the robustness of STRIP. The first one is applying a new trigger and discovering the instability of the system's effectiveness. The second kind of trigger is randomly generating a rectangle on the input, finding STRIP is unstable. The third attempt is to change the opacity of the trigger and discover the awful performance of STRIP. The last one we change some pixel value of pictures as triggers and find bad STRIP performance.

## 1. Code Replication:
  ###（1). CIFAR10
  ### (2). MNIST
  ### (3). GTSRB
## 2. Robustness of STRIP
  ### (1). Application of Trigger B and C on Fashion MNIST
  ### (2). Application of Goolge logo image trigger
  ### (3). Random generation of solid and hollow rectangular triggers
  ### (4). Change of the opacity in trigger image
  ###（5). Pixel value changes of four corners  on images in MNIST
