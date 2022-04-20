# NYC-Citi-Bike-Usage-Analysis
Tableau dashboard visualization of Citi Bike usage in New York City from April 2021-March 2022.

The Tableau viz can be accessed through this link: https://public.tableau.com/views/CitiBikesVisualization_16503918973590/BikeRides2021-2022?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link 

Bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

The following variables are included in the dataset:

*    Ride ID
*    Rideable type
*    Started at
*    Ended at
*    Start station name
*    Start station ID
*    End station name
*    End station ID
*    Start latitude
*    Start longitude
*    End latitude
*    End Longitude
*    Member or casual ride

The following phenomena were explored, and an analysis included. 

*   How many rides did member riders and casual riders take during this time period? How did usage change over the months?

    Members rode, approximately, between 16,000-54,000 times throughout the past year. Casual riders rode, approximately, between 6,500-42,000 times throughout the past year. The months of August, September, and October of 2021 saw the highest peaks in rides, with over 85,000 rides taken by member riders and casual riders. Considering the weather in New York City during these months, these trends are not surprising.  

*   What are the peak ride times during summer and winter months? How do these vary for members and casual riders?

    During the summer months (June, July, August, and September), members had the following peak times: between 7:00 am - 9:00 am with 10,000-12,000 rides and between 4:00 pm - 7:00 pm with 16,000-19,000 rides. These times correspond with the morning and afternoon rush hours, which makes sense for people commuting to work. There is another slight peak around 12:00 pm, which corresponds to the lunch hour.

    Casual riders had a similar peak ride time in the afternoon between 4:00 pm - 6:00 pm with over 14,000 rides. Casual riders gradually increased their rides at 8:00 am before dropping off after 6:00 pm, which is a similar trend observed by member riders.

    During the winter months (November, December, January, and February), members had similar peak times, but with noticeably fewer riders. The peak morning hours had between 6,000-8,000 member riders, and the peak afternoon hours had between 10,000-12,000 member riders. 
    
    Casual riders did not appear to have a morning peak, but gradually increased their rides starting at 8:00 am before peaking to around 4,300 rides at 5:00 pm before rapidly dropping. Considering the climate in New York City, this is not a surprising trend.

*   What are the most popular start and end destination stations? What are the least popular start and end destination stations?

    The most popular start and end destination stations were defined at having over 15,000 rides recorded and are marked in teal (blue-green). The most popular start and end destination stations include: Grove St PATH, Hoboken Terminal- Hudson St & Hudson Pl, Hoboken Terminal- River St & Hudson Pl, 11th & Washington St, Columbus Drive at Exchange Pl, and South Waterfront Walkway- Sinatra & 1st. Bikes at these stations will likely need the most service, and these stations should be well-maintained considering the observed traffic.

    The least popular start and end stations were defined as having less than 7,000 rides recorded. Stations that did not have any rides recorded were excluded. The bikes and facilities at these stations will likely require less attention, but it is still prudent to keep a regular maintenance schedule so those stations and bikes are not neglected.

*   Where are the stations located on the official City map? How does station popularity change over time?

    The most popular stations are marked with larger, dark blue circles and less popular stations are marked with smaller, light blue circles. There is some variability in station popularity over time (as evidenced by the month filters). It is important to note that higher income areas of New York have the most popular bike stations, and more bike stations overall. Lower-income boroughs do not have as many bike stations and have less popular bike stations, with the exception of Sip Ave. 

*   What are the differences in rideable (classic, docked, electric) use over time?

    Overall, classic bikes are the most frequently used bikes, with a dip in use observed between November and January. Docked bikes have the highest usage between the months of April and June, but are hardly used for the rest of the year. Electric bikes are used between June-March, with no usage noted in April and May. 

*   What are the peak times for the rideables during the summer and winter months?

    Similar to the overall noted trend, there are significantly higher use of rideables in the summer months compared to the winter months. Docked bikes were hardly used during the winter months, but were used more during the summer months. Classic bikes had a fairly consistent trend of peak usage times during the morning and afternoon rush hours for both summer and winter. Electric bikes had a similar trend in the summer month, but a relatively constant rate of usage during the winter months.

*   What are the member riders' and casual riders' usage rates for rideable type?

    Overall, both types of riders used classic bikes the most. Proportionally more casual riders used electric bikes compared to member riders. These numbers are likely reflective of the available inventory of bikes, but are intersting to note for future inventory maintenance.






