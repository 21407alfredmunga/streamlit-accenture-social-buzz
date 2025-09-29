# Social Buzz Content Performance Dashboard

A Streamlit web application that analyzes and visualizes content performance data for Social Buzz, focusing on the top-performing content categories and their engagement metrics.

## 🚀 Features

- **Interactive Dashboard**: Real-time filtering and visualization of content performance data
- **Category Analysis**: Explore the top 5 performing content categories (Animals, Healthy Eating, Technology, Science, etc.)
- **Sentiment Analysis**: Visualize sentiment distribution across content categories
- **Time Series Analysis**: Track engagement trends over daily, weekly, or monthly periods
- **Key Performance Metrics**: Display total interactions, average sentiment scores, and positive sentiment share
- **Raw Data Explorer**: Interactive data table for detailed exploration

## 📊 Dashboard Components

### Key Metrics
- Total interactions count
- Average sentiment score
- Positive sentiment percentage

### Visualizations
- Top content categories leaderboard
- Sentiment distribution bar chart
- Engagement timeline with customizable granularity
- Interactive data tables

## 🛠️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/21407alfredmunga/streamlit-accenture-social-buzz.git
   cd streamlit-accenture-social-buzz
   ```

2. **Install required packages:**
   ```bash
   pip install streamlit pandas plotly pathlib
   ```

## 🏃‍♂️ Usage

1. **Run the Streamlit application:**
   ```bash
   streamlit run app.py
   ```

2. **Open your web browser** and navigate to the provided local URL (typically `http://localhost:8501`)

3. **Interact with the dashboard:**
   - Use the sidebar to filter by content category
   - Adjust time granularity for engagement trends
   - Expand the "Explore Raw Data" section for detailed data analysis

## 📁 Project Structure

```
streamlit-accenture-social-buzz/
├── app.py                          # Main Streamlit application
├── README.md                       # Project documentation
├── data/                          # Data files
│   ├── merged_top_5_dataframe.csv # Main dataset with interactions
│   ├── top_5_categories.csv       # Top performing categories
│   ├── Content (1).csv            # Content data
│   ├── Reactions (1).csv          # User reactions data
│   ├── ReactionTypes (1).csv      # Reaction type mappings
│   └── [other data files]         # Additional analysis datasets
├── notebooks/                     # Jupyter notebooks
│   ├── accenture.ipynb           # Main analysis notebook
│   └── accenture_visialization.ipynb # Visualization experiments
└── __pycache__/                  # Python cache files
```

## 📈 Data Sources

The dashboard uses several key datasets:

- **Content Data**: Information about posts, photos, and other content types
- **Reactions Data**: User interactions and engagement metrics
- **Reaction Types**: Sentiment classifications (positive, negative, neutral)
- **Merged Dataset**: Processed data combining content, reactions, and sentiment scores

## 🔧 Technical Details

- **Framework**: Streamlit for web application
- **Data Processing**: Pandas for data manipulation
- **Visualizations**: Plotly Express for interactive charts
- **Caching**: Streamlit's `@st.cache_data` for performance optimization

## 📊 Key Insights

The dashboard reveals insights about Social Buzz's top-performing content categories:

1. **Animals** - Highest engagement with 63,544 total score
2. **Healthy Eating** - Strong performance with 62,866 total score
3. **Technology** - Consistent engagement with 61,879 total score
4. **Science** - Solid performance with 60,575 total score
5. **Food** - Rounds out the top 5 categories

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Alfred Munga**
- GitHub: [@21407alfredmunga](https://github.com/21407alfredmunga)

## 🙏 Acknowledgments

- Accenture for providing the Social Buzz case study data
- Streamlit community for the excellent framework
- Plotly for interactive visualization capabilities

---

*Built with ❤️ using Streamlit and Python*