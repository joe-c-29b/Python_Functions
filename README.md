# Python_Functions
cohort_date2term_converter - a function for converting the begin and end dates of a member of any cohort into academic terms.
  input: a "cohort.csv" file containing a dataframe with beginning and ending dates and the current academic term as a 5 digit integer.
  output: a new dataframe where the beginning date and end date have been converted to a start term and an end term.

Pivot_Custom_Table - Function for creating pivot tables when using 2 to 8 demographic combinations. 
  input: a .csv file containing the dataframe that you wish to convert to a pivot table AND the # of columns that are going to be involved in the pivot.
  output: a pivot table matching the input needs.

CourseSurveySummaryStatistics - Function for calculating some descriptive summary statistics for each individual course during the semester to accompany the end of term student survey results.
  input: 1 dataframe with information for each course offered for the current term, 1 dataframe with information for the students that were enrolled during the current semester, 1 dataframe to serve as a key between the summarized student data and the summarized course data.
  output: a dataframe showing descriptive summary statistics for each course.

Date2TermConverter - Function for converting time/date values to academic terms.
  input: 1 dataframe, the string value of the name of the column with the date/time values you are converting, the string value of the name of the new column you want created to house the academic term.
  output: a new dataframe with a column that has the appropriate academic term.
