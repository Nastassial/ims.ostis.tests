#Common tests
##Description
Common tests are used for any ontology formation agent. They are covers basic test cases. Specific for some ontology test cases should be orgonized as seperated tests.
##Test 1
Input argument: valid subject domain.
Expected result: valid ontology.
##Test 2
Input argument: structure that is not subject domain.
Expected result: validation message "Wrong parameter! Node supplied as a parameter to the input is not a subject domain".
##Test 3
Input argument: subject domain with fake ontologies.
Expected result: agent should remove fake ontology and form new.
##Test 4
Input argument: subject domain without specified key sc-elements.
Expected result: agent should form ontology without elements.

#Note
 - There is declaration of common key elements for subject domain to test in `common_key_sc_elements.scs` file.
 - Each neighborhood of testable subject domain should be saved in seperated file in folder of an according agent. 
