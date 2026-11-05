# library-analytics-dashboard

 Power BI Library Analytics dashboard covering circulation, member behaviour, fines, branch benchmarking and key influencers, built on a 500-record sample dataset.
   
# 📚 Library Analytics Dashboard | Power BI

An interactive Power BI dashboard that turns library circulation data into clear, actionable insights on borrowing trends, overdue books, fine revenue, member behaviour and branch performance.

## 🎯 Objective
Help library managers answer questions like:
- Which book categories circulate the most?
- Who returns books late, and why?
- Where does fine revenue come from?
- Which branch performs best?
- Does a member's distance from the library affect returns?

## 📊 Dashboard Pages
1. **Cover**: project title and introduction
2. **Overview**: KPI cards (Total Books, Issued, Returned, Overdue, Avg Rating), Return % and fine revenue by category
3. **Branch Performance**: availability and status by branch and book type
4. **Circulation & Fine Trends**: monthly fines, yearly issues, category demand
5. **Member Behaviour**: gender, age group, membership type, payment mode, branch map
6. **Staff & Acquisition**: librarian performance and acquisition sources
7. **Branch Benchmark**: satisfaction, share %, fines and fine waivers by branch and city
8. **Facilities & Access**: member distance vs return %
9. **Key Influencers**: factors that lower return rates

## 🗂️ Dataset
- 500 records, 22 columns, 6 branches, 4 cities, 8 book categories
- Fields include: Branch, Category, Book_Type, Membership_Type, Status, Issue/Due/Return Date, Fine_Amount, Distance_KM, Rating and more
- ⚠️ This is a **simulated sample dataset** created for portfolio demonstration. It is not real library data.

## 🛠️ Tools & Skills
- **Power BI Desktop**: data modelling, DAX measures, slicers, bookmarks
- **Power Query**: data cleaning and type transformation
- **DAX**: Return %, Overdue count, Total Fine, Avg Rating
- **Visuals**: combo charts, donuts, matrices, gauge, map, key influencers

## 💡 Sample Insights
- About 35% of records are returned, while 12% are overdue
- Total fine revenue is ₹3,418 across the network
- Members living more than 6 km away return fewer books (31% vs 37%)
- Premium members have the highest return rate

## 📁 Repository Contents
- `Library_Data.csv`: sample dataset
- `Library_Analytics_Dashboard.pbix`: Power BI report file
- `Library_Analytics_Dashboard_Report.pdf`: exported dashboard report

## 🚀 How to Use
1. Download the repository
2. Open the `.pbix` file in Power BI Desktop
3. Use the City, Year and Book_Type slicers to explore the data

## 👤 Author
**Shankzz**: aspiring Data Analyst | Power BI · SQL · Python · Excel
