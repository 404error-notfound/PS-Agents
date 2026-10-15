# GROUP MEMBERS
- 168974 – Koi JoyJudy Wangui
- 189545 – Omondi Angela Achieng
- 189225 – Githaiga Emmanuel Mundia

## QUESTION 1
### PEAS FRAMEWORK DESIGN
- **Performance Measure:** Fuel Efficiency, time taken to reach the destination (Kisumu), cost of the path  (total kilometers travelled), safety (avoiding collision).<br/>
- **Environment:** Road signs and traffic lights, weather conditions, pedestrians, traffic & other vehicles,  towns along the road, highway networks for example A8, B1, B3, B5.<br/>
- **Actuators:** Steering wheel, accelerator, brake, indicators, gear shift.<br/>
- **Sensors:** GPS, speedometer, radar, cameras<br/>

### CLASSIFYING THE ENVIRONMENT
a. Observability<br/>
**_Partially observability_** - the agent is not fully aware of its environment since it cannot  see beyond hills and buildings or even around meandering corners along the roads.<br/>

b. Determinism<br/>
**_Stochastic_** - The next state cannot be determined only by the actions and current state of the agent.  Other drivers, pedestrians, and weather conditions make the environment unpredictable.<br/>

c. Episodic vs. Sequential<br/>
**_Sequential_** - Current actions depend on the previous actions. For example, deciding to turn  right at Oyugis depends on having driven from Bomet through Narok.<br/>

d. Static vs. Dynamic<br/>
**_Dynamic_** - The environment changes while the agent is deliberating to choose an action. For example, traffic moves,  traffic lights chnage, and speed limit also changes.  This requires the agent to consult the environment frequently and act in real-time.<br/>

e. Single vs. Multi-Agent<br/>
**_Multi-Agent_** - The trailer operates with other agents such that the agent's decisions affect and are affected  by these other agents for example, human drivers, pedestrians and cyclistst.<br/>


## QUESTION 2: DIRECTED GRAPH AND SEARCH TREE
![A directed graph showing possible paths that the PS-Agent can take.]()

![A search tree showing possible routes from Nairobi, the initial state, to Kisumu, the goal state.]()

## QUESTION 3
