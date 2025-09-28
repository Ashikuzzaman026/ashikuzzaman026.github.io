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
      <a href="/StackLiverNet_ICCCNT2025.pdf" download target="_blank">Download Preprint</a> | 
      <a href="https://scholar.google.com/citations?user=A0NBq7kAAAAJ&hl=en&authuser=1" target="_blank">Google Scholar</a>
      <br><em>Acceptance: Accepted for presentation at ICCCNT 2025, July 2025</em>
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
