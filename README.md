Artificial-selection-on-X.-saxesenii

Description: In this study, we investigated the effect of selection for early dispersal on the life history, behaviour and fungal community of an ambrosia beetle, Xyleborinus saxesenii. We bred beetles in a control lineage and a selected lineage. We measured various traits of the life history of the beetles and their behaviour. We also sampled the fungal community of X. saxesenii to identify the fungi that develop in association with the beetles.
In this repository, you will find the data we collected. The files are organised in two folders:

1.	Life history and behaviour: This folder contains the raw data related to the life history traits and behaviours of the beetles. The data are organised in different files

Success Rate: this file provides a record of the success or failure of all nests that were initiated during the study
•	colony: each nest had a unique label. Labels are the group of the nest associated with a number
•	group: nests belonged to 10 groups identified “CG1”, “CG2”, “CG3”, “CG4”, “CG5”, “EDG1”, “EDG2”, “EDG3”, “EDG4” and “EDG5”
•	condition: the state of the nest ten days after initiation
•	condition_num: a value reflecting the state of the nest after ten days in numerical format (0 = nest had failed, 1 = nest was successful)
•	lineage: the lineage the nest belongs to
•	generation: the generation the nest belongs to

Survival analysis: this file provides a record of the eggs, larvae, pupae, adult beetles and dispersers observed in the nests at the days of observation
•	colony: each nest had a unique label. Labels are the group of the nest associated with a number
•	group: nests belonged to 10 groups identified “CG1”, “CG2”, “CG3”, “CG4”, “CG5”, “EDG1”, “EDG2”, “EDG3”, “EDG4” and “EDG5”
•	lineage: the lineage the nest belongs to
•	generation: the generation the nest belongs to
•	date: the date of observations. The first observation was conducted on the day of initiation of the nest.
•	age: age of the nest at the time of observation (the difference between the date of observation and the date of initiation of the nest)
•	eggs: number of eggs observed in the nest
•	larvae: number of larvae observed in the nest
•	pupae: number of pupae observed in the nest
•	adults: number of adult females observed in the nest
•	dispersers: number of dispersers observed leaving the nest

Natural history: this file provides a record of the first times eggs, larvae, pupae, adults and dispersers were observed in the nests. The time of end of the nests, and the total number of dispersing females for each, are also recorded
•	ID: each nest had a unique label. Labels are the group of the nest associated with a number
•	date_colony: The date of initiation of the nest
•	group: nests belonged to 10 groups identified “CG1”, “CG2”, “CG3”, “CG4”, “CG5”, “EDG1”, “EDG2”, “EDG3”, “EDG4” and “EDG5”
•	lineage: the lineage the nest belongs to
•	generation: the generation the nest belongs to
•	fungal_garden: the date we observed the developing fungal garden
•	first_egg: the date we observed eggs in the nest for the first time
•	first_larva: the date we observed larvae in the nest for the first time
•	first_pupa: the date we observed pupae in the nest for the first time
•	first_adult: the date we observed adult females in the nest for the first time
•	first_disperser: the date we observed dispersers leaving the nest for the first time
•	nest_end: the date we observed dispersers leaving the nest for the last time
•	total_dispersers: the total number of dispersers that left the nest

Behaviour: this file provides a record of the behaviours observed in the nests
•	ID: each nest had a unique label. Labels are the group of the nest associated with a number
•	group: nests belonged to 10 groups identified “CG1”, “CG2”, “CG3”, “CG4”, “CG5”, “EDG1”, “EDG2”, “EDG3”, “EDG4” and “EDG5”
•	lineage: the lineage the nest belongs to
•	generation: the generation the nest belongs to
•	larva_rest: number of times larvae were observed resting
•	larva_walk: number of times larvae were observed walking
•	larva_dig: number of times larvae were observed digging
•	larva_feed: number of times larvae were observed feeding
•	larva_clean: number of times larvae were observed cleaning
•	larva_groom: number of times larvae were observed grooming
•	larva_ball: number of times larvae were observed balling
•	larva_cannibalise: number of times larvae were observed cannibalising
•	adult_rest: number of times adult females were observed resting
•	adult_walk: number of times adult females were observed walking
•	adult_dig: number of times adult females were observed digging
•	adult_feed: number of times adult females were observed feeding
•	adult_clean: number of times adult females were observed cleaning
•	adult_shuffle: number of times adult females were observed shuffling
•	adult_groom: number of times adult females were observed grooming
•	adult_copulate: number of times adult females were observed copulating
•	adult_cannibalise: number of times adult females were observed cannibalising
•	adult_block: number of times adult females were observed blocking

2.	Fungal community analysis: This folder contains the sequences obtained from metabarcoding the fungal community associated with X. saxesenii.

Fungal garden_tax: this file associates each zotu to a taxonomic output. Not every zotu is identified to the species level

Fungal garden_zotu_table: this file associates the zotu and samples. Each cell indicates how many sequences of every zotu were found in every sample

Fungal garden_metadata: this file was manually constructed, to associate each sample to the metadata relevant for this study
