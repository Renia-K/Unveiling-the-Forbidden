# Unveiling the Forbidden: A Digital Dive into North America's Censored Literature

## Corpus Overview

This repository contains a dataset of 46 books banned in the United States of America from the 19th century to the present, investigating the historical and cultural context surrounding book banning. By analyzing censored works, applying topic modeling for frequently used words, and evolving societal pressures, the project uncovers trends in banning, focusing on themes such as race, sexuality, and social issues. The resulting research offers insights into patterns of suppression and creates a searchable digital archive to preserve these literary works.
The dataset is designed for textual analysis, digital humanities research, educational purposes, and historical inquiry, showcasing the evolution of book banning in North America through themes such as race, sexuality, social issues, and freedom of expression, while uncovering the thematic patterns behind suppressed literary works and serving as a comprehensive resource for investigating the multifaceted history of literary suppression in North America.


## Corpus Description

The dataset includes a carefully curated selection of historically censored books. These works, spanning from the 19th century to 2024, represent diverse themes and genres targeted by banning, such as abolitionist literature, works exploring sexuality, and those addressing race, gender, or social taboos.



**Highlights of the Corpus**: 

`19th Century`: Abolitionist literature like "Uncle Tom’s Cabin" by Harriet Beecher Stowe.

`20th Century`: Books affected by the Comstock Act like "Memoirs of a Woman of Pleasure" by John Cleland and banned works during the Boston censorship era of the 1920s.

`1950-2024`: Works censored for addressing LGBTQIA+ or BIPOC issues, including "The Color Purple" by Alice Walker and Gender Queer by Maia Kobabe.



**Selection Criteria**: 

Books were selected based on their historical significance, documented instances of censorship, and the evolving focus of literary suppression over time. The criteria included:

`Status of Censorship or Ban`: Books were chosen only if they have been officially banned, rather than simply challenged. These are books that faced total prohibition rather than partial alteration.

`Restrictions in Specific Environments`:  The selection focused on books that have been banned on a statewide or nationwide level in the United States of America, rather than those restricted only within certain schools or libraries.

`Accessibility for Extraction`: Books were selected based on their availability in public digital repositories, ensuring they were accessible for research or extraction. Data was sourced from publicly accessible platforms such as Project Gutenberg and other open digital libraries.

Note: The aforementioned criteria were followed when collecting 19th century and early 20th century banned books. Eligibility standards required adjustments when selecting more recent texts: a Federal Law for nationwide bans was no longer in action, and with a recent exponential increase in selected States' book bans and endless possibilities to access information on the Internet, the pool was too wide. Moreover, especially in the 21st century, books can be easily retrieved on online platforms, making bans in local libraries and school curricula the only vehicles for preventing their distribution. 
For these reasons, the second criterion was modified to include books banned in specific counties or school districts. Specifically, volumes censored after 2020 were selected from PEN America's list of banned books in American schools during the 2022-2023 school year. Considered the highest percentages of censorships coming from Florida and Texas, the lists of books banned in the two States were cross referenced, and the resulting overlaps were taken into consideration. The list was further refined based on the availability of the books in open-source online libraries.


Each entry includes:

`Title`: The name of the book.

`Author`: The name of each book's author.

`Filename`: The name of the .txt file connected to the book. 


## Included Books- Data scraped

`Source`: 

Below is a list of banned books organized by the century in which they were banned:

**19th century**: 
1. "Memoirs of a Woman of Pleasure" by John Cleland.
2. "The Sorrows of Young Werther" by Johann Wolfgang von Goethe.
3. "The Age of Reason" by Thomas Paine.
4. "Narrative of the Life of Frederick Douglass" by Frederick Douglass.
5. "Uncle Tom’s Cabin" by Harriet Beecher Stowe.
6. "Leaves of Grass" by	Walt Whitman.
7. "Incidents in the Life of a Slave Girl" by Harriet Jacobs.
8. "The Kama Sutra" - English translation by Sir Richard Francis Burton.
9. "The Canterbury Tales" by Geoffrey Chaucer.
10. "The Adventures of Huckleberry Finn" by	Mark Twain.
11. "The Picture of Dorian Gray" by	Oscar Wilde.
12. "Jude the Obscure" by Thomas Hardy.
13. "On the Origin of Species" by Charles Darwin.
14. "The Decameron" by Giovanni Boccaccio.

