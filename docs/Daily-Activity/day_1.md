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

.intro-box {
    background: rgba(255, 255, 255, 0.5);
    border-radius: 8px;
    padding: 20px;
    margin-bottom: 20px;
}

.quote-box {
    background: rgba(103, 58, 183, 0.1);
    border-left: 4px solid #673ab7;
    padding: 20px;
    margin: 20px 0;
    border-radius: 0 8px 8px 0;
    font-style: italic;
}

.quote-box-title {
    font-weight: bold;
    color: #673ab7;
    font-size: 1.1em;
    margin-bottom: 10px;
    font-style: normal;
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

.paradigm-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 15px;
    margin: 20px 0;
}

.paradigm-item {
    background: rgba(255, 255, 255, 0.6);
    padding: 15px;
    border-radius: 8px;
    border-left: 3px solid #ff9800;
}

.paradigm-item strong {
    display: block;
    color: #ff9800;
    font-size: 1.1em;
    margin-bottom: 8px;
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

/* .highlight-text {
    background: linear-gradient(120deg, #84fab0 0%, #8fd3f4 100%);
    padding: 2px 6px;
    border-radius: 3px;
    font-weight: 500;
} */
</style>

<div class="activity-container">

<h1 class="main-header">Activity of Day 1</h1>
<h2 class="sub-header">Foundations of Modeling & Fabrication</h2>



<div class="content-card">
    <h2 class="section-title">Course Understanding</h2>
    <p>This documentation explores the core philosophy that <span class="highlight-text">design and making are inseparable</span>.</p>
    <p>In this module, we move beyond simple manufacturing to understand that design today is <span class="highlight-text">computational, material-driven, and production-aware</span>.</p>
    
    <h3 class="subsection-title">Key Concepts</h3>
    <div class="quote-box">
        <div class="quote-box-title">The Design-to-Fabrication Continuum</div>
        <p>The process is not a straight line. It is an <strong>iterative cycle</strong>:</p>
        <ol class="numbered-list">
            <li><strong>Design:</strong> Establishing intent.</li>
            <li><strong>Model:</strong> Representing form, logic, and behavior.</li>
            <li><strong>Prototype:</strong> Testing assumptions.</li>
            <li><strong>Fabricate:</strong> Transforming models into physical artifacts.</li>
            <li><strong>Evaluate:</strong> Using feedback to improve the design.</li>
        </ol>
    </div>
</div>

<div class="content-card blue">
    <h2 class="section-title">Digital Modeling</h2>
    
    <h3 class="subsection-title">Modeling Workflow</h3>
    <p>Modeling is more than just creating a shape; it is the <strong>representation of form, logic, and behavior</strong>. My workflow incorporates two distinct approaches:</p>
    
    <ol class="numbered-list">
        <li><strong>Geometric Modeling:</strong> Defining static shapes and physical dimensions.</li>
        <li><strong>Parametric & Rule-Based Modeling:</strong> Using parameters to enable variation without needing to redesign the entire object.</li>
    </ol>
    
    <h3 class="subsection-title">Design Decisions</h3>
    <p>Every design choice was made with the understanding that <span class="highlight-text">fabrication method is a design choice</span>.</p>
    
    <h4 class="subsection-title" style="font-size: 1.2em;">Parametric Thinking</h4>
    <p>By utilizing parametric thinking, I treat my models as <strong>research tools</strong>. This allows me to:</p>
    <ul class="bullet-list">
        <li>Test assumptions about fit and function.</li>
        <li>Quickly adjust variables when physical constraints change.</li>
    </ul>
    
    <div class="image-container">
        <!-- <img src="../images/parametric.png" alt="Parametric Model"> -->
        <p class="image-caption">A parametric model.</p>
    </div>
</div>

<div class="content-card orange">
    <h2 class="section-title">Fabrication Logic</h2>
    
    <h3 class="subsection-title">Fabrication Paradigms</h3>
    <p>To transform my digital models into physical reality, I considered the four main paradigms of digital fabrication:</p>
    
    <div class="paradigm-grid">
        <div class="paradigm-item">
            <strong>Additive</strong>
            Layer-by-layer construction e.g., 3D Printing.
        </div>
        <div class="paradigm-item">
            <strong>Subtractive</strong>
            Removing material e.g., CNC Milling
        </div>
        <div class="paradigm-item">
            <strong>Formative</strong>
            Shaping via molds and forces.
        </div>
        <div class="paradigm-item">
            <strong>Hybrid</strong>
            Combining methods for optimal results.
        </div>
    </div>
    
    <h3 class="subsection-title">Material & Tolerance Considerations</h3>
    <p>Real-world fabrication introduces physical constraints that digital models often ignore.</p>
</div>

<div class="content-card teal">
    <h2 class="section-title">Reflections and Outcomes</h2>
    
    <h3 class="subsection-title">The Iterative Process</h3>
    <p>The most important lesson from this module is that the process is <span class="highlight-text">iterative, not linear</span>. Feedback was gathered at every stage, allowing me to refine the design before final production.</p>
    
    <h3 class="subsection-title">Failures as Learning</h3>
    <p>I treated every prototyping failure not as a mistake, but as a <strong>learning tool</strong>. This "evidence in design inquiry" helped me understand the limitations of my chosen machines.</p>
    
    <h3 class="subsection-title">Ethics & Sustainability</h3>
    <p>Beyond the technical skills, I reflected on the ethical implications of my work:</p>
    <ul class="bullet-list">
        <li><strong>Sustainability:</strong> considering material waste and energy use.</li>
        <li><strong>Responsibility:</strong> Designing for reuse and repair rather than disposability.</li>
    </ul>
    
    <h3 class="subsection-title">Final Learning Outcomes</h3>
    <p>Through this project, I have learned to:</p>
    <ol class="numbered-list">
        <li><strong>Design with fabrication logic</strong> in mind.</li>
        <li><strong>Understand material behavior</strong> and its impact on form.</li>
        <li><strong>Translate ideas</strong> into buildable, functional systems.</li>
    </ol>
</div>

</div>

<p style="clear: both;"></p>
<br/>