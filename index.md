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

<!-- STICKY HOVERING FLOATING GLASS NAV BAR WITH MOBILE DROP DOWN -->
<div class="sticky-nav">
    <div class="nav-name">Akshaj Murhekar</div>
    
    <!-- Hidden Checkbox & Hamburger Label for Mobile Toggle -->
    <input type="checkbox" id="nav-toggle" class="nav-toggle">
    <label for="nav-toggle" class="nav-toggle-label">
        <span></span>
        <span></span>
        <span></span>
    </label>

    <div class="nav-links">
        <a href="#about">About</a>
        <a href="#research">Research</a>
        <a href="#education">Education</a>
        <a href="#awards">Awards</a>
        <a href="#projects">Projects</a>
        <a href="#teaching">Teaching</a>
    </div>
</div>

<!-- INTRO & INTERESTS BLOCK: Headshot Left Column with Links underneath / Content Right Column -->
<div id="about" style="display: flex; flex-wrap: wrap; justify-content: center; align-items: flex-start; gap: 40px; margin-bottom: 35px; margin-top: 40px;">
    
    <!-- Left Column: Centered Image & Contact Links (Inspired by Screenshot 2026-06-15 at 2.38.53 PM.jpg) -->
    <div style="flex-shrink: 0; width: 300px; max-width: 100%; display: flex; flex-direction: column; align-items: center; text-align: center;">
    <img src="assets/headshot.png" alt="Akshaj Murhekar" style="width: 100%; border-radius: 8px; margin-bottom: 20px;">
    
    <div style="display: flex; justify-content: center; align-items: center; gap: 18px; margin-bottom: 14px;">
        <a href="https://scholar.google.com/citations?user=iObTPf8AAAAJ" target="_blank" title="Google Scholar" style="display: inline-flex; align-items: center;">
            <svg viewBox="0 0 24 24" style="width: 22px; height: 22px; fill: #57606a; transition: fill 0.2s;" onmouseover="this.style.fill='#0366d6'" onmouseout="this.style.fill='#57606a'"><path d="M12 24a7 7 0 0 1-7-7c0-2.95 1.76-5.45 4.35-6.5L12 12.8l2.65-2.3c2.6 1.05 4.35 3.55 4.35 6.5a7 7 0 0 1-7 7M12 0l11 9h-4.33a7 7 0 0 1-13.34 0H1L12 0Z"/></svg>
        </a>

        <a href="https://linkedin.com/in/akshaj-murhekar" target="_blank" title="LinkedIn" style="display: inline-flex; align-items: center;">
            <svg viewBox="0 0 24 24" style="width: 21px; height: 21px; fill: #57606a; transition: fill 0.2s;" onmouseover="this.style.fill='#0366d6'" onmouseout="this.style.fill='#57606a'"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
        </a>

        <a href="https://github.com/akshajmurhekar" target="_blank" title="GitHub" style="display: inline-flex; align-items: center;">
            <svg viewBox="0 0 24 24" style="width: 21px; height: 21px; fill: #57606a; transition: fill 0.2s;" onmouseover="this.style.fill='#0366d6'" onmouseout="this.style.fill='#57606a'"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/></svg>
        </a>

        <a href="#" onclick="return false;" title="Curriculum Vitae" style="display: inline-flex; align-items: center;">
            <svg viewBox="0 0 24 24" style="width: 20px; height: 20px; fill: #57606a; transition: fill 0.2s;" onmouseover="this.style.fill='#0366d6'" onmouseout="this.style.fill='#57606a'"><path d="M14 2H6c-1.1 0-1.99.9-1.99 2L4 20c0 1.1.89 2 1.99 2H18c1.1 0 2-.9 2-2V8l-6-6zm2 16H8v-2h8v2zm0-4H8v-2h8v2zm-3-5V3.5L18.5 9H13z"/></svg>
        </a>
    </div>
    
    <div style="display: inline-flex; align-items: center; justify-content: center; gap: 6px; font-size: 0.93em;">
        <svg viewBox="0 0 24 24" style="width: 16px; height: 16px; fill: #57606a;"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg>
        <a href="mailto:akshaj.murhekar@utexas.edu" style="font-weight: 500; color: #0366d6; text-decoration: none;">akshaj.murhekar@utexas.edu</a>
    </div>
