# Summer Internship at Laurentian University

# WhatsApp Chat Analyzer

The **WhatsApp Chat Analyzer** project is dedicated to providing users with a powerful and sophisticated tool for conducting in-depth analysis of their WhatsApp conversations. In an age defined by extensive communication through messaging platforms, this project offers users valuable insights into their chat data. By employing advanced data analysis techniques and compelling visualizations, this application empowers users to uncover meaningful patterns, sentiment trends, and communication dynamics within their WhatsApp conversations.

## Features

### 1. Data Parsing and Preprocessing

- The project initiates by reading WhatsApp chat data from a specified file using Python's file handling capabilities.
- Utilizing regular expressions (regex), it identifies and extracts relevant components such as timestamps, senders, and messages from each chat line.
- The extracted data is then structured into a Pandas DataFrame, facilitating easy manipulation and analysis.

### 2. Sentiment Analysis and Emoji Analysis

- Sentiment analysis is performed using the TextBlob library, which assigns a sentiment polarity score to each chat message.
- A function categorizes messages as positive, negative, or neutral based on the sentiment score.
- Another function extracts emojis from chat messages using regex, enabling emoji analysis.

### 3. Data Analysis and Visualization

- Various data analysis techniques and visualizations are incorporated to provide insights:
  - A word cloud visually represents frequently used words from the combined messages.
  - Monthly and daily usage charts showcase the volume of messages over time.
  - An activity map illustrates communication intensity by day and hour of the week.

### 4. Participant Analysis

- The application identifies and displays the most active participants based on their message counts.
- Participant counts are computed and presented in a clear format.

### 5. User Interaction and Execution

- The main function orchestrates the entire process by calling necessary functions and executing the analysis.
- Users provide the path to the WhatsApp chat data file, which is then parsed and analyzed.
- Analysis results, including sentiment analysis, emoji usage, visualizations, and participant information, are displayed for the user.

### 6. Technologies and Libraries Used

- The architecture leverages various Python libraries, including Pandas, NumPy, Matplotlib, and TextBlob.
- Regular expressions (regex) are employed for effective data extraction and manipulation.
- The architecture is designed to be executed locally, providing users with the convenience of running the analysis on their own machines.

## Screenshots

![image](https://github.com/Suryadipsinh/Summer-Internship-at-LU/assets/77860201/762028d5-0f30-43ab-9a69-70abba938b2c)
![image](https://github.com/Suryadipsinh/Summer-Internship-at-LU/assets/77860201/8936f585-58bf-49c4-bc6b-c2034010a01f)
![image](https://github.com/Suryadipsinh/Summer-Internship-at-LU/assets/77860201/74b5fd2a-bec3-4eca-8e1e-229f3a9dc933)
![image](https://github.com/Suryadipsinh/Summer-Internship-at-LU/assets/77860201/32b1377b-2774-4e51-b918-4299478968cb)
![image](https://github.com/Suryadipsinh/Summer-Internship-at-LU/assets/77860201/bd465b4b-1c3b-40d1-b23d-7344f6ad1e36)


[Link to the GitHub repository](https://github.com/Suryadipsinh/Summer-Internship-at-LU)

