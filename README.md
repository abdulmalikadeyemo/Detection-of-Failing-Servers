# Detection of Failing Servers on a Network
**Check the python notebook for the complete solution** [Click Here](https://github.com/abdulmalikadeyemo/Fault-Detection-in-Servers/blob/main/Anomaly_Detection.ipynb)

In this project, I implemented an anomaly detection algorithm to detect anomalous behavior in server on a network. The dataset contained two features: throughput (mb/s) and latency (ms) of response of each server. I collected 307 examples of how the servers were behaving while they were operating, resulting in an unlabeled dataset.

I suspected that the vast majority of these examples were “normal” (non-anomalous) examples of the servers operating normally, but there might also be some examples of servers acting anomalously within this dataset. To detect anomalous examples in the dataset, I used a Gaussian model.

I started working on a 2D dataset that allowed me to visualize what the algorithm was doing. On that dataset, I fit a Gaussian distribution and then found values that had very low probability and hence could be considered anomalies. After that, I applied the anomaly detection algorithm to a larger dataset with many dimensions.

**The ultimate goal of this project is to create a robust anomaly detection algorithm that can accurately identify anomalous server behavior, which can help prevent system failures and improve the overall performance of the servers.**
