customer-churn-analysis/
│
├── Churn_Analysis.ipynb # Main analysis notebook
├── README.md # This file




Key Features
- **All-in-one analysis**: Single notebook covering entire workflow
- **RFM segmentation**: Classifies customers into risk groups
- **Product analysis**: Finds which items impact churn most
- **Time trends**: Identifies seasonal churn patterns

How to Use
1. **Open the notebook** in Jupyter or Google Colab
2. **Run all cells** sequentially
3. **View results**: All outputs appear below each code cell

What's Inside the Notebook
1. Data Preparation**  
   - Creates sample e-commerce data
   - Sets up proper data types

2. Customer Segmentation**  
   ```python
   # Finds at-risk customers
   rfm.withColumn("Segment", 
       when(col("Recency") > 90, "At Risk"))

   Product Analysis
3. Ranks products by importance
ABC classification (A = most valuable)
Time Analysis
Daily/Monthly sales trends
Interactive charts


Future Improvements

Connect to real database
Add automated alerts for at-risk customers
Build prediction model



Why This Works Well:
1. **Clear Structure** - Shows everything is in one notebook but still organized
2. **Visual Tags** - Badges and emojis make it skimmable
3. **Code Preview** - Shows actual RFM code snippet
4. **Business Focus** - Connects technical work to real outcomes

Key Takeaways 
- The single notebook approach makes it easy to:
  - Share (just one file)
  - Reproduce (run top-to-bottom)
  - Present (all visuals stay with code)

