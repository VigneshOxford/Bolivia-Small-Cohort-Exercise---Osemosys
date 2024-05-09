Welcome to our team’s repository! To fully run the OSeMOSYS model and achieve results similar to those in our report, follow these steps. Before we begin, make sure you have a few prerequisites installed on your local machine.


OSeMOSYS (Open Source Energy Modeling System) is a powerful energy system optimization model. It helps analyze energy systems, plan investments, and assess policy scenarios. In our model, we use MoManI (Model Manager for OSeMOSYS) as the interface that communicates with OSeMOSYS.

1. Installation
   Visit the OSeMOSYS Interfaces page at http://www.osemosys.org/interfaces.html
   Under the MoManI section, you’ll find information on how to install OSeMOSYS via their YouTube video. and The same video will guide      you through installing a solver (such as GLPK or CPLEX) that OSeMOSYS relies on.

2. Scenario Folders
   Download the scenario folders from our repository. These folders represent different scenarios:
      BAU (Business As Usual): Represents the baseline scenario.
      CN (Climate Neutral or Net Zero): A scenario aiming for zero net emissions.
      AP (Announced Policies): Reflects the impact of specific policies.
  Each folder contains two main text files: data and model.
      The model file is a script that runs OSeMOSYS based on the data file.
      The data file serves as an input file and will differ across scenarios.
  
3. Running Osemosys
   After successfully installing OSeMOSYS, the solver, and downloading the scenario folders, navigate to the desired scenario folder.
   Look for the “Run Simulation” option within the folder and Execute it to run OSeMOSYS with the specified data and model files.
 
This model is adapted from this paper : https://doi.org/10.1016/j.rser.2023.113946  and this is their repository: https://zenodo.org/records/7633742
