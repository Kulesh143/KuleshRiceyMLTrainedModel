<h1>Detection of Paddy Leaf Deficiencies
Using Machine Learning Algorithms
for Optimized Crop Health
Monitoring</h1>


![bnan](https://github.com/user-attachments/assets/3bef1e78-11f0-40d5-b36a-2edc3a3a3560)
![manaa](https://github.com/user-attachments/assets/27ea8e60-5f5a-45e6-a2cd-0bb0c9435eff)




In this study, two deep learning models, ResNet and VGG16, were evaluated for their performance in
detecting paddy leaf disease. Both models exhibited strong results, but some key differences between them
indicate which may be more suitable for this specific task.
The ResNet model achieved an impressive accuracy of 96.67%, meaning it correctly classified nearly 97% of the
test samples. With a precision of 0.9344, it showed strong capability in correctly identifying true positive
cases—healthy leaves—while minimizing false positives. The recall of 0.9667 further emphasizes its ability to
correctly identify the vast majority of true positives, indicating high sensitivity to paddy leaf disease. An F1-
score of 0.9503 highlights a good balance between precision and recall, making the ResNet model highly
reliable in recognizing both healthy and unhealthy leaf samples. However, the confusion matrix shows that the
model made four errors, all of which were false negatives, meaning it missed some unhealthy samples.
Similarly, the VGG16 model also demonstrated outstanding performance, matching ResNet’s accuracy at
96.67%. Its precision (0.9344), recall (0.9667), and F1-score (0.9503) align closely with those of the ResNet
model. Like ResNet, VGG16 also misclassified four instances, as shown by the confusion matrix. This indicates
that both models perform similarly in terms of overall classification effectiveness and balance between
precision and recall.

By SLIIT MSc. in IT Student- A.Kulesh.B.M.Abhayasundara
While both models perform exceptionally well, the choice between them ultimately depends on additional
factors such as computational efficiency, model complexity, and ease of deployment. Since both models yield
similar accuracy, precision, and recall, either ResNet or VGG16 would be suitable for this task. However,
ResNet’s architecture, which is designed to mitigate the vanishing gradient problem, may provide additional
robustness in larger-scale datasets, potentially making it a better choice for further scaling and real-world
applications in agriculture.
