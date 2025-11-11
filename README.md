🎯 Project Overview
The Breakthrough Tech Dyslexia Toolkit is an open-source initiative that leverages AI and NLP technologies to create accessible learning experiences for individuals with dyslexia. This project combines text simplification, concept extraction, and visual mind mapping to transform complex information into dyslexia-friendly formats.
Dyslexia affects 15-20% of the population, impacting reading, writing, and information processing. This toolkit aims to reduce cognitive load and improve learning outcomes through AI-powered accessibility solutions.
🌟 Key Features

🔤 Text Simplification: Converts complex text into plain, easy-to-read language
🧠 Concept Extraction: Identifies and highlights key concepts from educational content
🗺️ Visual Mind Maps: Generates interactive, dyslexia-friendly concept maps
🎨 Accessible Design: Implements WCAG-compliant color contrast and typography
📊 Evaluation Framework: Benchmarks for measuring accessibility improvements


🚀 Live Demo ( Coming Soon - Q1'26)
🔗 Try the Demo on Hugging Face Spaces

👥 Team
This project is led by Anupama Garani as part of her mentorship work with Break Through Tech Austin, guiding students to build production-grade AI accessibility solutions.
Student Contributors
NameRoleFocus AreaSamTechnical Lead & ResearchArchitecture & Speech-to-TextShreyaNLP EngineerText SimplificationAnusha KokalaNLP EngineerText SimplificationJanice KennedyML EngineerConcept ExtractionMaha Shanawaz SyedaML EngineerConcept ExtractionCaroline ViraniFrontend DeveloperVisual Mind MapsAmshuFrontend DeveloperVisual Mind MapsAline JouaidiUX/Accessibility DesignerDyslexia-Friendly Styling

🏗️ Architecture
breakthrough-tech-dyslexia-toolkit/
├── src/
│   ├── text_simplification/     # NLP models for text simplification
│   ├── concept_extraction/       # Key concept identification
│   ├── mindmap_generator/        # Visual mind map creation
│   ├── accessibility/            # WCAG compliance & styling
│   └── evaluation/               # Benchmarking framework
├── data/
│   ├── benchmarks/               # Accessibility test datasets
│   └── samples/                  # Example inputs/outputs
├── notebooks/                    # Jupyter notebooks for experimentation
├── demo/                         # Hugging Face Space demo
├── docs/                         # Technical documentation
└── tests/                        # Unit and integration tests

📚 Technical Approach
1. Text Simplification Module

Models: Fine-tuned T5/BART for text-to-text generation
Approach: Paraphrasing complex sentences while preserving meaning
Evaluation: BLEU, SARI, and readability scores (Flesch-Kincaid)

2. Concept Extraction Module

Models: KeyBERT, spaCy NER, or custom BERT fine-tuning
Approach: Identifying main ideas, entities, and relationships
Output: Structured concept hierarchies

3. Mind Map Generator

Visualization: D3.js or Cytoscape.js for interactive graphs
Design Principles:

High contrast colors (WCAG AAA compliant)
Dyslexia-friendly fonts (OpenDyslexic, Comic Sans alternatives)
Clear node spacing and visual hierarchy
Customizable layouts

4. Accessibility Features

Typography: Adjustable font size, spacing, and style
Color Schemes: Pre-configured dyslexia-friendly palettes
Navigation: Keyboard shortcuts and screen reader support


🛠️ Installation
bash# Clone the repository
git clone https://github.com/[your-username]/breakthrough-tech-dyslexia-toolkit.git
cd breakthrough-tech-dyslexia-toolkit

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run tests
pytest tests/

# Start demo application
python demo/app.py

📖 Usage Example
pythonfrom dyslexia_toolkit import SimplifyText, ExtractConcepts, GenerateMindMap

# Initialize components
simplifier = SimplifyText(model="t5-base")
extractor = ExtractConcepts()
mapper = GenerateMindMap(style="dyslexia-friendly")

# Process complex text
text = "Photosynthesis is the biochemical process by which plants..."
simplified = simplifier.transform(text)
concepts = extractor.extract(simplified)
mindmap = mapper.create(concepts)

# Export as interactive HTML
mindmap.save("output.html")

🎓 Research & Methodology
This project draws from established research in:

Cognitive Load Theory: Reducing mental effort in learning
Universal Design for Learning (UDL): Multiple means of representation
Accessibility Standards: WCAG 2.1 Level AA/AAA compliance
Dyslexia Research: Font design, color theory, and information architecture

Key References

TBD..


🤝 Contributing
We welcome contributions from the community! Whether you're fixing bugs, adding features, or improving documentation, your help makes this toolkit better for everyone.
See CONTRIBUTING.md for guidelines.
Quick start:

Fork the repository
Create a feature branch (git checkout -b feature/amazing-feature)
Commit your changes (git commit -m 'Add amazing feature')
Push to the branch (git push origin feature/amazing-feature)
Open a Pull Request


📊 Project Milestones

 Phase 1: Project scoping and architecture design
 Phase 2: Core module development (Text Simplification, Concept Extraction)
 Phase 3: Mind map visualization and accessibility features
 Phase 4: Evaluation framework and benchmarking
 Phase 5: Hugging Face demo deployment
 Phase 6: Documentation and community release


🌍 Impact & Vision
This toolkit represents more than code—it's about democratizing education and ensuring that learning tools work for everyone, regardless of how their brain processes information.
Our Goals:

✅ Create production-ready, open-source accessibility tools
✅ Establish benchmarks for AI-powered dyslexia support
✅ Demonstrate how mentorship can drive social impact through technology
✅ Inspire other teams to build inclusive AI solutions


📬 Contact & Support
Name :
Linkedin: 

Break Through Tech Austin: breakthroughtech.org

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments

Break Through Tech for creating mentorship opportunities that bridge education and industry
Cornell Tech, Accenture, Lyft, and Goldman Sachs for supporting the BTT program
International Dyslexia Association for research and guidance
Open-source community for the tools and libraries that make this possible


🌟 Star This Project
If you find this toolkit helpful or believe in accessible education, please ⭐ star this repository to help others discover it!

Built with ❤️ by the Break Through Tech Austin Fall 2025 Cohort
