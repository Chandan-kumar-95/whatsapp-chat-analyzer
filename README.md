Analyze your WhatsApp chats with beautiful visualizations and statistics using Python, Pandas, and Streamlit.


**Features**

Upload your exported WhatsApp chat (.txt) file.

Get overall & user-specific statistics:

Total Messages,  

Total Words, 

Media Shared, 

Links Shared


**Visualizations:**

Monthly & Daily Timeline, 

Activity Map (Most active days, months, hours), 

Heatmap of activity, 

 Most Busy Users, 
 
 WordCloud of most used words, 
 
 Most Common Words, 
 
Emoji Analysis (Table + Pie Chart)



**Tech Stack**

Python, 

Pandas, NumPy – Data processing, 

Matplotlib, Seaborn – Visualization, 

WordCloud – Word clouds, 

URLEXtract, Emoji – Links & emoji analysis, 

Streamlit – Interactive dashboard UI



Project structure 

whatsapp-chat-analysis/

│── app.py              # Main Streamlit app (UI + logic)

│── helper.py           # Functions for stats, wordcloud, emoji analysis

│── preprocessor.py     # Preprocess chat data into structured format

│── requirements.txt    # Dependencies for project

│── stop_hinglish.txt   # Stopwords for wordcloud

│── sample_chat.txt     # Example WhatsApp chat file
