INFO regarding the running of Lab4 Labview panel

Procedure:
*make sure the RIO board is plugged in before running any VIs in this project*
STEP 1:
First open the 'load_I_T_from_file.vi' to load the input and target data. RUN the VI. In the front panel, set: Hidden Layers to '1' AND Nodes Per Stage array (top to bottom) to '5','8','3'. 
Click OK to select 'input_data' first, followed by 'targets'. The Inputs Shuffled an Targets shuffled should be displayed in the front panel window. 
**IF one of the arrays is empty after running the VI, you may need to repeat STEP 1 again. After the second import all the data will be imported and ready to use**

STEP 2:
Next open the 'PositionNetTrainer.vi' and run it. You have the option to stop training at any point by pressing the stop button.

STEP 3:
Finally open the 'PositionNet.vi', the weights computed in the previous step will automatically be used. Run the VI and use the RIO board to see if all three positions can be properly detected.


URL to Video:

