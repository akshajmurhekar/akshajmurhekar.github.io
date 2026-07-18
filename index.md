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

    <!-- Hidden Checkbox remains at the top level -->
    <input type="checkbox" id="nav-toggle" class="nav-toggle">
    
    <!-- Right Side Global Control Bar -->
    <div class="nav-controls">
        <!-- Theme Toggle Button -->
        <button id="theme-toggle" class="theme-toggle" aria-label="Toggle dark mode" title="Toggle theme">
            <svg class="sun-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                <circle cx="12" cy="12" r="5"></circle>
                <line x1="12" y1="1" x2="12" y2="3"></line>
                <line x1="12" y1="21" x2="12" y2="23"></line>
                <line x1="4.22" y1="4.22" x2="5.64" y2="5.64"></line>
                <line x1="18.36" y1="18.36" x2="19.78" y2="19.78"></line>
                <line x1="1" y1="12" x2="3" y2="12"></line>
                <line x1="21" y1="12" x2="23" y2="12"></line>
                <line x1="4.22" y1="19.78" x2="5.64" y2="18.36"></line>
                <line x1="18.36" y1="5.64" x2="19.78" y2="4.22"></line>
            </svg>
            <svg class="moon-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                <path d="M21 12.79A9 9 0 1 1 11.21 3 7 7 0 0 0 21 12.79z"></path>
            </svg>
        </button>

        <!-- Hamburger Label -->
        <label for="nav-toggle" class="nav-toggle-label">
            <span></span>
            <span></span>
            <span></span>
        </label>
    </div>

    <!-- Menu Links -->
    <div class="nav-links">
        <a href="#about">About</a>
        <a href="#research">Research</a>
        <a href="#education">Education</a>
        <a href="#projects">Projects</a>
        <a href="#awards">Awards</a>
        <a href="#ta">TA & Mentoring</a>
    </div>
</div>

<!-- INTRO & INTERESTS BLOCK: Headshot Left Column with Links underneath / Content Right Column -->
<div id="about" style="display: flex; flex-wrap: wrap; justify-content: center; align-items: center; gap: 40px; margin-bottom: 35px; margin-top: 40px;">
    
    <!-- Left Column: Centered Image & Contact Links (Inspired by Screenshot 2026-06-15 at 2.38.53 PM.jpg) -->
    <div style="flex-shrink: 0; width: 300px; max-width: 100%; display: flex; flex-direction: column; align-items: center; text-align: center;">
        <img src="assets/headshot.webp" alt="Akshaj Murhekar" style="width: 100%; border-radius: 8px; margin-bottom: 20px; background: transparent !important; border: none !important; padding: 0 !important;">
        
        <!-- Clean Row of Normalized Favicons from your local assets -->
        <div style="display: flex; justify-content: center; align-items: center; gap: 22px; margin-bottom: 14px;">
            <!-- Google Scholar -->
            <a href="https://scholar.google.com/citations?user=iObTPf8AAAAJ" target="_blank" title="Google Scholar" class="profile-icon-link">
                <img src="assets/icons/scholar.svg" alt="Google Scholar" class="profile-icon">
            </a>

            <!-- LinkedIn -->
            <a href="https://linkedin.com/in/akshaj-murhekar" target="_blank" title="LinkedIn" class="profile-icon-link">
                <img src="assets/icons/linkedin.svg" alt="LinkedIn" class="profile-icon">
            </a>

            <!-- GitHub -->
            <a href="https://github.com/akshajmurhekar" target="_blank" title="GitHub" class="profile-icon-link">
                <img src="assets/icons/github.svg" alt="GitHub" class="profile-icon">
            </a>

            <!-- Document / CV (Placeholder link) -->
            <a href="#" onclick="return false;" title="Curriculum Vitae" class="profile-icon-link">
                <img src="assets/icons/cv.svg" alt="CV" class="profile-icon">
            </a>
        </div>
        
        <!-- Email Link Block with Normalized Envelope Favicon -->
        <div style="display: inline-flex; align-items: center; justify-content: center; gap: 8px; font-size: 0.93em;">
            <img src="assets/icons/email.svg" alt="Email" class="profile-icon" style="width: 16px; height: 16px;">
            <a href="mailto:akshaj.murhekar@utexas.edu" style="font-weight: 500; color: #0366d6; text-decoration: none;">akshaj.murhekar@utexas.edu</a>
        </div>
    </div>

    <!-- Right Column: Bio Paragraph & Research Interests -->
    <div style="flex: 1; min-width: 280px; line-height: 1.6;">
        <p style="margin: 0; margin-bottom: 24px; color: #24292f; text-align: justify;">
            I am a graduate researcher at UT Austin with a focus on language modeling, representation learning, and multimodal deep learning. During my time as an M.S. student, I worked with <a href="https://abhijitmishra.github.io/" target="_blank">Dr. Abhijit Mishra</a> on challenging problems at the intersection of language models and neural signal processing. My research focused on leveraging in-context learning capabilities of Large Language Models (LLMs). Specifically, I developed privacy-preserving neuro-symbolic decoding pipelines and efficient retrieval frameworks designed to bridge the gap between brain activity and text, translating electroencephalography (EEG) signals directly into natural language.
        </p>

        <h3 style="font-size: 1.15em; font-weight: 600; color: var(--text-primary); margin-bottom: 10px;">Research Interests</h3>
        <ul style="line-height: 1.7; padding-left: 20px; color: #24292f; margin: 0;">
            <li style="margin-bottom: 4px;"><strong>Multimodal Deep Learning</strong></li>
            <li style="margin-bottom: 4px;"><strong>Neuro-Symbolic Learning</strong></li>
            <li style="margin-bottom: 4px;"><strong>Sparse & Efficient Architectures</strong></li>
            <li style="margin-bottom: 4px;"><strong>LLM Evaluation & Behavioral Alignment</strong></li>
        </ul>
    </div>
