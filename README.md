# python-cimec-2025-Mohit-Jaiswal
Hosts a mini-project as part of final submission for the Python coursework of summer 2025, for CiMeC PhD year 1 (Cycle 40).

The notebook is documented well enough to dictate what is going on, but I will provide a gist here as well.

The project aims at designing behavioral transition matrices for mice behavioral data, which includes parameters like grooming, sniffing, atttack, freezing, etc. This is part of my previous work as an intern at the European Molecular Biology Laboratory (EMBL), Rome, where I worked on the territorial induction in the mammalian hypothalamus. Before delving in the neural basis of such territorial aggression in the ventromedial hypothalamus, behavioral basis of the said aggression needed to be studied and analyzed. Such analysis included understanding the behavioral dynamics through video data, followed by utlizing SimBA (Simple Behavioral Analysis) and DeepLabCut (DLC) pipelines.

To give more context about the work and setup - it includes a rectangular arena, which are divided into 2 to 4 compartments of equal size, having resource platforms hosting food, water and nesting materials. Each compartment houses a 'native' mouse, and the compartments are connected by doors/gates, which are typically closed. But during the behavioral assay, the gates are opened, and the two 'native' mice from each compartment are free to go to each other's territory (resident-intruder effect). We study this pair-wise behavioral interaction by recording through Basler cameras (and also BONSAI) suspended on top of each compartment.

Manual scoring of these video datas at a sub-second resolution allows us to characterise the different behavioral parameters mentioned before (and in the notebook) with the help of SimBA, and that data allows us to further go ahead and generate transition matrices, ethograms, etc.

Much more details of the work can be found [here]((https://www.nature.com/articles/s41598-024-75545-4))!

So, in the contents of the notebook, you will see I proceeded (with synthetic/ghost data), and how I tried to design network plots, thus informing us about further analysis downstream.

I worked on Google Colab, so it is very straightforward. You just have to connect to the local runtime and just execute every cell sequentially. I have included all the libraries I have used, so there should not be any errors or inconsistencies.

Thanks!
