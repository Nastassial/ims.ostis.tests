# Tests
## Test 1
Input argument: TS_agent_of_removing_sc_element2.
Expected result: sc-links with identifiers should't be removed because they are related to another sc-element.
## Test 2
Input argument: binary arc
	TS_agent_of_removing_sc_element
	**=>** nrel_main_idtf:
		[test(agent of removing sc-element)]
		(* <- lang_en;; *);
Expected result: `TS_agent_of_removing_sc_element` doesn't have main identifier on English. 

## Test 3
Input argument: `Russian language`
Expected result: there is no `Russian language` sc-element in KB. 

#Before each test
Find `TS_agent_of_removing_sc_element_struct` to get access to removal sc-elements
