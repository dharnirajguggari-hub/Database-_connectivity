### Company Data Storage Requirements

TECHIMPACKT:

The company is organized into branches. Each branch has a unique number, a name, and a particular employee who manages it.

The company makes it’s money by selling to clients. Each client has a name and a unique number to identify it.

The foundation of the company is it’s employees. Each employee has a name, birthday, sex, salary and a unique number.

An employee can work for one branch at a time, and each branch will be managed by one of the employees that work there. We’ll also want to keep track of when the current manager started as manager.

An employee can act as a supervisor for other employees at the branch, an employee may also act as the supervisor for employees at other branches. An employee can have at most one supervisor.

A branch may handle a number of clients, with each client having a name and a unique number to identify it. A single client may only be handled by one branch at a time.

Employees can work with clients controlled by their branch to sell them stuff. If nescessary multiple employees can work with the same client. We’ll want to keep track of how many dollars worth of stuff each employee sells to each client they work with.

Many branches will need to work with suppliers to buy inventory. For each supplier we’ll keep track of their name and the type of product they’re selling the branch. A single supplier may supply products to multiple branches.

## E-R Diagram ### Company Data Storage Requirements

TECHIMPACKT:

The company is organized into branches. Each branch has a unique number, a name, and a particular employee who manages it.

The company makes it’s money by selling to clients. Each client has a name and a unique number to identify it.

The foundation of the company is it’s employees. Each employee has a name, birthday, sex, salary and a unique number.

An employee can work for one branch at a time, and each branch will be managed by one of the employees that work there. We’ll also want to keep track of when the current manager started as manager.

An employee can act as a supervisor for other employees at the branch, an employee may also act as the supervisor for employees at other branches. An employee can have at most one supervisor.

<img width="1220" height="736" alt="er diagrams" src="https://github.com/user-attachments/assets/0655a22b-0f0a-4d52-9ec3-3219a9dd6f05" />


 Algorithem for Schema diagram

### seps1:-
	 Mapping of regular entity Type	for each regular entity type create a realtion type create a realtion (table)that  include all that includes the smile attributes of that entity

### Step 2: Mapping of Weak Entity Types:
	For each weak entity type create a relation (table) that includes all simple attributes of the weak entity

### Step 3: Mapping of Binary 1:1 Relationship Types: 
	Include one side of the relationship ##as a foreign key in the other Favor total participation

### Step 4: Mapping of Binary 1:N Relationship Types
	Include the 1 side's primary key as a foreign key on the N side relation (table)

### Step 5: Mapping of Binary M:N Relationship Types
	Create a new relation (table) who's primary key is a combination of both entites' primary key's. Also include any relationship attribtes

<img width="1220" height="736" alt="ERschema" src="https://github.com/user-attachments/assets/cda752d4-716f-4ef1-822c-3421fcc56c0d" />
