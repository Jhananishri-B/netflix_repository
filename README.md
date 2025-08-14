*This project uses the Netflix Titles dataset, which contains detailed information about movies 
    and TV shows available on Netflix as of the data collection date. The dataset, stored in
    netflix_titles.csv, consists of 8,807 entries, each describing a title’s metadata. The columns 
    include show_id (unique identifier), type (movie or TV show), title (name of the content), director
    (film director), cast (main actors), country (origin), date_added (when it was added to Netflix), 
    release_year (original release year), rating (maturity rating), duration (length or seasons), 
    listed_in (genres or categories), and description (short summary)
*For processing the data, missing values in the country and listed_in columns were replaced with 
   “Unknown” to ensure consistency. The str.get_dummies() function was used to handle cases where a
    single title belongs to multiple countries or genres, enabling accurate counting. Counts of 
    countries, genres, and release years were calculated using Pandas aggregation methods, and the 
    results were sorted to identify top contributors and trends.
*This dataset opens up multiple opportunities for deeper analysis, including time-series studies on
     how Netflix’s content library has evolved, regional trends in content production, and even the
     potential development of a recommendation system based on genre and country patterns.
