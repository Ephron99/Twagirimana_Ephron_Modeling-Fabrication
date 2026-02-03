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

.content-card.amber {
    background: linear-gradient(to right, #fff8e1 0%, #ffecb3 100%);
    border-left-color: #ffa726;
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

.hero-image {
    text-align: center;
    margin: 30px 0;
}

.hero-image img {
    max-width: 100%;
    border-radius: 12px;
    box-shadow: 0 6px 20px rgba(0,0,0,0.2);
}

.divider {
    height: 2px;
    background: linear-gradient(to right, #4caf50, #2196f3);
    margin: 40px 0;
    border-radius: 2px;
}

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

.note-box {
    background: rgba(33, 150, 243, 0.1);
    border-left: 4px solid #2196f3;
    padding: 15px 20px;
    margin: 20px 0;
    border-radius: 0 8px 8px 0;
    font-style: italic;
}

.step-header {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 15px 25px;
    border-radius: 8px;
    margin: 30px 0 20px 0;
    font-size: 1.5em;
    font-weight: 600;
}

.software-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 15px;
    margin: 20px 0;
}

.software-item {
    background: rgba(255, 255, 255, 0.6);
    padding: 15px;
    border-radius: 8px;
    border-left: 3px solid #2196f3;
}

.software-item strong {
    display: block;
    color: #2196f3;
    font-size: 1.1em;
    margin-bottom: 8px;
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

.badge.red {
    background: #f44336;
}

.badge.blue {
    background: #2196f3;
}
</style>

<div class="activity-container">

<h1 class="main-header">Activity of Day 5</h1>
<h2 class="sub-header">Laser Cutting Machine Activity</h2>

<div class="hero-image">
    <img src="../images/day_4/2.jfif" alt="Laser Cutting Machine">
</div>

<p class="project-subtitle">Computer-Aided Design and Digital Fabrication Using Laser Cutter</p>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">Objective</h2>
    <p>The objective of this activity is to introduce students to <span class="highlight-text">laser cutting technology</span> for digital fabrication.</p>
    <p>Students will design a 2D object using vector-based software and fabricate it using a <strong>laser cutting machine</strong>.</p>
    <p style="font-size: 1.1em; margin-top: 20px;">By the end of this task, students will understand the full workflow from <span class="highlight-text">digital design to physical production</span>.</p>
</div>

<div class="divider"></div>

<div class="hero-image">
    <img src="../images/day_4/Laser-cutting.jpg" alt="Laser Cutting Process">
</div>

<div class="content-card teal">
    <h2 class="section-title">Functional Description</h2>
    <ul class="bullet-list">
        <li>Students design a <strong>2D vector file</strong></li>
        <li>The design is prepared according to <strong>laser cutting constraints</strong></li>
        <li>The file is sent to a <strong>laser cutting machine</strong></li>
        <li>The final object is cut from sheet material such as plywood or acrylic</li>
    </ul>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">Machine Used</h2>
    <p style="font-size: 1.2em; margin-bottom: 20px;"><strong>Laser Cutting Machine</strong></p>
    
    <p><strong>Common types:</strong></p>
    <ul class="bullet-list">
        <li>CO₂ Laser Cutter</li>
        <li>Desktop or Industrial Laser Cutter</li>
    </ul>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">Materials</h2>
    
    <table class="data-table">
        <thead>
            <tr>
                <th>Material</th>
                <th>Thickness</th>
                <th>Notes</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><strong>Plywood</strong></td>
                <td>3 mm</td>
                <td>Easy to cut, beginner-friendly</td>
            </tr>
            <tr>
                <td><strong>Acrylic</strong></td>
                <td>3 mm</td>
                <td>Clean edges, requires ventilation</td>
            </tr>
            <tr>
                <td><strong>Cardboard</strong></td>
                <td>2–3 mm</td>
                <td>Good for testing designs</td>
            </tr>
        </tbody>
    </table>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">Tools & Software</h2>
    
    <div class="software-grid">
        <div class="software-item">
            <strong>Design Software</strong>
            Inkscape
        </div>
        <div class="software-item">
            <strong>Laser Control</strong>
            LightBurn, RDWorks, LaserGRBL
        </div>
        <div class="software-item">
            <strong>Hardware</strong>
            Laser Cutter Machine
        </div>
    </div>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">Safety Precautions</h2>
    
    <div class="warning-box">
        <div class="warning-title">Laser safety is critical</div>
        <p><strong>Students must:</strong></p>
        <ul class="bullet-list">
            <li>Never leave the laser cutter unattended</li>
            <li>Wear safety glasses if required</li>
            <li>Ensure proper ventilation is ON</li>
            <li>Keep flammable materials away</li>
            <li>Stop the machine immediately if fire occurs</li>
            <li>Be supervised by a trained instructor</li>
        </ul>
    </div>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">Design to Fabrication Workflow</h2>
    
    <div class="step-header">Step 1 – Design the 2D Model</div>
    <p><strong>Students must:</strong></p>
    <ul class="bullet-list">
        <li>Create a <strong>2D vector design</strong></li>
        <li>Use <strong>closed paths only</strong></li>
        <li>Convert all lines to vectors</li>
        <li>Use real dimensions (mm)</li>
    </ul>
    <p style="margin-top: 15px;"><strong>Recommended:</strong> Object size smaller than <span class="badge blue">300 × 200 mm</span></p>
    
    <div class="step-header">Step 2 – Design Rules for Laser Cutting</div>
    <table class="data-table">
        <thead>
            <tr>
                <th>Rule</th>
                <th>Value</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><strong>Stroke color</strong></td>
                <td>Red (RGB: 255, 0, 0)</td>
            </tr>
            <tr>
                <td><strong>Stroke width</strong></td>
                <td>0.01 mm (hairline)</td>
            </tr>
            <tr>
                <td><strong>Units</strong></td>
                <td>Millimeters</td>
            </tr>
            <tr>
                <td><strong>No fills</strong></td>
                <td>Cutting only</td>
            </tr>
        </tbody>
    </table>
    <div class="note-box">
        <strong>Note:</strong> Different labs may use different color rules.
    </div>
    
    <div class="step-header">Step 3 – Prepare the Laser File</div>
    <p><strong>Students must:</strong></p>
    <ul class="bullet-list">
        <li>Check scale and dimensions</li>
        <li>Remove duplicate lines</li>
        <li>Place objects efficiently to reduce material waste</li>
        <li>Export as: <span class="badge">.SVG</span> <span class="badge">.DXF</span> <span class="badge">.PDF</span></li>
    </ul>
    
    <div class="step-header">Step 4 – Machine Setup</div>
    <p><strong>Students must:</strong></p>
    <ul class="bullet-list">
        <li><strong>Turn ON:</strong> Laser cutter, Air assist, Ventilation system</li>
        <li>Place material flat on the bed</li>
        <li>Focus the laser head correctly</li>
        <li>Set the <strong>origin</strong> (home position)</li>
    </ul>
    
    <div class="step-header">Step 5 – Laser Cutting Parameters</div>
    <table class="data-table">
        <thead>
            <tr>
                <th>Material</th>
                <th>Power (%)</th>
                <th>Speed (mm/s)</th>
                <th>Passes</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><strong>3 mm plywood</strong></td>
                <td>70–80</td>
                <td>10–15</td>
                <td>1</td>
            </tr>
            <tr>
                <td><strong>3 mm acrylic</strong></td>
                <td>60–70</td>
                <td>8–12</td>
                <td>1</td>
            </tr>
            <tr>
                <td><strong>Cardboard</strong></td>
                <td>30–40</td>
                <td>20–25</td>
                <td>1</td>
            </tr>
        </tbody>
    </table>
    <div class="note-box">
        Parameters may vary depending on the machine.
    </div>
    
    <div class="step-header">Step 6 – Cutting Process</div>
    <ul class="bullet-list">
        <li>Run a <strong>frame test</strong></li>
        <li>Start the cutting job</li>
        <li>Monitor the process continuously</li>
        <li>Pause or stop if issues occur</li>
    </ul>
    
    <div class="step-header">Step 7 – Post-Processing</div>
    <p><strong>Students must:</strong></p>
    <ul class="bullet-list">
        <li>Remove the cut pieces carefully</li>
        <li>Clean burnt edges if necessary</li>
        <li>Test fit components</li>
        <li>Record any design or cutting issues</li>
    </ul>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">Example Laser-Cut Project</h2>
    <p style="font-size: 1.2em; margin-bottom: 20px;"><strong>Press-Fit Box / Key Holder / Phone Stand</strong></p>
    
    <p><strong>Design considerations:</strong></p>
    <ul class="bullet-list">
        <li>Material thickness tolerance</li>
        <li>Kerf compensation</li>
        <li>Tab and slot fit</li>
    </ul>
</div>

</div>

<p style="clear: both;"></p>
<br/>