# Unveiling the Forbidden: A Digital Dive into North America's Censored Literature

## Corpus Overview

This repository contains a dataset of 46 books banned in United States of America from the 19th century to the present, investigating the historical and cultural context surrounding book banning. By analyzing censored works, applying topic modeling for frequently used words, and evolving societal pressures, the project uncovers trends in banning, focusing on themes such as race, sexuality, and social issues. The resulting research offers insights into patterns of suppression and creates a searchable digital archive to preserve these literary works.
The dataset is designed for textual analysis, digital humanities research, educational purposes, and historical inquiry, showcasing the evolution of book banning in North America through themes such as race, sexuality, social issues, and freedom of expression, while uncovering the thematic patterns behind suppressed literary works and serving as a comprehensive resource for investigating the multifaceted history of literary suppression in North America.

## Corpus Description

The dataset includes a carefully curated selection of historically censored books. These works, spanning from the 19th century to 2024, represent diverse themes and genres targeted by banning, such as abolitionist literature, works exploring sexuality, and those addressing race, gender, or social taboos.

**Highlights of the Corpus**: 

`19th Century`: Abolitionist literature like "Uncle Tom’s Cabin" by Harriet Beecher Stowe.
`20th Century`: Books affected by the Comstock Act like "Memoirs of a Woman of Pleasure" by John Cleland and banned works during the Boston censorship era of the 1920s.
`1950-2024`: Works censored for addressing LGBTQIA+ or BIPOC issues, including "The Color Purple" by Alice Walker and Gender Queer by Maia Kobabe.



**Selection Criteria**: 

Books were selected based on their historical significance, documented instances of censorship, and the evolving focus of literary suppression over time. The criteria included:

`Status of Censorship or Ban`: Books were chosen only if they have been officially banned, rather than simply censored. These are books that faced total prohibition rather than partial alteration.

`Restrictions in Specific Environments`:  The selection focused on books that have been banned on a statewide or nationwide level in United States of America, rather than those restricted only within certain schools or libraries.

`Accessibility for Extraction`: Books were selected based on their availability in public digital repositories, ensuring they were accessible for research or extraction. Data was sourced from publicly accessible platforms such as Project Gutenberg and other open digital libraries.



Each entry includes:

`Title`: The name of the book.

`Author`: The name of each book's author.

`Filename`: The name of the .txt file connected to the book. 

## Included Books- Data scraped

`Source`: 

Below is a list of banned books organized by the century in which they were banned:

**19th century**: Memoirs of a Woman of Pleasure by John Cleland // The Sorrows of Young Werther by	Johann Wolfgang von Goethe // The Age of Reason by Thomas Paine // Narrative of the Life of Frederick Douglass by Frederick Douglass // Uncle Tom’s Cabin by	Harriet Beecher Stowe // Leaves of Grass by	Walt Whitman // Incidents in the Life of a Slave Girl by Harriet Jacobs // The Kama Sutra - English translation by Sir Richard Francis Burton // The Canterbury Tales by	Geoffrey Chaucer // The Adventures of Huckleberry Finn by	Mark Twain // The Picture of Dorian Gray by	Oscar Wilde // Jude the Obscure by Thomas Hardy // On the Origin of Species by Charles Darwin // The Decameron by	Giovanni Boccaccio

**20th century**: Alice's Adventures in Wonderland by Lewis Carroll // An American Tragedy by	Theodore Dreiser // Elmer Gantry by	Sinclair Lewis // Lady Chatterley's Lover by D.H Lawrence // Oil! by Upton Sinclair // On the Origin of Species by	Charles Darwin // The Sun Also Rises by	Ernest Hemingway // Three Weeks by Elinor Glyn // Ulysses by James Joyce // Antic Hay by Aldous Huxley // Desire Under the Elms by	Eugene O'Neill // Strange Interlude by Eugene O'Neill

**21st century**: 1984 by George Orwell // The Catcher in the Rye by J. D. Salinger // The Scarlet Letter by Nathaniel Hawthorne // To Kill a Mockingbird by Harper Lee // The Grapes of Wrath by	John Steinbeck // Slaughterhouse Five by Kurt Vonnegut // The Great Gatsby by	F. S. Fitzgerald // The Color Purple by	Alice Walker // The Canterbury Tales by	Geoffrey Chaucer // The Da Vinci Code by Dan Brown // Harry Potter series (book 1 available) by J. K. Rowling // The Lord of the Rings ("The fellowship of the ring” available) by	J. R. R. Tolkien // The Adventures of Captain Underpants by	Dav Pilkey // Thirteen Reasons Why by	Jay Asher // The Handmaid’s Tale by	Margaret Atwood // Call Me by Your Name by Andre Aciman // Aristotle and Dante Discover the Secrets of the Universe by Benjamin Sáenz // The DUFF: Designated Ugly Fat Friend by	Kody Keplinger // Throne of glass by Sarah J. Maas // I’ll Give You the Sun by Jandy Nelson // Gabi, A Girl in Pieces by Isabel Quintero // Eleanor and Park by	Rainbow Rowell // Gender Queer: A Memoir by	Maia Kobabe

