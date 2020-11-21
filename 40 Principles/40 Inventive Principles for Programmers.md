# 40 Inventive Principles for Programmers

This is an adapted and extended version of 40 TRIZ Inventive Principles originally developed by G Altshuller The titles and formulations of the principles might not coincide with the titles and formulations available in other literature about TRIZ and systematic Innovation due to the original nature of research and development performed by ICG T&C to create this document.

This version has been developed by A. Kugushev and is based on the materials by G. Altshuller, R. Fulbright, D. Mann, K. Rea, V. Sushkov, A. Kuryan.

## 01 SEGMENTATION
![](/40%20Principles/resources/01%20SEGMENTATION.png)
### Strategies and Recommendations
- Divide your system or object into independent parts or interconnected parts.
- Divide your system or object into parts so that some part of it can be easily taken away when necessary.
- Assemble your system or object from smaller segments.
- Increase the degree of the system’s segmentation by composing the system from a number of smaller various objects or subsystems.
- Break a process or activity to smaller segments.
- Increase the degree of segmentation of homogeneous systems or processes.
- Increase the difference between segments.
### Examples
- Follow Interface Segregation Principle and divide a huge interface to multiple interfaces with a dedicated responsibility
- Component based architecture
- Microservices architecture

## 02 TAKING AWAY
![](/40%20Principles/resources/02%20TAKING%20AWAY.png)
### Strategies and Recommendations
- If some part of your system or your process interferes with other parts or creates a negative effect, “take away” the interfering part of your system or your process by separating it from the system or the process by removing or isolating it from the system or the process. 
- If some property of a system interferes with other properties of functions of the system, find out what part of the system is a carrier of the property and separate it from the system by creating another system or transferring the property to some other part of the system.
- “Single out” the only necessary property of a system by creating another system which has the required property only.  
### Examples
- Creating a standalone service with responsibility that is related to the negative effect
- Process Spawning 
- Creating a dedicated IoC container for a task to locate negative side effects
- Temporary table in SQL
- Taking away some tests to a dedicated suite

## 03 LOCAL QUALITY 
![](/40%20Principles/resources/03%20LOCAL%20QUALITY.png)
### Strategies and Recommendations
- Instead of a uniform structure of your system or an object, use a non-uniform structure of the system or the object.
- Instead of a uniform structure of your process, use a nonuniform structure.
- Vary in time or space the part of your process that causes problems.
- Instead of a uniform structure of environment, use a nonuniform structure of environment.
- If two (or more) different functions have to be performed by the same part of the system, but this causes problems, divide this part into two (or more) parts.
- Make parts of the system and its environment function in most suitable and proper conditions for each part.
- Make activities within a process and its environment function in most suitable and proper conditions for each activity.
### Examples
- Unsafe code, ASM includes
- Allocate extra resources per some services

## 04 ASYMMETRY 
![](/40%20Principles/resources/04%20ASYMMETRY.png)
### Strategies and Recommendations
- If your system has an asymmetrical structure or shape, consider making it asymmetrical.
- If your system is asymmetrical, increase the degree of asymmetry.
- Change the degree of asymmetry by varying the asymmetry dynamically depending on the operating conditions.
- Increase or decrease the degree of symmetry in processes depending on the operating conditions and required effects
### Examples
- Test Pyramid
- Dependency Inversion Principle
- Data denormalization in relational database

## 05 MERGING
![](/40%20Principles/resources/05%20MERGING.png)
### Strategies and Recommendations
- Merge identical (or similar) parts or components of a system in space.
- Merge identical (or similar) parts or components of a system in time.
- Merge two or more different systems to achieve the synergetic effect.
- Merge two or more systems to increase efficiency or to save space, time, energy, or any other resources.
- Merge two or more different processes into a single process.
- Transfer activities from one process to another process
### Examples
- Pattern façade
- Use a host process to run multiple jobs, so we can save time launching a new process, e.g. application pools in IIS
- Merge multiple representation of the one entity to the one physical class and keep differences by exposing different interfaces