**20th century**: 
1. "Alice's Adventures in Wonderland" by Lewis Carroll.
2. "An American Tragedy" by	Theodore Dreiser.
3. "Elmer Gantry" by Sinclair Lewis.
4. "Lady Chatterley's Lover" by D.H Lawrence.
5. "Oil!" by Upton Sinclair.
6. "On the Origin of Species" by Charles Darwin.
7. "The Sun Also Rises" by Ernest Hemingway.
8. "Three Weeks" by Elinor Glyn.
9. "Ulysses" by James Joyce.
10. "Antic Hay" by Aldous Huxley.
11. "Desire Under the Elms" by Eugene O'Neill.
12. "Strange Interlude" by Eugene O'Neill.

**21st century**: 
1. "1984" by George Orwell.
2. "The Catcher in the Rye" by J. D. Salinger.
3. "The Scarlet Letter" by Nathaniel Hawthorne.
4. "To Kill a Mockingbird" by Harper Lee.
5. "The Grapes of Wrath" by	John Steinbeck.
6. "Slaughterhouse Five" by Kurt Vonnegut.
7. "The Great Gatsby" by F. S. Fitzgerald.
8. "The Color Purple" by Alice Walker.
9. "The Canterbury Tales" by Geoffrey Chaucer.
10. "The Da Vinci Code" by Dan Brown.
11. "Philosopher's Stone" Harry Potter series by J. K. Rowling.
12. "The Fellowship of the Ring” The Lord of the Rings by J. R. R. Tolkien.
13. "The Adventures of Captain Underpants" by Dav Pilkey.
14. "Thirteen Reasons Why" by Jay Asher.
15. "The Handmaid’s Tale" by Margaret Atwood.
16. "Call Me by Your Name" by Andre Aciman.
17. "Aristotle and Dante Discover the Secrets of the Universe" by Benjamin Sáenz.
18. "The DUFF: Designated Ugly Fat Friend" by Kody Keplinger.
19. "Throne of Glass" by Sarah J. Maas.
20. "I’ll Give You the Sun" by Jandy Nelson.
21. "Gabi, A Girl in Pieces" by Isabel Quintero.
22. "Eleanor and Park" by Rainbow Rowell.
23. "Gender Queer: A Memoir" by Maia Kobabe.

The corpus was also categorized into six distinct themes, and the books were assigned to their respective themes to facilitate analysis and identify trends or common patterns that may have contributed to bans accordingly. 
These include: 

`Human Desire and Relationships`: 
1. "Memoirs of a Woman of Pleasure" by John Cleland.
2. "The Kama Sutra" - English translation by Sir Richard Francis Burton.
3. "The Decameron" by Giovanni Boccaccio.
4. "Lady Chatterley's Lover" by D.H Lawrence.
5. "Three Weeks" by Elinor Glyn.
6. "Desire Under the Elms" by Eugene O'Neill.
7. "Strange Interlude" by Eugene O'Neill.
8. "The Da Vinci Code" by Dan Brown.
9. "Philosopher's Stone" Harry Potter by J. K. Rowling.
10. "The Adventures of Captain Underpants" by Dav Pilkey.
11. "Call Me By Your Name" by Andre Aciman.
    
`Religion and Morality`: 
1. "The Age of Reason" by Thomas Paine.
2. "The Picture of Dorian Gray" by Oscar Wilde.
3. "Elmer Gantry" by Sinclair Lewis.
4. "The Scarlet Letter" by Nathaniel Hawthorne.
5. "To Kill a Mockingbird" by Harper Lee.
6. "The Handmaid’s Tale" by Margaret Atwood.
7. "Throne of Glass" by Sarah J. Maas.
   
`Slavery, Racism, and Power`: 
1. "Narrative of the Life of Frederick Douglass" by Frederick Douglass.
2. "Uncle Tom’s Cabin" by Harriet Beecher Stowe.
3. "Incidents in the Life of a Slave Girl" by Harriet Jacobs.
4. "The Adventures of Huckleberry Finn" by Mark Twain.
5. "The Grapes of Wrath" by John Steinbeck.
6. "The Color Purple" by Alice Walker.
   
`Nature, Science, and Philosophy`: 
1. "Leaves of Grass" by Walt Whitman.
2. "On the Origin of Species" by Charles Darwin.
3. "Slaughterhouse Five" by Kurt Vonnegut.
   
