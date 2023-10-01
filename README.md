# FraudGuard: Advanced Credit Card Fraud Detection

In the realm of financial security, FraudGuard stands tall as a cutting-edge credit card fraud detection system. The pivotal role of this system is to empower credit card companies to swiftly identify and thwart fraudulent transactions, ensuring that customers are shielded from unauthorized charges.

### Dataset Overview

The dataset encapsulates credit card transactions that transpired in September 2013, involving European cardholders. Within the span of two days, a total of 284,807 transactions occurred, among which 492 were identified as fraudulent. This dataset is characterized by a high level of imbalance, with fraudulent transactions accounting for a mere 0.172% of the total.

Download the Dataset from <a href='https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud'>here. </a>

### Model Prediction

FraudGuard leverages state-of-the-art anomaly detection algorithms to fortify the security infrastructure. Two key algorithms employed in this endeavor are the Isolation Forest Algorithm and the Local Outlier Factor (LOF) Algorithm.

### Isolation Forest Algorithm :

The Isolation Forest Algorithm is a beacon of innovation in anomaly detection. Its foundation rests on the premise that anomalies are scarce and distinctive. Leveraging the concept of isolation, anomalies are singled out efficiently.

#### How It Works:

- Isolation Trees: The algorithm isolates observations by randomly selecting a feature and a split value within the feature's range.
- Anomaly Score: An anomaly score is computed based on the number of conditions needed to isolate an observation. Fewer conditions imply a higher anomaly score.

### Local Outlier Factor (LOF) Algorithm

The LOF Algorithm is an unsupervised outlier detection method, gauging the local density deviation of a data point concerning its neighbors. It identifies outliers as samples with significantly lower density than their neighbors.

#### Key Features:

1. Neighbor Consideration: The algorithm considers the local density deviation with respect to the number of neighbors. A balance is struck to capture outliers while avoiding excessive dependence on neighbors.
2. Parameter Selection: The parameter n_neighbors is set judiciously, generally exceeding the minimum cluster size and staying below the potential maximum number of nearby objects.

#### 🔍 Visual Insights:

FraudGuard provides visual representations of anomaly scores, aiding in the intuitive interpretation of potential fraud patterns.
Graphical depictions showcase the isolation trees and path lengths, offering transparency into the anomaly detection process.
FraudGuard is not merely a shield; it is a proactive guardian, harnessing the power of advanced algorithms to safeguard financial transactions with unparalleled precision and efficiency.
