---
layout: project
type: project
image: /Users/p-roberts/aft-score-table.jpg
title: "Army Fitness Test Basic Calculator"
date: 2026
published: true
labels:
  - Army
  - AFC
  - Army Fitness
  - Holistic Health and Fitness
  - H2F
summary: "A basic caculator to compute the total score of the Army Fitness Test. "
--- 

<img width="1536" height="864" alt="ACFT-grading-table-1536x864" src="https://github.com/user-attachments/assets/ffb8cff1-9014-4214-b661-43dec93d48cf" />

# Army Fitness Test (AFT) Calculator

The Army Fitness Test (AFT) Calculator is one segment of an ongoing Leader's Book project designed to support Army leadership in managing Soldier data and readiness. Built with HTML, CSS, and JavaScript, this calculator uses standards sourced directly from army.mil/aft and Army Directive 2026-07. Once complete, this tool will be embedded into the full Leader's Book project as a linked resource for leaders in the field.

The AFT is a fitness assessment conducted by Army leadership to fulfill semi-annual requirements and evaluate Soldier readiness. The test consists of five events: the 3 Repetition Maximum Deadlift, the Hand Release Push-Up, the Sprint-Drag-Carry, the Plank, and the 2-Mile Run. Each event requires a minimum score of 60 points to pass. It is important to note that this version of the calculator does not yet distinguish scoring by age or gender. Users must first consult the official AFT scoring chart at army.mil/aft to convert their raw performance into a point score before entering it into the calculator.
This project introduced me to core web development concepts including HTML structure, CSS formatting, and JavaScript functions. The calculator uses a calculate() function that retrieves each event score by its unique element ID, sums them into a total, and evaluates the result against the passing requirement using a conditional statement. 

Building this tool reinforced my understanding of JavaScript logic, HTML framework, GitHub project development, and the importance of citing official sources when developing applications that impact real people's careers and readiness.

## Source: [army.mil/aft](https://www.army.mil/aft)
