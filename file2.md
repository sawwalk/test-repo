Formulate problem:

Issue: Some people are in multiple performances and they need adequate time to change with limited space.

Goal: to estimate the number of people who need to change during each block. 

System: The show is broken into 2 halves, half1 and half2. Within each half there are 9 performances. The plan is to call up the people performing in each half to backstage in 2 blocks, the 1st block contains people performing in the 1st 5 performances of that half, the 2nd block contains people from the remaining 4 performances. 



the system repeats for the 2nd half so there are 4 blocks in total. 



Since everyone can get changed before the show and during intermission we will focus on the 2nd and 4th block that directly follows another block. 



Data syntax:

Each row represents 1 person, column x = name, column y = performances that they are performing in separated by commas e.g. "performance1 - teacher name, performance2 = teacher name, ... 



Can you help me to brainstorm ideas on how to tackle this problem my initial thoughts are outlined bellow, please ask questions if you need more context. 



Change room analysis:

* How many people need to get quick-changed in the same block?
* How many people are performing in both blocks and will therefore need to change in-between.
* Try to estimate the total number of people using the change room as the sum of people quick changing within the same block + the number of people changing after performing in the previous block.