## 06 UNIVERSALITY
![](/40%20Principles/resources/06%20UNIVERSALITY.png)
### Strategies and Recommendations
- If you have several objects or systems delivering different functions, consider creating a new single system that could deliver these functions thus  eliminating the need for having several different systems.
- If you have several separate different processes delivering different functions, consider creating a single process that will deliver a multiple functionality
### Examples
- Strategy pattern
- Polymorphism
- Double Dispatching, Pattern Visitor
- Pattern Builder

## 07 NESTING
![](/40%20Principles/resources/07%20NESTING.png)
## Strategies and Recommendations
- Place an object or a system inside another system.
- Increase a number of systems or objects nested.
- Make one system dynamically become a part of another system when necessary and then separate the systems again.
- Introduce a new process inside an existing process.
- Increase a number of “nested” processes.
- Make process activities dynamically appear when needed and disappear when not needed.
### Examples
- Nested classes, functions
- Extract method refactoring
- Any submodules

## 08 COUNTERACTION
![](/40%20Principles/resources/08%20COUNTERACTION.png)
## Strategies and Recommendations
- If a certain action by a system causes a negative effect but the action should be preserved, subject the system to a “counterforce”—a reverse action that cancels the negative effect.
- Consider dividing a system into parts so that the undesired action that produces a negative effect, and the desired action compensate each other.
- Change the environment of your system in such a way that the environment itself introduce such a “counter-” or “compensation” force.
- Merge two systems, which deliver opposite functions (actions), together
### Examples
- Cache expiration 
- Logs archiving
- Tasks Queue Pattern

## 09 PRIOR ANTI-ACTION
![](/40%20Principles/resources/09%20PRIOR%20ANTI-ACTION.png)
## Strategies and Recommendations
- If your system or object is subjected to a certain action which produces both negative and positive effects on the system or its supersystem, consider subjecting the system to an antipodal (inverse) action beforehand, so that it will compensate or eliminate the negative effect when the negative effect occurs.
### Examples
- Reboot of the server at the begging of the day
- Cleanup all possible side effects in tests setup
- GC Collect before running 

## 10 PRIOR ACTION
![](/40%20Principles/resources/10%20PRIOR%20ACTION.png)
## Strategies and Recommendations
o If your system or process experiences harmful influence of its supersystem, create preliminary conditions that will prevent the system from influence of those harmful factors.
o If your system or process is going to be changed in a certain moment of time but such a change is difficult to achieve exactly when needed, perform the required change of the system/object (fully or partially) in advance.
o Prearrange different parts of your system or process activities in such a way that they can be “assembled” right where and when it becomes necessary but not before.
### Examples
- Serverless tasks prewarm
- Cache prewarm
- Prefetch resources
- Server Side Rendering
- Denormalization

## 11 BEFOREHAND CUSHIONING
![](/40%20Principles/resources/11%20BEFOREHAND%20CUSHIONING.png)
## Strategies and Recommendations
- Create conditions in advance that will eliminate a chance for a negative effect to happen.
- Create conditions in advance that will immediately fix the negative effect if it happens.
- Create conditions in advance that will immediately compensate for the negative effect.
### Examples
- Redundancy
- SAGA
- Memento Pattern
- Dispose Pattern

## 12 TENSION REMOVAL
![](/40%20Principles/resources/12%20TENSION%20REMOVAL.png)
## Strategies and Recommendations
- Create conditions to eliminate or compensate possible tension that occur or may occur within a system or between a system and its supersystem.
- Create conditions to eliminate or compensate possible tension that occur or may occur within a process or between a process and its supersystem.
- Integrate different objects or systems to remove tension.
- Introduce a new object or a process activity to decrease possible tension.
- Eliminate or replace an object or process activity that creates tension.
- Break a process to smaller steps to remove possible tension
### Examples
#TBD