`Mental Health and Existential Struggles`: 
1. "The Sorrows of Young Werther" by Johann Wolfgang von Goethe.
2. "The Sun Also Rises" by Ernest Hemingway.
3. "Antic Hay" by Aldous Huxley.
4. "The Catcher in the Rye" by J. D. Salinger.
5. "Thirteen Reasons Why" by Jay Asher.

`Identity and Growth`: 
1. "Alice's Adventures in Wonderland" by Lewis Carroll.
2. "Ulysses" by James Joyce.
3. "Aristotle and Dante Discover the Secrets of the Universe by Benjamin Sáenz.
4. "The DUFF: Designated Ugly Fat Friend" by Kody Keplinger.
5. "I’ll Give You the Sun" by Jandy Nelson.
6. "Gabi, A Girl in Pieces" by Isabel Quintero.
7. "Eleanor and Park" by Rainbow Rowell.
8. "Gender Queer: A Memoir" by Maia Kobabe.
   
`Social Critique and Class Dynamics`: 
1. "The Canterbury Tales" by Geoffrey Chaucer.
2.  "Jude the Obscure" by Thomas Hardy.
3.  "An American Tragedy" by Theodore Dreiser.
4.  "Oil!" by Upton Sinclair.
5.  "1984" by George Orwell.
6.  "The Great Gatsby" by F. S. Fitzgerald.
7.  "The Fellowship of the Ring” The Lord of the Rings  by	J. R. R. Tolkien.

## File Formats 

The corpus is available in the following formats:

**Annotated Corpus File (.csv)**: Includes all the scraped data pieces of information, including columns for Title, Author and FileName.

| CSV Column Names   | Description                                     |
|--------------------|-------------------------------------------------| 
| 'Title'            | Title of the book                               |
| 'Author'           | Author's name                                   |
| 'FileName'         | The name of the .txt file connected to the book |

**Processed text file (.txt)**: Raw text processed for the topic modelling.

**Visualization Outputs**: .html for interactive maps, .png or .svg for charts.


## Code and Processing

Below, you will find the analytical steps employed in the Jupyter notebook Banned_Books_USA.ipynb for creating this dataset:

`Data Retrieval`: HTML files containing book texts were downloaded from Project Gutenberg and organized into a specified directory (HTML_BOOK_LIST) for structured data retrieval. Books banned between 1950 and present day (except for "The Scarlet Letter" and "The Great Gatsby") were collected from Internet Archive, whose HTML files were not structured properly to allow extraction by scraping. Consequently, the .txt files were manually retrieved, grouped into a separate directory (NON_SCRAPABLES_TXT) and inserted into the code to be cleaned, added to the rest of the exctracted text files, and processed. 

`Directory Navigation`: For this step, `os` and `glob` libraries were employed to navigate the directory containing the HTML files. These libraries facilitated the retrieval of the books stored in a specific directory (HTML_BOOK_LIST), allowing for seamless access to the data.

`HTML Parsing & Metadata extraction`: `BeautifulSoup`, a Python library for parsing HTML documents, was used to parse the HTML content of each book. It efficiently extracted the preamble, which includes key metadata such as the book’s title and author. Regular expressions (from the `re` library) were applied to match specific HTML patterns to extract this metadata precisely.

`Metadata`: The `pandas` library was used to organize the metadata into a structured DataFrame. The metadata, including titles, authors, and filenames of processed books, was then saved into a well-formatted CSV file (Banned_Books_metadata.csv). For books that could not be scraped, additional metadata was retrieved from a separate non_scrapables.csv file. This data was merged with the main dataset to ensure a comprehensive record of all books, including those with incomplete or missing data.

`File encoding`: Encoding issues during file export were fixed as the final metadata CSV file was saved using UTF-8 encoding with BOM (utf-8-sig). This ensures compatibility across different systems and software.


**Text Preprocessing**: Several Python libraries were used to efficiently process and clean the HTML format corpus of books downloaded from Project Gutenberg and the Internet archive.

   *Tokenization*: Using the `SpaCy` library the cleaned text was processed for tokenization. `SpaCy` efficiently divided the content into individual words, preparing it for advanced analysis and ensuring that the text could be easily processed at the token level.
   
   *Cleaning & Preprocessing*: The `string` module was utilized to remove unwanted characters and normalize whitespace. This process cleaned the main text, ensuring it remained consistent and readable. All text was converted to lowercase to ensure uniformity and a list of stopwords (using the `nltk.corpus.stopwords library`) was removed from the text to eliminate common but insignificant words, to improve the quality of the dataset, ensuring accurate results in the analysis. Also using `string.punctuation` and `isalpha()`, punctuation marks and non-alphabetical characters were stripped from the content, to focus on the meaningful words.
   

