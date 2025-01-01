### Data Flow Structure for Clinical Trial Enrollment Prediction

- **Conditions**  
    |  
    v  
- **Time Taken for Enrollment** <----- **Country**  
    |                      ↑                        |  
    v                      |                        v  
- **Interventions** ---> **Enrollment** ---> **Study Design** ---> **Period**  
    |                      ↑                |  
    v                      |                v  
- **Primary Outcome Measures**      |       **Study Phases**  
    |                      |                ↑  
    v                      |                |  
- **Secondary Outcome Measures**    |         **Criteria**  
    |                      ↑  
    v  
- **Sex** ---------> **Age** --> **City** -----> **Count**