## File Formats 

The corpus is available in the following formats:

**Annotated Corpus File (.csv)**: Includes all the scraped data informations, including columns for Title, Author and FileName.

| CSV Column Names   | Description                                     |
|--------------------|-------------------------------------------------| 
| 'Title'            | Title of the book                               |
| 'Author'           | Author's name                                   |
| 'FileName'         | The name of the .txt file connected to the book |

**Processed text file (.txt)**: Raw text processed for the topic modelling.

**Visualization Outputs**: .html for interactive maps, .png or .svg for charts.

## Code and Processing
Below, you will find the analytical steps employed in the Jupyter notebook Banned_Books_USA.ipynb for creating this dataset:

`Data Retrieval`: HTML files containing book texts were downloaded from Project Gutenberg and organized into a specified directory (HTML_BOOK_LIST) for structured data retrieval.

`Directory Navigation`: For this step, `os` and `glob` libraries were employed to navigate the directory containing the HTML files. These libraries facilitated the retrieval of the books stored in a specific directory (HTML_BOOK_LIST), allowing for seamless access to the data.

`HTML Parsing & Metadata extraction`: `BeautifulSoup`, a Python library for parsing HTML documents, was used to parse the HTML content of each book. It efficiently extracted the preamble, which includes key metadata such as the book’s title and author. Regular expressions (from the `re` library) were applied to match specific patterns in the HTML to precisely extract this metadata.

`Metadata`: The `pandas` library was used to organize the metadata into a structured DataFrame. The metadata, including titles, authors, and filenames of processed books, was then saved into a well-formatted CSV file (Banned_Books_metadata.csv). For books that could not be scraped, additional metadata was retrieved from a separate non_scrapables.csv file. This data was merged with the main dataset to ensure a comprehensive record of all books, including those with incomplete or missing data.

`File encoding`: Encoding issues during file export were fixed as the final metadata CSV file was saved using UTF-8 encoding with BOM (utf-8-sig). This ensures compatibility across different systems and software.

**Text Preprocessing**: Several Python libraries were used to efficiently process and clean the HTML format corpus of books downloaded from Project Gutenberg and Internet archive.

  >Tokenization: Using the `SpaCy` library the cleaned text was processed for tokenization. `SpaCy` efficiently divided the content into individual words, preparing it for advanced analysis and ensuring that the text could be easily processed at the token level.
   
  Cleaning & Preprocessing: The `string` module was utilized to remove unwanted characters and normalize whitespace. This process cleaned the main text, ensuring it remained consistent and readable. All text was converted to lowercase to ensure uniformity and a list of stopwords (using the `nltk.corpus.stopwords library`) was removed from the text to eliminate common but insignificant words, so that to imrpove the quality of the dataset, ensuring accurate results in the analysis. Also using `string.punctuation` and `isalpha()`, punctuation marks and non-alphabetical characters were stripped from the content, to focus on the meaningful words. 

`Output Generation`: The processed text [cleaned text files] for each book was saved as .txt files in the designated output directory (FINAL_TXT). This organized structure ensures easy access to the cleaned data for analysis. 

`Saving preproccessed text`: The cleaned and processed texts were stored in a dictionary (preprocessed_texts), where the keys are filenames and the values are the corresponding cleaned texts.
The processed text was then saved into .txt files within the FINAL_TXT directory, ensuring the data is ready for analysis. 

## Analytical Tools

**Topic Modeling**: 
    `Zeta Analysis`: Zeta analysis, using R software, is used to explore and identify key themes and topics across censored works, focusing on contrasts and thematic shifts over time, by analyzing preferred, avoided or common words between the centuries.
    `Voyant Tool`: This tool is employed for interactive topic modeling, allowing the identification of recurring themes, word frequencies, and trends within the texts through various visualizations, like  word clouds and term frequency graphs.
**Geospatial Visualization**: GIS tools [`ArcGIS` software`] are used to map the geographic distribution of banning, enabling users to explore regional patterns and historical shifts in censorship practices.















## Outcomes 

The project will produce:

  1. A *digital archive* of banned books with a searchable interface for easy access.
  2. *Analytical insights* on banning trends and their emotional or thematic triggers.
  3. *Visualizations* such as interactive maps to explore banning patterns over time.


## Terms and Conditions



## Creators
This dataset was created and curated by Theodora-Stavroula Korma, Olga Rojas- Valle and Letizia- Maria Marietti on behalf of the course Collecting Data, for the MA Digital Humanities. 

**Contact Information**:
email: t.s.korma@student.rug.nl, 

## Usage
This dataset is provided for educational purposes, intended to support the final individual assignment for the course **Collecting Data**, of 1b semester of MA Digital Humanities. 
