# Personal Finance Project

## Overview
This project is designed to help individuals manage their finances effectively. It includes features for tracking expenses, creating budgets, analyzing financial trends, and generating financial reports. By using this application, users can gain a better understanding of their spending patterns and take control of their financial health.

![image_alt](https://github.com/iamanirudhnair/Personal_Finance/blob/main/Finance%20Dashboard.png?raw=true)

## What I Learned

- **Financial Data Management**: I learned how to manage and organize financial data, including income, expenses, and savings. This was a key part of the project, as organizing data accurately is essential to providing meaningful financial insights.
  
- **Data Visualization**: I explored different ways to present financial data through visual charts. This is especially useful for users to quickly understand their financial health. I gained a deeper understanding of visualizations like bar charts, line charts, and pie charts to represent income, expenses, and budget comparisons.

- **Budget Calculation Algorithms**: I implemented algorithms that help calculate monthly budgets, savings, and expenditures. This required a deep understanding of how to process and compare financial data over time.

## Techniques Used

1. **Python Programming**: Python was the primary language used for data processing and implementing algorithms. I utilized libraries such as `pandas` for data manipulation and `matplotlib`/`seaborn` for data visualization.
   - **Why this technique**: Python offers robust libraries for data analysis and visualization. It was an ideal choice for handling large datasets and creating interactive charts to provide actionable insights.

2. **Flask for Web Application**: Flask was used to build the web interface where users can input their financial data and view reports.
   - **Why this technique**: Flask is lightweight and allows rapid development, which made it suitable for creating a simple and functional web app for this project.

3. **SQLite for Data Storage**: The project uses SQLite as the database to store users' financial records.
   - **Why this technique**: SQLite is easy to integrate with Flask and offers a lightweight, file-based solution for data storage, which is ideal for personal use projects.

## Errors and Solutions

- **Error: Database Connection Issues**
  - **Problem**: Initially, I faced issues with the connection between Flask and SQLite. The application wasn’t properly saving or retrieving data from the database.
  - **Solution**: After troubleshooting, I realized the problem was related to improper database initialization. I solved this by ensuring that the database was properly initialized and that the file paths were correctly set up in the project’s configuration.

- **Error: Data Not Updating on the Frontend**
  - **Problem**: The data entered into the form wasn't reflecting on the frontend in real-time.
  - **Solution**: The issue was due to the lack of proper data reloading after submitting the form. I resolved this by adding a redirect after the form submission to reload the page with updated data.

- **Error: Incorrect Budget Calculations**
  - **Problem**: Initially, the budget calculations were incorrect due to errors in how the algorithms processed expenses and income.
  - **Solution**: I reviewed the logic of the budget calculation algorithm and realized that I had not properly accounted for some edge cases (e.g., zero expenses or income). Once I refined the algorithm, the calculations were accurate.

## Future Improvements

- **User Authentication**: Implementing user authentication (e.g., sign-up and login) would allow users to store and access their data securely across sessions.
  
- **Data Export**: Adding a feature to export the data to CSV or PDF formats could make it easier for users to analyze their financial data offline.

- **Enhanced Visualizations**: Adding more advanced visualizations such as financial forecasts or debt tracking could enhance the user experience.
   ```

4. Open your browser and navigate to `http://127.0.0.1:5000` to start using the app.

## Acknowledgments
- The development of this project was inspired by the resources from [CodeBasics](https://www.youtube.com/channel/UCQfFQU4d8Qk01ALk1jXw1gA).
