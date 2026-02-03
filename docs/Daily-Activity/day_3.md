---
glightbox: false
---

<style>
.activity-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

.main-header {
    text-align: center;
    font-size: 2.8em;
    font-weight: bold;
    color: #2c3e50;
    margin-bottom: 15px;
}

.sub-header {
    text-align: center;
    font-size: 2em;
    color: #546e7a;
    margin-bottom: 20px;
    font-weight: 600;
}

.project-subtitle {
    text-align: center;
    font-size: 1.3em;
    color: #78909c;
    margin-bottom: 40px;
    font-style: italic;
}

.content-card {
    background: linear-gradient(to right, #e8f5e9 0%, #e3f2fd 100%);
    border-left: 5px solid #4caf50;
    border-radius: 10px;
    padding: 35px;
    margin-bottom: 30px;
    box-shadow: 0 3px 10px rgba(0,0,0,0.1);
}

.content-card.purple {
    background: linear-gradient(to right, #f3e5f5 0%, #e1bee7 100%);
    border-left-color: #9c27b0;
}

.content-card.blue {
    background: linear-gradient(to right, #e3f2fd 0%, #bbdefb 100%);
    border-left-color: #2196f3;
}

.content-card.orange {
    background: linear-gradient(to right, #fff3e0 0%, #ffe0b2 100%);
    border-left-color: #ff9800;
}

.content-card.teal {
    background: linear-gradient(to right, #e0f2f1 0%, #b2dfdb 100%);
    border-left-color: #009688;
}

.content-card.indigo {
    background: linear-gradient(to right, #e8eaf6 0%, #c5cae9 100%);
    border-left-color: #3f51b5;
}

.content-card.red {
    background: linear-gradient(to right, #ffebee 0%, #ffcdd2 100%);
    border-left-color: #e53935;
}

.section-title {
    font-size: 1.8em;
    font-weight: 600;
    color: #2c3e50;
    margin-bottom: 20px;
    margin-top: 0;
}

.bullet-list {
    list-style: none;
    padding-left: 0;
}

.bullet-list li {
    padding: 12px 0;
    padding-left: 30px;
    position: relative;
    color: #424242;
    font-size: 1.05em;
    line-height: 1.6;
}

.bullet-list li:before {
    /* content: "●"; */
    color: #4caf50;
    font-weight: bold;
    position: absolute;
    left: 0;
    font-size: 1.3em;
}

.highlight-text {
    background: linear-gradient(120deg, #84fab0 0%, #8fd3f4 100%);
    padding: 2px 6px;
    border-radius: 3px;
    font-weight: 500;
}

.spec-box {
    background: rgba(255, 255, 255, 0.6);
    border-radius: 8px;
    padding: 20px;
    margin: 20px 0;
}

.spec-box p {
    margin: 10px 0;
    font-size: 1.05em;
}

.image-container {
    text-align: center;
    margin: 25px 0;
}

.image-container img {
    max-width: 100%;
    border-radius: 8px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.15);
}

.image-caption {
    font-style: italic;
    color: #666;
    margin-top: 10px;
    font-size: 0.95em;
}

.divider {
    height: 2px;
    background: linear-gradient(to right, #4caf50, #2196f3);
    margin: 40px 0;
    border-radius: 2px;
}

.image-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 25px;
    margin: 30px 0;
}

.image-grid-item {
    background: white;
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 3px 10px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
}

.image-grid-item:hover {
    transform: translateY(-5px);
    box-shadow: 0 5px 15px rgba(0,0,0,0.2);
}

.image-grid-item img {
    width: 100%;
    border-radius: 8px;
}

.badge {
    display: inline-block;
    background: #4caf50;
    color: white;
    padding: 5px 15px;
    border-radius: 20px;
    font-size: 0.9em;
    font-weight: 600;
    margin: 5px 5px 5px 0;
}

.badge.blue {
    background: #2196f3;
}

.badge.orange {
    background: #ff9800;
}

.badge.purple {
    background: #9c27b0;
}
</style>

<div class="activity-container">

<h1 class="main-header">Activity of Day 3</h1>
<h2 class="sub-header">Single-Sided Microcontroller PCB Design (KiCad)</h2>
<p class="project-subtitle">ATtiny45 LED Control with Push Button & ISP Programming</p>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">Objective</h2>
    <p>The objective of this activity is to design a single-sided PCB using KiCad based on a real microcontroller system.</p>
    
    <div class="spec-box">
        <p><strong>Students will create a board that:</strong></p>
        <ul class="bullet-list">
            <li>Uses an <strong>ATtiny45 microcontroller</strong></li>
            <li>Controls an <strong>LED using a push button</strong></li>
            <li>Can be programmed via a <strong>6-pin ISP header</strong></li>
            <li>Is suitable for <strong>PCB milling</strong> and <strong>hand soldering</strong></li>
        </ul>
    </div>
    
    <p style="font-size: 1.1em; margin-top: 20px;">This is a <strong>complete embedded system design</strong>, not a demo circuit.</p>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">Functional Description</h2>
    
    <div style="margin: 20px 0;">
        <span class="badge">ATtiny45</span>
        <span class="badge blue">5V Operation</span>
        <span class="badge orange">ISP Programming</span>
        <span class="badge purple">LED Control</span>
    </div>
    
    <ul class="bullet-list">
        <li>The <strong>ATtiny45 runs at 5V</strong></li>
        <li>The <strong>LED turns ON when the push button is pressed</strong></li>
        <li>The program is uploaded using an <strong>ISP programmer</strong></li>
        <li>The board is powered using an <strong>external 5V connector</strong></li>
    </ul>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">Design Diagrams & Documentation</h2>
    
    <div class="image-grid">
        <div class="image-grid-item">
            <img src="../images/day_3/Fab_Lab_Again_PCB.png" alt="PCB Schematic">
            <p class="image-caption">PCB Schematic Design</p>
        </div>
        
        <div class="image-grid-item">
            <img src="../images/day_3/Fab_Lab_Again_PCB_2.png" alt="PCB Layout">
            <p class="image-caption">PCB Layout View</p>
        </div>
        
        <div class="image-grid-item">
            <img src="../images/day_3/Fab_Lab_Again_PCB_22.jpg" alt="3D Render">
            <p class="image-caption">3D Board Visualization</p>
        </div>
        
        <div class="image-grid-item">
            <img src="../images/day_3/Fab_Lab_Again_PCB_224.jpg" alt="Component Placement">
            <p class="image-caption">Component Placement</p>
        </div>
        
        <div class="image-grid-item">
            <img src="../images/day_3/Fab_Lab_Again_PCB_2246.jpg" alt="Final Design">
            <p class="image-caption">Final PCB Design</p>
        </div>
    </div>
</div>

</div>

<p style="clear: both;"></p>
<br/>