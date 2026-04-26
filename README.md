# cs-370
Current and Emerging Trends in Computer Science

# Project Reflection: Pirate Intelligent Agent

## Resources Used
- Python
- Jupyter Notebook
- Reinforcement Learning (Deep Q-Learning)
- Neural Networks

## Overview

Over the course of this term, I developed a Pirate Intelligent Agent using the concepts of reinforcement learning and neural networks within the Jupyter Notebook environment. The goal of the project was to design an AI agent capable of navigating a maze from start to finish, with the goal of obtaining the treasure at the end while avoiding obstacles. This project demonstrates how artificial intelligence can be applied to solve pathfinding problems through learning and adaptation rather than predefined rules, which likely would have been the standard method of solving this type of problem until recently.

The Pirate Intelligent Agent project built upon concepts introduced throughout the course, including machine learning, neural networks, and deep Q-learning. Towards the end, the agent was able to learn an efficient path to the goal through repeated training episodes, underscoring the benefits of reinforcement learning by showcasing increased accuracy over time by running repeated sessions of the maze.

---

## Work Completed

For this project, I was provided with starter code that included:
- The maze environment and structure.
- A replay memory system for storing experiences.
- A partially implemented neural network model.
- Supporting helper functions for training and evaluation.

My primary responsibility was to complete the **Q-training algorithm**, which included:
- Implementing the reinforcement learning loop.
- Applying an exploration vs. exploitation strategy (epsilon-greedy).
- Storing and replaying experiences for training.
- Updating the neural network using training batches.
- Tracking performance through win rate and loss metrics.

This portion of the project required integrating multiple concepts learned over the course of this term together to create a functioning intelligent system.

---

## What Problem Was Being Solved

The core problem addressed in this project is commonly referred to as a **pathfinding problem**, where an intelligent agent must determine the best route through an environment to reach a goal. However, instead of using traditional rule-based logic that most programs of the past would have used, the agent learns optimal behavior through repeated interaction with the environment, which serves as an excellent example of reinforcement learning.

This reflects real-world applications where environments are dynamic or too complex to solve using static algorithms, such as robotics, autonomous vehicles, and game AI.

---

## Approach and Key Concepts At Play

The approach used in this project was **Deep Q-Learning (DQN)**, which combines reinforcement learning with neural networks.

Key concepts applied include:

- **Reinforcement Learning:** The agent learns by receiving rewards or penalties based on its actions.
- **Exploration vs. Exploitation:** The agent balances trying new actions with using known successful strategies.
- **Experience Replay:** Past experiences are stored and reused to improve learning stability.
- **Neural Networks:** Used to approximate Q-values and guide decision-making.
- **Target Networks:** Help stabilize training by reducing rapid fluctuations in learning.

This approach demonstrated how reinforcement learning enables system sot optimize decision-making through repeated interaction with an environment rather than relying on predefined rules. It was readily apparent that more thorough testing required more time, and required more computational resources, but resulted in improved performance.

---

## Growth in Understanding Computer Science Concepts and Computer Science As a Field

This course served to expand my understanding of some of the key concepts behind artificial intelligence and its implementation within computer science.

Computer scientists design systems that solve complex problems by combining theory, algorithms, and practical implementation. This matters because many real-world problems cannot be solved efficiently through manual processes or simple logic alone. Additionally, those that can be solved by manual processes may be solved in an inefficient manner, and in the world of business, efficiency is critical in both technical and business contexts. Therefore, if an automated option exists that will make the process of solving a problem more time efficient, while still achieving quality results, it should at least be strongly considered, if not consistently chosen each time.

Through this project, I learned to approach problems more systematically by:
- Breaking problems into smaller, manageable components, which is in line with the previously learned concept of the SDLC.
- Evaluating multiple possible solutions before implementation.
- Understanding how algorithms behave over time rather than just producing immediate results.
- Thinking in terms of data-driven decision-making rather than fixed rules.

This shift in thinking will likely serve as a major step forward in how I will approach software development in the future.

---

## Ethical Responsibilities

Developing AI systems comes with important ethical responsibilities, particularly when those systems influence real-world decisions.

Key ethical considerations in this project included:
- **Accuracy:** Ensuring the agent makes reliable decisions.
- **Bias:** Preventing unintended bias in training data or outcomes.
- **Transparency:** Understanding how decisions are made.
- **Accountability:** Ensuring human oversight remains part of the process.

In my original work, I identified concerns such as incorrect decision-making and fairness. With a deeper understanding from this course, I now recognize the importance of incorporating safeguards such as:
- Monitoring system performance throughout the development and testing phases.
- Validating outputs before applying real-world consequences.
- Maintaining human involvement in decision-making processes as a form of 'checks and balances'.

Balancing technological capability with ethical responsibility remains a significant challenge, however, it is essential for building trustworthy AI systems.

---

## Maintainability, Readability, and Adaptability

I made efforts to ensure the code in this project was:
- Clearly structured for better readability.
- Well-commented so I may have an easier time revisiting previous work, or so others may better understand what was done and why.
- Easy to follow and modify for any future add-ons or re-writes.

This included:
- Using descriptive variable names to avoid unintentional ambiguity.
- Adding comments to explain key logic.
- Organizing the training process into logical steps that can be replicated or improved upon as AI technology continues to move forward.

These practices all serve to improve maintainability and allow others to understand and build upon the work in the future.

---

## Portfolio Artifact

This repository includes:
- The completed **Jupyter Notebook** for the Pirate Intelligent Agent.
- The implemented **Deep Q-Learning training algorithm**.
- This README file.

This artifact serves to demonstrate the ability to apply artificial intelligence concepts, implement machine learning algorithms, and reflect on both the technical and ethical aspects of my work.

---

## Conclusion

The Pirate Intelligent Agent project showcases a significant step forward in my understanding of artificial intelligence and machine learning. By applying reinforcement learning and neural networks to a practical problem, I was able to see how intelligent systems can learn and adapt over time using a real-world example. The hands-on experience obtained in this course has strengthened my ability to approach complex problems and reinforced the importance of thoughtful design and ethical responsibility in the implementation of AI and computer science in general.
