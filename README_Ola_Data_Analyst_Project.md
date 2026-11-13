# Ola Data Analyst Project \| Bengaluru Ride Analysis

An end-to-end ride-booking analysis project using **SQL and Power BI**,
focused on booking trends, ride demand, cancellations, vehicle
preferences, customer experience, and operational performance in
Bengaluru.

![Ola Ride Analysis Dashboard](images/ola-dashboard.png)

> Add your Power BI dashboard screenshot to the `images/` folder and
> name it `ola-dashboard.png` to display it here on GitHub.

## Project Overview

This project explores a five-month Ola ride-booking dataset for
Bengaluru containing **50,000 records** and 20+ fields. It examines
booking behaviour, peak-hour demand, ride status, cancellation patterns,
vehicle preferences, pickup and drop locations, ride metrics, and
payment information.

The aim is to use SQL for data querying and analysis and Power BI for
interactive reporting, turning booking data into practical insights that
can support operational and customer-experience decisions.

## Project Objectives

-   Track booking trends by date and time to identify demand patterns
    and peak hours.
-   Measure successful, customer-cancelled, driver-cancelled, and
    incomplete rides.
-   Understand customer and driver cancellation reasons.
-   Identify preferred vehicle categories.
-   Analyze pickup and drop locations to understand ride demand.
-   Review ride metrics such as Vehicle Time to Arrive (VTAT), Customer
    Time to Arrive (CTAT), and ride distance.
-   Explore booking value, payment methods, and customer/driver ratings.

## Dataset

**File:** `Bengaluru_Ola_Booking_Data.csv`

-   Records: 50,000
-   Coverage: Five-month period
-   Fields: 21 columns

### Data fields

  -----------------------------------------------------------------------
  Area                                Fields
  ----------------------------------- -----------------------------------
  Booking details                     Date, Time, Booking ID, Booking
                                      Status, Customer ID

  Ride details                        Vehicle Type, Pickup Location, Drop
                                      Location

  Arrival metrics                     Avg VTAT, Avg CTAT

  Cancellations                       Cancelled Rides by Customer, Reason
                                      for Cancelling by Customer,
                                      Cancelled Rides by Driver, Reason
                                      for Cancelling by Driver

  Incomplete rides                    Incomplete Rides, Incomplete Rides
                                      Reason

  Payment and value                   Booking Value, Payment Method

  Ride and service ratings            Ride Distance, Driver Ratings,
                                      Customer Rating
  -----------------------------------------------------------------------

The location fields represent pickup and drop zones across Bengaluru.
The project overview describes the location values as randomized across
20+ zones; treat them as analysis zones rather than verified
street-level addresses.

## Tools & Technologies

-   **SQL:** Data querying, filtering, aggregation, and analysis.
-   **Microsoft Power BI:** Interactive dashboard, KPI cards, and visual
    reporting.
-   **CSV:** Structured booking dataset used for analysis.

## Power BI Dashboard

The dashboard presents the following views:

1.  **KPI summary:** Total revenue, successful bookings, total
    bookings/ride volume, average VTAT, and average CTAT, as displayed
    in the dashboard.
2.  **Booking value distribution:** Breakdown of booking values by
    vehicle type.
3.  **Ride distribution by date:** Daily ride volume and demand
    patterns.
4.  **Most preferred vehicle type:** Comparison of vehicle categories
    based on booking preference.
5.  **Average customer rating by vehicle type:** Customer experience
    comparison across vehicle categories.
6.  **Top pickup locations:** Locations contributing the highest booking
    volume.

Use the dashboard's date filters to explore the selected reporting
period.

## Key Findings Highlighted in the Project

The project notes and dashboard call out these patterns:

-   Approximately **62% of bookings are successful**.
-   Customer cancellation rate is reported as **below 7%**.
-   Driver cancellation rate is reported as **below 18%**.
-   Booking value distribution is summarized as approximately **70%
    below ₹500**, **20% between ₹500 and ₹1,000**, and **10% above
    ₹1,000**.
-   Higher booking values and ride distances are noted on weekends.
-   The cancellation analysis distinguishes customer-side and
    driver-side reasons.

These are project-reported dashboard observations. Recalculate them from
the supplied CSV and SQL queries if you change the dataset or reporting
filters.

## SQL Analysis Areas

The SQL project can be used to explore:

-   Total bookings and booking status distribution.
-   Successful booking volume and rate.
-   Customer and driver cancellation counts and reasons.
-   Incomplete ride counts and reasons.
-   Booking trends by date, time, and peak-hour period.
-   Vehicle type preference.
-   Booking value and payment method distribution.
-   Pickup and drop location demand.
-   Average VTAT, CTAT, ride distance, and customer/driver ratings.

See the SQL script included in this repository for the actual SQL
statements.

## Business Insights & Recommendations

-   **Reduce cancellations:** Identify frequent cancellation reasons and
    prioritize process improvements for the most common causes.
-   **Improve peak-hour availability:** Use hourly and daily booking
    patterns to plan driver availability during high-demand periods.
-   **Optimize vehicle availability:** Use vehicle preference trends to
    support category-level supply planning.
-   **Improve customer experience:** Compare customer ratings and
    arrival-time metrics across vehicle types.
-   **Focus on high-demand zones:** Use pickup and drop trends to
    support driver positioning and local demand planning.
-   **Review booking value patterns:** Use fare bands and payment method
    trends to inform customer offers and operational decisions.

## Repository Structure

``` text
Ola-Data-Analyst-Project/
│
├── README.md
├── Bengaluru_Ola_Booking_Data.csv
├── Ola_DA_Project.pbix
├── [your SQL analysis script].sql
└── images/
    └── ola-dashboard.png
```

Replace `[your SQL analysis script].sql` in the folder tree with the
exact filename of your SQL script when you upload it.

## How to Run the Project

### 1. Get the files

Clone or download this repository. The CSV dataset and Power BI file
should be available locally.

### 2. Explore the dataset

Open `Bengaluru_Ola_Booking_Data.csv` in Excel or import it into your
preferred SQL environment.

### 3. Run the SQL analysis

Open the SQL script in your SQL editor, load the CSV data into a table,
and adjust the table name or import settings if needed. Run the queries
to reproduce the booking analysis.

### 4. Open the Power BI dashboard

Open `Ola_DA_Project.pbix` in Power BI Desktop. If Power BI prompts for
the data source location, point it to `Bengaluru_Ola_Booking_Data.csv`,
then refresh the model.

### 5. Explore the dashboard

Use the available filters and visuals to investigate booking trends,
vehicle types, ride status, locations, and customer experience.

## Project Files

  -----------------------------------------------------------------------
  File                                Description
  ----------------------------------- -----------------------------------
  `Bengaluru_Ola_Booking_Data.csv`    Booking dataset with 50,000 records
                                      and 21 fields

  `Ola_DA_Project.pbix`               Interactive Power BI dashboard

  SQL script                          Queries used for data analysis
  -----------------------------------------------------------------------

## Author

**Prerana C**

Business Analytics \| SQL \| Power BI \| Data Analysis