## 13 OTHER WAY ROUND
![](/40%20Principles/resources/13%20OTHER%20WAY%20ROUND.png)
## Strategies and Recommendations
- Instead of the required actions, consider performing an antipodal (inverse) action to achieve the desired positive effect.
- Consider replacing the parts of your system with the parts that have opposite (inverse) features: filled−hollow, black−white, and so on.
- Reverse the order of actions/activities.
- Make the non-dynamic part of your system dynamic or fix the dynamic parts.
- Turn your object/system upside down.
- Invert the entire process or some of the steps of the process.
### Examples
- Dependencies Inversion
- Double Dispatching
- Graph traversal from the end


## 14 NON-LINEARITY
![](/40%20Principles/resources/14%20NON-LINEARITY.png)
### Strategies and Recommendations
- Instead of linear parts or structure of a system, consider using “curved”, “spherical” parts or systems.
- Instead of linear processes use nonlinear processes.
- Sequel linear and nonlinear parts within a process.
- If a process is nonlinear, consider increasing the degree of nonlinearity.
- Use a circular flow instead of a linear flow.
- Use roundabout solutions in a process.
### Examples
- Recursive algorithms
- Use explicit implementation of the interface if the class have a property with the same name 


## 15 DYNAMIZATION
![](resources/15%20DYNAMIZATION.png)
### Strategies and Recommendations
- If your system is static and immobile, make it dynamic and movable.
- Divide your system into the parts capable of moving relatively to each other.
- Increase the degree of free motion within your system.
- Make your object or its nearest supersystem dynamically change and adapt in accordance with the required conditions at each stage of operation.
- Make the structure of your process more dynamic.
- Increase the degree of dynamics of those process activities that experience negative influence of supersystem or which performance has to be increased.
### Examples
- Use reflection any convention based utilities
- Code Generation 
- Dynamic Proxies

## 16 SLIGHTLY LESS OR MORE
![](/40%20Principles/resources/16%20SLIGHTLY%20LESS%20OR%20MORE.png)
## Strategies and Recommendations
- If the required change of your system or your process cannot be achieved precisely, or the desired goal cannot be achieved in full, then reformulate the problem:
  - How to make or deliver slightly less and then achieve the required effect.
  - Make or deliver slightly more to achieve the required effect.
### Examples
#TBD

## 17 ANOTHER DIMENSION
![](/40%20Principles/resources/17%20ANOTHER%20DIMENSION.png)
## Strategies and Recommendations
- Use other dimensions, in addition to the already used ones, in your system or your process.
- Introduce a new dimension to your system, process, or their supersystem.
- Use a multi-layered arrangement instead of a single-layer one for a system or a process.
- Tilt or reorient the system in space.
- Introduce viewing of your system or process at a different angle
### Examples
- Use multidimensional array

## 18 RESONANCE (COORDINATION)
![](/40%20Principles/resources/18%20RESONANCE%20(COORDINATION).png)
## Strategies and Recommendations
- Make your system “vibrate”.
- Make actions produced by your system match the actions of another system to achieve an optimal running or a synergetic effect.
- Match the periodicity of the actions/activities produced by two different systems or processes.
- Match intervals of actions produced by two systems or processes.
- Match in space or in shape two systems that interact with each other
### Examples
#TBD


## 19 PERIODIC ACTION
![](resources/19%20PERIODIC%20ACTION.png)
### Strategies and Recommendations
- Instead of a continuous process, use periodic or “pulsed” actions.
- Introduce diversification among time intervals between the actions, depending on the operating conditions or changes in the supersystem.
- Dynamically vary periodicity of process actions according to the operating conditions or changes in the system or supersystem.
- Use the available pauses between process actions to perform some other useful process action(s).
### Examples
- Use timer to run periodic tasks
- Run integration tests every night
- Regular pinging to prevent the system from switching to the “sleep” mode


