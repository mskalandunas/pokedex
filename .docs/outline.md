# Outline
## OVERVIEW
The overview is a high-level description of what this project is as well as its goals.  Talk about the goal of the Pokédex project and the "role-playing" element of it.

## PROBLEM STATEMENT
Describe why the Pokédex needs to be made.  Pretend this is a world where there are Pokémon but no one has come up with a way to categorize and document them al in such a way that's accessible to trainers on the go.

## APPROACH
This section should describe the overall approach from problem statement to implementation.  I believe loosely following DDD is the right move -- establish ubiquitous language, domain events, domain models, etc.  

Make sure to mention when efforts could be parallelized.  Even though things will be done linearly for this document, mentioning how an AGILE team could parallelize efforts at least paints a fuller picture.

## PRODUCT REQUIREMENTS
List out product requirements with explanations.  Mention that engineering and design can now begin work.  Engineering can begin to conceptualize an implementation, especially if there is no UI as domain entities will have been decided by this point, and design can work on the UI.

## DESIGN
Mention that UI design will be shoddy given the lack of experience.  Describe how design will be sequenced given product requirements (mobile first).  

Mention that conversations with product and engineering should be happening to discuss 1) how designs, in their current iteration, match up with product specs and 2) feasibility, especially given that designs can lead to scope creep.

## TECHNICAL REQUIREMENTS
It needs to be clear that the poke API is being used.  Because it's a 3rd party API, measures to mitigate rate limiting as well as tight coupling to our codebase need to be described.

Other requirements we know upfront:
- Mobile first
- Transferrable business logic

## IMPLEMENTATION
Describe all of the high-level details of the implementation, and only get to the low-level details in the architecturally significant places.  Make sure to mention interfaces as being of primary importance -- it's hard to change an interface but easy to change the code behind it.  

## CONCLUSION
Discuss the approach, implementation, and some differences from building enterprise software.