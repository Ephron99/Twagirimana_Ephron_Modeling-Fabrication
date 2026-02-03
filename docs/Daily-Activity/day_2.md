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

.section-title {
    font-size: 1.8em;
    font-weight: 600;
    color: #2c3e50;
    margin-bottom: 15px;
    margin-top: 0;
}

.subsection-title {
    font-size: 1.4em;
    font-weight: 600;
    color: #37474f;
    margin-top: 25px;
    margin-bottom: 15px;
}

.project-specs {
    background: rgba(255, 255, 255, 0.6);
    border-radius: 8px;
    padding: 20px;
    margin-bottom: 20px;
}

.project-specs p {
    margin: 8px 0;
    font-size: 1.05em;
}

.bullet-list {
    list-style: none;
    padding-left: 0;
}

.bullet-list li {
    padding: 10px 0;
    padding-left: 30px;
    position: relative;
    color: #424242;
    font-size: 1.05em;
}

.bullet-list li:before {
    /* content: "●"; */
    color: #4caf50;
    font-weight: bold;
    position: absolute;
    left: 0;
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

.info-box {
    background: rgba(103, 58, 183, 0.1);
    border-left: 4px solid #673ab7;
    padding: 20px;
    margin: 20px 0;
    border-radius: 0 8px 8px 0;
}

.info-box-title {
    font-weight: bold;
    color: #673ab7;
    font-size: 1.1em;
    margin-bottom: 10px;
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

/* .highlight-text {
    background: linear-gradient(120deg, #84fab0 0%, #8fd3f4 100%);
    padding: 2px 6px;
    border-radius: 3px;
    font-weight: 500;
} */

.tool-tag {
    display: inline-block;
    background: #ff9800;
    color: white;
    padding: 4px 12px;
    border-radius: 15px;
    font-size: 0.9em;
    font-weight: 600;
    margin-right: 10px;
}

.parameter-tag {
    display: inline-block;
    background: #4caf50;
    color: white;
    padding: 4px 12px;
    border-radius: 15px;
    font-size: 0.9em;
    font-weight: 600;
    margin-right: 10px;
}

.fabrication-table {
    width: 100%;
    border-collapse: collapse;
    margin: 20px 0;
    background: white;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

.fabrication-table thead {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
}

.fabrication-table th {
    padding: 15px;
    text-align: left;
    font-weight: 600;
    font-size: 1.1em;
}

.fabrication-table td {
    padding: 15px;
    border-bottom: 1px solid #e0e0e0;
}

.fabrication-table tr:last-child td {
    border-bottom: none;
}

.fabrication-table tbody tr:hover {
    background: #f5f5f5;
}

.divider {
    height: 2px;
    background: linear-gradient(to right, #4caf50, #2196f3);
    margin: 40px 0;
    border-radius: 2px;
}

blockquote {
    border-left: 4px solid #ff9800;
    background: rgba(255, 152, 0, 0.1);
    padding: 15px 20px;
    margin: 20px 0;
    border-radius: 0 8px 8px 0;
    font-style: italic;
}
</style>

<div class="activity-container">

<h1 class="main-header">Activity of Day 2</h1>
<h2 class="sub-header">Digital Modeling: L-Bracket Project</h2>

<div class="content-card teal">
    <h2 class="section-title">Project Overview</h2>
    <div class="project-specs">
        <p><strong>Objective:</strong> Design a structural L-shaped bracket using <span class="highlight-text">FreeCAD</span>.</p>
        <p><strong>Design Intent:</strong> Create a robust mounting point with 90° geometry, reinforced mounting holes, and stress-relieving fillets.</p>
        <p><strong>Software:</strong> FreeCAD (Part Design Workbench).</p>
    </div>
</div>

<div class="content-card">
    <h2 class="section-title">Modeling Workflow</h2>
    <p>My workflow follows the standard <span class="highlight-text">Parametric Modeling</span> approach: <em>Sketch, Constrain, Extrude, Refine.</em></p>
</div>

<div class="content-card teal">
    <div class="phase-header">Phase 1: Creating the Base Body (Additive)</div>
    
    <div class="step-card">
        <div class="step-title">Step 1: Setup & Sketch</div>
        <p>I started by creating a new <strong>Body</strong> in the Part Design Workbench and selecting the <strong>XY Plane</strong>.</p>
        
        <ul class="bullet-list">
            <li><span class="tool-tag">Tool</span> Polyline <code>CreatePolyline</code></li>
            <li><strong>Action:</strong> Drew a rough "L" shape starting from the origin (0,0).</li>
            <li><strong>Constraints:</strong>
                <ul class="bullet-list" style="margin-top: 10px;">
                    <li>Applied <strong>Vertical</strong> and <strong>Horizontal</strong> constraints to ensure 90° angles.</li>
                    <li><strong>Vertical Height:</strong> 60mm</li>
                    <li><strong>Horizontal Length:</strong> 40mm</li>
                    <li><strong>Thickness:</strong> 10mm (uniform)</li>
                </ul>
            </li>
        </ul>
        
        <div class="info-box">
            <div class="info-box-title">Parametric Logic</div>
            <p>By fully constraining the sketch (turning the lines green), I ensure that the dimensions can be easily modified later without breaking the model geometry.</p>
        </div>
    </div>
    
    <div class="step-card">
        <div class="step-title">Step 2: Padding (Extrusion)</div>
        <p>Once the 2D profile was defined, I transformed it into a 3D solid.</p>
        
        <ul class="bullet-list">
            <li><span class="tool-tag">Tool</span> Pad <code>PartDesign_Pad</code></li>
            <li><span class="parameter-tag">Parameter</span> Length = 40mm</li>
            <li><strong>Result:</strong> A solid 3D block representing the raw material volume.</li>
        </ul>
        
        <div class="image-container">
            <img src="../images/day_2/DESIGN2_2.jpg" alt="Extruded L-Shape">
            <p class="image-caption">Screenshot of the Extruded L-Shape</p>
        </div>
    </div>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <div class="phase-header">Phase 2: Adding Features (Subtractive & Refinement)</div>
    
    <div class="step-card">
        <div class="step-title">Step 3: Creating Holes</div>
        <p>To allow for mounting screws, I used a <strong>Subtractive</strong> process to remove material.</p>
        
        <ol class="bullet-list">
            <li><strong>Select Face:</strong> Clicked the top flat face of the bracket.</li>
            <li><strong>Sketch:</strong> Drew a circle and constrained the radius to <strong>2.5mm</strong> (for M5 bolts).</li>
            <li><span class="tool-tag">Tool</span> Pocket <code>PartDesign_Pocket</code> set to <strong>"Through All"</strong>.</li>
        </ol>
        
        <blockquote>
            <em>Repeating this process on the vertical face ensures the bracket can be mounted on two axes.</em>
        </blockquote>
    </div>
    
    <div class="step-card">
        <div class="step-title">Step 4: The Fillet (Edge Refinement)</div>
        <p>Sharp corners in mechanical parts are stress concentrators. To mitigate this, I added a fillet.</p>
        
        <ul class="bullet-list">
            <li><span class="tool-tag">Tool</span> Fillet <code>PartDesign_Fillet</code></li>
            <li><strong>Target:</strong> The inner corner of the "L".</li>
            <li><span class="parameter-tag">Radius</span> 5mm</li>
        </ul>
        
        <div class="image-container">
            <img src="../images/day_2/dESIGN2_1.jpg" alt="Filleted Corner">
            <p class="image-caption">Screenshot of the Filleted Corner</p>
        </div>
    </div>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">The "Rib" Reinforcement (Advanced)</h2>
    <p><em>Note: While the basic requirement was a simple L-shape, I added a structural rib (as seen in the project reference) to increase rigidity.</em></p>
    
    <ol class="bullet-list">
        <li><strong>Sketch Plane:</strong> Created a sketch on the side face of the bracket.</li>
        <li><strong>Geometry:</strong> Drew a triangle connecting the vertical and horizontal arms.</li>
        <li><strong>Pad:</strong> Extruded the triangle using <strong>"Symmetric to Plane"</strong> to center it perfectly on the bracket.</li>
    </ol>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">Fabrication Considerations</h2>
    
    <div class="image-container">
        <img src="../images/day_2/Day2_Activity1.png" alt="Filleted Design">
        <p class="image-caption">Final design with fabrication considerations</p>
    </div>
    
    <p>Connecting this design to the physical production process:</p>
    
    <table class="fabrication-table">
        <thead>
            <tr>
                <th>Feature</th>
                <th>Fabrication Logic</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><strong>Flat Faces</strong></td>
                <td>Designed to lay flat on the 3D printer bed (minimizing supports).</td>
            </tr>
            <tr>
                <td><strong>Hole Diameter (5mm)</strong></td>
                <td>Designed with a <strong>0.2mm tolerance</strong> (actual print: 4.8mm) to ensure screws fit.</td>
            </tr>
            <tr>
                <td><strong>Fillet</strong></td>
                <td>Prevents layer separation at the corner during 3D printing.</td>
            </tr>
        </tbody>
    </table>
</div>

</div>

<p style="clear: both;"></p>
<br/>