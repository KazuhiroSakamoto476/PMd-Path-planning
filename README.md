# PMd-Path-planning
This folder contains a spike data folder in text format and a MATLAB file, FullAuto.m, for regression analysis.

Please modify the file input directory specification within FullAuto.m as needed. Also, please create an output directory for the calculation results beforehand.

The spike data folder consists of data from two brain areas: the prefrontal cortex (Pfc) and the dorsal premotor cortex (PMd) of two monkeys (Monkey 1 and Monkey 2). Within each of these spike data folders, there are four subfolders: GoalOn, MovOn1, MovOn2, and MovOn3. The GoalOn folder contains data from 2000 ms before to 8000 ms after goal onset. The other folders contain data from 2000 ms before to 2000 ms after their respective movement onsets. The data represents the spike counts within 100 ms bins. Each line in the data represents the spike data for a single trial. Before the spike data, condition data for each trial is appended. The regression analysis in FullAuto.m is performed based on this condition data.

For any questions, please contact sakamoto@tohoku-mpu.ac.jp.
