## Machine Learning in R

Before starting, the user should have both R and RStudio installed:
R is available from: https://www.r-project.org/
RStudio is available from: https://rstudio.com/products/rstudio/download/

The user will need the following files:
GUI.R
Random_Forest.R
training.csv

**First**: The user should adjust the file path in Random_Forest.R and Neural_Network.R so that it can find training.csv ( getwd() returns the working directory, and can help here). The user should also adjust the file path in GUI.R to find the Random_Forest.R file

**Second**: The user must run Random_Forest.R (ctr+shift+enter helps) to place 'rf' in the global environment and train the model

**Third**: The user must run Neural Network.R (ctr+shift+enter helps) to place 'neural network' in the global environment and train the model.However the file contains two parts of Neural Network in which at first the single layer Neural Network has been implemented. So first execute that to see the result. Then a more complex multilayer Neural Network has been implemented under the section "#Fine tuning the neural network". Run that piece of code to get the different results.

**Fourth**: The user should run (ctrl+shift+enter) GUI.R. An application titled "Patent Grants Predictor" will open

**Fifth**: The user should adjust the input values to reflect metrics for the community in question and the desired timeframe for the prediction

**Sixth**: The user should press the 'Plot' button in the lower right

**Seventh**: The user should switch to the Patent Projections page to view the projection

That should be enough to get you started.

Thank you!
Ayush Dwivedi
Jeff Bivin
Tyler Jones

The presentation of this project is available at https://drive.google.com/file/d/1kxHGl4aGWMZGP_5-WZXjxwjL_o0PtslA/view?usp=sharing
