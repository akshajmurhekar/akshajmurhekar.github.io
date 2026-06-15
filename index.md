---
layout: default
title: Academic Portfolio
---

<script>
    // Dynamically injects your local UT favicon into the document head
    (function() {
        var link = document.createElement('link');
        link.type = 'image/svg+xml';
        link.rel = 'icon';
        link.href = 'assets/longhorn-icon.svg';
        document.getElementsByTagName('head')[0].appendChild(link);
    })();
</script>

<!-- INTRO BLOCK: Headshot centered vertically with the text column -->
<div style="display: flex; flex-wrap: wrap; justify-content: center; align-items: center; gap: 34px; margin-bottom: 35px;">
    <!-- Headshot Column -->
    <div style="flex-shrink: 0; text-align: center;">
        <img src="assets/headshot.png" alt="Akshaj Murhekar" style="width: 300px; max-width: 100%; border-radius: 8px;">
    </div>
    
    <!-- Content Column that expands to fill the right side -->
    <div style="flex: 1; min-width: 280px; line-height: 1.6;">
        <span style="font-size: 1.3em; font-weight: 600; color: #24292f;">Graduate Research Assistant, UT Austin</span>
        
        <div style="margin-top: 8px; margin-bottom: 16px;">
            <a href="https://scholar.google.com/citations?user=iObTPf8AAAAJ" target="_blank" style="font-weight: 500;">Google Scholar</a> &middot; 
            <a href="https://linkedin.com/in/akshaj-murhekar" target="_blank" style="font-weight: 500;">LinkedIn</a> &middot; 
            <a href="https://github.com/akshajmurhekar" target="_blank" style="font-weight: 500;">GitHub</a> &middot; 
            <a href="mailto:akshaj.murhekar@utexas.edu" style="font-weight: 500;">Email</a>
        </div>
        
        <!-- Clean, human-readable bio -->
        <p style="margin: 0; color: #24292f;">
            I am a graduate researcher at UT Austin with a focus on language modeling, representation learning, and multimodal deep learning. During my time as an M.S. student, I worked with <a href="https://abhijitmishra.github.io/" target="_blank">Dr. Abhijit Mishra</a> on challenging problems at the intersection of language models and neural signal processing. My research focused on leveraging in-context learning capabilities of Large Language Models (LLMs). Specifically, I developed privacy-preserving neuro-symbolic decoding pipelines and efficient retrieval frameworks designed to bridge the gap between brain activity and text, translating electroencephalography (EEG) signals directly into natural language. Please bear with me while I wait for Google Search to index this page.
        </p>
    </div>
</div>

## Research Interests

<ul style="line-height: 1.8; padding-left: 20px; color: #24292f; margin-bottom: 35px;">
    <li style="margin-bottom: 4px;"><strong>Multimodal Deep Learning</strong></li>
    <li style="margin-bottom: 4px;"><strong>Neuro-Symbolic Learning</strong></li>
    <li style="margin-bottom: 4px;"><strong>Sparse & Efficient Architectures</strong></li>
    <li style="margin-bottom: 4px;"><strong>LLM Evaluation & Behavioral Alignment</strong></li>
</ul>

## Research & Preprints

