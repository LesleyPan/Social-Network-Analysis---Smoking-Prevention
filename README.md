# Social-Network-Analysis---Smoking-Prevention
A Social Network Analysis Study to investigate the peer influence of a student smoking prevention

This study examines a one school cohort in a secondary school in a peer-led program with respect to its associations between friendship and smoking-related behavior during the post-intervention period, trying to add evidence to some conclusions of previous research as well as add insights to the field. A ***Stochastic Actor Oriented Models (SAOM) -based approach*** is employed here to conduct the longitudinal social network analysis.

## Data Collection
The datasets were collected in the ASSIST (A Stop Smoking in Schools Trial) program
conducted in the UK, which aimed to reduce adolescent smoking prevalence by the schoolbased,
peer-led, smoking intervention. In this program, students in the fifty-nine randomly
selected secondary schools were followed up for at least two years to see the effects of the
intervention. Interviews and questionnaires were used to obtain data from participated
students. This study evaluates a 3-wave penal dataset of a one school cohort in a Welsh
secondary school starting at age 13-15 of participants in 2003, where a total of 211 students
engaged, while 181 students were present at all three measurements. Up to 8 students were
trained to encourage their classmates not to smoke during the intervention period.

## Methods
I use the approach based on the stochastic actor-oriented model (SAOM) to test the three 
hypothesizes. SAOM is currently the most popular method for modeling longitudinally
observed networks, focusing on the co-evolution of network features and individual characteristics.
The central part of SAOM is modeling the Ministeps which allows us to examine
both selection and influence processes simultaneously. This analysis implements SAOM in
R by using RSiena (Simulation Investigation for Empirical Network Analysis) package.

## Examples of the Result Visualization

<img width="439" alt="1635938948(1)" src="https://user-images.githubusercontent.com/56775305/140052577-d7cf4f70-d426-41ca-9ad1-e88e9c9a361f.png">

Figure 1: Obeserved Distribution of three smoking behaviors

<img width="518" alt="1635938990(1)" src="https://user-images.githubusercontent.com/56775305/140052660-1911bdc2-9dca-4f69-96fb-763306da7c80.png">

Figure 2: Distribution of Moran’s I
