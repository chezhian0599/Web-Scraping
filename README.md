# Web-Scrapping

## **Agenda:**
To Scrap data from a set of websites and to do text analysis on the scrapped data.

## **Tools used:**
- Programming Language - Python
- Text editor - Visual Studio Code

## **Libraries Used:**
- Pandas
- Selenium (from selenium I have imported the webdriver)
- Beautifulsoup
- os

## **Procedures:**

- It starts by importing the necessary libraries.

- The CSV file is read into a pandas dataframe using the **pd.read_csv() function**.

- Then, it uses the **selenium** library to open a web browser (Chrome) and create a **webdriver object** that is used to navigate the pages of the URLs.

- Next, a for loop is used to iterate over the rows of the dataframe.

- For each row, the code grabs the URL and an ID from the dataframe and navigates to that URL using the webdriver.

- After that, the code use the **BeautifulSoup** Library to parse the html source of the page, then it tries to find the elements with the 
class **'entry-title'** and **'td-post-content'**, they are the title of the page and the body of the page respectively, and the try block will print the title and the body.

- It then opens a file with the name of the URL's ID and appends the title and the body of the page to it, also it adds new lines to separate the title and the body.

- Finally, when the loop completes, the driver quit the browser.

- If anything goes wrong with the page the except block will run and print the error message **'Page Error'**


## **Text Analysis:**

- I have done  **[Text Analysis](https://github.com/chezhian0599/Text-Analysis)** on the data scrapped in this project. Kindly Check it.





