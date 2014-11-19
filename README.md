# OffLine-Log-Analysis
====================
This is a repository for my case study in offline log analysis.
Different approaches of off-line log analysis will be researched and compared.

The question of how to reproduce the experiments using RV-Monitor and MOP property file (serving the same functionality as policy file) will be investigated.

Basically, there are 5 steps to be performed in order to achieve the final goal.

1. Reproduce the offline log analysis experiment with toy demo using monpoly. 

2. Reproduce the offline log analysis experiment with 18G's Nokia's cvs log file using monpoly.

3. Design a toy scenario where RV-Monitor uses a simple property (written in MOP) to monitor the log file.

4. Scale up. Use RV-Monitor to monitor the 18G's log. Using single machine.

5. Use MPI/ MapReduce to parallelize the work.

### Referenced Resources
[monpoly project](http://www.infsec.ethz.ch/research/projects/mon_enf)

[monpoly tool](http://sourceforge.net/projects/monpoly/files/)
