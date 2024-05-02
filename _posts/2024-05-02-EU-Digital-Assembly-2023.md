---
title: 'NordIQuEst at the EU Digital Assembly 2023'
date: 2024-05-02
permalink: /_posts/2024-05-02-EU-Digital-Assembly-2023/
published: true
layout: single
tags:
  - qal9000
  - puhuri
  - lumi
  - eu digital assembly
---

# NordIQuEst at the EU Digital Assembly 2023

On June the 15-16 2023, the European Commission held its annual Digital Assembly at Arlanda XPO, Sweden. This major event brought together policy makers from across Europe to discuss and showcase advancements in digital technologies.  
 
For the first time in 2023, the Assembly included a dedicated session on quantum technology, a rapidly developing field with the potential to revolutionize computing, communication, and materials science. 

This session featured four live demonstrations, all showcasing the cutting edge of European-based quantum technologies. 

One of the demonstrations was presented by Dr. Miroslav Dobsicek, a senior research engineer at Chalmers University of Technology and a member of the NordIQuEst project team. Dr. Dobsicek's presentation focused on the practical aspect of current state quantum computing with superconducting circuits.

{% include figure image_path="/assets/images/eu-digital-assembly-miroslav-presenting.png" alt="Screenshot of the Live Demonstration given at the EU Digital Assembly by Dr. Miroslav Dobsicek." caption="Miroslav Dobsicek presenting at the EU Digital Assembly 2023. Credit: Permanent Representation of Sweden to the European Union" %}

He demonstrated the execution of a simple quantum computing application that harnessed the combined power of geographically separated computing resources.  

This application utilized the LUMI high-performance computer (HPC) located in Finland for classical processing tasks, while simultaneously leveraging the processing power of the QAL 9000 quantum processor housed in Gothenburg, Sweden.  

The project also utilized a pan-European approach to resource management, with project resources being allocated through the Puhuri allocation service in Estonia. 

{% include figure image_path="/assets/images/eu-digital-assembly-qal9000-lumi-puhuri-interconnection.png" alt="Diagram showing of the interconnection between QAL 9000, LUMI and Puhuri." caption="Interconnection between QAL 9000, LUMI and Puhuri. Credit: Dr. Miroslav Dobsicek" %}

Dr. Dobsicek's live demonstration showcased two crucial stages involved in this innovative application.  
 
At the outset, he demonstrated a live calibration measurement of the QAL 9000 processor. Quantum computing applications rely on incredibly precise control of quantum states.  

To achieve this level of precision, Dr. Dobsicek utilized QAL 9000’s cloud RESTful API interface to perform a live recalibration measurement called a π-pulse. This specific pulse drives the transition of qubits, the quantum bits that hold information, between the quantum states of 0 and 1. With this recalibration a noticeable better state discrimination has been achieved.

{% include figure image_path="/assets/images/eu-digital-assembly-qal9000-live-tuneup.png" alt="A Screenshot of the live tune up of QAL 9000." caption="A Screenshot of the live tune up of QAL 9000. Credit: Martin Ahindura" %}

Of note is that the calibration was performed concurrently on a significant portion of the processor, focusing on12 out of the 25 total qubits available on the QAL 9000 chip. 

The state discrimination has improved after the recalibration; Less blue dots, |1> state, we present in the red point-could. 

After the successful recalibration, Dr. Dobsicek demonstrated a basic machine 
learning algorithm tailored to classify points within a two-dimensional plane. The algorithm was based on the concepts described in [1]. 

{% include figure image_path="/assets/images/eu-digital-assembly-quantum-neural-network.png" alt="Diagram showing A quantum neural network in QAL 9000 with a classical optimizer in LUMI." caption="A quantum neural network in QAL 9000 with a classical optimizer in LUMI. Credit: Dr. Miroslav dobsicek" %}

Before the demo, a neural network was encoded into the quantum processor. LUMI ran a classical optimization loop which adjusted the weights in the neural network during the training phase. 

During the live demo, LUMI generated random points within the plane, and these points were then classified by the quantum processor. This workflow effectively demonstrated a hybrid approach, where a high-performance computer and a quantum computer collaborate on a single task.  

Notably, this demonstration also highlighted the potential of geographically distributed computing resources, showcasing how collaboration across borders within the European Union can unlock advancements in this exciting field. 

The full recording of Dr. Dobsicek's demonstration, including his insightful commentary, is available for viewing on [YouTube](https://www.youtube.com/live/52vOdakwT1Q?si=lBdCI6vdNP7Q9OJl&t=18522). 

## References

[1] ['Quantum embeddings for machine learning' arXiv preprint arXiv:2001.03622 paper](https://arxiv.org/abs/2001.03622) by 'Lloyd, S., Schuld, M., Ijaz, A., Izaac, J., & Killoran, N. (2020). 
