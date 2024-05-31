#Setup and load data #Load the two source files #Read school and Student Data file and store into Pandas dataframes #combine the data into a singer dataset
District Summary: #calculate the total number of students #calculate the total budget #calculate the average math score #calculate the average reading score #calculate the Percenrage passing math and percentage passing reading (socres greater than or equal to 70) #Calculate the percentage of students that passed math and reading #creat and display a summary dataframe
School summary: #calculate the total student count per school from school data #calculate the total student count per school from school data # calculate the total school budget and percapita spending per school from school_data (tutor helped corrected the code here) #calculate the average test scores per school from school data #calculate the percentage of students per school with math scores of 70 or higher from school data complete #Calculate the percentage of students per school with math scores of 70 or higher from school_data_complete (googled to figure out a shorter code to do the calculations) #Calculate the percentage of students per school with reading scores of 70 or higher from school_data_complete #calculate the number of students per school that passed both math and reading with scores of 70 or higher #Create a DataFrame called `per_school_summary` with columns for the calculations above
Highest-Performing schools (by percentage overall passing): #Sort the schools by `percentage Overall Passing` in descending order and display the top 5 rows.
Bottom performing schools (by percentage overall passing): #Sort the schools by `percentage Overall Passing` in ascending order and display the top 5 rows.
Math Scores by grade: #Seperate the data by grade #Group by `school_name` and take the mean of the `math_score` column for each # Combine each of the scores above into single DataFrame called `math_scores_by_grade`# Minor data wrangling # Display the DataFrame
Reading score by grade: #Separate the data by grade #Group by `school_name` and take the mean of the the `reading_score` column for each #Combine each of the scores above into single DataFrame called `reading_scores_by_grade`# Minor data wrangling # Display the DataFrame
Scores by school spending: #Create spending bins and labels #Create a copy of the school summary since it has be Per student budget @Use pd.cut to categorize spending based on the bins (Tutor helped adjust the proir codes to help correctly set up the bins here) #calculate averages for the desired columns #Assemble into DataFrame # display results
Scores by school size: #establish the bins #Categorize the spending based on the bins #calculate mean scores per size range #Create a DataFrame called size_summary that breaks dowm school performance based on school size #Display results
Scores by school type: #Group the per_school_summary DataFrame by "School Type" and average the results #Assemble the new data by type into a DataFrame called `type_summary`#display results
