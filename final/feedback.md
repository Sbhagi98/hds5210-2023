# Feedback on your final

**Final Score: 55/60**

The grading rubric for the final can be found in GitHub: https://github.com/paulboal/hds5210-2023/blob/main/final/final-instructions.pdf

**Functional Requirements**
* 5 points - Uses data from at least two different sources: local file, internet, web service, relational database, AWS S3, etc; and formats: CSV, JSON, database, XML, Excel, etc
* 5 points - Data from multiple sources has to be joined together at least twice
* 5 points - Data is aggregated or pivoted at least twice during the program
* 5 points - Some kind of field-level transformation is performed at least 5 times
* 5 points - The program creates 3 or more data visualizations 
* 5 points - The program serves a theoretical purpose described in documentation, that could potentially do something in healthcare or another industry of interest

**Modularity / Style**
* 15 points - The code is broken up into various functions or classes to make testing and reuse easier

**Documentation and Professionalism**
* 15 points - All functions are documented and notebook cells include annotations and explanations.

**(-2) Generic variable names like `dataset1` or `dataset2` are not acceptable.  They make it hard for the reader to understand what is going on and what this variable refers to. You continue this throughout your project with merged and pivot dataframes.**

**(-1) You do a step where you drop duplicates based on Age... but the data is more specific than Age.  By dropping data, you're just ignoring some of the information. It would be better to aggregate the data somehow rather than just arbitrarily throw some away.**

**(-2) It would have been useful to explain WHY you did the specific exploration you did.  Why was it important to plot Cholesterol Level by Gender, for example.  You did lots of great visualization, buy WHY and WHAT DID YOU LEARN?**

**Your final project was very good.  You fulfilled all the technical requirements, but your report and programming style could have been strong. Keep practicing and think about the person reading your code.  Will they find it easy to understand?**

