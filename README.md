## Project Overview:
This project employs NetLogo to simulate diverse COVID-19 scenarios, allowing for the adjustment of critical factors like population size, infection rate, vaccination rate, mask usage rate, mask-reduced infection rate, recovery rate, hospital capacity affecting recovery rate, and death rate. The simulation aims to evaluate the effects of these factors on disease spread and fatality, providing a comprehensive analysis of the pandemic dynamics. 
## How to use:
In NetLogo, the results are generated through a combination of various elements within the environment, including the interface slides, monitors, code execution, and the BehaviorSpace tool. Here's a breakdown of each component:

Interface Slides: NetLogo allows you to create an interactive user interface using slides. Interface elements such as sliders, buttons, and switches can be adjusted by users to set parameters before running the simulation. These parameters directly influence the behavior of the model.

Monitors: Monitors in NetLogo display real-time information during the simulation. They can show variables, counts, and other relevant data. Monitors are useful for tracking the progress of the simulation and observing key indicators.

Running the Code in the Code Tab: The main logic of the simulation is implemented in the Code tab. This is where you write the NetLogo code that defines the agents, their behaviors, and the rules governing their interactions. Running the code executes the simulation, and the results are reflected in the interface and monitors.

Setup in BehaviorSpace: BehaviorSpace is a tool in NetLogo that allows for systematic exploration of different parameter settings. You can define multiple experimental runs by specifying different combinations of input values. BehaviorSpace automates the process of running simulations across these settings and records the results.

In summary, users can interact with the model through the interface, adjusting parameters using slides. Monitors provide real-time feedback during the simulation. The code in the Code tab defines the underlying logic of the model. BehaviorSpace enables the systematic exploration of different scenarios. The results are a combination of these elements, providing insights into how the model behaves under various conditions.     

## The html files included in the repo cannot be viewed directly unless downloaded locally.
Example screenshots in these html files to explain the setup and key findings are now listed in the sections below.
## Findings and recommendations
This research employs Agent-Based Modeling (ABM) through NetLogo to assess vaccination, mask-wearing, and healthcare capacity's impact on pandemic dynamics. Findings indicate that increased vaccination rates, mask usage, and improved hospital capacity effectively mitigate disease spread and reduce fatalities. The recommendation is to advocate for these measures not only in the context of COVID-19 but also for combating other infectious diseases. Supporting agent-based modeling studies in healthcare is also advised for enhanced preparedness and response strategies.
## Color setup
The turtles was originally set up using 4 colors: vaccinated and recovered set to blue (both being immune), masked healthy set to green, unmasked healthy set to violet, infected set to red, and dead set to gray.
More colors could be used to distinguish turtles at a different status, e.g. vaccinated changed to pink, and masked healthy changed to orange (example6). 
## Intervention effects on incidence and_or fatality rate.html
Vaccination rate = 0.25 on incidence rate and/or fatality rate / Masked vs unmasked on incidence rate and/or fatality rate
(example.png)     
Vaccination rate = 0.50 on incidence rate and/or fatality rate / Masked vs unmasked on incidence rate and/or fatality rate
(example2.png)     
Vaccination rate = 0.80 on incidence rate and/or fatality rate / Masked vs unmasked on incidence rate and/or fatality rate
(example3.png)     
Hospital capacity = 100, recovery-rate = 0.10 on incidence rate and/or fatality rate
(example4_1.png, and example4.png)     
Hospital capacity = 200, recovery-rate = 0.15 on incidence rate and/or fatality rate
(example5_1.png, and example5.png)     
## Explanation of BehaviorSpace & Command Center.html
Set up BehaviorSpace     
To run 270 combinations in sequential order, as selected; to measure (and export the counts to a csv file) at every step
(example7_1.png, example7_2.png, and example7_3.png)   

Command Center to monitor Turtle 181 (Exportable)     
To monitor any or all individual turtles and optionally export results to a txt file
(example8_1.png, and example8_2.png)     