## 20 ACTION CONTINUITY
![](resources/20%20ACTION%20CONTINUITY.png)
### Strategies and Recommendations
- Make all processes in your system work continuously.
- Eliminate all idle running from your process.
- If it is not possible to avoid idle pauses in your process, consider filling them with some other positive process activities.
### Examples
- Hadoop style: assign disposable tasks on servers with no load
- Return multiple result sets from stored procedure if it's required
- Data packing: keep similar from usage perspective data close to each other to reduce extra calls, e.g. asset packing, textures packing, etc.
- Context pattern: keep all scope data in one class to save the user from writing extra accessor code


## 21 HIGH SPEED
![](resources/21%20HIGH%20SPEED.png)
### Strategies and Recommendations
- If your system/object is subjected to harmful or hazardous actions within some process, perform the required process at a very high speed.
- If your process experiences harmful effects caused by the environment, conduct the process at a high speed.
- If it is difficult to perform some change of your system due to emergence of negative effects during the process of change, perform the required change at a very high speed.
- Increase the speed of the process that causes harmful effects.
- Locate the activity within a process that might cause a negative effect and conduct this activity at a high speed.
### Examples
- Avoid race condition by keeping data in local variable and assign it to a shared field only via atomic interlocked operation


## 22 BLESSING IN DISGUISE
![](/40%20Principles/resources/22%20BLESSING%20IN%20DISGUISE.png)
## Strategies and Recommendations
- Use harmful factors or negative effects that arise in your system, your process or their supersystem to achieve positive results.
- Eliminate a harmful factor by adding it to another harmful factor.
- Amplify the harmful factor to such a degree that it would stop bringing harm to your system or its supersystem.
### Examples
#TBD

## 23 FEEDBACK
![](/40%20Principles/resources/23%20FEEDBACK.png)
## Strategies and Recommendations
- Integrate feedback into your system or between your system and its supersystem.
- If feedback is available but is not effective enough, consider making it dynamic by varying the feedback components and structure in accordance with the operating conditions.
- If it is known that a negative effect can occur, consider creating the conditions that can initiate a negative feedback loop directed toward eliminating this negative effect or reducing its harmful consequences.
- Increase the magnitude and scale of the existing feedback
### Examples
- Use callbacks

## 24 INTERMEDIARY
![](/40%20Principles/resources/24%20INTERMEDIARY.png)
## Strategies and Recommendations
- Use an intermediate carrier to provide necessary functionality or to eliminate the negative effects while preserving the positive effects.
- Check if available resources can act as an intermediary object.
- Temporarily merge your object/system with a foreign object/system that will provide the required action and then, if necessary, remove (eliminate) the foreign system/object.
- Temporarily merge your process with a foreign process that will provide the required action.
- Introduce a new intermediary object/system, which is a modification of the first or the second object (system), if a problem relates to the interaction between the two systems. The modification should be understood in a broad sense: as a material, property, energy, or any other type of modification.
### Examples
- Proxy Pattern
- Decorator Pattern


## 25 SELF-SERVICE
![](resources/25%20SELF-SERVICE.png)
### Strategies and Recommendations
- The object/system must serve itself by performing tuning, adjusting, and repair operations all by itself.
- Use available resources or waste resources within your system to achieve the required degree of self-service.
- Use available resources or waste resources within the environment of your system to achieve the desired degree of self-service.
- Consider using already available activities in your process to service other activities
### Examples
- Inject IoC container directly to the class to resolve required dependencies on its own
- Add validation logic to model itself via annotations or dedicated method


## 26 USE OF COPIES AND MODELS
![](/40%20Principles/resources/26%20USE%20OF%20COPIES%20AND%20MODELS.png)
## Strategies and Recommendations
- If you need to undertake certain actions that may damage a fragile or expensive system/object, use its simpler and cheaper copy.
- If you need to undertake certain actions with respect to unavailable, complex, expensive, or dangerous object, use its copy instead.
- If the required process is too complex and risky, use a simplified version of the process to run experiments.
- Instead of a real physical system/object, use their “virtual” copies (images, holograms).
- Use virtual models of your systems.
- Before launching a complex process, experiment with its simpler “copies”.
### Examples
- Safe Copy


