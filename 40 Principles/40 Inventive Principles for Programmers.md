# 40 Inventive Principles for Programmers

This is an adapted and extended version of 40 TRIZ Inventive Principles originally developed by G Altshuller The titles and formulations of the principles might not coincide with the titles and formulations available in other literature about TRIZ and systematic Innovation due to the original nature of research and development performed by ICG T&C to create this document.

This version has been developed by A. Kugushev and is based on the materials by G. Altshuller, R. Fulbright, D. Mann, K. Rea, V. Sushkov, A. Kuryan.

## 01 SEGMENTATION
![](/resources/01%20SEGMENTATION.png)
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
![](/resources/02%20TAKING%20AWAY.png)
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
![](/resources/03%20LOCAL%20QUALITY.png)
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
![](/resources/04%20ASYMMETRY.png)
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
![](/resources/05%20MERGING.png)
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
![](/resources/06%20UNIVERSALITY.png)
### Strategies and Recommendations
- If you have several objects or systems delivering different functions, consider creating a new single system that could deliver these functions thus  eliminating the need for having several different systems.
- If you have several separate different processes delivering different functions, consider creating a single process that will deliver a multiple functionality
### Examples
- Strategy pattern
- Polymorphism
- Double Dispatching, Pattern Visitor
- Pattern Builder

## TBD

## 14 NON-LINEARITY
![](/resources/14%20NON-LINEARITY.png)
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

## TBD

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

## TBD

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

## TBD

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

## TBD

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
