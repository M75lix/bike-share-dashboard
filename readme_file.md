# 🚴 Bike Share Data Analysis Dashboard

An interactive web-based dashboard for analyzing bike share ride data with beautiful visualizations and key statistics.

## 📊 Features

- **Real-time Data Upload**: Upload your CSV file directly in the browser
- **Key Metrics Display**: 
  - Total rides
  - Member vs Casual rider breakdown
  - Average ride length
- **Interactive Charts**:
  - Rides by day of week
  - Member vs Casual distribution (pie chart)
  - Comparative trends by user type
  - Top 10 most popular start stations
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **No Installation Required**: Pure HTML/CSS/JavaScript - runs entirely in the browser

## 🚀 Live Demo

View the live dashboard: [Your GitHub Username].github.io/[Your Repository Name]

## 📁 Dataset Information

The dashboard analyzes bike share data with the following columns:
- `ride_id`: Unique identifier for each ride
- `started_at`: Start timestamp
- `ended_at`: End timestamp
- `start_station_id`: Starting station ID
- `end_station_id`: Ending station ID
- `start_lat/start_lng`: Starting coordinates
- `end_lat/end_lng`: Ending coordinates
- `member_casual`: User type (member or casual)
- `day_of_week`: Day of the week (0-6)
- `ride_length`: Duration of the ride

**Dataset Size**: 84,770 rides

## 🛠️ Usage

1. Open `index.html` in your web browser
2. Click "Choose CSV File" button
3. Select your `df_copy.csv` file
4. Dashboard will automatically load and display visualizations

## 💻 Technologies Used

- **HTML5/CSS3**: Structure and styling
- **JavaScript**: Data processing and interactivity
- **Chart.js**: Beautiful, responsive charts
- **PapaParse**: Fast CSV parsing

## 📈 Insights

This dashboard helps answer questions like:
- Which days of the week are busiest?
- What's the split between members and casual riders?
- Which stations are most popular?
- How do usage patterns differ between member types?

## 📝 License

This project is open source and available for educational and commercial use.

## 👤 Author

Created as part of a data analysis project to visualize bike share patterns and trends.

---

*Last updated: October 2025*