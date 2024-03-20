## WhatsApp Chat Analyzer

This project is a Python web application that analyzes WhatsApp chat data to provide insights into communication patterns and message content.

### Features

* **Upload WhatsApp Chat Data:** Upload a text file containing your WhatsApp chat export (without media).
* **User Analysis:** Select a specific user or analyze the entire chat.
* **Chat Statistics:** View key statistics like total messages, words used, media shared, and links shared.
* **Timeline Analysis:** Explore message activity over time, including monthly and daily trends.
* **Activity Heatmaps:** Identify the busiest days and months for each user (or overall).
* **Word Cloud:** Visualize the most frequently used words in the chat.
* **Most Common Words:** See a list of the most common words used, excluding stop words.
* **Emoji Analysis:** Analyze emoji usage within the chat (for users who have emojis enabled).

### How to Use

1. **Install Dependencies:** Ensure you have Python and the required libraries installed. You can install them using `pip install -r requirements.txt`. Refer to the `requirements.txt` file for the specific list of dependencies.
2. **Run the App:** Run the Streamlit application using `streamlit run app.py` (replace `app.py` with the actual filename if different).
3. **Upload Chat Data:** In the web interface, upload the text file containing your WhatsApp chat export.
4. **Analyze the Chat:** Select a user (optional) and explore the various visualizations and statistics provided.

### Technologies Used

* Python (programming language)
* Streamlit (web framework)
* Pandas (data manipulation)
* matplotlib (data visualization)
* wordcloud (word cloud generation)
* urlextract (URL extraction)
* emoji (emoji analysis) (optional)

### Contributing

We welcome contributions to this project! Feel free to fork the repository, make your changes, and submit a pull request.


### Working Demo


https://whatsapp-chat-analyser-2-prf3.onrender.com

