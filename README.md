# streamlit-cheatsheet
## 📦 Import Streamlit
```python
import streamlit as st
📝 Display Elements
Element	Code Example
Title	st.title("Your Title")
Header/Subheader	st.header("Header"), st.subheader("Subheader")
Text/Markdown	st.text("Text"), st.markdown("**bold** _italic_")
Code Block	st.code("your_code")
Write Anything	st.write("Mix of text and data")

🎯 Input Widgets
Widget	Code Example
Text Input	st.text_input("Enter name")
Number Input	st.number_input("Enter age")
Text Area	st.text_area("Description")
Checkbox	st.checkbox("Show result")
Radio Button	st.radio("Choose", ["A", "B", "C"])
Select Box	st.selectbox("Pick one", options)
Multiselect	st.multiselect("Pick multiple", options)
Slider	st.slider("Range", 0, 100)
Button	st.button("Click Me")
File Upload	st.file_uploader("Upload File")

📐 Layouts & Containers
Feature	Code Example
Sidebar	st.sidebar.title("Sidebar Title")
Columns	col1, col2 = st.columns(2)
Tabs	tab1, tab2 = st.tabs(["Tab 1", "Tab 2"])
Expander	with st.expander("See more"):

📊 Display Data
Type	Code Example
DataFrame	st.dataframe(df)
Table	st.table(df.head())
JSON	st.json({"name": "Harshita"})
Metric	st.metric("Temp", "70°F", "-1°F")

🖼️ Media
Type	Code Example
Image	st.image("img.png", caption="Image")
Audio	st.audio(file)
Video	st.video(file)

📈 Charts & Graphs
Type	Code Example
Line Chart	st.line_chart(data)
Bar Chart	st.bar_chart(data)
Area Chart	st.area_chart(data)
Matplotlib	st.pyplot(fig)
Plotly	st.plotly_chart(fig)

✨ Magic Commands
Just write markdown directly — no st. needed:

markdown
Copy
Edit
# Hello *Streamlit*!
▶️ Run the App
bash
Copy
Edit
streamlit run your_app.py
💡 Tip
Use st.write() for anything — it automatically figures out what you're passing!

⭐ Connect with Me
GitHub: https://github.com/bingiharshita

LinkedIn: https://www.linkedin.com/in/harshita-bingi/

Built for beginners and creators — Happy Coding!
