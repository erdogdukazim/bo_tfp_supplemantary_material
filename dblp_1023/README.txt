DBLP REDUCED NETWORK WITH ORIGINAL AUTHOR IDs
=============================================

Important design choices
------------------------
- Selected network contains 1023 authors.
- Original DBLP author IDs are preserved; there is NO renumbering.
- dblpskills58.txt is the ORIGINAL full 12,855 x 58 skill matrix.
  Therefore row i still corresponds exactly to original author vi.
- dblp_random_58_skills.txt is also kept unchanged for the same reason.
- dblpNoOfPubAndDistance58.txt contains only relationships for selected
  authors, but every author ID remains the original v*** ID.
- selected_authors.txt defines which original author IDs belong to the
  reduced network and their selection order.
- qno values in dblp_instance_information.txt were recomputed using only
  the selected-author population.

Skills missing from the selected 1023-author population: [4, 28, 32, 33, 44]
