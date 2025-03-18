---
layout: page
title: Research
description: not much to show yet but I'm trying
image: 
nav-menu: true
---

<!-- Research Section -->
<div class="12u 12u$(medium)">
    <h3>Projects</h3>
    <ul>
        <li>
            <strong>Representation of Energy Flexibility with a Semantic Ontology</strong>, funded by PITA and Johnson Controls (05/2023 – present)
            <ul>
                <li>Aim: Facilitating application portability across building automation systems through machine-readable descriptions of physical environments with a specific focus on energy flexibility applications.</li>
            </ul>
        </li>
        <li>
            <strong>Leveraging Sensor Networks for Flexibility and Comfort</strong> (08/2022 – 08/2023)
            <ul>
                <li>Data Scale: Handled a large dataset involving 5-minute resolution data from 1000 houses, equipped with multiple sensors, for the year 2017.</li>
                <li>ML-Driven Analysis: Employed ML techniques for enhancing comfort in multi-room single-zone houses using smart thermostats and sensor data.</li>
                <li>Physics-Based Modeling: Applied physics-based ML algorithms to analyze and model energy dynamics in 100 residential units, each equipped with sensor networks comprising 6 nodes.</li>
            </ul>
        </li>
    </ul>
</div>

<!-- Publications Section -->
<div class="12u 12u$(medium)">
    <h3>Publications</h3>
    <div class="bubble-container">
        <!-- 2025 Publications -->
        <a href="http://arxiv.org/abs/2501.16368" class="bubble journal" target="_blank">
            <p><strong class="first-author">Baris, O.</strong>, Chen, Y., Dong, G., Han, L., Kimura, T., Quan, P., Wang, R., Wang, T., Abdelzaher, T., Bergés, M., Liang, P. P., & Srivastava, M. (2025). <em>Foundation Models for CPS-IoT: Opportunities and Challenges</em>.<br /> arXiv.</p>
        </a>
        <a href="https://openreview.net/forum?id=bmE39sqscK" class="bubble conference" target="_blank">
            <p><strong class="first-author">Quan, P., Mulayim, O. B.</strong>, Han, L., Hong, D., Bergés, M., & Srivastava, M. (2025). <em>Reimagining Time Series Foundation Models: Metadata and State-Space Model Perspectives</em>.<br /> NeurIPS Workshop on Time Series in the Age of Large Models.</p>
        </a>
        <a class="bubble conference" target="_blank">
            <p><strong class="first-author">Mulayim, O. B.</strong>, & Bergés, M. (2025). <em>On the Impact of Simulated Occupancy Behavior Assumptions on Reinforcement Learning for HVAC Controls</em>.<br /> Conference in Rotterdam, Netherlands.</p>
        </a>
        <a class="bubble conference" target="_blank">
            <p><strong class="first-author">Mulayim, O. B.</strong>, Fierro, G., Bergés, M., & Pritoni, M. (2025). <em>Towards Zero-shot Question Answering in CPS-IoT: Large Language Models and Knowledge Graphs</em>.<br /> The 2nd International Workshop on Foundation Models for CPS-IoT (Submitted).</p>
        </a>
        <!-- 2024 Publications -->
        <a href="https://www.cambridge.org/core/journals/data-centric-engineering/article/unmasking-the-role-of-remote-sensors-in-comfort-energy-and-demand-response/E16D3E3AE43075A636FABDAC25E6DFBF" class="bubble journal" target="_blank">
            <p><strong class="first-author">Mulayim, O. B.</strong>, Severnini, E., & Bergés, M. (2024). <em>Unmasking the Role of Remote Sensors in Comfort, Energy, and Demand Response</em>.<br /> Data-Centric Engineering.</p>
        </a>
        <a href="https://ieeexplore.ieee.org/abstract/document/10738056/" class="bubble conference" target="_blank">
            <p><strong class="first-author">Mulayim, O. B.</strong>, & Bergés, M. (2024). <em>Leveraging Grey Box Models for Enhanced Energy Flexibility in Centralized and Decentralized Single-Zone Multi-Node Systems</em>.<br /> IEEE International Conference on Communications, Control, and Computing Technologies for Smart Grids.</p>
        </a>
        <a href="https://dl.acm.org/doi/10.1145/3671127.3698792" class="bubble conference" target="_blank">
            <p><strong class="first-author">Mulayim, O. B.</strong>, Paul, L., Pritoni, M., Prakash, A. K., Sudarshan, M., & Fierro, G. (2024). <em>Large Language Models for the Creation and Use of Semantic Ontologies in Buildings: Requirements and Challenges</em>.<br /> ACM BuildSys.</p>
        </a>
        <a href="https://dl.acm.org/doi/10.1145/3671127.3698177" class="bubble conference" target="_blank">
            <p><strong class="first-author">Mulayim, O. B.</strong>, Quan, P., Han, L., Ouyang, X., Hong, D., Bergés, M., & Srivastava, M. (2024). <em>Are Time Series Foundation Models Ready to Revolutionize Predictive Building Analytics?</em><br /> ACM BuildSys.</p>
        </a>
        <a href="https://docs.lib.purdue.edu/cgi/viewcontent.cgi?article=1436&context=ihpbc" class="bubble conference" target="_blank">
            <p><strong class="first-author">Mulayim, O. B.</strong>, & Bergés, M. (2024). <em>Beyond Average: Evaluating Indoor Average Temperature in Grey Box Modeling</em>.<br /> International High Performance Buildings Conference.</p>
        </a>
        <a class="bubble conference" target="_blank">
            <p><strong class="first-author">Mulayim, O. B.</strong>, Qu, G., Kircher, K., & Bergés, M. (2024). <em>Physics-Informed RL for Real-World HVAC Controls: Lessons from Imitation to Deployment</em>.<br /> Reinforcement Learning Journal.</p>
        </a>
        <!-- 2023 Publications -->
        <a href="https://dl.acm.org/doi/10.1145/3600100.3623724" class="bubble conference" target="_blank">
            <p><strong class="first-author">Mulayim, O. B.</strong>, & Bergés, M. (2023). <em>Unmasking the Thermal Behavior of Single-Zone Multi-Room Houses: An Empirical Study</em>.<br /> ACM BuildSys.</p>
        </a>
    </div>
</div>


<style>
.bubble-container {
    display: flex;
    flex-direction: column;
    gap: 5px; /* Adjust the gap to reduce vertical distance between bubbles */
    align-items: center; /* Center align bubbles horizontally */
}

.bubble {
    display: block;
    padding: 5px 10px; /* Reduce padding to make bubbles shorter */
    border-radius: 15px;
    text-decoration: none;
    color: #000;
    width: 100%; /* Reset width to default */
    background-color: #f0f0f0;
    line-height: 1.2; /* Adjust line height for compactness */
}

.bubble:hover {
    background-color: #e0e0e0;
}

.journal {
    background-color: #d1e7dd;
}

.conference {
    background-color: #f0f0f0;
}

.first-author {
    color: #000; /* Ensure the bolded first author text is black */
}
</style>


