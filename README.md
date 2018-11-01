# --- in progress ---
<p>
<p>
  
# DonorsChoose.org Challenge: 

# Supporting Educators & Refugee Students
<p>
  
## Who We Are
Teachers come to DonorsChoose.org to request the materials and experiences they need most for their classrooms, and donors give to the projects that inspire them. To date, 3,365,526 people and partners have funded 1,231,234 projects on the site, reaching 29,584,677 students and making DonorsChoose.org the leading platform for supporting U.S. public schools. DonorsChoose.org is the only crowdfunding platform that vets each request, delivers materials directly to schools, and captures the impact of every funded project with photos, thank yous, and a cost report showing how each dollar was spent.
<p>
We believe we have a unique role to play in improving the experience for refugee students in public schools across the country, and for the educators who serve them. 
<p>
  
  #### Challenge Leads
  Barbara Cvenic - @barbara - Director, Data Science & Analytics
  <p>
  Amit Wadhera - @amit - Sr. Director, Customer Insights

## Challenge Objectives
  
#### I. How well are we supporting refugee students and the educators that serve them today?
We want to identify "funding deserts" across the U.S. -- are there certain states, cities, or districts where there are large refugee student populations that are not receiving DonorsChoose.org funding? 
<p>
  <u>This task could involve:</u>
  
    1. Parsing text in project essays to identify and label projects serving refugee students
    2. Mapping the funding those projects received
    3. Mapping resettlement data on top of project funding to see where funds are going to serve refugee populations, and where refugee populations exist with little DonorsChoose.org funding
    4. Finding external datasets that identify refugee student populations on a more granular level, (city, district, school, etc.)
    
#### II. Who are our donors? Which donors are most likely to fund projects supporting refugee students? What type of language in a project essay is most effective?
We want to better understand who are donors are, so we may better market to them, ultimately unlocking more dollars to classroom projects across the country. We're particularly interested to see if there is anything unique about the donors who support refugee students, in particular.
<p>
  <u>This task could involve:</u>
  
    1. Finding trends in the types of projects first-time donors have given to, the amounts they've given, etc.
    2. Using NLP to analyze donation messages to better understand donor motivation
    3. Analyzing supplemental donor data, including demographic data, voter reg data, etc. 
    4. Using NLP to analyze project essays to identify trends in the type of language that appeals to different groups of first-time donors
    
#### III. What do teachers who serve refugees need to be successful in the classroom?
Teachers often use DonorsChoose.org not only to get the resources they need for their classrooms, but to gather inspiration from other educators. Our teachers look to one another to determine the best way to teach financial literacy, or navigate a national conversation with students. We want to better understand what teachers serving refugee populations need for their classrooms, so we can serve up relevant, compelling recommendations to similar teachers.
<p>
  <u>This task could involve:</u>
  
    1. Analyzing survey data
    2. Using NLP to analyze project essays and resources to identify trends in the type of resources teachers serving refugee students need
    3. Building a recommendation system that suggests relevant projects to teachers based on their attributes


## The Data Available

  | Dataset                                                                                                                                                | Details                                               | Challenges                                                                 |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------|-------------------------------------------------------------------------------|
| <b>Transactional data about projects and donations<b>                                                                          | Every project that is posted on DonorsChoose.org includes a detailed project essay, describing the students in the classroom and the resources or experiences the teacher is requesting. <p><p>It also includes detailed resource information about the materials the teacher is requesting, (down to the SKU or ASIN number). We also every donation, including the amount, whether we think the donor knew the teacher personally, and the donation message they left the classroom. | I, II, & III |
  | <b>Survey data</b> | We surveyed a group of teachers across the country, receiving around 1,000 responses, to find out more about who serves refugee students, how those students perform academically compared to their peers, what services are provided to those students, and teachers' general literacy around refugee issues. | I & III |
| <b>School data</b>                                                                                |Some additional data about the schools our teachers come from, including whether those schools have an ELL program, the percentage of students in the district who are in ELL programs, and geographic information (city, state, district, metro type). | I & III |
| <b>Supplemental donor data</b>                                                                                |We've obtained some additional data about our first-time donors, including their age, gender, and political affiliations.| II |
| <b>Refugee resettlement data</b>                                                                                |This is data we pulled from U.S. government sites on the number of refugees resettled, by State.| I |