</div>

<!-- BEAUTIFIED NEWS TIMELINE CARD WITH ROTATING GRADIENT BORDER -->
<div class="news-shadow-container" style="margin-top: 40px; margin-bottom: 45px;">
    <div class="news-card-wrapper" style="margin: 0;">
        <div class="news-card-content">
            <!-- Header section: Clean text, no pill background -->
            <h3 style="font-size: 1.15em; font-weight: 700; color: var(--text-primary); margin: 0 0 20px 0; text-transform: uppercase; letter-spacing: 0.5px;">
                News & Updates
            </h3>
            
            <div class="news-timeline-list">
                <!-- Entry 1 -->
                <div class="news-timeline-item border-bottom-dashed">
                    <div class="news-date-wrapper">
                        <span class="news-date-pill pill-orange">Jul 2026</span>
                    </div>
                    <div class="news-text-content">
                        Our paper <strong style="color: var(--text-link);">SENSE</strong> was officially accepted to <strong>ICMI 2026</strong> @ Naples, Italy! 🇮🇹
                    </div>
                </div>
                
                <!-- Entry 2 -->
                <div class="news-timeline-item">
                    <div class="news-date-wrapper">
                        <span class="news-date-pill pill-gray">May 2026</span>
                    </div>
                    <div class="news-text-content">
                        Graduated with an M.S. in Information Science from <strong>The University of Texas at Austin</strong>.
                    </div>
                </div>
            </div>
        </div>
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
        <img src="assets/longhorn-icon.svg" alt="UT Austin Logo" style="width: 120px; height: auto;">
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


## Teaching Assistantships & Mentorship {#ta}

### Research Mentorship
<ul style="line-height: 1.7; padding-left: 20px; color: #24292f; margin-bottom: 24px;">
    <li style="margin-bottom: 12px;">
        <!-- Standardized Flexbox wrapping container to handle mobile drop-downs cleanly -->
        <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: baseline;">
            <span><strong>Undergraduate Research Mentor</strong> &middot; UT Austin</span>
            <span style="font-size: 0.95em; color: #57606a; font-weight: 500;">2025 &ndash; 2026</span>
        </div>
        <ul style="font-size: 0.95em; color: #57606a; margin-top: 6px; padding-left: 20px; list-style-type: disc;">
            <li style="margin-bottom: 4px;">Mentored an undergraduate researcher, <a href="https://www.linkedin.com/in/christinal-iu/" target="_blank">Christina Liu</a>, on advanced multimodal machine learning frameworks, directly leading to her co-authorship on our SENSE paper (ICMI 2026).</li>
            <li style="margin-bottom: 4px;">Guided her through foundational research methodologies, from navigating complex neuro-signal processing literature to structuring rigorous experimental workflows.</li>
            <li style="margin-bottom: 0px;">Provided technical and academic direction, helping translate deep learning concepts into practice and supporting the completion of her Honors Bachelor's Thesis.</li>
        </ul>
    </li>