<ol style="padding-left: 20px; margin: 0;">
    <!-- PUBLICATION 1 -->
    <li style="margin-bottom: 28px; line-height: 1.6; color: #24292f;">
        <div style="font-size: 1.1em; font-weight: 600; color: #24292f; margin-bottom: 4px;">
            SYNAPSE: Neuro-Symbolic Visual Thought-to-Text Decoding via Topological Semantic Denoising
        </div>
        <div style="font-size: 0.95em; color: #24292f; margin-bottom: 8px;">
            <strong>A. Murhekar</strong>, A. Mishra. <span style="color: #57606a;">(2026). <em>Under review at EMNLP 2026</em>.</span>
        </div>
        <div style="display: flex; flex-wrap: wrap; gap: 8px; font-size: 0.85em;">
            <a href="https://arxiv.org/abs/2605.27790" target="_blank" style="padding: 4px 10px; background-color: #f1f2f4; color: #0366d6; border-radius: 6px; text-decoration: none; font-weight: 500; border: 1px solid #e1e4e8;">arXiv Abstract</a>
            <a href="https://arxiv.org/pdf/2605.27790.pdf" target="_blank" style="padding: 4px 10px; background-color: #f1f2f4; color: #0366d6; border-radius: 6px; text-decoration: none; font-weight: 500; border: 1px solid #e1e4e8;">PDF</a>
            <a href="https://github.com/akshaj-utexas/neuro-symbolic-eeg-to-text" target="_blank" style="padding: 4px 10px; background-color: #f1f2f4; color: #0366d6; border-radius: 6px; text-decoration: none; font-weight: 500; border: 1px solid #e1e4e8;">Code</a>
        </div>
    </li>

    <!-- PUBLICATION 2 -->
    <li style="margin-bottom: 28px; line-height: 1.6; color: #24292f;">
        <div style="font-size: 1.1em; font-weight: 600; color: #24292f; margin-bottom: 4px;">
            SENSE: Efficient EEG-to-Text via Privacy-Preserving Semantic Retrieval
        </div>
        <div style="font-size: 0.95em; color: #24292f; margin-bottom: 8px;">
            <strong>A. Murhekar</strong>, C. Liu, A. Mishra, S. Roychowdhury, J. Gwizdka. <span style="color: #57606a;">(2026). <em>Under review at ICMI 2026</em>.</span>
        </div>
        <div style="display: flex; flex-wrap: wrap; gap: 8px; font-size: 0.85em;">
            <a href="https://arxiv.org/abs/2603.17109" target="_blank" style="padding: 4px 10px; background-color: #f1f2f4; color: #0366d6; border-radius: 6px; text-decoration: none; font-weight: 500; border: 1px solid #e1e4e8;">arXiv Abstract</a>
            <a href="https://arxiv.org/pdf/2603.17109.pdf" target="_blank" style="padding: 4px 10px; background-color: #f1f2f4; color: #0366d6; border-radius: 6px; text-decoration: none; font-weight: 500; border: 1px solid #e1e4e8;">PDF</a>
            <a href="https://github.com/akshaj-utexas/efficient-eeg-2-text" target="_blank" style="padding: 4px 10px; background-color: #f1f2f4; color: #0366d6; border-radius: 6px; text-decoration: none; font-weight: 500; border: 1px solid #e1e4e8;">Code</a>
        </div>
    </li>

    <!-- PUBLICATION 3 -->
    <li style="margin-bottom: 28px; line-height: 1.6; color: #24292f;">
        <div style="font-size: 1.1em; font-weight: 600; color: #24292f; margin-bottom: 4px;">
            A Survey on Bridging EEG Signals and Generative AI
        </div>
        <div style="font-size: 0.95em; color: #24292f; margin-bottom: 8px;">
            S. Shukla, J. Torres, <strong>A. Murhekar</strong>, C. Liu, A. Mishra, J. Gwizdka, S. Roychowdhury. <span style="color: #57606a;">(2025). <em>Under review at Neural Networks (Elsevier)</em>.</span>
        </div>
        <div style="display: flex; flex-wrap: wrap; gap: 8px; font-size: 0.85em;">
            <a href="https://arxiv.org/abs/2502.12048" target="_blank" style="padding: 4px 10px; background-color: #f1f2f4; color: #0366d6; border-radius: 6px; text-decoration: none; font-weight: 500; border: 1px solid #e1e4e8;">arXiv Abstract</a>
            <a href="https://arxiv.org/pdf/2502.12048.pdf" target="_blank" style="padding: 4px 10px; background-color: #f1f2f4; color: #0366d6; border-radius: 6px; text-decoration: none; font-weight: 500; border: 1px solid #e1e4e8;">PDF</a>
        </div>
    </li>
</ol>

## Education

<!-- UT AUSTIN ENTRY -->
<div style="display: flex; flex-wrap: wrap; justify-content: flex-start; align-items: center; gap: 24px; margin-bottom: 30px;">
    <div style="flex-shrink: 0; width: 130px; display: flex; justify-content: flex-start;">
        <img src="assets/ut-austin.svg" alt="UT Austin Logo" style="width: 120px; height: auto;">
    </div>
    <div style="flex: 1; min-width: 280px; line-height: 1.6;">
        <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: baseline; margin-bottom: 4px;">
            <span style="font-size: 1.15em; font-weight: 600; color: #24292f;">The University of Texas at Austin</span>
            <span style="font-size: 0.95em; color: #57606a; font-weight: 500;">2024 &ndash; 2026</span>
        </div>
        <div style="color: #24292f; margin-bottom: 6px;">
            <span style="font-weight: 500;">M.S. in Information Science (Thesis Track)</span>
        </div>
        <div style="font-size: 0.95em; color: #57606a; margin-bottom: 2px;">
            <strong>Specialization:</strong> Applied Machine Learning and Deep Learning
        </div>
        <div style="font-size: 0.95em; color: #57606a;">
            <strong>Committee:</strong> 
            <a href="https://abhijitmishra.github.io/" target="_blank">Dr. Abhijit Mishra</a>, 
            <a href="https://ischool.utexas.edu/profiles/shounak-roychowdhury" target="_blank">Dr. Shounak Roychowdhury</a>, 
            <a href="https://jacekg.ischool.utexas.edu" target="_blank">Dr. Jacek Gwizdka</a>
        </div>
    </div>
