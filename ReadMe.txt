Femur_SSM_Example

Full model from Braun et al located in ./OJSM_2025_Braun_Model/

ShapeWorks Workshop SSM Examples and Exercise located in ./SSM_Exercise/

###
./SSM_Exercise
In ShapeWorks select "Open Existing Project" and select the SSM_Workshop_Exercise_Femur.xlsx file
This is an unoptimized new model ready for optimization
For an example of a model with an optimized solution you can similarly load the SSM_Workshop_Example_Solution_Femur.xlsx file

Within the ./SSM_Exercise/ directory there are four folders and two .xlsx files
.xlsx files are the ShapeWorks project files
./Mean_Models_Solution/ 		contains the mean shapes (.stl files) of the patient (cam), control, and overall mean shapes
./groomed/ 				contains the groomed and processed surfaces (.vtk files) of each of the samples
./constraints/ 				contains the points (.json files) for creating the cutting planes for each of the samples
./SSM_Workshop_Example_Solution_Femur/ 	contains the world and local (.particles) files for the solution shape model

