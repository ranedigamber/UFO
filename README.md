# UFO
# Overview of Election Audit

The goal of this project was to help Dana who is a UFO researcher create a table of various UFO sightings that have occured in US and display it on her website. We are using a javascript to create filters that will keep the users of her website informed of the various dates, locations and shapes of these events.

## Results:
### Default View
  * Any user visiting this webpage will be taken to this beautiful dark and mystifying background with a bold title and a introductory paragraph. 

![page_paragraph](https://user-images.githubusercontent.com/107159218/186801013-47fb98bd-1d21-4f27-822a-045d4239667a.PNG)

  * The introductory paragraph will be followed by a table consisting of 7 columns. Each row of this table describes a event that was reported. The table data is filterable and there are five criteria that can be used to filter the contents of the table. 
  
![page_table_filterelements](https://user-images.githubusercontent.com/107159218/186801603-f09f9c42-197d-4b84-9fd4-e1d989574da7.PNG)

  * A user visiting this page can filter the table content by date or city or state or country or by the shape of the object reported.

![filteredresult](https://user-images.githubusercontent.com/107159218/186801636-74638d50-7b90-435e-82d7-4f23817c820d.PNG)

### Summary of number of votes and the percentage of total votes for each county in the precinct
  * The result of the number of votes cast and percentage of total votes are as follows:
    * Denver county: 82.8% (306,055)
    * Jefferson county: 10.5% (38,855)
    * Arapahoe county: 6.7% (24,801)

### County with largest number of votes
  * **Denver county** had the largest voter turnout

### Summary of number of votes and the percentage of total votes for each candidates overall
  * The following is the tabulated result for total votes and percentage of the total for the three candidates:
    * **Diana DeGette: 73.8% (272,892)**
    * Charles Casper Stockham: 23.0% (85,213)
    * Raymon Anthony Doane: 3.1% (11,606) 

### Election outcome
  * The winner for this election was:
    * ***Diana DeGette*** who received **272,892** votes which was **73.8%** of the total votes casted.
 
### Various features of the code
  * How to get candidate vote count
 
 ![Code Candidate vote count](https://user-images.githubusercontent.com/107159218/176787617-18729b4d-f7fc-45b2-b9c1-f8c46c1c9dea.JPG)

  * How to get county vote count
 
 ![Code_countyvote count](https://user-images.githubusercontent.com/107159218/176787653-9dc5d13d-2cc9-4b7e-ad4d-94774a4a4e1e.JPG)

  * How to get candidate votes percentage
 
 ![Code_Candidate votes and their percentage](https://user-images.githubusercontent.com/107159218/176787717-54dc6077-5213-42a3-b38d-d2ef5ffb072c.JPG)

  * How to get county vote percentage
 
![Code_percentage of county votes](https://user-images.githubusercontent.com/107159218/176787780-d7fbdc41-35c7-4745-b9b6-1f68e7e2f016.JPG)

  * How to get total votes casted
  
 ![Code_total vote count](https://user-images.githubusercontent.com/107159218/176787828-ebb1f835-095e-4e80-9e57-3bc9e8898b37.JPG)

 
### Election Audit Summary
  * The script could be modifed for a national level elections, for example in this audit we declared a dictionary with *key=county* and *value=votes*. In a similar fashion we could use a dictionary of list with *key=states* and *values=[list of counties]*
  * We could also use modify the script to iterate over results from past years or they type of ballots cast (mail i
