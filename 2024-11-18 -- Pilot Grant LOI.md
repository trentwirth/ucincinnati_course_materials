Here is the revised version with each section expanded to approximately 300 words:

---

### **Research Interest and Impact**  

**Title of Research Project:**  
Behavioral Dynamics and Neural Computations of Retinotopic Optic Flow in Locomotor Control  

**Track Selected:**  
Track 1  

**Primary Applicant:**  
[Your Full Name, Degrees], [Your Title]  
College of [Your College]  
Department of [Your Department]  

**Internal/Affiliate Collaborators:**  
- Dr. Derek Wolf, [Title], College of Engineering, Department of [Engineering Department]  

**External Collaborators:**  
- Dr. Kate Bonnen, Assistant Professor, School of Optometry, Indiana University  

---

#### **Problem Statement** *(~300 words)*  

Humans rely on visual motion information to guide fundamental locomotor actions, such as medial-lateral foot placement during walking [Cite Matthis Curr Bio]. However, our understanding of the neural and behavioral mechanisms linking visual input to motor control remains incomplete, especially in dynamic and complex environments [Kate Huk 2023? Maybe]. 

The emerging combination of eye tracking and full-body motion capture represents a groundbreaking methodology [Cite Matthis Curr Bio, My Conference presentation], enabling connections between visual information and motor control that were previously inaccessible to the fields of psychophysics and biomechanics in their respective isolation. While still in its infancy, this approach demands the development of both experimentally controlled paradigms—critical for producing clean, interpretable data—and computational models that can deepen our understanding of this intricate system, a lack thereof that hinders any effort to design interventions for visual and motor disorders. Retinotopic optic flow, which is influenced by gaze direction, head motion, and environmental structure, remains understudied in its role as a control signal for motor action. Bridging this gap requires an integrated behavioral and computational neuroscience approach that leverages clean experimental data to develop predictive models, addressing unanswered questions about how sensory inputs are connected to motor outputs and unlocking progress in neuroscience, biomechanics, and clinical applications.

Our project aims to establish such a framework, providing both empirical data and computational tools to advance the field. By examining retinotopic optic flow during controlled walking tasks, developing dynamic systems models, and incorporating biologically plausible neural computations, we will address fundamental questions about sensory-motor integration. This research will not only deepen our understanding of human locomotion but also establish a foundation for translational work in clinical and rehabilitative contexts. The ability to simulate visual impairments in virtual reality (VR) offers a unique opportunity to study compensatory strategies, providing insights into designing assistive technologies and treatments for visual and motor deficits.  

---

#### **Approach** *(~300 words)*  

This project employs an innovative, interdisciplinary methodology to investigate how retinotopic optic flow influences medial-lateral foot placement during walking. By combining VR-based experiments, motion capture, and computational modeling, we aim to systematically unravel the sensory-motor dynamics at play.  

First, we will develop a controlled VR paradigm in which participants walk towards and fixate upon a visual target in a minimal, uncluttered virtual environment. Using a Meta Quest Pro HMD[cite], we will record retinotopic optic flow patterns (video sent to each eye cast in retinotopic coordinates) and use the internal eye tracking mechanism of the Meta Quest Pro to validate the fixation. Full-body motion data will be recorded using a marker-based motion capture system ([Motion Analysis]), allowing precise quantification of medial-lateral foot placement. This data will provide a robust empirical foundation for computational modeling.  

Next, I will collaborate with Dr. Derek Wolf to construct a dynamic systems model based on an inverted pendulum framework. This model will describe the relationship between retinotopic optic flow and medial-lateral foot placement. Each walking step will be treated as a “trial,” with the model constrained to use only visually available information to predict the next successful foot placement - theoretical work has demonstrated that the patterns of optical expansion ("divergence") and rotation ("curl") are sufficient to predict a body's momentum through space [Cite RF]. This model will initially focus on simplified lab data to ensure tractability.  

*Future Work*

To refine and validate the model, we will test it against real-world visuo-locomotor data collected by Dr. Kate Bonnen [Cite Berkeley]. This dataset offers an opportunity to identify model limitations, guiding improvements and suggesting new experimental directions.  

Finally, in collaboration with Dr. Oliver Layton, we will integrate biologically plausible neural computations into the model. Using simulations of MST/MT cortical cells, we aim to enhance the model’s biological realism and provide insights into the neural architecture linking visual input to locomotor output. This iterative process will culminate in a robust, experimentally validated framework that bridges behavioral and computational neuroscience.  

---

#### **Impact**

This project will create a foundational experimental and computational framework for understanding the role of retinotopic optic flow in locomotor control. By combining a clean experimental paradigm with dynamic systems modeling, this research will establish a platform for seeking larger-scale funding to expand and deepen this line of inquiry. The resulting framework will act as a “research engine” for generating new hypotheses and advancing the study of the visuo-locomotor system.

A critical aspect of this project is its commitment to open access. All data and models produced will be made publicly available, enabling other researchers to leverage the experimental datasets to develop their own models or test new hypotheses. Similarly, the computational models can serve as a starting point for refinement or application to diverse research questions. This openness will foster collaboration across disciplines, encouraging iterative improvements and broader application of the findings. In particular, computational neuroscientists will have the opportunity to develop and test deep learning networks that simulate visual and motor cortices, pushing the boundaries of biologically informed modeling [Cite Layton].

The mixed experimental and computational paradigm we propose has significant implications for clinicians and applied researchers. By illuminating how vision drives locomotor control, this research will aid in designing interventions for individuals with visual and motor impairments [Cite Paula parkinsons example]. Loss of mobility is one of the strongest predictors of a decline in quality of life [pull citation from f32]. By better understanding the mechanisms underlying visuo-locomotor control, this work lays the foundation for understanding, preserving, and improving mobility; ultimately enhancing quality of life for diverse populations.

This project is a key step toward uniting behavioral and computational neuroscience with applied research, creating a scalable, interdisciplinary platform that has the potential to transform both basic science and real-world interventions.