</ul>

### Teaching & Tutoring
<ul style="line-height: 1.7; padding-left: 20px; color: #24292f; margin-bottom: 35px;">
    <li style="margin-bottom: 12px;">
        <!-- Standardized Flexbox wrapping container to handle mobile drop-downs cleanly -->
        <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: baseline;">
            <span><strong>Graduate Teaching Assistant</strong> &middot; UT Austin</span>
            <span style="font-size: 0.95em; color: #57606a; font-weight: 500;">2025</span>
        </div>
        <div style="font-size: 0.95em; color: #57606a; margin-top: 2px;">
            Served as a Graduate TA across distinct academic disciplines, including Statistics and Academic Writing courses. Held weekly office hours to assist students with core course material, managed evaluation frameworks, and guided students through complex coursework requirements.
        </div>
    </li>
    <li style="margin-bottom: 8px;">
        <!-- Standardized Flexbox wrapping container to handle mobile drop-downs cleanly -->
        <div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: baseline;">
            <span><strong>Undergraduate Academic Tutor</strong> &middot; UT Arlington</span>
            <span style="font-size: 0.95em; color: #57606a; font-weight: 500;">2022 &ndash; 2024</span>
        </div>
        <div style="font-size: 0.95em; color: #57606a; margin-top: 2px;">
            Provided high-impact 1-on-1 and drop-in academic instruction across multiple departments. Covered core Computer Science curricula (Data Structures & Algorithms, Software Engineering), advanced Mathematics (Calculus I–III, Linear Algebra), and foundational courses in Philosophy and English.
        </div>
    </li>
</ul>

<!-- FOOTER DIVIDER LINE -->
<hr style="border: 0; border-top: 1px solid rgba(225, 228, 232, 0.4); margin: 50px 0 20px 0;">

<!-- FOOTER CONTAINER -->
<div class="site-footer">
    
    <!-- Left Side: Branding, UT Logo asset, and Copyright -->
    <div style="display: flex; align-items: center; gap: 10px;">
        <img src="assets/longhorn-icon.svg" alt="UT Austin Logo" style="width: 18px; height: auto; background: transparent !important; border: none !important; padding: 0 !important; margin: 0 !important; box-shadow: none !important;">
        <span>&copy; 2026 Akshaj Murhekar. All rights reserved.</span>
    </div>
    
    <!-- Right Side: Discreet Unique View Counter Badge -->
    <div style="display: flex; align-items: center; gap: 6px; font-size: 0.88em; color: #57606a;">
        <span>Views:</span>
        <span id="portfolio-views" style="display: inline-block; padding: 2px 8px; background-color: #BF5700; color: #ffffff; font-weight: 600; font-size: 0.9em; border-radius: 4px; min-width: 12px; text-align: center;">...</span>
    </div>

    <script>
        (async function() {
            const viewPill = document.getElementById('portfolio-views');
            const storageKey = 'akshajmurhekar_github_io_main_page_v2';
            const hasVisited = sessionStorage.getItem('has_visited_portfolio_session');

            try {
                let url = hasVisited 
                    ? `https://countapi.mileshilliard.com/api/v1/get/${storageKey}`
                    : `https://countapi.mileshilliard.com/api/v1/hit/${storageKey}`;
                
                if (!hasVisited) sessionStorage.setItem('has_visited_portfolio_session', 'true');

                const response = await fetch(url);
                if (response.ok) {
                    const data = await response.json();
                    viewPill.innerText = data.value;
                } else {
                    viewPill.innerText = '1';
                }
            } catch (error) {
                viewPill.innerText = '1';
            }
        })();
    </script>
</div>

