Installation instructions for different Operating Systems building from sources or using Anaconda for Clingo v5.4.0 can be found here: https://github.com/potassco/clingo/blob/master/INSTALL.md, https://potassco.org/clingo/, https://github.com/potassco/clingo/releases/tag/v5.4.0

There are 2 main folders, one for the scheduling of the different scenarios based on generated data and one for the scheduling with the real data.

Inside the scheduling folder there are 4 subfolders, each corresponding to one Scenario, and the encoder.
In each folder there are 10 instances.

To run the file you can execute the following command:
./clingo Scenario N/FILENAME.lp encoding.lp --opt-strategy=usc --parallel-mode 4
To change the number of days or sessions you can execute the following command:
./clingo Scenario N/FILENAME.lp encoding.lp --opt-strategy=usc --parallel-mode 4 --const s_max=n --const d_count=m

Inside the real_data folder there are the input files corresponding to the real data.