# pandas-challenge
pandas assignment for module 4
This was a challenging assignment, yet extremely rewarding.

I downloaded the zip to my computer. 
I saved the spreadsheets into my Pandas assignment folder. 
I created a jupyter notebook, which I searched online how to do.
I started from scratch.
I imported the files from the folder into Pandas.
My classnotes were my bread and butter for this assingment. 


I reached out to BCS four times to complete this assingment.  

1. Calculating the percentage of students who passed math. I was doing a groupby and placing the entire method in one line. BCS explained how a variable should first be created and then filter that variable per schools. BCS explained how the variable i built held a boolean. BCS also explained why a .size() was better than a .count(). Lebuso assisted me. 

2. Calculating budget per student. I knew I had to divide the budget per student and I knew I had to use the variables I created but I was using groupby and .mean() and paranthesis and brackets-everything that was not necessary. I reached out to BCS and they told me to just use the / to divide the variables. Jleverenz assisted me. 

3. Establishing bins. The inequlity sign in the labels list gave me problems. I got an error that said the < was not supported between int and string. I was not sure what that meant since I didn't think  had strings. BCS helped me place the correct variable within the pd.cut and explained how right=False was better than include_lowest=True. it will include the items on the left but not on the right since it will alredy be included within the next pairs sinc it will then be on the left. Khan assisted me. 

4. Calculate mean for the spending summary. I couldnt take the mean becuase my variables were in strings. BCS helped me realize that mapping turns it into strings. We went back to per_school_summary and we saw that i had mapped average reading, average math, passing math, passing reading and overall passing which was not allowing me to take the mean. BCS helped me maintain the 6 decimal places without turning them into a string. After fixing this issue I was able to take the mean for the spending summary. Rober assisted me. 
