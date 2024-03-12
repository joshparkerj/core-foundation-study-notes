# Terms

* accessibility testing
  * type of usability testing used to measure the degree to which a test item can be operated by users with the widest possible range of characteristics and capabilities
* actual results
  * set of behaviors or conditions of a test item, or set of conditions of associated data or the test environment, observed as a result of test execution
  * example: Outputs to hardware, changes to data, reports, and communication messages sent.
* backup and recovery testing
  * type of reliability testing that measures the degree to which system state can be restored from backup within specified parameters of time, cost, completeness, and accuracy in the event of failure
* black-box testing
  * see specification-based testing
* capacity testing
  * type of performance efficiency testing conducted to evaluate the level at which increasing load (of users, transactions, data storage, etc.) compromises a test item's ability to sustain required performance
* compatibility testing
  * type of testing that measures the degree to which a test item can function satisfactorily alongside other independent products in a shared environment (co-existence), and where necessary, exchanges information with other systems or components (interoperability)
* coverage item
  * see test coverage item
* decision
  * types of statements in which a choice between two or more possible outcomes controls which set of actions will result
  * typical decisions are simple selections (e.g. if-then-else), to decide when to exit loops (e.g. while-loop), and in case (switch) statements (e.g. case-1-2-3-..-N)
* dynamic testing
  * testing that requires execution of the test item
* endurance testing
  * type of performance efficiency testing conducted to evaluate whether a test item can sustain a required load continuously for a specified period of time
* equivalence partition
  * subset of the range of values of a variable, or set of variables, within a test item or its interfaces such that all the values in the partition can be reasonably expected to be treated similarly by the test item (i.e. they may be considered "equivalent") by the test item
* equivalence partition coverage
  * proportion of identified equivalence partitions of a test item that are covered by a test set
  * in many cases, the identification of equivalence partitions is subjective (especially in the sub-partitioning of "invalid" partitions), so a definitive count of the number of equivalence partitions in a test item could be impossible.
* equivalence partitioning
  * test design technique in which test cases are designed to exercise equivalence partitions by using one or more representative members of each partition
* error guessing
  * test design technique in which test cases are derived on the basis of the tester's knowledge of past failures, or general knowledge of failure modes
  * the relevant knowledge could be gained from personal experience, or might be encapsulated in, for example, a defects database or "bug taxonomy"
* expected results
  * observable predicted behavior of the test item under specified conditions based on its specification or another source
* exploratory testing
  * experience-based testing in which the tester spontaneously designs and executes tests based on the tester's existing relevant knowledge, prior exploration of the test item (including the results of previous tests), and heuristic "rules of thumb" regarding common software behaviors and types of failure
  * exploratory testing hunts for hidden properties (including hidden behaviors) that, while quite possibly benign by themselves, could interfere with other properties of the software under test, and so constitute a risk that the software will fail
* feature set
  * collection of items which contain the test conditions of the test item to be tested which can be collected from risks, requirements, functions, models, etc.
  * this could be the set of all features for the item (its full feature set), or a subset identified for a specific purpose (the functional feature set etc.)
* incident report
  * documentation of the occurence, nature, and status of an incident
* installability testing
  * type of portability testing conducted to evaluate whether a test item or set of test items can be installed as required in all specified environments
* load testing
  * type of performance efficiency testing conducted to evaluate the behavior of a test item under anticipated conditions of varying load, usually between anticipated conditions of low, typical, and peak usage
* maintainability testing
  * test type conducted to evaluate the degree of effectiveness and efficiency with which a test item may be modified
* Organizational Test Policy
  * an executive-level document that describes the purpose, goals, and overall scope of the testing within an organization, and which expresses why testing is performed and what it is expected to achieve
  * it is generally preferable to keep the organizational test policy as short as possible in a given context
* Organizational Test Process
  * test process for developing and managing organizational test specifications
* organizational test specification
  * document that provides information about testing for an organization, i.e. information that is not project-specific
  * the most common examples of organizational test specifications are Organizational Test Policy and Organizational Test Strategy
* Organizational Test Strategy
  * document that expresses the generic requirements for testing to be performed on all the projects run within the organization, providing detail on how the testing is to be performed
  * The Organizational Test Strategy is aligned with the Organizational Test Policy
  * An organization could have more than one Organizational Test Strategy to cover markedly different project contexts
* pass/fail criteria
  * decision rules used to determine whether a test item, or feature of a test item, has passed or failed after testing
* performance testing
  * type of testing performed to evaluate the degree to which a test item accomplishes its designated functions within given constraints of time and other resources
* portability testing
  * type of testing conducted to evaluate the ease with which a test item can be transferred from one hardware or software environment to another, including the level of modification needed for it to be executed in various types of environment
* procedure testing
  * type of functional suitability testing conducted to evaluate whether procedural instructions for interacting with a test item or using its outputs meet user requirements and support the purpose of their use
