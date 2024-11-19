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
- Dr. Oliver Layton, Assistant Professor, Department of Computer Science, Colby College  

---

#### **Problem Statement** *(~300 words)*  

Humans rely on visual motion information to guide fundamental locomotor actions, such as medial-lateral foot placement during walking. However, our understanding of the neural and behavioral mechanisms linking visual input to motor control remains incomplete, especially in dynamic and complex environments. 

The emerging combination of eye tracking and full-body motion capture represents a groundbreaking methodology, enabling connections between visual information and motor control that were previously inaccessible to the fields of psychophysics and biomechanics in their respective isolation. This knowledge gap restricts progress in neuroscience, biomechanics, and clinical applications, leaving unanswered how sensory inputs are connected to motor outputs.  

While still in its infancy, this approach demands the development of both experimentally controlled paradigms—critical for producing clean, interpretable data—and computational models that can deepen our understanding of this intricate system, a lack thereof that hinders any effort to design interventions for visual and motor disorders. Retinotopic optic flow, which is influenced by gaze direction, head motion, and environmental structure, remains understudied in its role as a control signal for motor action. Bridging this gap requires a combined behavioral and computational neuroscience approach, leveraging clean experimental data to develop predictive models.  

Our project aims to establish such a framework, providing both empirical data and computational tools to advance the field. By examining retinotopic optic flow during controlled walking tasks, developing dynamic systems models, and incorporating biologically plausible neural computations, we will address fundamental questions about sensory-motor integration. This research will not only deepen our understanding of human locomotion but also establish a foundation for translational work in clinical and rehabilitative contexts. The ability to simulate visual impairments in virtual reality (VR) offers a unique opportunity to study compensatory strategies, providing insights into designing assistive technologies and treatments for visual and motor deficits.  

---

#### **Approach** *(~300 words)*  

This project employs an innovative, interdisciplinary methodology to investigate how retinotopic optic flow influences medial-lateral foot placement during walking. By combining VR-based experiments, motion capture, and computational modeling, we aim to systematically unravel the sensory-motor dynamics at play.  

First, we will develop a controlled VR paradigm in which participants walk towards and fixate upon a visual target in a minimal, uncluttered virtual environment. Using a Meta Quest Pro HMD, we will record retinotopic optic flow patterns (video sent to each eye cast in retinotopic coordinates) and use the internal eye tracking mechanism of the Meta Quest Pro to validate the fixation. Full-body motion data will be captured using a marker-based motion analysis system (Motion Analysis), allowing precise quantification of medial-lateral foot placement. This data will provide a robust empirical foundation for computational modeling.  

Next, I will collaborate with Dr. Derek Wolf to construct a dynamic systems model based on an inverted pendulum framework. This model will describe the relationship between retinotopic optic flow and medial-lateral foot placement. Each walking step will be treated as a “trial,” with the model constrained to use only visually available information to predict the next successful foot placement - theoretical work has demonstrated that the patterns of optical expansion ("divergence") and rotation ("curl") are sufficient to predict a body's momentum through space [Cite RF]. This model will initially focus on simplified lab data to ensure tractability.  

*Future Work*

To refine and validate the model, we will test it against real-world visuo-locomotor data collected by Dr. Kate Bonnen [Cite Berkeley]. This dataset offers an opportunity to identify model limitations, guiding improvements and suggesting new experimental directions.  

Finally, in collaboration with Dr. Oliver Layton, we will integrate biologically plausible neural computations into the model. Using simulations of MST/MT cortical cells, we aim to enhance the model’s biological realism and provide insights into the neural architecture linking visual input to locomotor output. This iterative process will culminate in a robust, experimentally validated framework that bridges behavioral and computational neuroscience.  

---

#### **Impact**

The anticipated outcome of this project is a novel experimental and computational framework that advances our understanding of how visual motion signals guide locomotor control. Specifically, we aim to illuminate how retinotopic optic flow—captured during walking tasks—mediates medial-lateral foot placement, with implications for neuroscience, biomechanics, and clinical applications.  

This research will generate clean, tractable datasets and dynamic systems models that lay the groundwork for studying the sensory-motor integration underpinning locomotion. These findings will establish a foundation for long-term collaborations between behavioral scientists and computational neuroscientists, fostering interdisciplinary advancements. By bridging behavioral dynamics with neural computations, this project will create a scalable paradigm for investigating broader sensory-motor processes.  

A key translational goal of this work is its potential application to the study of visual and motor disorders. For instance, the VR paradigm developed here can simulate visual impairments such as glaucoma, allowing researchers to investigate how healthy individuals adapt to these conditions. This approach can provide valuable insights into the compensatory mechanisms employed by the nervous system, informing the development of rehabilitation protocols and assistive technologies for individuals with motor or visual deficits.  

Additionally, the integration of computational models offers a powerful tool for predicting and understanding real-world locomotor behavior. Future collaborations with Dr. Bonnen and Dr. Layton ensure the relevance and scalability of our findings, connecting empirical data to biologically informed models. The long-term impact includes not only advancing basic science but also providing practical solutions for clinical and rehabilitative challenges.  

Ultimately, this project contributes to a deeper understanding of human locomotion and its neural underpinnings, empowering researchers, clinicians, and rehabilitation specialists to address complex sensory-motor challenges with innovative tools and approaches.  
