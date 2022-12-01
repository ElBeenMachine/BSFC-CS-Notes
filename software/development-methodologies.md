# Development Methodologies

## **The Process**

* When writing a program, you are going through a number of distinct problems.
* Together, these phases are known as the Systems Development Life Cycle (SDLC):

### **Phase 1: Feasibility Study**

* Focuses on helping ask the essential question: should we proceed?

### **Phase 2: Requirements**

* Analyse carefully what the user wants and we define the project goals into a set of requirements.
* Try to gain as much information as possible.
* Analyse carefully what the client wants / user needs.
* Defining the procedures or what the system needs to do.
* Breaking down the problem into main functions.
  * This involves defining the data, uses, volumes and characteristics.
* The future - development plans and expected growth rates.
* Problems with any existing systems.
* The end result of this phase is a requirement specification document, which outlines everything the user wants the proposed system to do.
* It is this document which is checked and signed off during acceptance testing at the end of a project.

### **Phase 3: Analysis and Design**

* Describes the desired features and operations in detail.
* It includes mocked up screen layouts, business rules, process diagrams, pseudo code and lots of other documentation.
* **Design:**
  * Breaking down the process into individual modules and further breaking these down until each module performs a well designed task.
  * Things considered may include: processes, user interface, output, input, data structures (Arrays, Lists, DBs etc).
  * Security.

### **Phase 4: Implementation**

* This is the phase where the actual code is written.

### **Phase 5: Testing**

* All the code has to be placed in a special testing environment to be tested for errors and bugs.
* This phase checks that the system actually works as intended.
* **Acceptance Testing: a testing technique performed to determine whether or not the software system has met the requirement specifications. The main purpose of this test is to evaluate the system’s compliance with the business requirements and verify if it has met the requirements specified earlier.**

### **Phase 6: Evaluation**

* Using criteria, the finished system is evaluated against the objectives which were originally agreed between the client and the analyst.
* Evaluation includes:
  * Evidence of success or not: did the system meet the requirements?
  * Evidence that the new system functions as designed, both in terms of algorithmic functions and interface design.
  * Post-implementation review, which is a critical examination of the system three to six months after it has been put in operation.
  * The solution should be evaluated on the basis of effectiveness, usability and maintainability

### **Phase 7: Maintenance**

* Covers everything that happens in the rest of the software’s life, after it has been installed. Changes, corrections, additions and updates are all included.
* Discuss the future maintenance of the program and any limitations in the current versions.

## **Development Models**

### **Waterfall Model**

* Derives its name due to the cascading effect of one phase to another.
* Each phase has a well defined starting and end point, with identifiable deliveries onto the next phase. (each step has specific outputs that lead into the next step).
* Each step is completed one at a time from beginning to end.
* It is possible to return to a previous stage if necessary but the model shows that the developers then have to work back down through the following stages.
* The user / customer is involved at the start of the process, in the analysis stage, but then has little input until the evaluation stage.
* It has now been superseded by more effective models.

### **Rapid Action development (RAD)**

* Methodology for designing and writing software that includes producing successive prototyping versions of the software until the final version has been produced.
* Since very large projects may be developed over a long period of time during which both technology and user requirements change.
* Major changes at late stages of development can sometimes lead to projects being cancelled or restarted, at a considerable cost.
* In response to this problem the RAD methodology was introduced, offering the promise of much faster completion of major projects.
* The ideas behind it include:
  * Workshops and focus groups to gather requirements rather than formal requirements document.
  * The use of prototyping to continually refine the system in response to user involvement and feedback.
  * Producing within a strict time limit each part of the system, which may not be perfect but which is good enough.
  * Reusing any software components which have already been used elsewhere.
* Iterative development and each cycle can last a week.

### **Spiral Model**

* Risk driven approach to development. It acknowledges that risk is at the heart of many large scale development projects. It is designed to take into account these risks while they arise in the project and then deal with them before they become a major problem.
* At the start of the process the requirements are defined and the developers working towards an initial prototype.
* Each successive loop around the spiral generates a refined prototype until the product is finished.
* The model has four states:
  * The first quadrant determines objectives.
  * The next quadrant identifies and resolves risks.
  * A prototype is then developed, which is tested in the third quadrant.
  * The final quadrant is either completion or planning the next iteration.

### **Agile Methodologies and Extreme Programming**

* A group of development methodologies.
* Used when stages of software development may not be completed in a linear sequence.
* The developer may then go back to design another aspect of the system.
* Focus on the idea that the requirements will constantly shift and change whilst the development is taking place.
* This can only be done by producing software in an iterative manner, with each iteration having increased requirements and being shown to the user.
* Throughout the process, feedback will be obtained from the user, this an iterative process during which changes made are incremental as the next part of the system is built.
* **Extreme programming** is an example and it has short iterations.
* It is intended to improve software quality and responsiveness to changing customer requirements.
* It is a type of agile software development in which frequent “releases” of the software are made in short development cycles.
* This is intended to improve productivity and introduce checkpoints at which new customer requirements can be adopted.
* For this to work, a company will often embed a user into the development team, so it will be able to give instant feedback on the next iteration.

### Pros and Cons

#### Waterfall

| Pros                                   | Cons                                           |
| -------------------------------------- | ---------------------------------------------- |
| Simplicity                             | Lack of flexibility                            |
| Easy model to manage                   | High risk factor                               |
| Each stage has clear deliverables      | End user is very removed from development      |
| Each stage has well-defined boundaries | Poor choice for systems with unsure boundaries |
| Easy to spot timescale slips           |                                                |

#### Rapid Action Development

| Pros                                                      | Cons                                             |
| --------------------------------------------------------- | ------------------------------------------------ |
| User feels involved                                       | Regular contact with client needed               |
| End product is more likely to match the user requirements | Does not scale well to large products            |
|                                                           | Not suitable if efficiency of code is a priority |

#### Spiral Model

| Pros                          | Cons                                                   |
| ----------------------------- | ------------------------------------------------------ |
| Focuses on risks              | Risk management is a very specialised and costly skill |
| Works well for large products |                                                        |

#### Agile and Extreme

| Pros                         | Cons                         |
| ---------------------------- | ---------------------------- |
| Quality of code is very high | Increased development cost   |
| Efficient code and few bugs  | Heavy collaboration required |
|                              | Embedded end user required   |