## 27 CHEAP AND SHORT LIFE
![](/40%20Principles/resources/27%20CHEAP%20AND%20SHORT%20LIFE.png)
## Strategies and Recommendations
- Replace an expensive object/system with a number of cheaper ones.
- Instead of a long, continuous, and expensive process, use a number of short-term inexpensive activities.
### Examples
- Temporary tables


## 28 PRINCIPLE REPLACEMENT
![](/40%20Principles/resources/28%20PRINCIPLE%20REPLACEMENT.png)
## Strategies and Recommendations
- If a system or some its part cannot deliver its function with the required degree of performance or accuracy, consider replacing the system or its part with another one based on a different principle which is capable of delivering the required function or performance.
- Sometimes, in business systems it is sufficient to replace a basic operating principle behind the existing system part or a process activity it delivers without replacing that part.
- Add a new subsystem to your system that will deliver the required functionality based on a new principle.
- Check if your system, process or supersystem already has a component that meets the new required principle and use it to achieve the needed functionality.
### Examples
- Strategy Pattern


## 29 FLUIDITY
![](/40%20Principles/resources/29%20FLUIDITY.png)
## Strategies and Recommendations
- Increase the “fluidity” of your system. Make the “solid” parts “fluid” (with a high degree of freedom), or make some components capable of “flowing” through your system.
- Fluidity means the increased degree of freedom (flexibility) of components, of which the system is comprised.
- Fluidity can be achieved by a multitude of smaller “nonfluid” components acting together in a “fluid” way.
### Examples
- IoC container configuration in XML
- Late binding


## 30 THIN AND FLEXIBLE SHELLS
![](/40%20Principles/resources/30%20THIN%20AND%20FLEXIBLE%20SHELLS.png)
## Strategies and Recommendations
- Use “thin layers” to isolate a system or its part from the supersystem.
- Instead of impairing a feature to the whole system, impair the feature to its interface layer only.
- Use flexible thin layers as a “coating” to add the required functions or properties to your objects or system.
- Instead of complex and massive three-dimensional physical structures use flexible shells and thin structures that can be hollow inside.
- Introduce “thin barriers” to separate between process activities.
### Examples
- Default Interface Methods / Traits


## 31 HOLES AND NETWORKS
![](/40%20Principles/resources/31%20HOLES%20AND%20NETWORKS.png)
## Strategies and Recommendations
- Make your system “porous” by introducing “holes”.
- If the system is porous, fill the pores with other parts to deliver different functions or to achieve the desired results.
- Impart certain spatial structure to your system (e.g. networks).
- Introduce “filtering membranes” to diminish the influence of harmful factors of the environment or other system’s parts.
### Examples
#TBD


## 32 COLOR/VISIBILITY CHANGE
![](resources/32%20COLOR,%20VISIBILITY%20CHANGE.png)
### Strategies and Recommendations
- Change the visibility degree of different parts of your system respectively to other system parts or the supersystem
- Change color of an object/system, its part, or environment
- Use different colors to highlight different parts or different functions
- Change transparency of a system/ object, its part or environment
- Make your process or its part as transparent as possible
- Highlight the distinguishing property of your object/system/process
### Examples
- Encapsulation of implementation behind a high level interface
- Data export/import from one format into another
- Change of data type (float to integer, datatime to smalldatatime, numeric to financial)
- Change layer of entity: move from domain to DAL to allow adjusting requests to DB

## 33 HOMOGENITY
![](resources/33%20HOMOGENITY.png)
### Strategies and Recommendations
- Impair the interacting objects or parts of the system the same structure with similar or identical properties.
- Compose your system from a number of homogeneous objects.
- Make some parts of your system homogeneous with your supersystem.
- Make some parts of your process, which interact with supersystem, homogeneous with the supersystem
### Examples
- #TBD

