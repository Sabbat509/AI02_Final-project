#### Project Title
NCCU ICI Chatbot Assistant
#### Project Description
The AI Assistant for ICI Students is an advanced tool designed to assist students at the International College of Innovation (ICI) by answering questions about courses. This AI Assistant provides personalized guidance tailored to each student's academic preferences, career aspirations, and specific questions about available courses.

#### Key Features:
-Intelligent Responses: The chatbot understands natural language and provides relevant answers from both the PDF and Excel documents.
-Dual Data Sources: Leverages both detailed course descriptions (PDF) and structured data like schedules and professors (Excel).
-Contextual Understanding: Uses the gpt-4 model for advanced language processing and understanding.

#### How It Works:
1. Load & Process: The PDF and Excel files are loaded and broken down into smaller chunks for easier analysis.
2. Embed & Store: The text chunks are converted into numerical representations (embeddings) and stored in a vector database (Chroma) for efficient retrieval.
3. Understand & Respond: When you ask a question, the chatbot:
   -Finds the most relevant chunks of information in the database.
   -Uses the gpt-4 model to generate a clear and concise answer based on the retrieved information.

#### Getting Started
To begin using the AI Assistant for ICI Students:

- Run the code.
- Input your questions regarding ICI courses.
- Submit your input to receive the results.
- The output will include9(based on the question asked):
1. Course Lists for Each Year
2. Course Schedule
3. Professor Information
4. Course Descriptions

#### File Structure
1. AI02.ipynb;  our project coding file
2. ICI Data Collection.xlsx; the excel file contains the labeled dataset for generating the output
3. ICI Description.pdf; the pdf file contains the description of all the courses taught in ICI
4. README.md; information about our project

#### Analysis
Our AI Assistant for ICI students utilizes advanced AI models to provide personalized course recommendations, career path guidance, and academic goal planning. The analysis of our AI Assistant involved several key steps:

1. Data Collection and Preprocessing:

- We collected comprehensive data on available courses, including course titles, descriptions, credits, and schedules.
This data was meticulously organized and preprocessed to ensure suitability for the AI models.

Technology:
-The project uses OpenAI's gpt-4 model, LangChain for orchestrating the workflow, Chroma for vector storage, and Gradio for the user interface.

### Results

-Functionality: The chatbot successfully answers most questions about courses, including descriptions, schedules, and professors.
-Accuracy: The accuracy is generally good, but there are occasional inconsistencies. For example, the chatbot might miss information about classes on certain days, even though it can accurately identify professors who teach on those days.
-Speed: The response time can sometimes be slow, especially for more complex queries.

#### Conclusions:

The AI Assistant significantly enhances the course inquiry process for ICI students by providing personalized recommendations and career guidance. This leads to better academic outcomes and higher user satisfaction.

#### Recommendations:

The inconsistencies in accuracy likely stem from how the data is structured and retrieved. Potential solutions include:

Data Preprocessing: Ensure that the Excel data is consistently formatted and that information about schedules and professors is linked correctly.
Retrieval Optimization: Fine-tune the parameters of the vector database and retrieval process to improve the accuracy of finding relevant information.
Model Fine-tuning: Provide more training examples to the gpt-4 model to help it better understand the nuances of the course data and respond more accurately.

To improve conversational memory and speed:

Memory Enhancement: Explore using more sophisticated memory mechanisms within LangChain, such as storing past responses and relevant context.
Performance Optimization: Investigate ways to speed up the embedding and retrieval processes, potentially by using different vector databases or optimizing the code.

Overall, the AI Assistant provides a robust foundation for personalized academic planning and career guidance at the International College of Innovation. Its ability to deliver efficient and accurate recommendations supports students in achieving their academic and professional goals, making it a valuable addition to the educational tools available at ICI.


#### Contributors
1. Natthanicha 111ZU1027
2. Neri 111ZU1035
3. Chanyada 111ZU1028
4. Panisara 111ZU1053

### Acknowledgments

We would like to express our sincere gratitude to the following individuals and organizations for their invaluable support and guidance throughout the development of our AI Study Planner project:

1. Our Professors 
   - Pien Chung-pei: For insightful guidance, encouragement, and expertise, which have been instrumental in shaping the direction and execution of this project.

2. International College of Innovation (ICI)
   - For providing us with the resources, academic environment, and the opportunity to undertake this project. Special thanks to the administrative staff for their assistance with data collection and logistical support.

3. Family and Friend
   - For their unwavering support, patience, and encouragement throughout the duration of our project. Their belief in us has been a source of motivation and strength.

Thank you all for your contributions and support, without which this project would not have been possible.

### References
- Course information
https://ici.nccu.edu.tw/course/






