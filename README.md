# CHIS-exercise

The dataset is downloaded from the following link 

http://healthpolicy.ucla.edu/chis/data/public-use-data-file/Pages/TermsOfUse.aspx?file=/chis/data/public-use-data-file/Documents/chis09_adult_stata.zip

# Step 1:
Load dataset

# Step 2 :
Explore the dataset with summary and str

# Step 3 : 
Exploring data using Age Histogram

# Step 4 : 
Exploring data using BMI histogram

# Step 5 : 
Age colored by BMI, default binwidth

# Step 6 :
Remove individual aboves 84

# Step 7 : 
Remove individuals with a BMI below 16 and above or equal to 52

# Step 8 :
Relabel the race variable:

# Step 9 :
Relabel the BMI categories variable:

# Step 10:
color palette BMI_fill

# Step 11: 
Theme to fix category display in faceted plot

# Step 12: 
histogram, add BMI_fill and customizations 
  Plot 1 - Count histogram
  Plot 2 - Density histogram
  Plot 3 - Faceted count histogram
  Plot 4 - Faceted density histogram
  Plot 5 - Density histogram with position = "fill"
  Plot 6 - The accurate histogram
 
 # Step 13 :
 An attempt to facet the accurate frequency histogram from before (failed)
 
 # Step 14 : 
 Create DF with table()
 Use apply on DF to get frequency of each group
 Load reshape2 and use melt on DF to create DF_melted
 Change names of DF_melted
 Add code to make this a faceted plot
 
 # Step 15 : 
 The initial contingency table
 Add the columns groupsSum, xmax and xmin. Remove groupSum again.
 The groupSum column needs to be removed, don't remove this line
 Copy row names to variable X
 Melt the dataset
 dplyr call to calculate ymin and ymax
 Plot rectangles
 
 # Step 16 : 
 Adding statistics
 Perform chi.sq test (RBMI and SRAGE_P)
 Melt results$residuals and store as resid
 Change names of resid
 merge the two datasets:
 Update plot command
 
 # Step 17 : 
 Adding text
 Position for labels on x axis
 Position for labels on y axis 
 Plot
 
 # Step 18 : 
 Generalizations
 Script generalized into a function
 Chi-sq test
 Merge data
 Positions for labels
 plot:
 BMI described by age
 Poverty described by age
 
 