<style>
    /* ===== CSS VARIABLES FOR LIGHT MODE (DEFAULT) ===== */
    :root {
        --bg-primary: #ffffff;
        --bg-secondary: #f6f8fa;
        --bg-glass: rgba(255, 255, 255, 0.8);
        --bg-glass-border: rgba(225, 228, 232, 0.6);
        --bg-glass-shadow: rgba(0, 0, 0, 0.05);
        --bg-news-card: #ffffff;
        --bg-badge: #BF5700;
        --bg-tag: #f1f2f4;
        --text-primary: #24292f;
        --text-secondary: #57606a;
        --text-link: #0366d6;
        --text-link-hover: #0550ae;
        --accent-orange: #BF5700;
        --accent-blue: #0366d6;
        --border-subtle: rgba(225, 228, 232, 0.4);
        --border-tag: #e1e4e8;
        --shadow-news: rgba(0, 0, 0, 0.04), rgba(0, 0, 0, 0.08);
        --shadow-glass: 0 4px 20px rgba(0, 0, 0, 0.05);
        --icon-filter: invert(38%) sepia(8%) saturate(638%) hue-rotate(173deg) brightness(93%) contrast(89%);
        --icon-filter-hover: invert(31%) sepia(89%) saturate(2304%) hue-rotate(204deg) brightness(91%) contrast(98%);
        --gradient-1: #BF5700;
        --gradient-2: #0366d6;
        --gradient-3: #ff8f3d;
        --transition-speed: 0.3s;
    }

    /* ===== DARK MODE VARIABLES ===== */
    [data-theme="dark"] {
        --bg-primary: #0d1117;
        --bg-secondary: #161b22;
        --bg-glass: rgba(22, 27, 34, 0.85);
        --bg-glass-border: rgba(48, 54, 61, 0.6);
        --bg-glass-shadow: rgba(0, 0, 0, 0.3);
        --bg-news-card: #161b22;
        --bg-badge: #ff8f3d;
        --bg-tag: #21262d;
        --text-primary: #e6edf3;
        --text-secondary: #8b949e;
        --text-link: #58a6ff;
        --text-link-hover: #79c0ff;
        --accent-orange: #ff8f3d;
        --accent-blue: #58a6ff;
        --border-subtle: rgba(48, 54, 61, 0.4);
        --border-tag: #30363d;
        --shadow-news: rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.5);
        --shadow-glass: 0 4px 20px rgba(0, 0, 0, 0.4);
        --icon-filter: invert(84%) sepia(10%) saturate(0%) hue-rotate(180deg) brightness(95%) contrast(90%);
        --icon-filter-hover: invert(60%) sepia(50%) saturate(500%) hue-rotate(190deg) brightness(110%) contrast(100%);
        --gradient-1: #ff8f3d;
        --gradient-2: #58a6ff;
        --gradient-3: #BF5700;
    }

    /* ===== THEME TRANSITION ===== */
    body,
    .sticky-nav,
    .news-card-content,
    .news-shadow-container,
    body > *,
    body p, body li, body div, body span, body a, body h1, body h2, body h3 {
        transition: background-color var(--transition-speed) ease, color var(--transition-speed) ease, border-color var(--transition-speed) ease, box-shadow var(--transition-speed) ease;
    }

    body {
        background-color: var(--bg-primary);
    }

    .site-footer {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        align-items: center;
        gap: 15px;
        padding-bottom: 30px;
        font-size: 0.88em;
        color: #57606a;
    }

    @media screen and (max-width: 768px) {
        .site-footer {
            flex-direction: column;
            justify-content: center;
            text-align: center;
            gap: 12px;
        }
        .site-footer > div {
            justify-content: center;
        }
    }

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

    .profile-icon {
        width: 20px !important;
        height: 20px !important;
        background: transparent !important;
        border: none !important;
        padding: 0 !important;
        margin: 0 !important;
        box-shadow: none !important;
        filter: invert(38%) sepia(8%) saturate(638%) hue-rotate(173deg) brightness(93%) contrast(89%); 
        transition: filter 0.2s ease-in-out;
    }

    .profile-icon-link:hover .profile-icon {
        filter: invert(31%) sepia(89%) saturate(2304%) hue-rotate(204deg) brightness(91%) contrast(98%) !important; 
    }

    html {
        scroll-behavior: smooth;
        scroll-padding-top: 90px;
    }

    .sticky-nav {
        position: -webkit-sticky;
        position: sticky;
        top: 15px;
        z-index: 1000;
        display: flex;
        justify-content: space-between;
        align-items: center;
        background-color: var(--bg-glass);
        -webkit-backdrop-filter: blur(12px);
        backdrop-filter: blur(12px);
        padding: 12px 24px;
        border: 1px solid var(--bg-glass-border);
        border-radius: 12px;
        box-shadow: var(--shadow-glass);
    }

    .nav-name {
        font-size: 1.25em;
        font-weight: 700;
        color: var(--text-primary) !important;
        letter-spacing: -0.3px;
    }

    /* Desktop alignment overrides */
    .nav-links {
        display: flex;
        align-items: center;
        margin-left: auto; /* Pushes links to the right side next to controls */
    }

    .nav-controls {
        display: flex;
        align-items: center;
        gap: 15px;
        order: 3; /* Ensures it stays at the end of the flex layout */
        margin-left: 20px;
    }

    .nav-links a {
        margin-left: 20px;
        font-size: 0.93em;
        font-weight: 600;
        color: var(--text-secondary) !important;
        text-decoration: none !important;
        transition: color 0.2s ease-in-out;
    }

    .nav-links a:hover {
        color: var(--text-link) !important;
    }

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
        background-color: var(--text-primary);
        border-radius: 2px;
        transition: all 0.2s ease-in-out;
    }

    /* ===== THEME TOGGLE BUTTON ===== */
    .theme-toggle {
        margin-left: 20px;
        background: var(--bg-tag);
        border: 1px solid var(--border-tag);
        border-radius: 8px;
        padding: 6px 8px;
        cursor: pointer;
        display: flex;
        align-items: center;
        justify-content: center;
        transition: all 0.2s ease-in-out;
        color: var(--text-secondary);
    }

    .theme-toggle:hover {
        background: var(--bg-secondary);
        border-color: var(--text-secondary);
        color: var(--text-primary);
        transform: scale(1.05);
    }

    .theme-toggle svg {
        width: 18px;
        height: 18px;
        transition: all var(--transition-speed) ease;
    }

    .sun-icon {
        display: block;
    }

    .moon-icon {
        display: none;
    }

    [data-theme="dark"] .sun-icon {
        display: none;
    }

    [data-theme="dark"] .moon-icon {
        display: block;
    }

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
        /* FIX: Selects the sibling nav-links when nav-toggle is checked */
        .nav-toggle:checked ~ .nav-links {
            display: flex;
        }
        .nav-toggle:checked ~ .nav-controls .nav-toggle-label span:nth-child(1) {
            transform: translateY(7px) rotate(45deg);
        }
        .nav-toggle:checked ~ .nav-controls .nav-toggle-label span:nth-child(2) {
            opacity: 0;
        }
        .nav-toggle:checked ~ .nav-controls .nav-toggle-label span:nth-child(3) {
            transform: translateY(-7px) rotate(-45deg);
        }
        .theme-toggle {
            margin-left: 0;
            padding: 4px 6px;
        }
    }

    body, p, li, div, span {
        color: var(--text-primary) !important;
    }

    p a, li a, div a:not([style*="background-color"]) {
        color: var(--text-link) !important;
        text-decoration: none !important;
    }
    p a:hover, li a:hover, div a:hover {
        text-decoration: underline !important;
        color: var(--text-link-hover) !important;
    }
    div a.profile-icon-link:hover {
        color: transparent !important;
        text-decoration: none !important;
        background: transparent !important;
    }

    /* Define a custom property that browser animation engines can interpolate as an angle */
    @property --gradient-angle {
        syntax: '<angle>';
        initial-value: 0deg;
        inherits: false;
    }

    /* FIX: Unclipped outer shadow container */
    .news-shadow-container {
        position: relative;
        border-radius: 12px;
        box-shadow: var(--shadow-news);
    }

    /* Inner layout container with animated gradient border */
    .news-card-wrapper {
        position: relative;
        border-radius: 12px;
        padding: 1px; /* The border thickness */
        /* Dynamically updates the gradient angle based on the CSS variable */
        background: conic-gradient(
            from var(--gradient-angle),
            var(--gradient-1) 0deg,
            var(--gradient-2) 120deg,
            var(--gradient-3) 240deg,
            var(--gradient-1) 360deg
        );
        animation: spin-gradient-clean 6s linear infinite;
    }

    .news-card-content {
        position: relative;
        z-index: 1;
        background: var(--bg-news-card);
        border-radius: 11px;
        padding: 20px 24px;
    }

    .news-badge {
        display: inline-block;
        padding: 3px 10px;
        background-color: var(--bg-badge);
        color: #ffffff !important;
        font-weight: 700;
        font-size: 0.82em;
        text-transform: uppercase;
        letter-spacing: 0.5px;
        border-radius: 20px;
    }

    /* Clean animation targeting just the angle variable */
    @keyframes spin-gradient-clean {
        0% {
            --gradient-angle: 0deg;
        }
        100% {
            --gradient-angle: 360deg;
        }
    }

    /* ===== INLINE-STYLE OVERRIDES FOR DARK MODE ===== */
    [data-theme="dark"] .profile-icon {
        filter: var(--icon-filter) !important;
    }

    [data-theme="dark"] .profile-icon-link:hover .profile-icon {
        filter: var(--icon-filter-hover) !important;
    }

    [data-theme="dark"] .news-badge {
        color: #0d1117 !important;
    }

    [data-theme="dark"] hr {
        border-top-color: var(--border-subtle) !important;
    }

    /* Tag buttons (arXiv, PDF, Code) */
    [data-theme="dark"] a[style*="background-color: #f1f2f4"] {
        background-color: var(--bg-tag) !important;
        border-color: var(--border-tag) !important;
    }

    /* UT Logo SVGs */
    [data-theme="dark"] img[src*="ut-"],
    [data-theme="dark"] img[src*="longhorn"] {
        filter: brightness(0.8) contrast(1.2);
    }

    /* Headshot */
    [data-theme="dark"] img[src*="headshot"] {
        filter: brightness(0.95) contrast(1.05);
    }

    /* Fix white background blocks around SVGs in education section */
    img[src*=".svg"] {
        mix-blend-mode: multiply;
    }

    [data-theme="dark"] img[src*=".svg"] {
        mix-blend-mode: screen;
        /* Optional: turns dark vectors white/silver so they are visible on dark background */
        filter: invert(0.9) hue-rotate(180deg); 
    }

    /* Smooth interaction style for the news card container */
    .news-shadow-container {
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .news-shadow-container:hover {
        transform: translateY(-3px);
        box-shadow: 0 10px 30px rgba(0, 0, 0, 0.12);
    }

    [data-theme="dark"] .news-shadow-container:hover {
        box-shadow: 0 10px 30px rgba(0, 0, 0, 0.6);
    }

    /* Container Layouts */
    .news-timeline-list {
        display: flex;
        flex-direction: column;
        gap: 16px;
    }

    .news-timeline-item {
        display: flex;
        flex-direction: row;
        align-items: flex-start;
    }

    .border-bottom-dashed {
        padding-bottom: 16px;
        border-bottom: 1px dashed var(--border-subtle);
    }

    /* Date Pill Box Alignment */
    .news-date-wrapper {
        flex-shrink: 0;
        width: 85px;
        display: flex;
    }

    .news-date-pill {
        font-size: 0.85em;
        font-weight: 700;
        color: #ffffff !important;
        padding: 4px 10px;
        border-radius: 6px;
        white-space: nowrap;
        text-align: center;
        width: 100%;
    }

    .pill-orange {
        background-color: #BF5700;
        box-shadow: 0 2px 4px rgba(191, 87, 0, 0.2);
    }

    .pill-gray {
        background-color: var(--text-secondary);
    }

    [data-theme="dark"] .pill-gray {
        background-color: var(--bg-tag);
        color: var(--text-primary) !important;
        border: 1px solid var(--border-tag);
    }

    /* Text Positioning */
    .news-text-content {
        flex: 1;
        line-height: 1.5;
        color: var(--text-primary);
        margin-left: 16px;
    }

    /* Interaction Effects */
    .news-shadow-container {
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .news-shadow-container:hover {
        transform: translateY(-3px);
        box-shadow: 0 10px 30px rgba(0, 0, 0, 0.12);
    }

    [data-theme="dark"] .news-shadow-container:hover {
        box-shadow: 0 10px 30px rgba(0, 0, 0, 0.6);
    }

    /* ===== MOBILE RESPONSIVE LAYOUT ===== */
    @media screen and (max-width: 768px) {
        .news-timeline-item {
            flex-direction: column;
            align-items: flex-start;
            gap: 8px; /* Clean gap between pill and text underneath */
        }
        
        .news-date-wrapper {
            width: auto; /* Drops fixed width layout constraints */
        }
        
        .news-text-content {
            margin-left: 0; /* Aligns text flush left with the pill element */
        }
    }
</style>

<script>
    (function() {
        // Theme toggle functionality
        const toggleBtn = document.getElementById('theme-toggle');
        const html = document.documentElement;

        // Check for saved preference or default to light
        const savedTheme = localStorage.getItem('theme') || 'light';
        html.setAttribute('data-theme', savedTheme);

        toggleBtn.addEventListener('click', function() {
            const currentTheme = html.getAttribute('data-theme');
            const newTheme = currentTheme === 'dark' ? 'light' : 'dark';
            html.setAttribute('data-theme', newTheme);
            localStorage.setItem('theme', newTheme);
        });
    })();
</script>