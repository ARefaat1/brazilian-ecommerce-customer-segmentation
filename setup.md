 Data Directory Setup & Instructions

Welcome to the **Brazilian E-Commerce Customer Segmentation (Model 4)** project directory!

## 📁 Data Setup Instructions

Because large raw data files (`.csv`) are ignored by Git (via `.gitignore`), you must add the Kaggle dataset files locally to this `data/` directory before running the pipeline.

### Required Dataset Files:
Ensure the following CSV files are placed inside this `data/` folder:

1. `olist_customers_dataset.csv`
2. `olist_geolocation_dataset.csv`
3. `olist_order_items_dataset.csv`
4. `olist_order_payments_dataset.csv`
5. `olist_order_reviews_dataset.csv`
6. `olist_orders_dataset.csv`
7. `olist_products_dataset.csv`
8. `olist_sellers_dataset.csv`
9. `product_category_name_translation.csv`

---

## 🚀 How to Run the Notebook

1. **Verify Setup:** Make sure all 9 CSV files listed above are located inside `capstone_project/data/`.
2. **Open Notebook:** Navigate to `capstone_project/notebook/Capstone_Model4_Analysis.ipynb`.
3. **Execute Pipeline:** 
   - Open Jupyter / VS Code / Google Colab.
   - Run all cells sequentially (**Kernel -> Restart & Run All**).
4. **Outputs Generated:**
   - Preprocessed dataset: saved to `data/clean_orders.csv`
   - Model artifact: saved to `model/best_model.pkl`
   - Key evaluation plots: saved to `visuals/`