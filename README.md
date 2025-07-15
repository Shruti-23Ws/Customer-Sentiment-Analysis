📱 Flipkart iPhone 15 Review Sentiment Analysis Dashboard
📌 Tools Used: Python | Selenium | BeautifulSoup | TextBlob | Pandas | Matplotlib | WordCloud
📁 Dataset: 400+ Customer Reviews for iPhone 15 128GB scraped from Flipkart
1. Introduction
With the growing popularity of online shopping, customer reviews are a goldmine for understanding product quality, performance, and satisfaction. This project analyzes customer reviews for the iPhone 15 (128GB) model scraped from Flipkart using Python tools. The goal is to uncover sentiment patterns, highlight common feedback themes, and help brands make data-driven improvements in marketing, product design, and customer service.

2. Business Problem
Retailers and brands face key challenges:

Huge volume of reviews makes manual analysis inefficient.

Limited visibility into common complaints or praise from real users.

Difficulty in understanding what features customers care about most.

Need to connect textual reviews to star ratings and sentiment for better strategy.

Without automating review analysis, businesses may miss out on valuable customer feedback and lose the opportunity to improve satisfaction and loyalty.

3. Goal of the Dashboard
This dashboard was built to:

Collect 300+ real user reviews from Flipkart using web scraping.

Clean, preprocess, and analyze review text.

Perform sentiment classification (Positive, Neutral, Negative).

Visualize review distribution, sentiment trends, and popular keywords.

Help stakeholders understand what customers like/dislike about the iPhone 15.

4. Walkthrough of Key Visuals
⭐ Review Rating Distribution
A bar chart showing the spread of reviews from 1 to 5 stars.

🔍 Sentiment Breakdown
Pie chart showing percentage of positive, neutral, and negative reviews.

☁️ Word Cloud
Visual cloud of most used words in all reviews — highlights what's trending.

✏️ Review Length Distribution
Histogram to understand how detailed customers are in their reviews.

🔠 Top Keywords by Sentiment
Common words used in positive vs. negative reviews.

🧾 Customer Table
Full table with scraped data: customer name, rating, review, sentiment.

5. Key Insights & Business Impact
🔹 Over 80% of reviews are positive, with high praise for camera, performance, and design.
🔹 Negative reviews are rare and mostly focus on pricing or battery expectations.
🔹 High-frequency words include: camera, performance, design, premium, value.
🔹 Word clouds reveal what's most important to users and what creates satisfaction.
🔹 Businesses can use positive feedback for marketing and address minor concerns proactively.

💼 Business Value
📊 Supports automated sentiment monitoring at scale.

💡 Helps marketing teams identify what to promote in campaigns.

🔧 Aids in product improvement based on real customer input.

🚀 Builds a feedback loop between users and developers.

✅ Enhances trust through transparent and honest review analysis.

🔗 Project Structure
bash
Copy
Edit
📂 Flipkart-iPhone15-Review-Analysis/
│
├── 📄 README.md             # Project overview and documentation
├── 📜 flipkart_scraper.ipynb  # Web scraping code using Selenium
├── 📊 sentiment_analysis.ipynb # Review cleaning, sentiment classification, and plots
├── 📁 data/
│   └── iphone15_reviews.csv   # Final cleaned dataset
├── 📁 images/
│   ├── rating_distribution.png
│   ├── wordcloud.png
│   └── sentiment_pie_chart.png

