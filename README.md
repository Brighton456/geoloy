
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Engineering Geology Assignment - PowerPoint Ready</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Merriweather:wght@400;700&family=Roboto:wght@300;400;700&display=swap');
        
        /* PowerPoint-optimized styles */
        @media screen {
            body {
                font-family: 'Roboto', sans-serif;
                background: linear-gradient(135deg, #1e293b 0%, #334155 100%);
                color: #f1f5f9;
                line-height: 1.6;
                margin: 0;
                padding: 20px;
            }
        }
        
        @media print {
            body {
                background: white;
                color: #1e293b;
                font-size: 14pt;
                line-height: 1.4;
            }
            .question-block {
                page-break-inside: avoid;
                break-inside: avoid;
            }
            section {
                page-break-before: always;
            }
            section:first-child {
                page-break-before: auto;
            }
        }
        
        h1, h2, h3 {
            font-family: 'Merriweather', serif;
        }
        
        .slide-container {
            max-width: 1200px;
            margin: 0 auto;
            background: rgba(30, 41, 59, 0.95);
            border-radius: 12px;
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.3);
            overflow: hidden;
        }
        
        @media print {
            .slide-container {
                background: white;
                box-shadow: none;
            }
        }
        
        .section-header {
            border-bottom: 4px solid #f59e0b;
            padding-bottom: 0.75rem;
            color: #f59e0b;
            margin-bottom: 2rem;
            font-size: 2.5rem;
            font-weight: 700;
        }
        
        @media print {
            .section-header {
                color: #1e293b;
                border-bottom-color: #1e293b;
            }
        }
        
        .question-block {
            background: linear-gradient(135deg, #334155 0%, #475569 100%);
            border-left: 8px solid #2dd4bf;
            margin: 2rem 0;
            padding: 2rem;
            border-radius: 0 12px 12px 0;
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        @media print {
            .question-block {
                background: #f8fafc;
                border-left-color: #1e293b;
                box-shadow: none;
                border: 2px solid #e2e8f0;
            }
        }
        
        .question-block:hover {
            transform: translateY(-2px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.4);
        }
        
        .answer-block {
            background: rgba(63, 81, 106, 0.8);
            border-top: 2px solid #475569;
            padding: 1.5rem;
            margin-top: 1rem;
            border-radius: 8px;
        }
        
        @media print {
            .answer-block {
                background: #ffffff;
                border-top-color: #cbd5e1;
            }
        }
        
        .diagram {
            border: 3px solid #2dd4bf;
            border-radius: 8px;
            max-width: 100%;
            height: auto;
            margin: 1rem auto;
            display: block;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.3);
        }
        
        @media print {
            .diagram {
                border-color: #1e293b;
                box-shadow: none;
            }
        }
        
        .highlight-text {
            color: #f59e0b;
            font-weight: 700;
        }
        
        .accent-text {
            color: #2dd4bf;
            font-weight: 600;
        }
        
        @media print {
            .highlight-text {
                color: #1e293b;
            }
            .accent-text {
                color: #0f172a;
            }
        }
        
        .custom-list li::before {
            content: '◆';
            color: #f59e0b;
            font-weight: bold;
            display: inline-block;
            width: 1.5em;
            margin-left: -1.5em;
        }
        
        @media print {
            .custom-list li::before {
                color: #1e293b;
            }
        }
        
        /* Mobile responsiveness */
        @media (max-width: 768px) {
            .slide-container {
                margin: 10px;
                border-radius: 8px;
            }
            .section-header {
                font-size: 1.8rem;
            }
            .question-block {
                padding: 1.5rem;
                margin: 1rem 0;
            }
            h3 {
                font-size: 1.3rem;
            }
        }
        
        /* PowerPoint slide breaks */
        .page-break {
            page-break-before: always;
        }
        
        .no-break {
            page-break-inside: avoid;
        }
    </style>
</head>
<body>
    <div class="slide-container">
        <!-- Title Slide -->
        <header class="text-center p-8 no-break">
            <h1 class="text-5xl md:text-7xl font-extrabold highlight-text mb-4">Engineering Geology</h1>
            <h2 class="text-3xl md:text-4xl accent-text mb-6">Study Booklet</h2>
            <p class="text-xl md:text-2xl text-gray-300">Comprehensive Assignment Questions and Solutions</p>
            <div class="mt-8 text-lg text-gray-400">
                <p>Professional Engineering Geology Reference</p>
                <p class="mt-2">With Verified Geological Diagrams</p>
            </div>
        </header>

        <main class="p-8">
            <!-- SECTION A -->
            <section class="page-break">
                <h2 class="section-header">Section A: Mineralogy & Processes</h2>

                <!-- Question 1a -->
                <div class="question-block no-break">
                    <h3 class="text-2xl md:text-3xl font-bold text-white mb-4">1a) Significance of Engineering Geology (5 marks)</h3>
                    <div class="answer-block">
                        <p class="text-xl font-bold highlight-text mb-4">Key Applications:</p>
                        <ul class="space-y-3 pl-6 custom-list text-lg">
                            <li><span class="accent-text">Foundation Design:</span> Critical for determining stability, load-bearing capacity, and settlement characteristics</li>
                            <li><span class="accent-text">Hazard Mitigation:</span> Essential for identifying geo-hazards (faults, slopes, sinkholes) to prevent structural failure</li>
                            <li><span class="accent-text">Resource Identification:</span> Locating quality construction materials like aggregates and dimension stone</li>
                            <li><span class="accent-text">Groundwater Management:</span> Vital for controlling water during excavations and drainage design</li>
                            <li><span class="accent-text">Site Planning:</span> Guiding project feasibility and economical alignment for infrastructure</li>
                        </ul>
                    </div>
                </div>

                <!-- Question 1b -->
                <div class="question-block no-break">
                    <h3 class="text-2xl md:text-3xl font-bold text-white mb-4">1b) Geological Phenomena in Engineering</h3>
                    <div class="answer-block space-y-6">
                        <div>
                            <p class="text-xl font-bold highlight-text">i) Plate Tectonics (3 marks)</p>
                            <p class="text-lg mb-4">Theory of lithospheric plate movement. Engineers must account for <span class="accent-text">seismic risk</span> and <span class="accent-text">volcanism</span> at plate boundaries, requiring specialized structural designs.</p>
                            <div class="text-center bg-geo-card p-4 rounded-lg">
                                <img src="https://oceanexplorer.noaa.gov/ocean-fact/media/plate_boundaries.jpg" 
                                     alt="Plate Tectonic Boundaries" 
                                     class="diagram"
                                     onerror="this.onerror=null; this.src='https://placehold.co/800x400/334155/f59e0b?text=Plate+Tectonic+Boundaries'">
                                <p class="text-sm text-gray-400 mt-2">Figure 1.1: Types of Plate Tectonic Boundaries</p>
                            </div>
                        </div>

                        <div>
                            <p class="text-xl font-bold highlight-text">ii) Igneous Rock Formation (3 marks)</p>
                            <p class="text-lg">Solidification of magma/lava creates rocks with high crystalline strength. Intrusive rocks (granite) serve as superior <span class="accent-text">foundation materials</span> and durable <span class="accent-text">aggregates</span>.</p>
                        </div>

                        <div>
                            <p class="text-xl font-bold highlight-text">iii) Physical Weathering (3 marks)</p>
                            <p class="text-lg">Mechanical breakdown (frost wedging, thermal expansion) fragments rock, creating <span class="accent-text">unstable slopes</span> and weaker residual soils affecting foundation stability.</p>
                        </div>

                        <div>
                            <p class="text-xl font-bold highlight-text">iv) Metamorphic Rock Formation (3 marks)</p>
                            <p class="text-lg">Heat/pressure transformation creates foliation planes representing significant <span class="accent-text">weakness zones</span> that can cause shear failure in slopes and tunnels.</p>
                        </div>
                    </div>
                </div>

                <!-- Question 3 -->
                <div class="question-block no-break">
                    <h3 class="text-2xl md:text-3xl font-bold text-white mb-4">3) Geological Factors for Building Stones (6 marks)</h3>
                    <div class="answer-block">
                        <ul class="space-y-3 pl-6 custom-list text-lg">
                            <li><span class="accent-text">Mechanical Strength:</span> High crushing strength and impact resistance</li>
                            <li><span class="accent-text">Durability:</span> Resistance to weathering and chemical attack</li>
                            <li><span class="accent-text">Porosity/Permeability:</span> Low values prevent water absorption and decay</li>
                            <li><span class="accent-text">Texture/Grain Size:</span> Uniformity for better finishing and durability</li>
                            <li><span class="accent-text">Aesthetic Quality:</span> Color, patterns, and polishability</li>
                            <li><span class="accent-text">Discontinuities:</span> Jointing/bedding that allows efficient quarrying</li>
                        </ul>
                    </div>
                </div>

                <!-- Question 4 -->
                <div class="question-block no-break">
                    <h3 class="text-2xl md:text-3xl font-bold text-white mb-4">4) Mineral Properties Distinctions</h3>
                    <div class="answer-block space-y-6">
                        <div>
                            <p class="text-xl font-bold highlight-text">i) Cleavage vs Fracture (3 marks)</p>
                            <ul class="list-disc ml-6 text-lg space-y-2">
                                <li><span class="accent-text">Cleavage:</span> Breaking along smooth crystal structure planes (e.g., mica sheets)</li>
                                <li><span class="accent-text">Fracture:</span> Irregular breaking unrelated to crystal structure (e.g., quartz conchoidal)</li>
                            </ul>
                        </div>

                        <div>
                            <p class="text-xl font-bold highlight-text">ii) Streak vs Lustre (3 marks)</p>
                            <ul class="list-disc ml-6 text-lg space-y-2">
                                <li><span class="accent-text">Streak:</span> Color of mineral powder (more reliable than body color)</li>
                                <li><span class="accent-text">Lustre:</span> Surface appearance in reflected light (metallic, vitreous, dull)</li>
                            </ul>
                        </div>

                        <div>
                            <p class="text-xl font-bold highlight-text">iii) Color, Hardness, Tenacity (3 marks)</p>
                            <ul class="list-disc ml-6 text-lg space-y-2">
                                <li><span class="accent-text">Color:</span> Perceived hue (variable due to impurities)</li>
                                <li><span class="accent-text">Hardness:</span> Scratch resistance (Moh's scale)</li>
                                <li><span class="accent-text">Tenacity:</span> Resistance to breaking/bending (brittle, malleable)</li>
                            </ul>
                        </div>
                    </div>
                </div>

                <!-- Question 5 -->
                <div class="question-block no-break">
                    <h3 class="text-2xl md:text-3xl font-bold text-white mb-4">5) Moh's Hardness Scale (3 marks)</h3>
                    <div class="answer-block">
                        <p class="text-lg mb-4">Relative scale from 1 (<span class="accent-text">Talc</span>) to 10 (<span class="accent-text">Diamond</span>) measuring scratch resistance. Essential for field identification and predicting abrasive behavior in engineering applications.</p>
                        <div class="text-center bg-geo-card p-4 rounded-lg">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/5/5f/Mohs_scale_vs_absolute_hardness.png" 
                                 alt="Mohs Hardness Scale" 
                                 class="diagram"
                                 onerror="this.onerror=null; this.src='https://placehold.co/800x300/334155/f59e0b?text=Mohs+Hardness+Scale'">
                            <p class="text-sm text-gray-400 mt-2">Figure 1.2: Moh's Scale Comparison to Absolute Hardness</p>
                        </div>
                    </div>
                </div>
            </section>

            <!-- SECTION B -->
            <section class="page-break">
                <h2 class="section-header">Section B: Structural & Stratigraphic Geology</h2>

                <!-- Question 2 -->
                <div class="question-block no-break">
                    <h3 class="text-2xl md:text-3xl font-bold text-white mb-4">2) Intrusive Igneous Landforms</h3>
                    <div class="answer-block">
                        <p class="text-xl font-bold highlight-text mb-4">Major Types:</p>
                        <ul class="list-disc ml-6 space-y-3 text-lg">
                            <li><span class="accent-text">Batholiths:</span> Largest discordant intrusions, forming mountain cores after erosion</li>
                            <li><span class="accent-text">Dykes:</span> Vertical wall-like discordant intrusions filling fractures</li>
                            <li><span class="accent-text">Sills:</span> Horizontal sheet-like concordant intrusions between beds</li>
                            <li><span class="accent-text">Laccoliths:</span> Lens-shaped concordant intrusions creating dome structures</li>
                        </ul>
                        <div class="text-center bg-geo-card p-4 rounded-lg mt-4">
                            <img src="https://open.maricopa.edu/physicalgeologymaricopa/wp-content/uploads/sites/236/2022/05/Figure-4.4.5.png" 
                                 alt="Intrusive Igneous Landforms" 
                                 class="diagram"
                                 onerror="this.onerror=null; this.src='https://placehold.co/800x400/334155/f59e0b?text=Intrusive+Igneous+Landforms'">
                            <p class="text-sm text-gray-400 mt-2">Figure 2.1: Dykes, Sills, Batholiths, and Laccoliths</p>
                        </div>
                    </div>
                </div>

                <!-- Question 4i -->
                <div class="question-block no-break">
                    <h3 class="text-2xl md:text-3xl font-bold text-white mb-4">4i) Plutonic vs Volcanic Rocks (3 marks)</h3>
                    <div class="answer-block">
                        <ul class="list-disc ml-6 space-y-3 text-lg">
                            <li><span class="accent-text">Plutonic (Intrusive):</span> Slow cooling deep underground, coarse-grained texture (e.g., Granite)</li>
                            <li><span class="accent-text">Volcanic (Extrusive):</span> Rapid cooling at surface, fine-grained or glassy texture (e.g., Basalt)</li>
                        </ul>
                    </div>
                </div>

                <!-- Question 4ii -->
                <div class="question-block no-break">
                    <h3 class="text-2xl md:text-3xl font-bold text-white mb-4">4ii) Earth's Four Regions (6 marks)</h3>
                    <div class="answer-block">
                        <ul class="list-disc ml-6 space-y-3 text-lg mb-4">
                            <li><span class="accent-text">Crust:</span> Thin, brittle outer layer - zone for civil engineering</li>
                            <li><span class="accent-text">Mantle:</span> Thick, dense ductile layer driving plate tectonics</li>
                            <li><span class="accent-text">Outer Core:</span> Liquid iron-nickel layer generating magnetic field</li>
                            <li><span class="accent-text">Inner Core:</span> Solid, extremely dense iron-nickel center</li>
                        </ul>
                        <div class="text-center bg-geo-card p-4 rounded-lg">
                            <img src="https://www.usgs.gov/media/images/cutaway-views-showing-internal-structure-earth-left.jpg" 
                                 alt="Earth's Internal Structure" 
                                 class="diagram"
                                 onerror="this.onerror=null; this.src='https://placehold.co/800x400/334155/f59e0b?text=Earth%27s+Internal+Structure'">
                            <p class="text-sm text-gray-400 mt-2">Figure 2.2: Cross-section of Earth's Internal Structure</p>
                        </div>
                    </div>
                </div>

                <!-- Question 4iii -->
                <div class="question-block no-break">
                    <h3 class="text-2xl md:text-3xl font-bold text-white mb-4">4iii) Quarrying Operations Methods</h3>
                    <div class="answer-block">
                        <ul class="list-disc ml-6 space-y-3 text-lg">
                            <li><span class="accent-text">Blasting:</span> Explosives fracture rock for mass aggregate production</li>
                            <li><span class="accent-text">Ripping/Mechanical:</span> Heavy machinery breaks weaker, weathered rock</li>
                            <li><span class="accent-text">Diamond Wire Sawing:</span> Precision method for high-value dimension stone</li>
                            <li><span class="accent-text">Hydraulic Splitting:</span> Uses wedges to split stone along existing joints</li>
                        </ul>
                    </div>
                </div>

                <!-- Question 5 -->
                <div class="question-block no-break">
                    <h3 class="text-2xl md:text-3xl font-bold text-white mb-4">5) Geological Structures Formation</h3>
                    <div class="answer-block space-y-6">
                        <div>
                            <p class="text-xl font-bold highlight-text">i) Faults</p>
                            <p class="text-lg mb-4">Fractures with rock movement due to tectonic stress. Types: <span class="accent-text">Normal</span> (tension), <span class="accent-text">Reverse</span> (compression), <span class="accent-text">Strike-Slip</span> (shear). Major infrastructure hazard.</p>
                            <div class="text-center bg-geo-card p-4 rounded-lg">
                                <img src="https://open.maricopa.edu/geologylab/wp-content/uploads/sites/236/2022/06/Figure-6.1.4.png" 
                                     alt="Geological Fault Types" 
                                     class="diagram"
                                     onerror="this.onerror=null; this.src='https://placehold.co/800x350/334155/f59e0b?text=Geological+Fault+Types'">
                                <p class="text-sm text-gray-400 mt-2">Figure 2.3: Normal, Reverse, and Strike-Slip Faults</p>
                            </div>
                        </div>

                        <div>
                            <p class="text-xl font-bold highlight-text">ii) Folds</p>
                            <p class="text-lg mb-4">Bends in strata from compressional stress. <span class="accent-text">Anticlines</span> arch up, <span class="accent-text">Synclines</span> trough down. Affect slope stability and groundwater flow.</p>
                            <div class="text-center bg-geo-card p-4 rounded-lg">
                                <img src="https://upload.wikimedia.org/wikipedia/commons/2/2a/Syncline_and_anticline.jpg" 
                                     alt="Geological Fold Structures" 
                                     class="diagram"
                                     onerror="this.onerror=null; this.src='https://placehold.co/800x350/334155/f59e0b?text=Geological+Fold+Structures'">
                                <p class="text-sm text-gray-400 mt-2">Figure 2.4: Anticline and Syncline Structures</p>
                            </div>
                        </div>

                        <div>
                            <p class="text-xl font-bold highlight-text">iii) Aquifers</p>
                            <p class="text-lg mb-4">Permeable formations yielding significant groundwater. Require high <span class="accent-text">porosity</span> (storage) and <span class="accent-text">permeability</span> (flow). Bounded by impermeable layers.</p>
                            <div class="text-center bg-geo-card p-4 rounded-lg">
                                <img src="https://www.usgs.gov/media/images/aquifers-and-wells.jpg" 
                                     alt="Aquifer Systems" 
                                     class="diagram"
                                     onerror="this.onerror=null; this.src='https://placehold.co/800x350/334155/f59e0b?text=Aquifer+Systems'">
                                <p class="text-sm text-gray-400 mt-2">Figure 2.5: Confined and Unconfined Aquifer Systems</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Question 6 -->
                <div class="question-block no-break">
                    <h3 class="text-2xl md:text-3xl font-bold text-white mb-4">6) Non-Metallic Texture Terms</h3>
                    <div class="answer-block">
                        <ul class="list-disc ml-6 space-y-2 text-lg">
                            <li><span class="accent-text">Vitreous</span> (Glassy)</li>
                            <li><span class="accent-text">Pearly</span></li>
                            <li><span class="accent-text">Silky</span> (Fibrous)</li>
                            <li><span class="accent-text">Resinous</span></li>
                            <li><span class="accent-text">Greasy</span></li>
                            <li><span class="accent-text">Dull/Earthy</span></li>
                        </ul>
                    </div>
                </div>

                <!-- Question 7i -->
                <div class="question-block no-break">
                    <h3 class="text-2xl md:text-3xl font-bold text-white mb-4">7i) Igneous Rocks: Formation & Classification</h3>
                    <div class="answer-block">
                        <p class="text-xl font-bold highlight-text mb-3">Formation:</p>
                        <p class="text-lg mb-4">Crystallization of magma/lava. Cooling rate determines crystal size and texture.</p>
                        <p class="text-xl font-bold highlight-text mb-3">Classification:</p>
                        <ul class="list-disc ml-6 space-y-2 text-lg">
                            <li><span class="accent-text">Origin/Texture:</span> Intrusive (coarse-grained) or Extrusive (fine-grained)</li>
                            <li><span class="accent-text">Composition:</span> Felsic (high silica, light) or Mafic (low silica, dark)</li>
                        </ul>
                    </div>
                </div>
            </section>

            <!-- SECTION C -->
            <section class="page-break">
                <h2 class="section-header">Section C: Advanced Topics & Applications</h2>

                <!-- Question 7ii & 7iii -->
                <div class="question-block no-break">
                    <h3 class="text-2xl md:text-3xl font-bold text-white mb-4">7ii & 7iii) Sedimentary & Metamorphic Rocks</h3>
                    <div class="answer-block space-y-6">
                        <div>
                            <p class="text-xl font-bold highlight-text">ii) Sedimentary Rocks</p>
                            <p class="text-lg"><span class="accent-text">Formation:</span> Lithification of fragments, precipitates, or organic matter in layered structures.</p>
                            <p class="text-lg"><span class="accent-text">Classification:</span> Clastic (grain size), Chemical (precipitation), Organic (biological accumulation).</p>
                        </div>
                        <div>
                            <p class="text-xl font-bold highlight-text">iii) Metamorphic Rocks</p>
                            <p class="text-lg"><span class="accent-text">Formation:</span> Transformation by heat/pressure changing mineralogy and texture without melting.</p>
                            <p class="text-lg"><span class="accent-text">Classification:</span> Foliated (layered) or Non-foliated (massive).</p>
                        </div>
                    </div>
                </div>

                <!-- Question 8 -->
                <div class="question-block no-break">
                    <h3 class="text-2xl md:text-3xl font-bold text-white mb-4">8) Geological Hazards to Engineering</h3>
                    <div class="answer-block space-y-6">
                        <div>
                            <p class="text-xl font-bold highlight-text">i) Earthquakes</p>
                            <p class="text-lg">Ground shaking, <span class="accent-text">liquefaction</span>, ground rupture. Requires seismic design codes and energy dampening systems.</p>
                        </div>
                        <div>
                            <p class="text-xl font-bold highlight-text">ii) Landslides</p>
                            <p class="text-lg">Destruction of infrastructure, river damming. Mitigation: <span class="accent-text">slope stability analysis</span>, drainage, reinforcement.</p>
                        </div>
                        <div>
                            <p class="text-xl font-bold highlight-text">iii) Volcanism</p>
                            <p class="text-lg">Lava flows, ash fall, pyroclastic flows. Requires <span class="accent-text">site avoidance</span> or specialized defenses.</p>
                        </div>
                    </div>
                </div>

                <!-- Question 9 -->
                <div class="question-block no-break">
                    <h3 class="text-2xl md:text-3xl font-bold text-white mb-4">9) Groundwater Effects on Civil Engineering</h3>
                    <div class="answer-block">
                        <ul class="space-y-3 pl-6 custom-list text-lg">
                            <li><span class="accent-text">Uplift & Buoyancy:</span> Hydrostatic pressure can lift lightweight structures</li>
                            <li><span class="accent-text">Reduced Effective Stress:</span> Water pressure decreases soil/rock strength</li>
                            <li><span class="accent-text">Increased Lateral Pressure:</span> High water tables stress retaining structures</li>
                            <li><span class="accent-text">Dewatering Costs:</span> Often the most expensive foundation project component</li>
                            <li><span class="accent-text">Chemical Deterioration:</span> Aggressive water causes corrosion of concrete/steel</li>
                        </ul>
                    </div>
                </div>

                <!-- Question 10 -->
                <div class="question-block no-break">
                    <h3 class="text-2xl md:text-3xl font-bold text-white mb-4">10) Ground Investigation: Objectives & Stages</h3>
                    <div class="answer-block space-y-4">
                        <div>
                            <p class="text-xl font-bold highlight-text">Objectives:</p>
                            <ul class="list-disc ml-6 space-y-2 text-lg">
                                <li>Determine sub-surface stratification and materials</li>
                                <li>Assess mechanical properties for design parameters</li>
                                <li>Locate geological hazards and groundwater conditions</li>
                                <li>Provide recommendations for safe, economical design</li>
                            </ul>
                        </div>
                        <div>
                            <p class="text-xl font-bold highlight-text">Stages:</p>
                            <ul class="list-decimal ml-6 space-y-2 text-lg">
                                <li><span class="accent-text">Desk Study:</span> Review existing geological data and maps</li>
                                <li><span class="accent-text">Reconnaissance:</span> Initial site walkover by experienced geologist</li>
                                <li><span class="accent-text">Exploratory Investigation:</span> Invasive work (boreholes, testing)</li>
                                <li><span class="accent-text">Laboratory Testing:</span> Test samples for engineering properties</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Summary Slide -->
            <section class="page-break">
                <div class="text-center p-8 no-break">
                    <h2 class="section-header text-center">Key Takeaways</h2>
                    <div class="grid md:grid-cols-2 gap-8 text-lg">
                        <div class="bg-geo-card p-6 rounded-lg">
                            <h3 class="text-2xl font-bold highlight-text mb-4">Engineering Applications</h3>
                            <ul class="text-left space-y-2">
                                <li>• Foundation design & stability</li>
                                <li>• Hazard assessment & mitigation</li>
                                <li>• Material selection & quarrying</li>
                                <li>• Groundwater management</li>
                            </ul>
                        </div>
                        <div class="bg-geo-card p-6 rounded-lg">
                            <h3 class="text-2xl font-bold highlight-text mb-4">Geological Principles</h3>
                            <ul class="text-left space-y-2">
                                <li>• Rock formation & classification</li>
                                <li>• Structural geology & tectonics</li>
                                <li>• Weathering & soil mechanics</li>
                                <li>• Site investigation methods</li>
                            </ul>
                        </div>
                    </div>
                    <div class="mt-8 text-xl accent-text">
                        <p>Engineering Geology: Foundation of Safe Infrastructure</p>
                    </div>
                </div>
            </section>
        </main>

        <!-- Footer -->
        <footer class="text-center p-6 text-gray-400 no-break">
            <p class="text-sm">Engineering Geology Study Booklet - Professional Reference</p>
            <p class="text-xs mt-2">Optimized for PowerPoint conversion and mobile viewing</p>
        </footer>
    </div>
</body>
</html>
