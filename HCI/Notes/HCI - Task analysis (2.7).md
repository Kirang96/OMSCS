2024-09-09

Tags: #HCI
Topic: [[Human computer Interaction]]

### Task analysis

In HCI, we're looking at the tasks that users perform. We restructure the interface so users can do the task more efficiently.

###### GOMS

GOMS model is a human information processor model which means it builds off the processor model of the human's role in a system.

G - Goals
O - Operators
M - Methods
S - Selection rules

Users will have a goal that they want to achieve and they have a set of methods that they can choose from to accomplish those goals and these operators comprises of a series of operations that carries out that method and they have selection rules that help them decide what method to use and when.

![[Pasted image 20240909090549.png]]

Example of GOMS in an interface:

![[Pasted image 20240909094811.png]]

This shows the selection of a method for transferring information to a coworker. The method can be chosen based on the urgency and other criteria.

GOMS: Strengths and weaknesses
Weaknesses: 
1. Doesn't address complexity of problems: There can be many methods and sub-methods.
2. Assumes user is already an expert in the area.
Strengths: 
1. It formalizes user interaction into steps that we can use to make predictions: eg. count the number of steps in each method.

There are variations for GOMS model as well.
The one we discussed is the Vanilla GOMS 
2. KML-GOMS
Keystroke-level model: simply sum the operator and execution times to find the complexity
1. CMN-GOMS
It adds sub-methods and strict goal hierarchy. It allows us to choose a goal from options
1. NGOMSL
Natural GOMS language: its a natural language form of GOMS that lends itself to human interpretation: Since we can read how user needs to recall stuff from memory we can see how working memory is being used and redesign based on it.

Tips:
1. Focus on small goals: GOMS is designed for small goals like scroll to end of document.
2. Nest goals, not operators
3. Differentiate descriptive and prescriptive: We should focus on what users should do with the interface and not on what they will do.
4. Assign costs to operate
5. Use GOMS to trim waste: to remove unnecessary operators

### Cognitive task analysis

GOMS just uses the methods and operators and does not consider the humans role in the system. This is more predictor model oriented unlike GOMS which is processor model oriented.
It is concerned with the underlying thought process associated with performing a task, not just what we can see.
Process of task analysis:
1. Collecting preliminary knowledge
2. identify knowledge representations: what kind of things does a user need to know to complete their task?
3. Apply focused knowledge elicitation methods: we get users to tell us what's going on in their heads/environments.
4. Analyze and verify data acquired.
5. Format results for intended application 

![[cta_sshot.png]]
### Hierarchical task analysis:

A lot of tasks will have parts that are usually used and that can be abstracted over. If we're displaying the tasks as hierarchy of different tasks, then we can find the parts that can be abstracted. 
![[hta_sshot.png]]

In this example the billing and card information and reviewing the purchase is done all the time and that can be skipped with usual steps and designers can focus on other parts.

Strengths:
1. Emphasizes mental processes
2. Formal enough for interface design
Weaknesses:
1. Time-intensive
2. May deemphasize context: Since we're zooming in on the mental processes.
3. Ill-suited for novices

Other types of cognitive models also exist:
1. Critical Decision Method (CDM)
2. Task-Knowledge Structure (TKS)
3. Cognitive Function Model (CFM)
4. Applied CTA
5. Skill-based CTA









