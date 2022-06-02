# VLPB Assembly Workshop

## Location and travel
By invitation only!

Jun 7-8, 2022 - Delft Lecture room F206 (lecture room G) - building 22    

https://iamap.tudelft.nl/en/poi/applied-physics-faculty-of-applied-physics-2/

Keep in mind that parking your car is non-trivial and may add 10-15 minutes to regular travel time.

Workshop will be taught in English
 

# Tools and preparation
This is a bring your own machine workshop.

A conda package is available for each day. Review the exercise documentations to install them.

You will need a laptop with a linux-like environment available that can run the pre-packaged environment with its tools. You can use any linux-like environment: WSL2, linux, Mac, VM or a remote system. This system must support conda environment mentioned above
 
# Schedule

## June 7 -- Assembly in the context of haplotypes
 
### Topics 
- Assembly algorithm theory: de Brujn graphs and overlap-layout-consensus
- Assembly evaluation, polishing and scaffolding 

### Exercises
- Read QC (`NanoPlot`)
- Assembly using long and short reads (`Miniasm` and `Flye`)
- Assembly evaluation (`Quast`)
- Assembly visualization (`Bandage`)

### Planning

| &nbsp;      | &nbsp;                                                                       |
|-------------|------------------------------------------------------------------------------|
| 8:45        | Arrival                                                                      |
| 9:00        | Start                                                                        |
| 9:00-9:45   | Lecture: assembly part 1                                                     |
| 10:00-10:45 | Lecture: assembly part 2                                                     |
| 10:45-11:00 | Coffee break                                                                 |
| 11:00-12:30 | Exercises: getting started with practical environment and start of exercises |
| 12:30-13:30 | Lunch                                                                        |
| 13:30-15:15 | Exercises: assembly                                                          |
| 15:15-15:30 | Coffee break                                                                 |
| 15:30-15:45 | Lecture: assembly evaluation and visualization                               |
| 16:00-16:45 | Exercises: assembly                                                          |
| 16:45-17:00 | Day 1 wrap-up                                                                |

- You can find the documentation for day 1 exercises [HERE](https://abeellab.github.io/vlpb-assembly-workshop/exercises-day1.html).
 
## June 8 -- Haplotype phasing

### Topics
- Haplotype phasing theory
- Haplotype phasing evaluation
	- Different metrics and their interpretation
	- Hamming rate/switch error >> accuracy due to improvements in algorithms 

### Exercises
- Haplotype phasing on triploid simulated genome (`HAT` and `nPhase`)
- Assembling haplotype-phased reads (`miniasm`)
- Haplotype phasing evaluation (`Quast`)
- Haplotype phasing visualization (`GenomeView`)
  - Alignment of reads to reconstructed haplotypes
  - Alignment of haplotypes (`Mauve`) 


### Planning

| &nbsp;      | &nbsp;                                   |
|-------------|------------------------------------------|
| 8:45        | Arrival                                  |
| 9:00        | Start                                    |
| 9:00-9:45   | Lecture: haplotype phasing part 1        |
| 10:00-10:45 | Lecture: haplotype phasing part 2        |
| 10:45-11:00 | Coffee break                             |
| 11:00-12:30 | Exercises: continue                      |
| 12:30-13:30 | Lunch                                    |
| 13:30-15:15 | Exercises                                |
| 15:15-15:30 | Coffee break                             |
| 15:30-16:45 | HaploViewer: final lecture and exercises |
| 16:45-17:00 | workshop wrap-up                         |

- You can find the documentation for day 2 exercises [HERE](https://abeellab.github.io/vlpb-assembly-workshop/exercises-day2.html).
