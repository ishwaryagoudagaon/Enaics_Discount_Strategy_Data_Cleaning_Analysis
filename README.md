# Eniac Discount Strategy Review

A data-driven analysis of Eniac's discount strategy to understand whether bigger discounts lead to stronger sales and how discounts should be used across products and seasons.

## Business Question

**Should Eniac keep offering discounts?**

And if so:

- How big should the discounts be?
- On which products should Eniac offer discounts?
- Do bigger discounts actually generate bigger sales?

The analysis looks at every completed Eniac order between **January 2017 and March 2018**. 
---

## The Data

The analysis covers:

| Metric | Value |
|---|---:|
| Analysis period | Jan 2017 – Mar 2018 |
| Completed orders | **40,985** |
| Total revenue | **$7.8M** |
| Total discounts | **$1.52M** |
| Discount share of gross value | **16%** |

The dataset contains **40,985 completed orders** and represents **$7.8M in collected revenue** and **$1.52M in discounts**.

---

# Key Findings

## 1. Discount changes often fail to explain sales changes

The analysis shows that:

- **Discounts and sales often diverge.**
- **Bigger discounts do not guarantee bigger sales.**
- **Seasonal trends dominate sales performance.**

The category-level monthly analysis compares revenue with median discount and shows that changes in discount levels do not consistently correspond with changes in revenue. 

---

## 2. Small discounts generate a larger share of revenue

Orders were grouped according to discount size and compared by their share of orders and revenue.

| Discount Size | Number of Orders | % of All Orders | % of All Revenue |
|---|---:|---:|---:|
| Up to 15% | 19,659 | **40.9%** | **59.0%** |
| 15–25% | 12,695 | **26.5%** | **26.1%** |
| 25–35% | 7,264 | **15.1%** | **10.0%** |
| 35%+ | 8,339 | **17.4%** | **4.9%** |

The **up to 15%** discount group represents 40.9% of orders but 59.0% of revenue.

The **35%+** discount group represents 17.4% of orders but only 4.9% of revenue.

This creates a clear difference between the share of orders generated and the share of revenue collected. 

---

## 3. Bigger discounts don't fill bigger carts

The analysis also examines whether deeper discounts encourage customers to purchase more products per order.

The result is relatively consistent basket size:

**1.3 to 1.5 items per order**

This remains broadly similar regardless of discount size.

The analysis therefore does not show that increasing the discount leads to substantially larger baskets. Instead, a deeper discount can mean collecting less money for a similar-sized basket.

### Seasonal basket size

Average items per order varied only modestly across the period.

- **May:** 1.55 items
- **November / Black Friday:** 1.53 items

The presentation notes that basket size remained similarly high during Black Friday, indicating only modest seasonal variation. 

---

# Category Analysis

The presentation compares all 10 product categories by revenue and average discount.

| Category | Revenue | Average Discount |
|---|---:|---:|
| Mobile Devices | **$1.85M** | **9.0%** |
| Storage | **$1.52M** | **16.8%** |
| Other Products | **$0.94M** | **21.8%** |
| Networking | **$0.79M** | **12.7%** |
| Electronics | **$0.76M** | **16.9%** |
| Computers | **$0.59M** | **17.2%** |
| Accessories | **$0.46M** | **20.8%** |
| Audio | **$0.33M** | **21.9%** |
| Wearables | **$0.30M** | **11.7%** |
| Protection | **$0.28M** | **31.2%** |

The highest-revenue category is **Mobile Devices**, with **$1.85M** in revenue and an average discount of only **9.0%**.

**Protection** has the highest average discount at **31.2%**, while generating **$0.28M** in revenue.

---

# Recommendation

## 1. Cap everyday discounts at 5–15%

The presentation recommends:

> **Cap everyday discounts at 5–15% off**

The supporting evidence is that discounts of up to 15% account for **40.9% of orders but 59.0% of revenue**.

---

## 2. Save discounts above 25% for clearing old stock

Discounts above 25% should be reserved for situations such as clearing old stock.

The presentation highlights that these deeper discounts account for a substantial share of orders but a much smaller share of revenue. 

---

## 3. Don't discount the best-selling category to compete on price

The presentation recommends avoiding aggressive discounting of the best-selling category.

**Mobile Devices** generate the highest revenue:

- Revenue: **$1.85M**
- Average discount: **9%**

This category demonstrates that high revenue does not require deep discounting. 
---

## 4. Keep seasonal discounts at 15–22%

The presentation recommends:

> **Seasonal discounts should stay at 15–22%**

November and December are identified as two of the best months while remaining below 22% discounting.

January and July pushed toward 25% without outperforming those months.

---

# Final Takeaway

The analysis shows that **bigger discounts do not guarantee bigger sales**.

The data presented in the analysis points toward:

- **5–15%** for everyday discounts
- **15–22%** for seasonal discounts
- **25%+** primarily for clearing old stock
- Avoiding aggressive price competition in **Mobile Devices**
- Focusing on the relationship between **discount depth, revenue contribution, basket size, and seasonality**

The central finding is:

> **Small discounts pay for themselves. Big ones don't.**

---

# Analysis Structure

The presentation covers six main areas:

1. **The data**
2. **The core finding**
3. **Order trends**
4. **Category view**
5. **Product view**
6. **Recommendation**

---
# Technology

- Python (pandas, numpy)
- matplotlib, seaborn
- Jupyter / JupyterLab (conda environment: `pandas_project`)

