# Quantum Geneticists
> mentorship project at the Quantum Open Source Foundation

**Mentors:** Farhan T. Chowdhury (University of Exeter), Andrei Tretiakov (UCLA)  
**Mentees:** Eduardo Miguel Martinez Garcia, Hanchen Huang, Denisa Vítková   
**Duration:** April 2023–July 2023   

## Project description
We conducted some initial tests using a genetic approach for realising optimal quantum control of radical pair reactions. To that end the physically relevant quantities, namely the singlet probability and recombination yields, were minimised by tuning applied external magnetic field pulses to drive reaction outcomes. This approach was fine-tuned through to a hypervalidation setup, where different configurations were tested, and the best one was selected according to a given measure (the singlet probability), using a grid-search approach. To limited success, formulating a re-inforcement learning strategy was also attempted. 

## References
Chowdhury, F. T., Denton, M. C., Bonser, D. C., & Kattnig, D. R. (2023). Quantum Control of Radical Pair Dynamics beyond Time-Local Optimisation. arXiv preprint arXiv:2306.08613 [physics.chem-ph].

## Software
We make use of the following Python packages:
- [Array programming with NumPy](Nature 585, 357–362), Harris, C.R., Millman, K.J., van der Walt, S.J. et al.
- [QuTiP 2: A Python framework for the dynamics of open quantum systems](Comp. Phys. Comm. 184, 1234), Nori, F. et al.
- [Tensorflow](Symposium on Operating Systems Design and Implementation, pp. 265–283), Abadi, M., Agarwal, A. et al.
- [Fundamental Algorithms for Scientific Computing in Python](Nature Methods, 17(3), 261-272.), Virtanen, P. et al.
- [Matplotlib: A 2D graphics environment](Computing in Science & Engineering, vol. 9, no. 3, pp. 90-95), J. D. Hunter.

## Licence

MIT License

Copyright (c) 2023 Farhan Tanvir Chowdhury

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
