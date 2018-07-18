# Small Concept Spaces For Ontology Evaluations
Small concept spaces defined for usability evaluation of different ontology modelling tools. These are defined with an idea of having same cognitive complexity, so that usability evaluation results are not affected due to the difference in cognitive complexity. These concept spaces contain concepts from among four types that are **Class, Subclass, Datatype Property and Objecttype Property**. The concepts labeled with * can be used multiple times or not at all. Five small concept spaces are presented below:

### University Space(US)
We use this concept space only for training purposes, hence we haven't performed qualitative measurement over the time required to model this ontology.

 <table style="width:100%">
  <tr>
    <td>Staff Member</td>
    <td>Person</td>
    <td>Professor</td>
  </tr>
  <tr>
    <td>University</td>
    <td>Student</td>
    <td>Graduate Student</td>
  </tr>
   <tr>
    <td>has name</td>
    <td>teaches</td>
    <td>Course</td>
  </tr>
   <tr>
    <td>Undergraduate Student</td>
    <td>course name</td>
    <td></td>
  </tr>
   <tr>
    <td>has*</td>
    <td>Is a*</td>
    <td></td>
  </tr>
</table> 

### Zoo Space(ZS)

 <table style="width:100%">
  <tr>
    <td>Animal</td>
    <td>Herbivores</td>
    <td>Snow Leopard </td>
  </tr>
  <tr>
    <td>eats</td>
    <td>Carnivores</td>
    <td>Cheetah</td>
  </tr>
   <tr>
    <td>Zoo</td>
    <td>Goat</td>
    <td>Grass</td>
  </tr>
   <tr>
    <td>grass type</td>
    <td>has legs</td>
    <td></td>
  </tr>
   <tr>
    <td>has*</td>
    <td>Is a*</td>
    <td></td>
  </tr>
</table> 

### City Traffic Space(CTS)
 <table style="width:100%">
  <tr>
    <td>Vehicle</td>
    <td>Bus</td>
    <td>model name</td>
  </tr>
  <tr>
    <td>Manufacturer</td>
    <td>City Traffic</td>
    <td>Public Vehicle</td>
  </tr>
   <tr>
    <td>Car</td>
    <td>manufactured by</td>
    <td>Private Vehicle</td>
  </tr>
   <tr>
    <td>Train</td>
    <td>manufacturing date</td>
    <td></td>
  </tr>
   <tr>
    <td>has*</td>
    <td>Is a*</td>
    <td></td>
  </tr>
</table> 

### Media Space(MS)
 <table style="width:100%">
  <tr>
    <td>Media Network</td>
    <td>News Channel</td>
    <td>Daily News Channel</td>
  </tr>
  <tr>
    <td>channel name</td>
    <td>Sports Channel</td>
    <td>shows</td>
  </tr>
   <tr>
    <td>Local Sports Channel</td>
    <td>News Program</td>
    <td>Channel</td>
  </tr>
   <tr>
    <td>International Sports Channel</td>
    <td>Airing Time</td>
    <td></td>
  </tr>
   <tr>
    <td>has*</td>
    <td>Is a*</td>
    <td></td>
  </tr>
</table> 

### Family Space(FS)
<table style="width:100%">
  <tr>
    <td>Child</td>
    <td>childs birthplace</td>
    <td>Family Tree</td>
  </tr>
  <tr>
    <td>Female</td>
    <td>Mother</td>
    <td>Grandmother</td>
  </tr>
   <tr>
    <td>Male</td>
    <td>gives birth</td>
    <td>Father</td>
  </tr>
   <tr>
    <td>Person</td>
    <td>person name</td>
    <td></td>
  </tr>
   <tr>
    <td>has*</td>
    <td>Is a*</td>
    <td></td>
  </tr>
</table> 

## Quantitative Evaluation of The Concept Spaces
The quantitative evaluation of the above presented four concept spaces that are Zoo Space, Media Space, Family Space and City Traffic Space was measured by recording time completion time of particpants to model these concept spaces. The tool used to model these concept spaces was Protege. 

The task completion time to model the concept spaces are presented below:
<table style="width:100%">
 <tr>
    <th></th>
    <th colspan="4">Task Completion Time For Modeling Ontology(Seconds)</th>
  </tr>
  <tr>
    <th>Participant</th>
    <th>Family Space</th>
    <th>City Traffic Space</th>
    <th>Media Space</th>
    <th>Zoo Space</th>
  </tr>
  <tr>
    <td><b>A</b></td>
    <td>237</td>
    <td>302</td>
    <td>349</td>
    <td>362</td>
  </tr>
   <tr>
    <td><b>B</b></td>
    <td>330</td>
    <td>428</td>
    <td>429</td>
    <td>403</td>
  </tr>
   <tr>
    <td><b>C</b></td>
    <td>389</td>
    <td>183</td>
    <td>361</td>
    <td>270</td>
  </tr>
   <tr>
     <td><b>D</b></td>
    <td>343</td>
    <td>416</td>
    <td>503</td>
    <td>332</td>
  </tr>
 <tr>
     <td><b>SUM</b></td>
    <td>1299</td>
    <td>1329</td>
    <td>1642</td>
    <td>1367</td>
  </tr>
 <tr>
     <td><b>MEAN</b></td>
    <td>324.75</td>
    <td>332.25</td>
    <td>410.5</td>
    <td>341.75</td>
  </tr>
</table> 

## Counterbalancing The Order of Presentation
The order in which the users were asked to model the ontologies using the Protégé was radomized inorder to minimize the order effects. The table below presents the order in which participants were presented with the concept spaces:

<table style="width:100%">
 <tr>
    <th></th>
    <th colspan="4">Concept Spaces</th>
  </tr>
  <tr>
    <th>Participant</th>
    <th>Concept Space A</th>
    <th>Concept Space B</th>
    <th>Concept Space C</th>
    <th>Concept Space D</th>
  </tr>
  <tr>
     <td><b>A</b></td>
    <td>Zoo Space</td>
    <td>City Traffic Space</td>
    <td>Media Space</td>
    <td>Family Tree Space</td>
  </tr>
 
  <tr>
     <td><b>B</b></td>
    <td>City Traffic Space</td>
    <td>Zoo Space</td>
    <td>Family Tree Space</td>
    <td>Media Space</td>
  </tr>
  
  <tr>
     <td><b>C</b></td>
    <td>Family Tree Space</td>
    <td>Media Space</td>
    <td>City Traffic Space</td>
    <td>Zoo Space</td>
  </tr>
  
  <tr>
     <td><b>D</b></td>
    <td>Family Tree Space</td>
    <td>City Traffic Space</td>
    <td>Media Space</td>
    <td>Zoo Space</td>
  </tr>
</table>