* product risk
  * risk that a product may be defective in some specific aspect of its function, quality, or structure
* project risk
  * risk related to the management of a project
  * lack of staffing, strict deadlines, changing requirements
* regression testing
  * testing following modifications to a test item or its operational environment, to identify whether regression failures occur
  * the sufficiency of a set of regression test cases depends on the item under test and on the modifications to that item or its operational environment.
* reliability testing
  * type of testing conducted to evaluate the ability of a test item to perform its required functions, including evaluating the frequency with which failures occur, when it is used under stated conditions for a specified period of time
* retesting
  * re-execution of test cases that previously returned a "fail" result, to evaluate the effectiveness of intervening corrective actions
  * also known as confirmation testing
* risk-based testing
  * testing in which the management, selection, prioritisation, and use of testing activities and resources are consciously based on corresponding types and levels of analyzed risk
* scenario testing
  * class of test design technique in which tests are designed to execute individual scenarios
  * a scenario can be a user story, use-case, operational concept, or sequence of events the software may encounter, etc.
* scripted testing
  * dynamic testing in which the tester's actions are prescribed by written instructions in a test case
  * this term normally applies to manually executed testing, rather than the execution of an automated script
* security testing
  * type of testing conducted to evaluate the degree to which a test item, and associated data and information, are protected so that unauthorized persons or systems cannot use, read, or modify them, and authorized persons or systems are not denied access to them
* specification based testing
  * testing in which the principal test basis is the external inputs and outputs to the test item, commonly based on a specification, rather than its implementation in source code or executable software
  * synonyms for specification-based testing include black-box testing and closed box testing
* statement coverage
  * percentage of the set of all executable statements of a test item that are covered by a test set
* statement testing
  * test design technique in which test cases are construed to force execution of individual statements in a test item
* static testing
  * testing in which a test item is examined against a set of quality or other criteria without code being executed
  * reviews, static analysis
* stress testing
  * type of performance efficiency testing conducted to evaluate a test item's behavior under conditions of loading above anticipated or specified capacity requirements, or of resource availability below minimum specified requirements
* structural testing
  * see structure-based testing
* structure-based testing
  * dynamic testing in which the tests are derived from an examination of the structure of the test item
  * structure-based testing is not restricted to use at a component level and can be used at all levels, e.g. menu item coverage as part of a system test
  * techniques include branch testing, decision testing, and statement testing
  * synonyms for structure-based testing are structural testing, glass-box testing, and white box testing
* suspension criteria
  * criteria to (temporarily) suspend all or a portion of the testing activities
* test basis
  * body of knowledge used as the basis for the design of tests and test cases
  * the test basis may take the form of documentation, such as a requirements specification, design specification, or module specification, but may also be an undocumented understanding of the required behavior
* test case
  * set of test case preconditions, inputs (including actions, where applicable), and expected results, developed to drive the execution of a test item to meet test objectives, including correct implementation, error identification, checking quality, and other valued information
  * a test case is the lowest level of test input (i.e. test cases are not made up of test cases) for the test sub-process for which it is intended
  * test case preconditions include test environment, existing data (e.g. databases), software under test, hardware, etc.
  * inputs are the data information used to drive test execution
  * expected results include success criteria, failures to check for, etc.
* Test Case Specification
  * documentation of a set of one or more test cases
* Test Completion Process
  * Test Management Process for ensuring that useful test assets are made available for later use, test environments are left in satisfactory condition, and the results of testing are recorded and communicated to relevant stakeholders
* Test Completion Report
  * report that provides a summary of the testing that was performed
  * also known as a Test Summary Report
* test condition
  * testable aspect of a component or system, such as a function, transaction, feature, quality attribute, or structural element identified as a basis for testing
  * test conditions can be used to derive coverage items, or can themselves constitute coverage items
* test coverage
  * degree, expressed as a percentage, to which specified test coverage items have been exercised by a test case or test cases
* test coverage item
  * attribute or combination of attributes that is derived from one or more test conditions by using a test design technique that enables the measurement of the thoroughness of the test execution
* test data
  * data created or selected to satisfy the input requirements for executing one or more test cases, which may be defined in the Test Plan, test case, or test procedure
  * test data could be stored within the product under test (e.g. in arrays, flat files, or a database), or could be available from or supplied by external sources, such as other systems, other system components, hardware devices, or human operators.
* Test Data Readiness Report
  * document describing the status of each test data requirement
* Test Design and Implementation Process
  * test process for deriving and specifying the test cases and test procedures
* Test Design Specification
  * document specifying the features to be tested and their corresponding test conditions
* test design technique
  * activities, concepts, processes, and patterns used to construct a test model that is used to identify test conditions for a test item, derive corresponding test coverage items, and subsequently derive or select test cases
* test environment
  * facilities, hardware, software, procedures, and documentation intended for or used to perform testing of software
  * a test environment could contain multiple environments to accomodate specific test sub-processes (e.g. a unit test environment, )