</div>
    
    <!-- Right Column: Bio Paragraph & Research Interests -->
    <div style="flex: 1; min-width: 280px; line-height: 1.6;">
        <!-- Dives straight into the paragraph text -->
        <p style="margin: 0; margin-bottom: 24px; color: #24292f; text-align: justify;">
            I am a graduate researcher at UT Austin with a focus on language modeling, representation learning, and multimodal deep learning. During my time as an M.S. student, I worked with <a href="https://abhijitmishra.github.io/" target="_blank">Dr. Abhijit Mishra</a> on challenging problems at the intersection of language models and neural signal processing. My research focused on leveraging in-context learning capabilities of Large Language Models (LLMs). Specifically, I developed privacy-preserving neuro-symbolic decoding pipelines and efficient retrieval frameworks designed to bridge the gap between brain activity and text, translating electroencephalography (EEG) signals directly into natural language. Please bear with me while I wait for Google Search to index this page.
        </p>

        <h3 style="font-size: 1.15em; font-weight: 600; color: #24292f; margin-bottom: 10px;">Research Interests</h3>
        <ul style="line-height: 1.7; padding-left: 20px; color: #24292f; margin: 0;">
            <li style="margin-bottom: 4px;"><strong>Multimodal Deep Learning</strong></li>
            <li style="margin-bottom: 4px;"><strong>Neuro-Symbolic Learning</strong></li>
            <li style="margin-bottom: 4px;"><strong>Sparse & Efficient Architectures</strong></li>
            <li style="margin-bottom: 4px;"><strong>LLM Evaluation & Behavioral Alignment</strong></li>
        </ul>
    </div>
</div>


## Research & Preprints {#research}

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

## Education {#education}

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

## Selected Projects {#projects}

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

## Awards, Grants & Recognitions {#awards}

