# UFO
# Overview

The goal of this project was to help Dana who is a UFO researcher create a table of various UFO sightings that have occured in US and display it on her website. We are using a javascript to create filters that will keep the users of her website informed of the various dates, locations and shapes of these events.

## Results:
### Default View
  * Any user visiting this webpage will be taken to this beautiful dark and mystifying background with a bold title and a introductory paragraph. 

![page_paragraph](https://user-images.githubusercontent.com/107159218/186801013-47fb98bd-1d21-4f27-822a-045d4239667a.PNG)

  * The introductory paragraph will be followed by a table consisting of 7 columns. Each row of this table describes a event that was reported. The table data is filterable and there are five criteria that can be used to filter the contents of the table. 
  
![page_table_filterelements](https://user-images.githubusercontent.com/107159218/186801603-f09f9c42-197d-4b84-9fd4-e1d989574da7.PNG)

  * A user visiting this page can filter the table content by date or city or state or country or by the shape of the object reported.

![filteredresult](https://user-images.githubusercontent.com/107159218/186801636-74638d50-7b90-435e-82d7-4f23817c820d.PNG)

### Summary 
  * A drawback
    * One drawback of the filter setup is that two filter arguments cannot be simultaneously applied. For example; a user may want to filter based on shape and state. The current script does not have a provision for it.
  
  * Two recommendations for futher development
    * First, some of the filter boxes should be dropdowns. Especially for the shapes cause the text to this box is not very intuitive (there is one record that lists the shape as "changing", that's not a shape). Also, considering that there are only so many number of shapes reported this should not be a difficut application to create.
    * Second, the text in the filter boxes should not be case sensitive. Right now it is and may throw some users off
   

