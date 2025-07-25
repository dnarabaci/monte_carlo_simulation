# SBI Montecarlo

## Abstract

This study employs Monte Carlo simulations to explore the dynamics of a beetle population in a virtual ecosystem, focusing on the impact of point size genetics on mating success and survival. Several different variations of an environment simulations were conducted with different initial agent numbers and probabilities favoring more points and less points.

## Current status:
 __Point size genetics:__

two settings, one which favors fewer points, one which favors more points (with parameter favored = "more" or else)

- sight
    - for mating, sight = (self$beetles$points[f] - 1) or (7 - points/2) for more or less preferences, respectively
    - for food, (points + points/2) or (points + 11-points)

- more points cost more enery per iteration
    - with 4 points, energy loss in one iteration will be always 1
    - with 5 points, energy loss in one iteration will be in 10% of the cases 2
    - with 6 points, energy loss in one iteration will be in 20% of the cases 2
    - with 7 points, energy loss in one iteration will be in 30% of the cases 2
    if more is favored
    - with 7 points, energy loss in one iteration will be always 1
    - with 6 points, energy loss in one iteration will be in 10% of the cases 2
    - with 5 points, energy loss in one iteration will be in 20% of the cases 2
    - with 4 points, energy loss in one iteration will be in 30% of the cases 2

- females favor males with more points probably of chosing a male should be based on the number of points 
    - males with 7 points should have a higher chance of being selected, but 4 point males should be not without chance
    - points/7 vs 1-points/7 chance of mating, or reverse, depending on whether more or less is favored 

- monitor the average point count as well in the monitor plot
    - monitor graph has a line for average point count*50 for visibility



## Visuals
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/713217aa-3b45-455f-879c-8d1028df932d" />


## Authors
- name: Ayrin Sophie Piephoh
  affiliation: Department of Bioinformatics, University of Potsdam, Germany
- name: Duygu Nur Arabaci
  affiliation: Department of Bioinformatics, University of Potsdam, Germany
- name: Fatoumata Sow
  affiliation: Department of Bioinformatics, University of Potsdam, Germany
- name: Mekontso Tepeu Florentin Jose
  affiliation: Department of Bioinformatics, University of Potsdam, Germany
- name: Stevie Davies
  affiliation: Department of Bioinformatics, University of Potsdam, Germany



## Project status
Complete
