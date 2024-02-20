# Awesome Vision Neuroscience

[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)](https://github.com/cosyne2024-sos/awesome-vision-neuroscience/pulls) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Stars](https://img.shields.io/github/stars/cosyne2024-sos/awesome-vision-neuroscience?color=yellow)  ![Forks](https://img.shields.io/github/forks/cosyne2024-sos/awesome-vision-neuroscience?color=blue&label=Fork)

A curated collection of resources and research on vision neuroscience, with a focus on efficient neural representation and active vision following the [Sharpening Our Sight workshop](https://sites.google.com/view/cosyne2024-sos/home) at CoSyNe 2024. 

This is a collaborative work-in-progress. Please contribute via PRs!


## Contents


- [**Educational Resources**](#resources)
- [**Research Papers**](#research)
  - [Sharpening Our Sight Workshop](#SOSworkshop)
  - [Active Vision](#activevision)
  - [Neural Representations](#neurreps)
  - [Methods](#methods)
- [**Datasets**](#datasets)
- [**Software Libraries**](#software)
- [**Conferences and Workshops**](#conferences)




<br /><br />

<a name="resources" />

# Educational Resources

<a name="research" />

# Research Papers


<a name="SOSworkshop" />

## [Sharpening Our Sight Workshop](https://sites.google.com/view/cosyne2024-sos/home)

**Abstract**

Vision is remarkably efficient, capable of rapidly perceiving rich visual detail despite limited computational resources. To understand this feat, we must consider both how the visual system represents complex natural stimuli efficiently, as well as how active perceptual processes guide selective attention. This workshop brings together leading researchers investigating efficient representation strategies and goal-directed mechanisms of natural vision.

To explore representational frameworks for natural stimuli, this workshop will overview different stimulation and analysis approaches used across visual areas to study complex natural stimuli.  In parallel, it will examine how active perceptual processes shape efficient representation. Talks will explore how the visual system optimizes representation based on motivational drivers and behavioral objectives within natural environments. This goal-directed approach helps vision prioritize the most behaviourally relevant stimuli.

By integrating theory, machine learning, and experimental data, this interdisciplinary workshop aims to advance our conceptualization of vision as both an efficient representational and an active, goal-directed process of sense-making. Achieving a deeper understanding of these fundamental aspects of perception has implications for both neuroscience and developing more human-like computer vision.

### Speakers & Selected Contributions 

We selected two relevant papers from each speaker at our Cosyne workshop, with that we would like to kickstart this repository hosting relevant papers in vision neuroscience, leaning towards computation and intersections between active vision and efficient neural representations.

* [Cris Niell](https://nielllab.uoregon.edu/): Neural dynamics underlying active vision in the mouse
    * [**Movement-Related Signals in Sensory Areas: Roles in Natural Behavior** (2020) <br /> *Philip RL Parker, Morgan A Brown, Matthew C Smear, Cristopher M Niell* <br />](https://www.cell.com/trends/neurosciences/fulltext/S0166-2236(20)30123-5)
    * [**Movement-Related Signals in Sensory Areas: Roles in Natural Behavior** (2020) <br /> *Philip RL Parker, Morgan A Brown, Matthew C Smear, Cristopher M Niell* <br />](https://www.cell.com/trends/neurosciences/fulltext/S0166-2236(20)30123-5)

* [Carsen Stringer](https://www.janelia.org/people/carsen-stringer): Towards a simplified model of primary visual cortex
    * [**Spontaneous behaviors drive multidimensional, brainwide activity** (2019) <br /> *Carsen Stringer, Marius Pachitariu, Nicholas Steinmetz, Charu Bai Reddy, Matteo Carandini, Kenneth D Harris* <br />](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6525101/)
    * [**High-precision coding in visual cortex** (2021) <br /> *Carsen Stringer, Michalis Michaelos, Dmitri Tsyboulski, Sarah E Lindo, Marius Pachitariu* <br />](https://www.cell.com/cell/pdf/S0092-8674(21)00373-1.pdf)
 
* [Christopher Summerfield](https://nielllab.uoregon.edu/): How prospection skews the human representation of space during navigation
  * [**Movement-Related Signals in Sensory Areas: Roles in Natural Behavior** (2020) <br /> *Philip RL Parker, Morgan A Brown, Matthew C Smear, Cristopher M Niell* <br />](https://www.cell.com/trends/neurosciences/fulltext/S0166-2236(20)30123-5)
  * [**Movement-Related Signals in Sensory Areas: Roles in Natural Behavior** (2020) <br /> *Philip RL Parker, Morgan A Brown, Matthew C Smear, Cristopher M Niell* <br />](https://www.cell.com/trends/neurosciences/fulltext/S0166-2236(20)30123-5)

* [Stuart Trenholm](https://nielllab.uoregon.edu/): On assigning semantic meaning to the preferred stimulus of a visual neuron
  * [**Movement-Related Signals in Sensory Areas: Roles in Natural Behavior** (2020) <br /> *Philip RL Parker, Morgan A Brown, Matthew C Smear, Cristopher M Niell* <br />](https://www.cell.com/trends/neurosciences/fulltext/S0166-2236(20)30123-5)
  * [**Movement-Related Signals in Sensory Areas: Roles in Natural Behavior** (2020) <br /> *Philip RL Parker, Morgan A Brown, Matthew C Smear, Cristopher M Niell* <br />](https://www.cell.com/trends/neurosciences/fulltext/S0166-2236(20)30123-5)

* [Wiktor Młynarski](https://www.gsn.uni-muenchen.de/people/faculty/core/mlynarski/index.html): Interacting with the environment through flexible sensory codes
  * [**Efficient and adaptive sensory codes** (2022) <br /> *Wiktor F. Młynarski & Ann M. Hermundstad* <br />](https://www.nature.com/articles/s41593-021-00846-0)
  * [**Efficient coding theory of dynamic attentional modulation** (2022) <br /> *Wiktor Młynarski, Gašper Tkačik* <br />](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.3001889)

* [Andreas Tolias](https://toliaslab.org/): A Neuro-AI approach to decrypting neural representations
  * [**Movement-Related Signals in Sensory Areas: Roles in Natural Behavior** (2020) <br /> *Philip RL Parker, Morgan A Brown, Matthew C Smear, Cristopher M Niell* <br />](https://www.cell.com/trends/neurosciences/fulltext/S0166-2236(20)30123-5)
  * [**Movement-Related Signals in Sensory Areas: Roles in Natural Behavior** (2020) <br /> *Philip RL Parker, Morgan A Brown, Matthew C Smear, Cristopher M Niell* <br />](https://www.cell.com/trends/neurosciences/fulltext/S0166-2236(20)30123-5)

* [Sylvia Schröder](https://profiles.sussex.ac.uk/p531789-sylvia-schroeder): The impact of behavior and internal states on subcortical visual processing
  * [**Arousal modulates retinal output** (2020) <br /> *Sylvia Schröder, Nicholas A Steinmetz, Michael Krumin, Marius Pachitariu, Matteo Rizzi, Leon Lagnado, Kenneth D Harris, Matteo Carandini* <br />](https://www.cell.com/neuron/pdf/S0896-6273(20)30318-4.pdf)

* [Jin Hwa Lee](https://jinhl9.github.io/): CEBRA Tutorial on Vision Dataset
  * [**Learnable latent embeddings for joint behavioural and neural analysis** (2023) <br /> *Steffen Schneider, Jin Hwa Lee, Mackenzie Weygandt Mathis* <br />](https://www.nature.com/articles/s41586-023-06031-6)
 

<a name="activevision" />

## Active Vision


<a name="neurreps" />

## Neural Representations


<a name="methods" />

## Methods

<a name="datasets" />

# Datasets


<a name="software" />

# Software Libraries

<a name="conferences" />

# Conferences and Workshops


