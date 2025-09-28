---
layout: default
title: "Research"
---
<div class="section-card">
  <h2>Research</h2>
  <ul class="research-list">
    <li>
      <strong>StackLiverNet: A Novel Stacked Ensemble Model for Accurate and Interpretable Liver Disease Detection</strong><br>
      <em>ME Haque, SM Islam, S Mia, R Sharmin, Ashikuzzaman, MS Morshed, et al.</em><br>
      <em>Published at 16th International IEEE Conference on Computing Communication and Networking Technologies (ICCCNT), 2025</em><br>
      <p class="abstract-preview">Abstract: Liver diseases are a serious health concern in the world, which requires precise and timely diagnosis to enhance the survival chances of patients. <span class="abstract-full" style="display: none;">The current literature implemented numerous machine learning and deep learning models to classify liver diseases, but most of them had some issues like high misclassification error, poor interpretability, prohibitive computational expense, and lack of good preprocessing strategies. In order to address these drawbacks, we introduced StackLiverNet in this study; an interpretable stacked ensemble model tailored to the liver disease detection task. The framework uses advanced data preprocessing and feature selection technique to increase model robustness and predictive ability. Random undersampling is performed to deal with class imbalance and make the training balanced. StackLiverNet is an ensemble of several hyperparameter-optimized base classifiers, whose complementary advantages are used through a LightGBM meta-model. The provided model demonstrates excellent performance, with the testing accuracy of 99.89%, Cohen Kappa of 0.9974, and AUC of 0.9993, having only 5 misclassifications, and efficient training and inference speeds that are amenable to clinical practice (training time 4.2783 seconds, inference time 0.1106 seconds). Besides, Local Interpretable Model-Agnostic Explanations (LIME) are applied to generate transparent explanations of individual predictions, revealing high concentrations of Alkaline Phosphatase and moderate SGOT as important observations of liver disease. These findings prove that StackLiverNet is a precise, viable, and explainable model that may support clinicians in the early diagnosis of liver disease and enhance patient care.</span> <button class="read-more-btn" onclick="toggleAbstract(this)">Read More</button></p>
      <a href="StackLiverNet_ICCCNT2025.pdf" download target="_blank">Download Preprint</a> | 
      <a href="https://scholar.google.com/citations?user=A0NBq7kAAAAJ&hl=en&authuser=1" target="_blank">Google Scholar</a>
      <br><em>Acceptance: Accepted for presentation at ICCCNT 2025, July 2025</em>
    </li>
    <li>
      <strong>An Optimized Decision Tree-Based Framework for Explainable IoT Anomaly Detection</strong><br>
      <em>Ashikuzzaman, Md. Shawkat Hossain, Jubayer Abdullah Joy, Md Zahid Akon, Dr. Md Manjur Ahmed, Md. Naimul Islam</em><br>
      <em>Accepted at IEEE 2nd International Conference on Computing, Applications and Systems (COMPAS), 2025</em><br>
      <p class="abstract-preview">Abstract: The increase in the number of Internet of Things (IoT) devices has tremendously increased the attack surface of cyber threats thus making a strong intrusion detection system (IDS) with a clear explanation of the process essential towards resource-constrained environments. <span class="abstract-full" style="display: none;">Nevertheless, current IoT IDS systems are usually traded off with detection quality, model elucidability, and computational effectiveness, thus the deployment on IoT devices. The present paper counteracts these difficulties by suggesting an explainable AI (XAI) framework based on an optimized Decision Tree classifier with both local and global importance methods: SHAP values that estimate feature attribution using local explanations, and Morris sensitivity analysis that identifies the feature importance in a global view. The proposed system attains the state of art on the test performance with 99.91% accuracy, F1-score of 99.51% and Cohen Kappa of 0.9960 and high stability is confirmed by a cross validation mean accuracy of 98.93% (±0.0003). Efficiency is also enhanced in terms of computations to provide faster inferences compared to those that are generalized in ensemble models. SrcMac has shown as the most significant predictor in feature analyses according to SHAP and Morris methods. Compared to the previous work, our solution eliminates its major drawback lack because it allows us to apply it to edge devices and, therefore, achieve real-time processing, adhere to the new regulation of transparency in AI, and achieve high detection rates on attacks of dissimilar classes. This combination performance of high accuracy, explainability, and low computation make the framework useful and reliable as a resource-constrained IoT security problem in real environments.</span> <button class="read-more-btn" onclick="toggleAbstract(this)">Read More</button></p>
      <a href="Explainable_IoT_Anomaly_Detection_COMPAS2025.pdf" download target="_blank">Download Preprint</a> | 
      <a href="https://scholar.google.com/citations?user=A0NBq7kAAAAJ&hl=en&authuser=1" target="_blank">Google Scholar</a>
      <br><em>Acceptance: Accepted for presentation at COMPAS 2025, October 2025</em>
    </li>
  </ul>
</div>
<style>
  .research-list li { margin-bottom: 20px; }
  .section-card { padding: 20px; border: 1px solid #ddd; border-radius: 5px; }
  .read-more-btn { background-color: #4CAF50; color: white; border: none; padding: 5px 10px; cursor: pointer; border-radius: 3px; }
  .read-more-btn:hover { background-color: #45a049; }
</style>
<script>
  function toggleAbstract(button) {
    const fullAbstract = button.previousElementSibling;
    const isHidden = fullAbstract.style.display === 'none';
    fullAbstract.style.display = isHidden ? 'inline' : 'none';
    button.textContent = isHidden ? 'Read Less' : 'Read More';
  }
</script>
