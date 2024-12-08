# Hospitality Data Analysis Project

This project provides an in-depth analysis of booking and revenue data for a hospitality business. The objective is to derive meaningful insights from the data, identify trends, and help the business optimize operations and decision-making processes.

## Project Overview

The project focuses on:

1. **Analyzing Booking Patterns**: Understand booking trends, including platforms used, room categories, and the number of guests.
2. **Revenue Insights**: Analyze revenue generated and realized to identify performance gaps.
3. **Cancellations and Ratings**: Investigate booking cancellations and ratings given by guests to highlight potential service improvements.

### Dataset Overview

The dataset used contains the following columns:
- `booking_id`: Unique identifier for each booking.
- `property_id`: Identifier for the property.
- `booking_date`: Date of booking.
- `check_in_date` and `checkout_date`: Dates for the guest's stay.
- `no_guests`: Number of guests in the booking.
- `room_category`: Type of room booked.
- `booking_platform`: Platform used for booking (e.g., direct online, logtrip, others).
- `ratings_given`: Ratings provided by guests (if applicable).
- `booking_status`: Status of the booking (e.g., Checked Out, Cancelled).
- `revenue_generated` and `revenue_realized`: Revenue expected and actual revenue earned.

### How It Works

#### 1. **Data Loading and Preprocessing**
   - The dataset is loaded into a pandas DataFrame.
   - Data cleaning processes like handling missing values and incorrect data types are performed.

#### 2. **Exploratory Data Analysis**
   - Insights into booking trends based on platforms, room categories, and dates.
   - Distribution of ratings and their correlation with room categories and booking platforms.
   - Analysis of cancellations and revenue patterns.

#### 3. **Visualization**
   - Visualizations using libraries like Matplotlib and Seaborn to display trends, revenue patterns, and other findings dynamically.

#### 4. **Key Findings**
   - Identify high-performing platforms and room categories.
   - Highlight revenue leakages due to cancellations.
   - Provide actionable insights for improving customer satisfaction based on ratings.

## Technologies Used

- **Programming Language**: Python
- **Libraries**: Pandas, Matplotlib, Seaborn, NumPy
- **Tools**: Jupyter Notebook

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/hospitality-data-analysis.git
   cd hospitality-data-analysis
2. pip install -r requirements.txt
3. jupyter notebook
