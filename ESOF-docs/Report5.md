#Report 5: Software Maintenance/Evolution

##Index
1. [Introduction](#Intro)
2. [Software maintainability](#Maint)
3. [Evolution process](#Evolution)
4. [Pull Request](#Pull)

##Introduction  <a name="Intro"></a>

In this report we tried to discuss about software maintainability and evolution process of la4j. Software maintainability is defined as the degree to which an application is understood, repaired, or enhanced. Software maintainability is important because it is approximately 75% of the cost related to a project.And software evolution is the term used in software engineering (specifically software maintenance) to refer to the process of developing software initially, then repeatedly updating it for various reasons.

##Software maintainability  <a name="Maint"></a>

Software maintenance is the process of changing the software after it has been delivered, may be to correct coding or design errors or even to fulfil new requirements. Along comes software maintainability which is how easy a system can be modified and maintained. A good maintainability is a characteristic of software quality, since hardly no software stays unchangeable after its delivery.

Maintenance can be distinguished in four types: corrective maintenance, where bugs discovered are fixed, adaptive maintenance used to upgrade the system to adapted to environment changes, perfective maintenance where the software is changed to meet new requirements and, finally, preventive maintenance has the purpose to increase software quality in order to prevent future bugs from occurring. 

Software maintainability should be one of the main objectives when developing a new software. According to 'Building Maintainable Software' by Joost Visser "maintainability is a quality characteristic on a scale, it signifies different degrees of being able to maintain".  Software maintainability is an important characteristic of the system, because it can subsequently have a business and other quality characteristics impact.

By using the SIG metrics, we can establish if a given software is easy or hard to maintain. 


|SIG metric 	| Description
|---	        |---	
|Write short units of code 	  |  small units are easy to understand, easy to test and easy to reuse	
|Write simple units of code   |  keeping the number of branch points low makes units easier to modify and test	
|Write code once              |copied code makes that bugs need to be fixed at multiple places, which is inefficient and error-prone
|Keep unit interfaces small   |  keeping the number of parameters low makes units easier to understand and reuse 	
|Separate concerns in modules | changes in a loosely coupled codebase are much easier to oversee and execute than changes in a tightly coupled code‐ base	
|Couple architecture components loosely  	| isolated maintenance it’s easier with independent components
|Keep architecture components balanced 	  |   	balanced components makes it easier to locate code and allow for isolated maintenance
|Keep your codebase small  	  |   	keeping product, project and team size small is a crucial point for a successful software
|Automate tests             	| automated testing makes development foreseeable and less dangerous
|Write clean code             |clean code makes a maintainable software 

[![BCH compliance](https://bettercodehub.com/edge/badge/nunomiguel1995/ESOF-la4j)](https://bettercodehub.com)

To test la4j SIG metrics it was used Better Code Hub at https://bettercodehub.com where the project score a three out of ten. This is not a good grade, since it means that this software it is going to be hard to maintain and it will affect its quality. The only metric that la4j follows are couple architecture components loosely, a small codebase and clean code. Next follows the link to the Better Code Hub analysis.

##Evolution process  <a name="Evolution"></a>

##Pull Request  <a name="Pull"></a>

