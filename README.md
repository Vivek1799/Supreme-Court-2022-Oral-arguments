# Supreme-Court-2022-Oral-arguments
This project looks at the most cited sections in the U.S Supreme Court Oral arguments in 2022.  

# It answers the following questions: 
A) What were the most quoted sections in 2022?

B) How many times were the most key words - constitutional, due process and equal protection used in 2022?

C) How many times were the words like "argued", "asserted", and "contended" used in legal context?

# How did I do this?
I scraped the Supreme Court Oral arguments transcripts for 2022 using BeautifulSoup and then made a dataframe using pandas with columns - Case, Case name, Date, Docket number.
I then converted the pdf files into text files using tika and made another dataframe that contained all the text.
After this, I joined the two dataframes and performed Regular Expressions to look for the most quoted section. 
You can check my notebook to look for the results. 
