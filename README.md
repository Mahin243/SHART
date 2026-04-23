# SHART
The integration of the **Internet of Medical Things (IoMT)** and continuous physiological monitoring is fundamentally altering healthcare, shifting the paradigm from episodic clinical snapshots to real-time, proactive surveillance. Traditional anomaly detection methods frequently struggle with the highly non-linear, multi-dimensional, and temporally dynamic nature of physiological and environmental data. 

This paper presents a comprehensive framework integrating **Long Short-Term Memory (LSTM)** networks, **Convolutional Neural Networks (CNNs)**, multi-head attention mechanisms, and the unsupervised **Isolation Forest** algorithm to:

- Detect acute physiological distress
- Classify physical falls
- Control indoor environmental anomalies

By evaluating multi-source heterogeneous datasets—including **SisFall**, **UCI HAR**, **RHMCD-20**, and **IoT dormitory sensors**—we establish the superiority of hybrid architectures. Our CNN-LSTM-Attention model achieves an **F1-score** of **98.7%** for fall detection, while the Isolation Forest identifies critical psychological distress anomalies with a **Silhouette score** of **0.61**. Furthermore, we demonstrate the efficacy of mid-level physiological fusion combined with late fusion of subjective survey labels to achieve a **Mean Squared Error (MSE)** of **0.08** in stress prediction. These findings confirm that fusion-driven, context-aware deep learning architectures significantly enhance the reliability, interpretability, and real-time applicability of automated monitoring systems in resource-constrained edge environments.

## Keywords
- multi-modal fusion
- long short-term memory
- anomaly detection
- isolation forest
- fall detection
- physiological monitoring
- IoMT
- deep learning
- edge computing
- convolutional neural network