## 34 DISCARD AND RECOVER
![](resources/34%20DISCARD%20AND%20RECOVER.png)
### Strategies and Recommendations
- If your system has to include some part that only operates at a certain moment of time, consider introducing this part only when necessary and then remove it.
- Consider if an activity is needed each time when a process runs. If not, make this activity be included into the process only when needed.
- If some part of the system has fulfilled its function and becomes unnecessary or produces negative effect, eliminate or modify it so that it will not produce any negative effect.
- Add the components to your system that will automatically eliminate those parts of your system which have become unnecessary.
- Restore the consumable parts of the system during operation.
### Examples
- Create a disposable instance in an execution scope. Dispose it at the end of processing, e.g. query builder
- Addons

## 35 PARAMETER CHANGE
![](/40%20Principles/resources/35%20PARAMETER%20CHANGE.png)
## Strategies and Recommendations
- Vary parameters of your system adaptively.
- Instead of developing a new expensive system or a process, find a resource that is already available and can serve as partially developed object/process.
- Change the degree of flexibility of a system.
- Change your system’s or object’s physical state.
- Instead of expensive solid objects, use virtual copies, models, cheap objects, and vice versa.
- Change concentration or consistency of a system/object.
- Change emotional parameters.
- Change visual parameters.
- Change other sensory parameters.
### Examples
#TBD

## 36 PARADIGM SHIFT
![](/40%20Principles/resources/36%20PARADIGM%20SHIFT.png)
## Strategies and Recommendations
- Use the phenomena occurring at macroscale to shift the paradigms within your system.
- Use the external “push” factors to achieve the necessary changes in your system or process.
- Create the internal “push” factors to achieve necessary changes in your system or process.
### Examples
- Try to use Functional Programming/OOP/Component Based Architecture/Data Oriented Design


## 37 RELATIVE CHANGE
![](resources/37%20RELATIVE%20CHANGE.png)
### Strategies and Recommendations
- Consider using the already existing differences between different components of your system to achieve positive effects.
- Use the dynamic “expansion-contraction” effects.
- Merge two components of your system with similar parameters to achieve synergy.
- Use ongoing changes in the supersystem to achieve positive effects or modify your system/process.
### Examples
- Seed database by data from integration tests of another application (which is responsible for filling the database "on live")
- #TBD

## 38 ENRICHED ENVIRONMENT
![](/40%20Principles/resources/38%20ENRICHED%20ENVIRONMENT.png)
## Strategies and Recommendations
- Conduct required processes or activities within the “enriched” environments.
- Create an “enriched” environment for your system by bringing such component(s) to the environment that will boost your system’s performance or help achieve the desired effects.
- Modify the existing components of your system’s environment in a such a way that this will boost your system’s performance or help achieve the desired effects.
### Examples
- Extra containers limits
- Force mode in clouds


## 39 INERT ENVIRONMENT
![](/40%20Principles/resources/39%20INERT%20ENVIRONMENT.png)
## Strategies and Recommendations
- Replace the existing environment with an inert one.
- Place your system into a “vacuumed” environment.
- Isolate your system or process from its environment.
- If possible, remove the components from your system’s environment that produce negative effects on your system performance.
- Add neutral parts to an object/system.
### Examples
- Creating a dedicated IoC container for a task


## 40 COMPOSITE STRUCTURES
![](/40%20Principles/resources/40%20COMPOSITE%20STRUCTURES.png)
## Strategies and Recommendations
- Create composite systems, consisting of smaller systems or objects with different or “biased” parameters instead of uniform ones.
- Create composite systems from systems or objects with opposite properties.
- Create compositions in the form of layers with different properties.
- Link two different processes or activities.
- Create combinations of different functions, skills, and capabilities
### Examples
- Pattern Composite