</div>

<!-- UT ARLINGTON ENTRY -->
<div style="display: flex; flex-wrap: wrap; justify-content: flex-start; align-items: center; gap: 24px; margin-bottom: 30px;">
    <div style="flex-shrink: 0; width: 130px; display: flex; justify-content: flex-start;">
        <img src="assets/ut-arlington.svg" alt="UT Arlington Logo" style="width: 120px; height: auto;">
    </div>
    <div style="flex: 1; min-width: 280px; line-height: 1.6;">
        <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: baseline; margin-bottom: 4px;">
            <span style="font-size: 1.15em; font-weight: 600; color: #24292f;">The University of Texas at Arlington</span>
            <span style="font-size: 0.95em; color: #57606a; font-weight: 500;">2020 &ndash; 2024</span>
        </div>
        <div style="color: #24292f; margin-bottom: 4px;">
            <span style="font-weight: 500;">B.S. in Computer Science</span>
        </div>
        <div style="font-size: 0.95em; color: #57606a;">
            <strong>Honors:</strong> Presidential Scholarship (Full-Tuition Merit Award &middot; $108,000)
        </div>
        <div style="font-size: 0.95em; color: #57606a;">
            <strong>Senior Design:</strong> Autonomous Medical Supply Cart (NIH-Funded &middot; Presented at <a href="https://2023bmesannual.eventscribe.net/fsPopup.asp?PresenterID=1526288&mode=posterPresenterInfo" target="_blank" style="color: #0366d6; text-decoration: none; font-weight: 500;">BMES 2023</a>)
        </div>
    </div>
</div>

## Selected Projects

<ul style="line-height: 1.7; padding-left: 20px; color: #24292f; margin-bottom: 35px;">
    <li style="margin-bottom: 8px;">
        <strong>Scientific Sycophancy Benchmark:</strong> Engineered an evaluation pipeline uncovering an 85% failure rate where frontier LLMs prioritize helpfulness over physical laws, motivating a verification-aware RAG framework.
    </li>
    <li style="margin-bottom: 8px;">
        <strong>KV Cache Optimization:</strong> Engineered a PyTorch-based algorithm to reduce Llama-3 system memory usage by 50% during inference.
    </li>
    <li style="margin-bottom: 8px;">
        <strong>Audio-Visual Source Separation:</strong> Architected a U-Net with visual conditioning to separate target audio sources from mixtures via latent space modulation.
    </li>
    <li style="margin-bottom: 8px;">
        <strong>LLM Fine-tuning (Review Feedback):</strong> Fine-tuned Qwen2.5-1.5B using PEFT and Unsloth on a 46M-token synthetic dataset for high-throughput inference.
    </li>
</ul>

## Awards & Honors

<ul style="line-height: 1.7; padding-left: 20px; color: #24292f; margin-bottom: 35px;">
    <!-- Bullet 2 -->
    <li style="margin-bottom: 8px;">
        <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: baseline;">
            <span><strong>NIH Research Grant</strong> &middot; National Institutes of Health</span>
            <span style="font-size: 0.95em; color: #57606a; font-weight: 500;">2023 &ndash; 2024</span>
        </div>
    </li>
    <!-- Bullet 3 -->
    <li style="margin-bottom: 8px;">
        <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: baseline;">
            <span><strong>NSF REU Award (2x Recipient)</strong> &middot; National Science Foundation</span>
            <span style="font-size: 0.95em; color: #57606a; font-weight: 500;">2022 &ndash; 2024</span>
        </div>
    </li>
    <!-- Bullet 4 -->
    <li style="margin-bottom: 8px;">
        <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: baseline;">
            <span><strong>Undergraduate Research Appreciation Award</strong> &middot; UTARI</span>
            <span style="font-size: 0.95em; color: #57606a; font-weight: 500;">2024</span>
        </div>
    </li>
    <!-- Bullet 5 -->
    <li style="margin-bottom: 8px;">
        <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: baseline;">
            <span><strong>Undergraduate Research Rank 3</strong> &middot; College of Engineering, UT Arlington</span>
            <span style="font-size: 0.95em; color: #57606a; font-weight: 500;">2023</span>
        </div>
    </li>
</ul>

<style>
    /* Disables the self-referencing click link on your name */
    header a, .site-title, h1 a, a.site-title {
        pointer-events: none !important;
        cursor: default !important;
        text-decoration: none !important;
        color: #24292f !important;
    }
</style>