<ul style="line-height: 1.7; padding-left: 20px; color: #24292f; margin-bottom: 35px;">
    <!-- Award 1 -->
    <li style="margin-bottom: 16px;">
        <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: baseline;">
            <span><strong>Presidential Scholarship ($108,000)</strong> &middot; UT Arlington</span>
            <span style="font-size: 0.95em; color: #57606a; font-weight: 500;">2020 &ndash; 2024</span>
        </div>
        <div style="font-size: 0.93em; color: #57606a; margin-top: 2px;">
            The university's premier undergraduate merit award, covering full tuition and fees for four years based on exceptional academic entry credentials.
        </div>
    </li>
    
    <!-- Award 2 -->
    <li style="margin-bottom: 16px;">
        <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: baseline;">
            <span><strong>NSF REU Research Awards (2x Recipient)</strong> &middot; National Science Foundation</span>
            <span style="font-size: 0.95em; color: #57606a; font-weight: 500;">2022 &ndash; 2024</span>
        </div>
        <div style="font-size: 0.93em; color: #57606a; margin-top: 2px;">
            Funded undergraduate research fellowships supporting two distinct initiatives:
            <ul style="margin-top: 4px; margin-bottom: 0; padding-left: 20px; list-style-type: circle;">
                <li><strong>Assistive Robotics (2022–2023):</strong> Developed an outdoor drone navigation system for the visually impaired, which served as a foundational asset for my subsequent appointment at UT Arlington Research Institute.</li>
                <li><strong>Generative AI Systems (2023–2024):</strong> Developed an early-stage AI framework to convert raw text prompts into educational video content.</li>
            </ul>
        </div>
    </li>

    <!-- Award 3 -->
    <li style="margin-bottom: 16px;">
        <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: baseline;">
            <span><strong>NIH Institutional Research Grant Funding</strong> &middot; National Institutes of Health</span>
            <span style="font-size: 0.95em; color: #57606a; font-weight: 500;">2023 &ndash; 2024</span>
        </div>
        <div style="font-size: 0.93em; color: #57606a; margin-top: 2px;">
            Funded a year-long Senior Design initiative where I served as the project lead. Following summer field research with medical staff to identify clinical workflow constraints, I led the full-lifecycle engineering and development of an autonomous medical supply cart, presenting our initial framework at the <a href="https://2023bmesannual.eventscribe.net/fsPopup.asp?PresenterID=1526288&mode=posterPresenterInfo" target="_blank" style="color: #0366d6; text-decoration: none; font-weight: 500;">BMES 2023</a> Annual Meeting in Seattle.
        </div>
    </li>

    <!-- Award 4 -->
    <li style="margin-bottom: 16px;">
        <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: baseline;">
            <span><strong>Undergraduate Research Excellence (Rank 3)</strong> &middot; College of Engineering</span>
            <span style="font-size: 0.95em; color: #57606a; font-weight: 500;">2023</span>
        </div>
        <div style="font-size: 0.93em; color: #57606a; margin-top: 2px;">
            Ranked third overall across the entire College of Engineering for competitive undergraduate research project demonstrations, awarded specifically for the engineering design and execution of the assistive navigation drone system.
        </div>
    </li>

    <!-- Award 5 -->
    <li style="margin-bottom: 8px;">
        <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: baseline;">
            <span><strong>Undergraduate Research Appreciation Award</strong> &middot; UT Arlington Research Institute</span>
            <span style="font-size: 0.95em; color: #57606a; font-weight: 500;">2024</span>
        </div>
        <div style="font-size: 0.93em; color: #57606a; margin-top: 2px;">
            Awarded by the UT Arlington Research Institute in recognition of technical contributions to institutional computer vision, photogrammetry, and robotics projects.
        </div>
    </li>
</ul>


## Teaching & Mentorship {#teaching}

### Research Mentorship
<ul style="line-height: 1.7; padding-left: 20px; color: #24292f; margin-bottom: 24px;">
    <li style="margin-bottom: 8px;">
        <strong>Undergraduate Research Mentor</strong> &middot; UT Austin <span style="font-size: 0.9em; color: #57606a; float: right;">2025 &ndash; 2026</span>
        <div style="font-size: 0.95em; color: #57606a; margin-top: 2px;">
            Mentored an undergraduate researcher exploring multimodal machine learning. Co-guided her through project frameworks and research methodologies, directly supporting the execution of her Honors Bachelor's Thesis tied to our core deep learning pipeline.
        </div>
    </li>
</ul>

### Teaching & Tutoring
<ul style="line-height: 1.7; padding-left: 20px; color: #24292f; margin-bottom: 35px;">
    <li style="margin-bottom: 12px;">
        <strong>Graduate Teaching Assistant</strong> &middot; UT Austin <span style="font-size: 0.9em; color: #57606a; float: right;">2025</span>
        <div style="font-size: 0.95em; color: #57606a; margin-top: 2px;">
            Served as a Graduate TA across distinct academic disciplines, including Statistics and Academic Writing courses. Held weekly office hours to assist students with core course material, managed evaluation frameworks, and guided students through complex coursework requirements.
        </div>
    </li>
    <li style="margin-bottom: 8px;">
        <strong>Undergraduate Academic Tutor</strong> &middot; UT Arlington <span style="font-size: 0.9em; color: #57606a; float: right;">2022 &ndash; 2024</span>
        <div style="font-size: 0.95em; color: #57606a; margin-top: 2px;">
            Provided high-impact 1-on-1 and drop-in academic instruction across multiple departments. Covered core Computer Science curricula (Data Structures & Algorithms, Software Engineering), advanced Mathematics (Calculus I–III, Linear Algebra), and foundational courses in Philosophy and English.
        </div>
    </li>
