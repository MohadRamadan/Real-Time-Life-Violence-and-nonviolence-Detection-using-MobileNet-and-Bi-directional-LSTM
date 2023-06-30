# Real-Time-Life-Violence-and-nonviolence-Detection-using-MobileNet-and-Bi-directional-LSTM

ABSTRACT
Neural Networks (NNs) are considered efficient tools in the computer vision field as part of Deep learning (DL) engineering. They are broadly used in advanced engineering systems to enhance the performance of such systems. Analyzing human activity recognition is one of the growing fields where research is gaining momentum. The resultant recognition applications are used for detecting and identifying the activities of humans within any behavioral or industrial environment.
This project describes the implementation of a DL technique to show its ability to develop the human activity recognition system using a given data set. Further, it also shows the improvement of overall performance corresponding to this new NN technique to classify the normal/abnormal specifically (violence/non-violence) human activity within video streams from human activities in an efficient and faster manner with high recognition accuracy.
After exploring, analyzing and comparing several DL models for violence detection. It was found that the proposed DL technique: MobileNetV2-BiLSTM (which uses lightweight MobileNetV2 is for deep spatial feature extraction, BiLSTM is for temporal feature extraction from sequence video frames and the SoftMax function as the classifier) could improve the overall human activity recognition system compared with other methods which could not classify the overlapped objects within some of the data sets.
Training our proposed model over 20 epochs and batch size = 8, with SGD optimizer and cross-entropy as a loss function, resulted in recording a loss of 7.08%, accuracy of 98.06%, validation loss of 35.55% and validation accuracy of 91.11%.
We contributed to the growing body of work on violence detection using DL in real-time video streams in a more efficient and quicker manner, with high identification accuracy enabling for early intervention and better public safety.
