### BizCardX-Extract-business-card-with-OCR###

EasyOCR is a Python library designed for Optical Character Recognition (OCR), enabling developers to extract text effortlessly from images and scanned documents. It simplifies the process of text extraction from visual content.
In my project, I've employed EasyOCR to extract text from business cards, facilitating the digitization of contact details and other relevant information.

##Project Overview##
I've developed BizCardX, an intuitive tool tailored for extracting data from business cards using OCR technology. This tool streamlines the process of capturing information from business cards and populating it into a SQL database. The extracted data is made accessible through a user-friendly graphical interface built with Streamlit.
With BizCardX, users can easily upload a business card image, extract its information, view it in an organized format, and optionally store it in a database. Additionally, the stored data can be managed, updated, or deleted as per the user's requirements.


##Libraries/Modules Used##
Pandas: For creating and managing data in a DataFrame format.
mysql.connector: To establish connections with the MySQL database for data storage and retrieval.
Streamlit: For building the graphical user interface (GUI) of the application.
EasyOCR: For extracting text from uploaded business card images.

##Workflow##
To use BizCardX for data extraction, follow these steps:
Library Installation: Install the required libraries using pip.
pip install [library_name]
Run the Application: Execute the BizCardX_main.py script with Streamlit.
streamlit run BizCardX_main.py
User Interface: The application displays a webpage with three main menu options: HOME, UPLOAD & EXTRACT, and MODIFY. Users can upload a business card image to extract its information.
Text Extraction: EasyOCR processes the uploaded image to extract the text.
Data Classification: The extracted text is classified into categories like company name, cardholder name, designation, contact details, and address using custom functions and regular expressions.
Data Presentation: The classified data is presented on the screen for user review and editing.
Database Interaction: Users can choose to upload the extracted data to a MySQL database by clicking the "Upload to Database" button. (Note: Connection details need to be provided for database interaction.)
Data Management: The MODIFY menu allows users to perform Read, Update, and Delete operations on the data stored in the MySQL database.

Feel free to explore BizCardX and streamline your business card data extraction and management process!