`Output Generation`: The processed text [cleaned text files] for each book was saved as .txt files in the designated output directory (FINAL_TXT). This organized structure ensures easy access to the cleaned data for analysis. 

`Saving preproccessed text`: The cleaned and processed texts were stored in a dictionary (preprocessed_texts), where the keys are filenames and the values are the corresponding cleaned texts.
The processed text was then saved into .txt files within the FINAL_TXT directory, ensuring the data was ready for analysis. 


## Analysis Tools

**Topic Modeling**: 

   -'Zeta Analysis': Zeta analysis, using R software, is used to explore and identify key themes and topics across censored works, focusing on contrasts and thematic shifts over time, by analyzing preferred, avoided or common words between the centuries.
    
   -'Voyant Tool': This tool is employed for interactive topic modeling, allowing the identification of recurring themes, word frequencies, and trends within the texts through various visualizations, like  word clouds and term frequency graphs.
    
**Geospatial Visualization**: 
GIS tools [`ArcGIS` software`] are used to map the geographic distribution of banning, enabling users to explore regional patterns and historical shifts in censorship practices.

## Working with ArcGIS: Data Collection and Map Creation

This section outlines the process of working with ArcGIS and the steps followed: 

**Data Collection & CSV file creation**: 
Using the metadata from the Jupyter Notebook along with the State of the book banned, the theme of book and the reason for banning, spatial data were also collected using https://www.latlong.net/ including geographic coordinates (latitude and longitude) required for the map. 

**Structuring the CSV**: 
The data is organized in a tabular structure with columns representing attributes and geographic coordinates. 

| CSV Column Names   | Description                                                         |
|--------------------|---------------------------------------------------------------------| 
| 'State'            | The state each book was banned                                      |
| 'Title'            | Title of the book                                                   |
| 'Author'           | Author's name                                                       |
| 'Year_Banned"      | The Year/-s each book was banned                                    |
| 'Theme'            | The Theme of each book based on the division we clarified previously|
| 'Reason'           | The official reason lead to banning                                 |
| 'Latitude'         | The Latitude of each state                                          |
| 'Longitude'        | The Longitude of each state                                         |

**Importing and Preparing Data in ArcGIS**: 
1. The CSV file was first added to the map project using the Add Data option in ArcGIS Pro. This made the data available for further visualization. 
2. The latitude and longitude fields are used to generate a point layer. The XY Table To Point tool is used to define the spatial representation of the data, with the appropriate columns assigned to X (Longitude) and Y (Latitude).
3. A coordinate system, such as WGS 1984, is applied to ensure the data aligns with other spatial layers.
4. 


## Interactive Data Exploration Exercises

For this project, a series of exercises have been created to promote researcher engagement with the dataset and enhance their understanding of the underlying data. These exercises provide practical opportunities for exploring, analyzing, and visualizing the dataset generated as part of this research. By incorporating tools such as word frequency analysis, sentiment analysis, word cloud generation, and bigram analysis, the exercises not only make the dataset more accessible but also facilitate deeper insights into its content, providing material for further analysis.


**Setup Requirements**  

1. **Setup Before Starting the Exercise**  
Before starting this exercise, ensure you have completed the previous Jupyter Notebook provided. The outputs from that notebook, specifically the following files:  
     - `Banned_Books_Metadata.csv`  
     - `FINAL_TEXT.txt`  
Save these files in a dedicated folder on your computer. This folder will serve as the **working directory** for this exercise.  

2. **Stopwords File**
Download the `stopwords.txt` file provided. Place this file in the same directory as the exercise. Ensure the file path is correctly referenced in the code to avoid errors.  

3. **Provided Code**  
All the code required to complete the exercise is already included in the provided Jupyter Notebook. You simply need to follow the instructions, execute the code, and analyze the results. No additional coding is required unless you choose to expand or modify the exercise.


**Exercise 1: Text Preprocessing and Word Frequency Analysis**

`Purpose`: This exercise aims to provide hands-on experience in processing textual data and extracting meaningful insights. Through this activity, you will:

1. Preprocess textual data by removing unnecessary components such as stopwords and punctuation.
2. Analyze the frequency of words within a selected book's text to uncover its main themes.
3. Visualize the most frequently occurring words using a bar chart for easier interpretation.


`Features of the Exercise`: 
1. Text Preprocessing:
   Removes common, insignificant words, provided in the file stopwords. 
   Text Cleaning: Strips punctuation, converts text to lowercase, and filters out non-alphabetic words.
   Tokenization: Splits the text into individual words for analysis.
2. Word Frequency Analysis
   Counts the occurrence of each word in the processed text.
   Identifies the top 10 most frequently used words, which can reveal important themes or ideas.
3. Visualization
   Generates a bar chart displaying the top 10 words and their respective frequencies.


`Instructions`: 
1. Select a Book
   Browse the metadata CSV file (Banned_Books_Metadata.csv) to choose a book.
   Metadata includes details such as title, author, and file name for easy reference.
2. Preprocess the Text
   Load the book's text file from the specified directory, using the output text files from the Jupyter Notebook (FINAL_TXT). 
   Clean the text by removing punctuation, converting it to lowercase, and filtering out stopwords.
3. Analyze Word Frequencies
   Compute the frequency of each word in the text.
   Extract the top 10 most frequent words.
4. Visualize the Results
   Create a bar chart using matplotlib to display the top words and their frequencies.
   Interpret the chart to identify potential themes in the book.

`Expected Output`: 

Upon completion, you should obtain:

A bar chart displaying the top 10 most common words in the selected book.
Insights into the main themes or topics based on the frequent words.


**Exercise 2: Sentiment Analysis, WordCloud, and Bigram Analysis**

`Purpose`: This exercise enhances your understanding of text preprocessing and data visualization by focusing on three key areas:

1. Word Cloud Visualization – Highlight the key themes in the text.
2. Bigram Analysis – Provide contextual insights by analyzing the most common word pairs.
3. Basic Sentiment Analysis – Offer an emotional overview of the text.


`Features of the Exercise`: 

1. Word Cloud Visualization:
   Generate an artistic representation of the text's most frequent words using the wordcloud library.
   Customize the appearance of the word cloud for better visual appeal.
3. Bigram Analysis:
   Identify the most common two-word combinations (bigrams) using the nltk library.
   Visualize the top 5 bigrams in a bar chart.
3. Basic Sentiment Analysis:
   Measure the emotional tone (positive, negative, or neutral) of the text using the textblob library.

`Instructions`: 
1. Choose a Book
   Load the Banned_Books_Metadata.csv file.
   Search for a book by title or author and select one from the matching results.
2. Preprocess Text:
   Load the corresponding text file (FINAL_TEXT.txt).
   Preprocess the text by removing punctuation, converting text to lowercase, and eliminating stopwords.
3. Generate a Word Cloud:
   Create a visual representation of the text's most frequent words.
4. Perform Bigram Analysis:
   Identify and visualize the top 5 bigrams in the text using a bar chart.
5. Conduct Sentiment Analysis:
   Measure the emotional tone of the text and classify it as positive, negative, or neutral.

`Expected Output`: 
1. Word Cloud:
   A visually appealing image displaying the most common words in the text.
2. Bigram Analysis:
   A bar chart showing the top 5 most frequent word pairs (bigrams).
3. Sentiment Analysis:
   Polarity score ranging from -1.0 (negative) to +1.0 (positive).
   An interpretation of the overall emotional tone: Positive, Negative, or Neutral.














## Outcomes 

The project will produce:

  1. A *digital archive* of banned books with a searchable interface for easy access.

  2. *Analytical insights* on banning trends and their emotional or thematic triggers.
     
  3. *Visualizations* such as interactive maps to explore banning patterns over time.


## Terms and Conditions


## Creators
This dataset was created and curated by Theodora-Stavroula Korma, Olga Rojas Valle and Letizia Maria Marietti on behalf of the course Collecting Data, for the MA Digital Humanities. 

**Contact Information**:
email: t.s.korma@student.rug.nl, 
email: o.rojas.valle@student.rug.nl,
email: l.m.marietti@student.rug.nl


## Usage
This dataset is provided for educational purposes, intended to support the final individual assignment for the course **Collecting Data**, of 1b semester of MA Digital Humanities. 
