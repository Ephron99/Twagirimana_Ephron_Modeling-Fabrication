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

.content-card.red {
    background: linear-gradient(to right, #ffebee 0%, #ffcdd2 100%);
    border-left-color: #e53935;
}

.content-card.amber {
    background: linear-gradient(to right, #fff8e1 0%, #ffecb3 100%);
    border-left-color: #ffa726;
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

.numbered-list {
    list-style: none;
    counter-reset: item;
    padding-left: 0;
}

.numbered-list li {
    counter-increment: item;
    padding: 12px 0;
    padding-left: 40px;
    position: relative;
    color: #424242;
    font-size: 1.05em;
}

.numbered-list li:before {
    content: counter(item);
    background: #4caf50;
    color: white;
    font-weight: bold;
    border-radius: 50%;
    width: 28px;
    height: 28px;
    display: flex;
    align-items: center;
    justify-content: center;
    position: absolute;
    left: 0;
    font-size: 0.9em;
}

.quote-box {
    background: rgba(103, 58, 183, 0.1);
    border-left: 4px solid #673ab7;
    padding: 20px;
    margin: 20px 0;
    border-radius: 0 8px 8px 0;
}

.quote-box-title {
    font-weight: bold;
    color: #673ab7;
    font-size: 1.1em;
    margin-bottom: 10px;
}

.warning-box {
    background: rgba(255, 152, 0, 0.1);
    border-left: 4px solid #ff9800;
    padding: 20px;
    margin: 20px 0;
    border-radius: 0 8px 8px 0;
}

.warning-title {
    font-weight: bold;
    color: #ff9800;
    font-size: 1.1em;
    margin-bottom: 10px;
}

.tip-box {
    background: rgba(76, 175, 80, 0.1);
    border-left: 4px solid #4caf50;
    padding: 20px;
    margin: 20px 0;
    border-radius: 0 8px 8px 0;
}

.tip-title {
    font-weight: bold;
    color: #4caf50;
    font-size: 1.1em;
    margin-bottom: 10px;
}

/* .highlight-text {
    background: linear-gradient(120deg, #84fab0 0%, #8fd3f4 100%);
    padding: 2px 6px;
    border-radius: 3px;
    font-weight: 500;
} */

.material-tab {
    background: rgba(255, 255, 255, 0.7);
    border-left: 4px solid #2196f3;
    padding: 25px;
    margin: 20px 0;
    border-radius: 0 8px 8px 0;
}

.material-tab-title {
    font-size: 1.3em;
    font-weight: 600;
    color: #2196f3;
    margin-bottom: 15px;
}

.comparison-table {
    width: 100%;
    border-collapse: collapse;
    margin: 20px 0;
    background: white;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

.comparison-table thead {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
}

.comparison-table th {
    padding: 15px;
    text-align: left;
    font-weight: 600;
    font-size: 1.1em;
}

.comparison-table td {
    padding: 15px;
    border-bottom: 1px solid #e0e0e0;
}

.comparison-table tr:last-child td {
    border-bottom: none;
}

.comparison-table tbody tr:hover {
    background: #f5f5f5;
}

.divider {
    height: 2px;
    background: linear-gradient(to right, #4caf50, #2196f3);
    margin: 40px 0;
    border-radius: 2px;
}

.force-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    gap: 15px;
    margin: 20px 0;
}

.force-item {
    background: rgba(33, 150, 243, 0.1);
    padding: 15px;
    border-radius: 8px;
    border-left: 3px solid #2196f3;
    text-align: center;
}

.force-item strong {
    display: block;
    color: #2196f3;
    font-size: 1.1em;
    margin-bottom: 5px;
}
</style>

<div class="activity-container">

<h1 class="main-header">Activity of Day 4</h1>
<h2 class="sub-header">Materials & Fabrication Methods</h2>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">1. Core Philosophy: Designing Material Processes</h2>
    <p>In modern engineering, materials are not just components; they are the foundation of design. The key takeaway from our coursework is that <span class="highlight-text">we do not design objects—we design material processes</span>.</p>
    
    <div class="quote-box">
        <div class="quote-box-title">Materials as Design Drivers</div>
        <p>Materials are never neutral. They dictate form, influence structural integrity, and define the fabrication logic. A design must align the <strong>material + process</strong> for optimal results.</p>
    </div>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">2. Material Intelligence</h2>
    <p>Selecting the right material requires understanding its inherent properties and limitations.</p>
    
    <div class="material-tab">
        <div class="material-tab-title">Wood - Nature's Versatile Material</div>
        <ul class="bullet-list">
            <li><strong>Properties:</strong> Renewable, distinctive grain patterns.</li>
            <li><strong>Critical Constraint:</strong> Wood is anisotropic—it behaves differently along and across the grain. This directionality affects how it bends and breaks.</li>
            <li><strong>Best For:</strong> Furniture, architectural models, rapid prototyping.</li>
            <li><strong>Fabrication:</strong> CNC Routing, Laser Cutting.</li>
        </ul>
    </div>
    
    <div class="material-tab">
        <div class="material-tab-title">Plastics - Lightweight & Adaptable</div>
        <ul class="bullet-list">
            <li><strong>Types:</strong> Thermoplastics (PLA, ABS) and Thermosets.</li>
            <li><strong>Best For:</strong> 3D printing, laser cutting.</li>
        </ul>
        
        <div class="warning-box">
            <div class="warning-title">Heat Sensitivity</div>
            <p>Heat significantly affects plastics, often more than their geometric form. Watch for melting or warping during fabrication.</p>
        </div>
    </div>
    
    <div class="material-tab">
        <div class="material-tab-title"> Metals - Strength & Precision</div>
        <ul class="bullet-list">
            <li><strong>Common Types:</strong> Aluminum (lightweight), Steel (high strength), Brass (conductive).</li>
            <li><strong>Trade-off:</strong> High strength typically comes with increased cost and energy consumption.</li>
            <li><strong>Fabrication:</strong> CNC Milling (subtractive), Sheet Metal Forming.</li>
        </ul>
    </div>
    
    <div class="material-tab">
        <div class="material-tab-title"> Composites - Engineered Performance</div>
        <ul class="bullet-list">
            <li><strong>Definition:</strong> Combining multiple materials (e.g., Fiberglass, Carbon Fiber) to achieve properties not found in individual components.</li>
            <li><strong>Benefit:</strong> Extreme strength-to-weight ratio.</li>
            <li><strong>Challenge:</strong> Complex recycling and fabrication methods.</li>
        </ul>
    </div>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">3. The Fabrication Continuum</h2>
    <p>We categorize fabrication into two fundamental approaches:</p>
    
    <h3 class="subsection-title">A. Subtractive vs. Additive</h3>
    
    <table class="comparison-table">
        <thead>
            <tr>
                <th>Feature</th>
                <th>Subtractive Manufacturing</th>
                <th>Additive Manufacturing</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><strong>Process</strong></td>
                <td>Removing material from a block</td>
                <td>Building objects layer-by-layer</td>
            </tr>
            <tr>
                <td><strong>Examples</strong></td>
                <td>CNC Milling, Laser Cutting</td>
                <td>3D Printing</td>
            </tr>
            <tr>
                <td><strong>Strengths</strong></td>
                <td>Precision and surface finish</td>
                <td>Complexity and customization</td>
            </tr>
        </tbody>
    </table>
    
    <h3 class="subsection-title">B. Hybrid Fabrication</h3>
    <p>Advanced manufacturing often combines these methods. For example, using <strong>CNC machining</strong> to refine a <strong>3D printed</strong> part. This <span class="highlight-text">"Cross-Process Planning"</span> leverages the strengths of both machines to accelerate prototyping.</p>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">4. Design Logic & Constraints</h2>
    
    <h3 class="subsection-title">Material Form Factors</h3>
    <ul class="bullet-list">
        <li><strong>Sheet Materials:</strong> (Plywood, Acrylic) Ideal for 2D/2.5D processes like laser cutting. This promotes "Assembly Thinking" (interlocking parts).</li>
        <li><strong>Solid Stock:</strong> (Blocks, Bars) Used for structural components and subtractive 3D forms.</li>
    </ul>
    
    <h3 class="subsection-title">Forces at Play</h3>
    <p>During fabrication, materials react to five external forces:</p>
    
    <div class="force-grid">
        <div class="force-item">
            <strong>1. Compression</strong>
            Pushing
        </div>
        <div class="force-item">
            <strong>2. Tension</strong>
            Pulling/Stretching
        </div>
        <div class="force-item">
            <strong>3. Shear</strong>
            Sliding
        </div>
        <div class="force-item">
            <strong>4. Torsion</strong>
            Twisting
        </div>
        <div class="force-item">
            <strong>5. Bending</strong>
            Flexing
        </div>
    </div>
    
    <div class="tip-box">
        <div class="tip-title">Designing for Assembly</div>
        <p>Assembly is often the core fabrication method itself. Using smart joinery (like <strong>Box Joints</strong>, <strong>Dovetails</strong>, or <strong>Press-fits</strong>) can reduce the need for adhesives and fasteners.</p>
    </div>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">5. Learning from Failure</h2>
    <p>In our lab, failure is treated as <span class="highlight-text">data, not a mistake</span>. Common failure modes include:</p>
    
    <ul class="bullet-list">
        <li><strong>Warping:</strong> Signals uneven cooling or internal stress.</li>
        <li><strong>Cracking:</strong> Indicates excessive stress or brittle material properties.</li>
        <li><strong>Delamination:</strong> Suggests poor adhesion between layers (common in 3D printing).</li>
    </ul>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">6. Ethics & Sustainability</h2>
    <p>Every fabrication choice carries an ethical weight:</p>
    
    <ul class="bullet-list">
        <li><strong>Local Availability:</strong> Choosing materials found in the immediate region reduces transportation impact and fosters community resilience.</li>
        <li><strong>Repairability:</strong> Designing with common materials ensures products can be repaired locally, extending their lifespan.</li>
        <li><strong>Efficiency:</strong> Can this design do more with less material?</li>
    </ul>
</div>

</div>

<p style="clear: both;"></p>
<br/>