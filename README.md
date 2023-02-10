### Coding Challenge Guidelines

#### Description

At Financial Lease we want to create a system for our users to be able to earn credits every time
that they close a new contract. With these credits they should be able to get a discount on their
new contract, or they can use it to get additional services for their car.

The amount of credits that they get, will depend on the bank where the contract is closed, and the
size of the contract (in euros). For each euro, they will earn one credit

The credits status of the credits will be recorded our CRM application, but for the user we want to
give them insight in their credit, using an app. 

The app should be a web application, where users have an account. After logging in, they can see
all their contracts (with the appropriate details of the contract) and the amount of points earned on
that contract.
Assume that the CRM knows, based on the user credentials, which contracts should be visible to the user.

The app should retrieve get the information via an API from the CRM. Each contract is uniquely
identifiable.

The amount of credits is part of the response from the api.

#### Assignment

They asked you to distill the requirements from the description above. Try to formulate the
requirements (as much as you can distill) for the app.

For each requirement, write one or more scenario(s) to cover the requirement in such a way, that the
requirement and the risk of the requirement are covered. This means that you will need to identify the
features that, according to you are high risk. Contract, Bank and user information is considered as highly
confidential. If there is no need to cover it with a test scenario, explain why the requirement is omitted
in the test.

In the test scenario, also define the inputs that are required (state the system should be in) and the
state of the system after the test is executed.

If more information is needed, ask the stakeholders for input (rik.degroot@financiallease.nl)

BONUS: give advice on how to scope this into multiple releases.
BONUS: For the test scenarios, give an indication on the need to automate the cases.

#### Recording

Record the requirements in the [REQUIREMENTS.md](REqUIREMENTS.md) file, and the test scenarios in the
[TESTSCENARIOS.md](TESTSCENARIOS.md) files respectively. For the test scenarios, add a reference to
the requirement that it covers.

### Evaluation Criteria

#### Requirements

* Unambiguous
* Testable (verifiable)
* Clear (concise, terse, simple, precise)
* Correct
* Understandable
* Feasible (realistic, possible)
* Independent
* Atomic
* Necessary
* Implementation-free (abstract)

#### Test scenarios

* Executability
* Precoditions and state
* Inputs required
* Output definition

### CodeSubmit

Please organize, design, test, and document your code as if it were
going into production - then push your changes to the master branch.

Have fun coding! 🚀
