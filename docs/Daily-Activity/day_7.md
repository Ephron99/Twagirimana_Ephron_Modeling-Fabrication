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

.content-card.indigo {
    background: linear-gradient(to right, #e8eaf6 0%, #c5cae9 100%);
    border-left-color: #3f51b5;
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

.component-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
    margin: 25px 0;
}

.component-item {
    background: rgba(255, 255, 255, 0.7);
    padding: 20px;
    border-radius: 8px;
    border-left: 4px solid #9c27b0;
    transition: transform 0.3s ease;
}

.component-item:hover {
    transform: translateY(-3px);
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.component-title {
    font-weight: bold;
    color: #9c27b0;
    font-size: 1.2em;
    margin-bottom: 10px;
}

.strategy-card {
    background: rgba(255, 255, 255, 0.7);
    border-left: 4px solid #2196f3;
    padding: 20px;
    margin: 15px 0;
    border-radius: 0 8px 8px 0;
}

.strategy-title {
    font-weight: bold;
    color: #2196f3;
    font-size: 1.15em;
    margin-bottom: 8px;
}

.highlight-box {
    background: rgba(33, 150, 243, 0.1);
    border-left: 4px solid #2196f3;
    padding: 20px;
    margin: 20px 0;
    border-radius: 0 8px 8px 0;
}

.code-inline {
    background: #f5f5f5;
    padding: 3px 8px;
    border-radius: 4px;
    font-family: 'Courier New', monospace;
    color: #d32f2f;
    font-size: 0.95em;
}
</style>

<div class="activity-container">

<h1 class="main-header">Activity of Day 7</h1>
<h2 class="sub-header">Digital Fabrication III: CNC Router Milling</h2>

<div class="overview-section">
    <p>CNC (Computer Numerical Control) Routing is a <span class="highlight-text">subtractive</span> manufacturing process. Unlike 3D printing which builds layers, the CNC router starts with a solid sheet of material and cuts away the excess using a spinning tool.</p>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">1. Systems & Components</h2>
    <p>Understanding the machine architecture is the first step to safe operation.</p>
    
    <div class="component-grid">
        <div class="component-item">
            <div class="component-title">Spindle</div>
            <p>The motor that rotates the cutting tool (End Mill).</p>
        </div>
        
        <div class="component-item">
            <div class="component-title">Gantry</div>
            <p>The bridge that moves the spindle along the X and Y axes.</p>
        </div>
        
        <div class="component-item">
            <div class="component-title">Bed/Spoilboard</div>
            <p>The sacrificial layer (usually MDF) that supports the stock material.</p>
        </div>
        
        <div class="component-item">
            <div class="component-title">Collet</div>
            <p>The cone-shaped sleeve that grips the tool bit.</p>
        </div>
    </div>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">2. Tooling & Material Compatibility</h2>
    <p>Selecting the right "End Mill" (bit) is critical for finish quality and machine safety.</p>
    
    <table class="data-table">
        <thead>
            <tr>
                <th>Tool Type</th>
                <th>Geometry</th>
                <th>Best Application</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><strong>Flat End Mill</strong></td>
                <td>Flat tip</td>
                <td>Cutting profiles, pockets, and straight edges.</td>
            </tr>
            <tr>
                <td><strong>Ball Nose Mill</strong></td>
                <td>Rounded tip</td>
                <td>3D contouring, curved surfaces.</td>
            </tr>
            <tr>
                <td><strong>V-Bit</strong></td>
                <td>V-shaped tip</td>
                <td>Engraving text, chamfering edges.</td>
            </tr>
            <tr>
                <td><strong>Compression Bit</strong></td>
                <td>Up/Down spiral</td>
                <td>Cutting plywood without chipping the top or bottom veneer.</td>
            </tr>
        </tbody>
    </table>
    
    <div class="warning-box">
        <div class="warning-title">Feeds & Speeds</div>
        <p>Every material (Plywood, Acrylic, Aluminum) requires a specific <strong>Feed Rate</strong> (speed of movement) and <strong>Spindle Speed</strong> (RPM). Running too fast can break the bit; too slow can burn the material.</p>
    </div>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">3. CAM Workflows & Toolpath Strategies</h2>
    <p>Computer-Aided Manufacturing (CAM) is the bridge between your CAD design and the machine.</p>
    
    <h3 class="subsection-title">Core Toolpath Strategies</h3>
    
    <div class="strategy-card">
        <div class="strategy-title">1. Profile / Contour</div>
        <p>Cutting along the outline to separate the part from the sheet.</p>
    </div>
    
    <div class="strategy-card">
        <div class="strategy-title">2. Pocketing</div>
        <p>Clearing out an internal area to a specific depth (not cutting through).</p>
    </div>
    
    <div class="strategy-card">
        <div class="strategy-title">3. Drilling</div>
        <p>Creating vertical holes for screws or alignment.</p>
    </div>
    
    <div class="strategy-card">
        <div class="strategy-title">4. Engraving</div>
        <p>Following a line on the surface for text or artwork.</p>
    </div>
    
    <h3 class="subsection-title">Nesting & Optimization</h3>
    <p><strong>Nesting</strong> is the process of arranging multiple parts on a single sheet to maximize yield and minimize waste.</p>
    
    <ul class="bullet-list">
        <li><strong>Gap:</strong> Always leave at least <span class="code-inline">2x Tool Diameter</span> between parts for stability.</li>
        <li><strong>Tabs:</strong> Small bridges of material left behind to hold the part in place so it doesn't fly loose when cut.</li>
    </ul>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">4. Design for CNC Fabrication</h2>
    <p>CNC routers have physical limitations that usually dictate the design logic.</p>
    
    <h3 class="subsection-title">The "Internal Corner" Problem</h3>
    <p>Because the cutting tool is round, a CNC router <strong>cannot cut a sharp internal 90° corner</strong>. The radius of the tool will always remain.</p>
    
    <div class="tip-box">
        <div class="tip-title">Solution: Dog-Bones & T-Bones</div>
        <p>To fit a rectangular tenon into a slot, we must create <strong>"Dog-Bone" fillets</strong> (over-cutting the corners) to allow the mating part to seat fully square.</p>
    </div>
    
    <h3 class="subsection-title">Tolerances & Press-Fit Joinery</h3>
    <p>For parts to snap together without glue (Press-Fit), tolerances must be exact.</p>
    
    <ul class="bullet-list">
        <li><strong>Kerf/Runout:</strong> The actual cut width is often slightly larger than the tool diameter due to vibration.</li>
        <li><strong>Offset:</strong> Designing parts with a <span class="code-inline">0.1mm - 0.2mm</span> interference for a tight friction fit.</li>
    </ul>
</div>

<div class="divider"></div>

<div class="content-card teal">
    <h2 class="section-title">5. Assembly & Structural Evaluation</h2>
    
    <ul class="bullet-list">
        <li><strong>Joinery:</strong> Using Mortise & Tenon or Box Joints for mechanical strength.</li>
        <li><strong>Structural Evaluation:</strong> Checking if the sheet material direction (grain) aligns with the load-bearing requirements of the assembly.</li>
    </ul>
</div>

</div>

<p style="clear: both;"></p>
<br/>