</ul>


<style>
    /* ULTIMATE PRIMER THEME OVERRIDE: Targets the exact structural container structure that forces the header */
    .container-lg > h1,
    .container-lg > h1 a,
    .container-md > h1,
    header.site-header,
    .site-header,
    .page-header {
        display: none !important;
        opacity: 0 !important;
        height: 0 !important;
        padding: 0 !important;
        margin: 0 !important;
        visibility: hidden !important;
        pointer-events: none !important;
    }

    /* Smooth Scroll configuration */
    html {
        scroll-behavior: smooth;
        scroll-padding-top: 90px;
    }

    /* Beautiful Glassmorphism Floating Top Bar */
    .sticky-nav {
        position: -webkit-sticky; /* Safari support */
        position: sticky;
        top: 15px; 
        z-index: 1000;
        display: flex;
        justify-content: space-between;
        align-items: center;
        flex-wrap: wrap; 
        
        /* Glass styling */
        background-color: rgba(255, 255, 255, 0.8); 
        -webkit-backdrop-filter: blur(12px);
        backdrop-filter: blur(12px); 
        
        padding: 12px 24px;
        border: 1px solid rgba(225, 228, 232, 0.6); 
        border-radius: 12px; 
        box-shadow: 0 4px 20px rgba(0, 0, 0, 0.05); 
    }

    .nav-name {
        font-size: 1.25em;
        font-weight: 700;
        color: #24292f !important;
        letter-spacing: -0.3px;
    }

    /* Desktop Navigation link configuration */
    .nav-links {
        display: flex;
        align-items: center;
    }

    .nav-links a {
        margin-left: 20px;
        font-size: 0.93em;
        font-weight: 600;
        color: #57606a !important;
        text-decoration: none !important;
        transition: all 0.2s ease-in-out;
    }

    .nav-links a:hover {
        color: #0366d6 !important;
    }

    /* Hiding toggle logic mechanics on Desktop layouts */
    .nav-toggle {
        display: none;
    }
    
    .nav-toggle-label {
        display: none;
        cursor: pointer;
        flex-direction: column;
        justify-content: space-between;
        width: 22px;
        height: 16px;
    }

    .nav-toggle-label span {
        display: block;
        height: 2px;
        width: 100%;
        background-color: #24292f;
        border-radius: 2px;
        transition: all 0.2s ease-in-out;
    }

    /* MOBILE SPECIFIC MEDIA QUERY RENDERING */
    @media screen and (max-width: 768px) {
        .nav-toggle-label {
            display: flex; 
        }

        .nav-links {
            display: none; 
            flex-direction: column;
            width: 100%;
            margin-top: 15px;
            padding-top: 5px;
            border-top: 1px solid rgba(225, 228, 232, 0.4);
        }

        .nav-links a {
            margin: 10px 0;
            margin-left: 0;
            width: 100%;
            font-size: 1.05em;
        }

        .nav-toggle:checked ~ .nav-links {
            display: flex;
        }

        .nav-toggle:checked ~ .nav-toggle-label span:nth-child(1) {
            transform: translateY(7px) rotate(45deg);
        }
        .nav-toggle:checked ~ .nav-toggle-label span:nth-child(2) {
            opacity: 0;
        }
        .nav-toggle:checked ~ .nav-toggle-label span:nth-child(3) {
            transform: translateY(-7px) rotate(-45deg);
        }
    }

    /* Global layout color unification */
    body, p, li, div {
        color: #24292f !important;
    }
    
    p a, li a, div a:not([style*="background-color"]) {
        color: #0366d6 !important;
        text-decoration: none !important;
    }
    p a:hover, li a:hover, div a:hover {
        text-decoration: underline !important;
    }
</style>