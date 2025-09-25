---
title: "Holistic Surgical Phase Recognition with Hierarchical Input Dependent State Space Models"
collection: publications
category: manuscripts
excerpt: 'Surgical workflow analysis is essential in robot-assisted surgeries, yet the long duration of such procedures poses significant challenges for comprehensive video analysis. Recent approaches have predominantly relied on transformer models; however, their quadratic attention mechanism restricts efficient processing of lengthy surgical videos. In this paper, we propose a novel hierarchical input-dependent state space model that leverages the linear scaling property of state space models to enable decision making on full-length videos while capturing both local and global dynamics. Our framework incorporates a temporally consistent visual feature extractor, which appends a state space model head to a visual feature extractor to propagate temporal information. The proposed model consists of two key modules: a local-aggregation state space model block that effectively captures intricate local dynamics, and a global-relation state space model block that models temporal dependencies across the entire video. The model is trained using a hybrid discrete-continuous supervision strategy, where both signals of discrete phase labels and continuous phase progresses are propagated through the network. Experiments have shown that our method outperforms the current state-of-the-art methods by a large margin (+2.8% on Cholec80, +4.3% on MICCAI2016, and +12.9% on Heichole datasets). Code will be publicly available after paper acceptance.'
date: 2025-06-26
venue: 'In submission to IEEE TMI'
slidesurl: 'https://william-hywu.github.io/HID-SSM/'
paperurl: 'https://arxiv.org/abs/2506.21330'
citation: "<b>Haoyang Wu</b>, Tsun-Hsuan Wang, Mathias Lechner, Ramin Hasani, Jennifer A. Eckhoff, Paul Pak, Ozanan R. Meireles, Guy Rosman, Yutong Ban, Daniela Rus"
---

<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 20px;">
  <div style="flex: 0 0 300px;">
    <img src="{{ site.baseurl }}/_publications/HID-SSM.png" alt="HID-SSM Framework" width="300" style="border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
  </div>
  <div style="flex: 1;">
    <h2 style="margin-top: 0;">Holistic Surgical Phase Recognition with Hierarchical Input Dependent State Space Models</h2>
    <p style="font-size: 18px; color: #666; margin-bottom: 10px;"><strong>Haoyang Wu</strong>, Tsun-Hsuan Wang, Mathias Lechner, Ramin Hasani, Jennifer A. Eckhoff, Paul Pak, Ozanan R. Meireles, Guy Rosman, Yutong Ban, Daniela Rus</p>
    <p style="font-style: italic; margin-bottom: 15px;">In submission to IEEE TMI, 2025</p>
    <div style="display: flex; gap: 10px; flex-wrap: wrap;">
      <a href="https://arxiv.org/abs/2506.21330" style="padding: 8px 16px; background-color: #f0f0f0; text-decoration: none; color: #333; border-radius: 4px; border: 1px solid #ccc;">ARXIV</a>
      <a href="https://william-hywu.github.io/HID-SSM/" style="padding: 8px 16px; background-color: #f0f0f0; text-decoration: none; color: #333; border-radius: 4px; border: 1px solid #ccc;">PROJECT</a>
      <a href="{{ site.baseurl }}/files/HID-SSM.pdf" style="padding: 8px 16px; background-color: #f0f0f0; text-decoration: none; color: #333; border-radius: 4px; border: 1px solid #ccc;">PDF</a>
    </div>
  </div>
</div>
