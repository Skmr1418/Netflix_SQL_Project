 📊 Netflix SQL Analysis Project

This project focuses on exploratory data analysis (EDA) using **SQL** on a cleaned Netflix dataset. The objective was to uncover business insights, usage patterns, and content trends using PostgreSQL queries.

---

 🛠️ Tools Used

* PostgreSQL
* SQL (DML, DQL, CTEs, window functions)
* VS Code / pgAdmin / any SQL IDE

---

 📂 Dataset

The dataset contains records of Netflix content including fields like:

* `show_id`, `title`, `type`, `director`, `cast`, `country`
* `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

---

🔍 Key Analyses Performed

1. **Content Type Split** – Count of Movies vs. TV Shows
2. **Popular Ratings** – Most common ratings by type
3. **Released in 2020** – All movies released in a specific year
4. **Top Countries** – Countries with the most Netflix content
5. **Recent Additions** – Content added in the last 5 years
6. **By Director** – Listings by a specific director like *Rajiv Chilaka*
7. **TV Show Seasons** – Filtering shows with more than 5 seasons
8. **Genre Popularity** – Count of content by genre using `listed_in`
9. **Indian Market Analysis** – % of Indian content released year-over-year
10. **Documentaries** – Movie filtering by genre keywords
11. **Missing Data** – Finding content with no listed director
12. **Actor-Based Search** – Appearances of *Salman Khan* in the last 10 years
13. **Top Actors in Indian Content** – Most frequent actors in Indian productions
14. **Content Classification** – Flagging content as “Good” or “Bad” based on keywords like `kill` or `violence` in descriptions

---

 🧠 Skills Demonstrated

* String manipulation (`SPLIT_PART`, `UNNEST`)
* Aggregation and filtering
* Date and time functions
* Conditional logic using `CASE`
* Window functions like `RANK()`
* Subqueries and `CTEs`

---

✅ Output

All queries return actionable insights that could help Netflix or similar streaming platforms in:

* Understanding user content preferences
* Improving recommendations
* Optimizing regional content strategies

