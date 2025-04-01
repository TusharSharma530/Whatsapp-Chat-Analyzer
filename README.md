# WhatsApp Chat Analyzer🔢📊

### **LIVE LINK:** https://whatsapp-chat-analyzer-u9t581i3ch.streamlit.app/

_Note: Please copy the app URL and paste it in a new tab for smooth functioning of the app._

This project offers a comprehensive toolkit for analyzing WhatsApp chat exports, using Python to process chat logs and deliver insightful statistics and visualizations. Key features include an overview of top chat statistics, identification of the most active users, analysis of monthly and daily messaging trends, peak day and month insights, word clouds, a weekly activity heatmap, emoji usage and sentiment analysis. Designed for exploring communication patterns, this tool enables in-depth insights for both individual and group WhatsApp conversations.

_Note: Please download the WhatsApp chat export without media for optimal results._

## Features

### 📅 First & Last Message Dates

![image]https://whatsapp-chat-analyzer-u9t581i3ch.streamlit.app/
This section displays the date of the first and last messages in the selected chat, giving insight into the duration of the conversation history.

### 👀 Top Statistics

![image](https://whatsapp-chat-analyzer-u9t581i3ch.streamlit.app/)
This section highlights the core statistics of the chat, including:

- Total Messages: Count of all messages sent.
- Total Words: Total number of words in all messages.
- Media Shared: Number of media files (images, videos, etc.) shared.
- Links Shared: Count of shared URLs.

### 👑 Most Active User in Chats

![image](https://whatsapp-chat-analyzer-u9t581i3ch.streamlit.app/)
Creating a bar graph to display the top 5 most active members, alongside a table showing all group members and their respective percentage contributions to the chat on the right.

### 📅 Monthly Messaging Trends

![image](https://whatsapp-chat-analyzer-u9t581i3ch.streamlit.app/)

This section provides insights into messaging activity over time on a monthly basis. The line graph displays the message count for each month, allowing you to identify peaks and patterns in messaging behavior.

### 📈 Daily Message Trends

![image](https://whatsapp-chat-analyzer-u9t581i3ch.streamlit.app/)

Here, you can view the daily messaging trends, with a line graph plotting the message count for each day. This feature is useful for pinpointing specific days of heightened activity, such as holidays or important events.

### 📊 Chat Activity

![image](https://whatsapp-chat-analyzer-u9t581i3ch.streamlit.app/)

The Chat Activity section includes two visualizations:

1. **Peak Day of the Week 📅** - A bar graph displays the number of messages sent on each day of the week, helping to identify the days with the highest chat activity.
2. **Peak Month of the Year 📆** - This bar chart showcases monthly activity levels, indicating the busiest months in terms of chat messages.

### ☁️ Word Cloud

![image](https://whatsapp-chat-analyzer-u9t581i3ch.streamlit.app/)

The Word Cloud feature provides a visual representation of the most frequently used words in the chat. The larger the word, the more often it appears in the messages. This feature is great for understanding dominant topics or themes in the chat.

### 🕒 Weekly Activity Heatmap

![image](https://whatsapp-chat-analyzer-u9t581i3ch.streamlit.app/)

The Weekly Activity Heatmap shows the distribution of messages throughout the week and at different times of the day. It visually represents peak activity times, allowing users to see which days and hours are the most active in the chat.

### 👀 Emoji Analysis

![image](https://whatsapp-chat-analyzer-u9t581i3ch.streamlit.app/)

The Emoji Analysis provides insights into emoji usage in the chat, including:

- **Count of Emojis Used 🔢** - Displays a table of emojis and their respective counts, showing the most popular emojis used in the chat.
- **Emoji vs. Non-Emoji Messages** - A pie chart shows the proportion of messages with and without emojis.
- **Emoji Sentiment Analysis 😁😐😕** - Sentiment analysis of emojis used in the chat, categorizing them as positive, neutral, or negative.

## Getting Started

To get started with the WhatsApp Chat Analyzer, follow the installation guide below to set up the environment and run the application locally.

### Prerequisites

Before you begin, ensure you have the following installed on your system:

- Python 3.7 or later
- pip (Python package installer)

### Installation Guide

1. **Clone the Repository**
   Open your terminal and clone the repository using the following command:

   ```bash
   git clone https://github.com/hiteshmahto/Whatsapp-Chat-Analyzer.git
   ```

2. **Navigate to the Project Directory**
   Change into the project directory:

   ```bash
   cd whatsapp-chat-analyzer
   ```

3. **Install Required Packages**
   Install the necessary Python packages using pip:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**
   To start the Streamlit application, run the following command:

   ```bash
   streamlit run app.py
   ```

## Contributing

If you'd like to contribute to this project, feel free to open an issue or submit a pull request. Contributions are welcome!

## Acknowledgments

Thank you for taking the time to explore the WhatsApp Chat Analyzer! Your feedback and support are greatly appreciated. I hope this project provides valuable insights into your WhatsApp communication patterns. If you have any questions or suggestions, feel free to reach out.
