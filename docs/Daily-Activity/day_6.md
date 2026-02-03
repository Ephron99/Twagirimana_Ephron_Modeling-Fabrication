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
    margin-bottom: 40px;
    font-weight: 600;
}

.overview-section {
    text-align: center;
    font-size: 1.1em;
    color: #546e7a;
    margin-bottom: 40px;
    line-height: 1.8;
    max-width: 900px;
    margin-left: auto;
    margin-right: auto;
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

.content-card.red {
    background: linear-gradient(to right, #ffebee 0%, #ffcdd2 100%);
    border-left-color: #e53935;
}

.content-card.cyan {
    background: linear-gradient(to right, #e0f7fa 0%, #b2ebf2 100%);
    border-left-color: #00acc1;
}

.section-title {
    font-size: 1.8em;
    font-weight: 600;
    color: #2c3e50;
    margin-bottom: 20px;
    margin-top: 0;
}

.subsection-title {
    font-size: 1.4em;
    font-weight: 600;
    color: #37474f;
    margin-top: 25px;
    margin-bottom: 15px;
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

/* .highlight-text {
    background: linear-gradient(120deg, #84fab0 0%, #8fd3f4 100%);
    padding: 2px 6px;
    border-radius: 3px;
    font-weight: 500;
} */

.data-table {
    width: 100%;
    border-collapse: collapse;
    margin: 20px 0;
    background: white;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

.data-table thead {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
}

.data-table th {
    padding: 15px;
    text-align: left;
    font-weight: 600;
    font-size: 1.1em;
}

.data-table td {
    padding: 15px;
    border-bottom: 1px solid #e0e0e0;
}

.data-table tr:last-child td {
    border-bottom: none;
}

.data-table tbody tr:hover {
    background: #f5f5f5;
}

.divider {
    height: 2px;
    background: linear-gradient(to right, #4caf50, #2196f3);
    margin: 40px 0;
    border-radius: 2px;
}

.info-box {
    background: rgba(33, 150, 243, 0.1);
    border-left: 4px solid #2196f3;
    padding: 20px;
    margin: 20px 0;
    border-radius: 0 8px 8px 0;
}

.info-box-title {
    font-weight: bold;
    color: #2196f3;
    font-size: 1.1em;
    margin-bottom: 15px;
}

.warning-box {
    background: rgba(244, 67, 54, 0.1);
    border-left: 4px solid #f44336;
    padding: 20px;
    margin: 20px 0;
    border-radius: 0 8px 8px 0;
}

.warning-title {
    font-weight: bold;
    color: #f44336;
    font-size: 1.2em;
    margin-bottom: 15px;
    display: flex;
    align-items: center;
}

.warning-title:before {
    content: "⚠️";
    margin-right: 10px;
    font-size: 1.3em;
}

.phase-header {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 15px 25px;
    border-radius: 8px;
    margin: 30px 0 20px 0;
    font-size: 1.5em;
    font-weight: 600;
}

.step-card {
    background: rgba(255, 255, 255, 0.7);
    border-left: 4px solid #2196f3;
    padding: 25px;
    margin: 20px 0;
    border-radius: 0 8px 8px 0;
}

.step-title {
    font-size: 1.3em;
    font-weight: 600;
    color: #2196f3;
    margin-bottom: 15px;
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

.image-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
    gap: 30px;
    margin: 30px 0;
}

.image-grid-item {
    background: white;
    padding: 20px;
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
</style>

<div class="activity-container">

<h1 class="main-header">Activity of Day 6</h1>
<h2 class="sub-header">Ultimaker 3D Printer Operation</h2>

<div class="overview-section">
    <p>This documentation covers the operation of the <span class="highlight-text">Ultimaker</span> printer, which uses <span class="highlight-text">Fused Deposition Modeling (FDM)</span> technology. In this process, the printer builds objects layer-by-layer by melting and extruding plastic filaments.</p>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">1. Machine & Materials</h2>
    <p>The Ultimaker is a desktop FDM printer known for reliability and precision. Before printing, it is critical to select the right material for the job.</p>
    
    <table class="data-table">
        <thead>
            <tr>
                <th>Material</th>
                <th>Properties</th>
                <th>Best Application</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><strong>PLA</strong></td>
                <td>Biodegradable, easy to print.</td>
                <td>General prototyping, visual models.</td>
            </tr>
            <tr>
                <td><strong>ABS</strong></td>
                <td>Strong, temperature-resistant.</td>
                <td>Functional parts, mechanical gears.</td>
            </tr>
            <tr>
                <td><strong>PETG</strong></td>
                <td>Impact-resistant, combines PLA ease with ABS strength.</td>
                <td>Snap-fits, protective cases.</td>
            </tr>
            <tr>
                <td><strong>TPU</strong></td>
                <td>Flexible and rubber-like.</td>
                <td>Phone cases, seals, gaskets.</td>
            </tr>
        </tbody>
    </table>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">2. The Printing Workflow</h2>
    
    <div class="phase-header">Phase A: Slicing (Ultimaker Cura)</div>
    <p>Before the printer can move, the digital 3D model (STL/OBJ) must be "sliced" into G-code instructions.</p>
    
    <div class="info-box">
        <div class="info-box-title">Key Slicing Settings</div>
        <ul class="bullet-list">
            <li><strong>Layer Height:</strong> Determines resolution. Lower (e.g., 0.1mm) is smoother but slower.</li>
            <li><strong>Infill Density:</strong> Controls internal strength. 20% is standard; 100% is solid.</li>
            <li><strong>Supports:</strong> Essential for overhangs greater than 45°.</li>
        </ul>
    </div>
    
    <div class="phase-header">Phase B: Printer Setup</div>
    
    <div class="step-card">
        <div class="step-title">1. Load Filament</div>
        <p>Feed the filament into the extruder path. Ensure the material matches the Cura profile!</p>
    </div>
    
    <div class="step-card">
        <div class="step-title">2. Level Build Plate</div>
        <p><strong>Critical Step:</strong> The build plate must be perfectly level to ensure the first layer adheres correctly. Use the manual leveling screws or auto-calibration if available.</p>
    </div>
    
    <div class="step-card">
        <div class="step-title">3. Clean Surface</div>
        <p>Wipe the glass plate with isopropyl alcohol to remove oils (fingerprints) that cause warping.</p>
    </div>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">3. Operations & Troubleshooting</h2>
    
    <h3 class="subsection-title">Monitoring the Print</h3>
    <div class="warning-box">
        <div class="">Watch the First Layer</div>
        <p>Always monitor the first few layers. Most failures (like detachment) happen here. If the nozzle is too high, the plastic won't stick; too low, and it will block flow.</p>
    </div>
    
    <h3 class="subsection-title">Common Issues & Fixes</h3>
    <table class="data-table">
        <thead>
            <tr>
                <th>Issue</th>
                <th>Symptom</th>
                <th>Solution</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><strong>Warping</strong></td>
                <td>Corners lifting off the plate.</td>
                <td>Clean the bed, use glue stick, or increase bed temperature.</td>
            </tr>
            <tr>
                <td><strong>Stringing</strong></td>
                <td>Fine plastic hairs between parts.</td>
                <td>Lower nozzle temperature or increase retraction settings.</td>
            </tr>
            <tr>
                <td><strong>Under-extrusion</strong></td>
                <td>Gaps or thin layers.</td>
                <td>Check for nozzle clogs or filament tangles.</td>
            </tr>
        </tbody>
    </table>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">4. Safety Guidelines</h2>
    <p>Operating a 3D printer involves high heat and moving parts.</p>
    
    <ul class="bullet-list">
        <li><strong>Heat Hazard:</strong> The nozzle reaches 200°C+ and the bed 60°C+. <strong>Do not touch</strong> these components during operation.</li>
        <li><strong>Ventilation:</strong> Ensure the room is well-ventilated, especially when printing materials like ABS that release fumes.</li>
        <li><strong>Supervision:</strong> Never leave the printer unattended for long periods.</li>
    </ul>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">5. Project Showcase</h2>
    <p style="font-style: italic; margin-bottom: 30px;">Below are the results from using this workflow:</p>
    
    <div class="image-grid">
        <div class="image-grid-item">
            <img src="../images/day_6/3.jpeg" alt="3D Printing Machine">
            <p class="image-caption">Figure 1: Printing machine in operation.</p>
        </div>
        
        <div class="image-grid-item">
            <img src="../images/day_6/1.jpeg" alt="3D Printed Object">
            <p class="image-caption">Figure 2: My printed object.</p>
        </div>
    </div>
</div>

</div>

<p style="clear: both;"></p>
<br/>