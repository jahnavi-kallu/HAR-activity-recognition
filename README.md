<h1>Dimensionality Reduction Using K-Means for Activity Recognition</h1>
<h3>Objective:</h3>
<p>Improved activity recognition models using high-dimensional sensor data from smartphones by implementing k-means clustering for dimensionality reduction.</p>
<h3>Approach:</h3>
<ui>
<li>Baseline Model: Constructed an initial model using all 561 features from various smartphone sensors.</li>
<li>Dimensionality Reduction: Applied k-means clustering to group similar features, reducing the feature set to 50 by selecting representative features from each cluster.</li>
<li>Normalized the data and used Gaussian Naive Bayes for classification.</li>
</ui>
<h3>Results:</h3>
<ui>
<li>Baseline Model (All Features): Achieved an accuracy of 73.15% with a training time of 0.15 seconds.</li>
<li>Reduced Model (K-Means): Enhanced accuracy to 78.59% with a significantly reduced training time of 0.01 seconds.</li>
<li>Efficiency: Reduced the number of features from 561 to 50, improving model interpretability and computational efficiency.</li>
</ui>
<h3>Key Achievements</h3>
<ui>
<li>Increased Accuracy: Achieved a 7.44% improvement in model accuracy through effective feature selection using k-means clustering.</li>
<li>Enhanced Efficiency: Reduced training time by approximately 92%, significantly boosting computational efficiency.</li>
<li>Feature Reduction: Streamlined the feature set from 561 to 50, leveraging k-means clustering to maintain essential information and discard redundancy.</li>
<li>Activity Recognition: Utilized the reduced feature set to build robust models for Human Activity Recognition using smartphone sensor data.</li>
</ui>
<h3>Dataset</h3>
<h4>UCI Human Activity Recognition Using Smartphones</h4>
<p>Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra, Jorge L. Reyes-Ortiz (2013)</p>
<p>https://archive.ics.uci.edu/dataset/240</p>
<p>30 subjects · Samsung Galaxy S2 · waist-mounted</p>
<p>7,352 training samples · 561 features · 6 activity classes</p>
<img width="1660" height="558" alt="Screenshot 2026-06-26 135656" src="https://github.com/user-attachments/assets/af8a15d1-f2d8-4774-a752-e383dfe8388f" />
<img width="500" height="500" alt="Screenshot 2026-06-26 135637" src="https://github.com/user-attachments/assets/7d275783-bcac-489d-9a63-e2d2f9d905ff" />
<img width="500" height="500" alt="Screenshot 2026-06-26 135557" src="https://github.com/user-attachments/assets/f1c71705-897f-402d-8000-1678922817e5" />

