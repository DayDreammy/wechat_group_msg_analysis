# Group Chat Records Analysis

This Python script is designed for the analysis of group chat records, generating corresponding data visualizations and word cloud images. Below are the main features and usage instructions of the script.

## Features

1. **Data Reading and Cleaning:** Reads group chat records from a text file and performs data cleaning and processing.
2. **Data Preprocessing:** Converts timestamps to standard datetime format and adds related time features such as year, month, date, weekday, and hour.
3. **Metadata Analysis:** Calculates the number of participants, start and end dates, total days, total number of messages, and total number of words in the group chat.
4. **Individual Contributions:** Counts the number of messages and words for each participant and generates corresponding bar charts.
5. **Time Distribution Analysis:** Analyzes the distribution of messages throughout the day for each participant and creates corresponding bar charts.
6. **Date Distribution Analysis:** Examines the distribution of messages on different dates for each participant and generates corresponding bar charts.
7. **Weekday Distribution Analysis:** Studies the distribution of messages on different weekdays for each participant and creates corresponding bar charts.
8. **Month Distribution Analysis:** Investigates the distribution of messages in different months for each participant and generates corresponding bar charts.
9. **Group Chat Word Cloud:** Creates a word cloud for the entire group chat.
10. **Individual Word Clouds:** Generates word clouds for each participant.

## Usage

1. **Prepare Data:** Decrypt and export chat records in HTML format using the [WeChatMsg](https://github.com/LC044/WeChatMsg) tool.

2. **Prepare Data Manually:** Manually process HTML files (future optimization will be implemented), and save group chat records as a text file (e.g., `test.txt`).

3. **Set Stopwords:** Modify the stopwords list in the code according to your needs.

4. **Run the Script:** Execute the script in the terminal or command line. Ensure that the required Python libraries such as `jieba`, `pandas`, `matplotlib`, `wordcloud`, etc., are installed.

   ```
   bashCopy code
   python script_name.py
   ```

5. **Review Results:** Upon completion, a Word document (`Group_Chat_Analysis.docx`) will be generated, containing various analysis results, charts, and word cloud images.

Each functional module in the script can be adjusted and expanded based on specific requirements. Make sure to have the necessary Python libraries installed when using the script.