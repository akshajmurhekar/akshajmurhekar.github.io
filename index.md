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
        <a href="#projects">Projects</a>
        <a href="#awards">Awards</a>
        <a href="#ta">TA & Mentoring</a>
    </div>
</div>

<!-- INTRO & INTERESTS BLOCK: Headshot Left Column with Links underneath / Content Right Column -->
<div id="about" style="display: flex; flex-wrap: wrap; justify-content: center; align-items: center; gap: 40px; margin-bottom: 35px; margin-top: 40px;">
    
    <!-- Left Column: Centered Image & Contact Links (Inspired by Screenshot 2026-06-15 at 2.38.53 PM.jpg) -->
    <div style="flex-shrink: 0; width: 300px; max-width: 100%; display: flex; flex-direction: column; align-items: center; text-align: center;">
        <img src="assets/headshot.png" alt="Akshaj Murhekar" style="width: 100%; border-radius: 8px; margin-bottom: 20px; background: transparent !important; border: none !important; padding: 0 !important;">
        
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


## Teaching Assistantships & Mentorship {#ta}

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

<!-- FOOTER DIVIDER LINE -->
<hr style="border: 0; border-top: 1px solid rgba(225, 228, 232, 0.4); margin: 50px 0 20px 0;">

<!-- FOOTER CONTAINER -->
<div style="display: flex; flex-wrap: wrap; justify-content: space-between; align-items: center; gap: 15px; padding-bottom: 30px; font-size: 0.88em; color: #57606a;">
    
    <!-- Left Side: Branding, UT Logo asset, and Copyright -->
    <div style="display: flex; align-items: center; gap: 10px;">
        <img src="assets/longhorn-icon.svg" alt="UT Austin Logo" style="width: 18px; height: auto; background: transparent !important; border: none !important; padding: 0 !important; margin: 0 !important; box-shadow: none !important;">
        <span>&copy; 2026 Akshaj Murhekar. All rights reserved.</span>
    </div>
    
    <!-- Right Side: Discreet View Counter Badge -->
    <div style="display: flex; align-items: center; gap: 6px; font-size: 0.95em;">
        <span style="color: #8c95a0;">Views:</span>
        <!-- Dynamic Hit Counter Badge -->
        <img src="https://hitcounter.pythonanywhere.com/count/tag.svg?url=https%3A%2F%2Fakshajmurhekar.github.io" alt="Hits" style="height: 18px; background: transparent !important; border: none !important; padding: 0 !important; margin: 0 !important; box-shadow: none !important; filter: grayscale(100%) opacity(0.75);">
    </div>
</div>


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

    /* Normalizes the sizing, resets theme-forced backgrounds, and sets gray tone */
    .profile-icon {
        width: 20px !important;
        height: 20px !important;
        background: transparent !important; /* Strips out the gray box in Screenshot 2026-06-15 at 3.05.22 PM.png */
        border: none !important;            /* Strips out any forced theme border outlines */
        padding: 0 !important;              /* Strips layout spacing bloating */
        margin: 0 !important;
        box-shadow: none !important;
        filter: invert(38%) sepia(8%) saturate(638%) hue-rotate(173deg) brightness(93%) contrast(89%); 
        transition: filter 0.2s ease-in-out;
    }

    /* Smooth transition over to matching link blue (#0366d6) on cursor hover */
    .profile-icon-link:hover .profile-icon {
        filter: invert(31%) sepia(89%) saturate(2304%) hue-rotate(204deg) brightness(91%) contrast(98%) !important; 
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
    div a.profile-icon-link:hover {
    color: transparent !important;
    text-decoration: none !important;
    background: transparent !important;
}
</style>