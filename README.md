# COVID-19 Dashboard API

This code shows a dashboard that visualizes the global COVID-19 situation using three different charts. It uses the COVID-19 API to fetch the data and Highcharts library to display the charts. Here's an overview of the code:

## **HTML**

The HTML code contains the following elements:

- A title for the dashboard
- Three cards that each contain a chart
- Two buttons to link to additional pages

## **CSS**

The CSS code adds some styling to the cards to make them look like panels.

## **JavaScript**

The JavaScript code does the following:

### **Fetches the data**

It fetches data from the COVID-19 API using the **`fetch`** method and the **`await`** keyword to handle the response.

### **Renders the charts**

The code uses the Highcharts library to render the charts. There are three types of charts:

1. Bar chart: displays the number of confirmed, deaths, and recovered cases globally.
2. Column chart: displays the number of confirmed cases by country globally.
3. Pie chart: displays the percentage of cases in each country out of the total global cases.

### **Displays the data**

The code displays the data on the charts with the following information:

- The title of the chart.
- The source of the data.
- The type of chart.
- The x-axis label and y-axis label.
- The data points for each chart.

The code also includes buttons that link to additional pages where users can search for COVID-19 cases by country or view the top 15 countries with the most cases.

## **Table Display**

The table displays data for each country in the following columns:

- Country
- Cases
- Deaths
- Recovered
- Active

## **Data Source**

The data is fetched from the COVID-19 API: **[https://api.covid19api.com/summary](https://api.covid19api.com/summary)**

## **Chart Display**

The chart displays the total cases for a country entered in the search bar. It uses Chart.js library to display data in a bar chart format.

## **Search Feature**

The search feature allows the user to search for a specific country's COVID-19 data. It provides the following functionality:

- Enter the name of the country in the search bar
- Click the search button to retrieve the total cases for that country
- If no data is available for the selected country, an alert message will be displayed
- The chart will be updated with the retrieved data

Note: The code assumes that the user will input the correct name of the country.

The following code is a simple web application that utilizes the COVID-19 API to display COVID-19 cases by country in a bar chart. The application allows the user to select a country from a dropdown menu and updates the chart with the selected country's data.

## **Technologies Used**

- HTML
- JavaScript
- Chart.js Library
- Axios Library

## **Code Walkthrough**

- The code starts by importing the required libraries in the head of the HTML document.
- A div with the class "card" is created to contain the chart and the country selection form.
- The country selection form contains a dropdown menu populated with country data retrieved from the API using Axios.
- The bar chart is created using the Chart.js library.
- The updateChart() function is called whenever a new country is selected from the dropdown menu.
- The function retrieves the selected country's data from the previously stored object, formats the data into an array, and updates the chart with the new data.

## **API Used**

- The COVID-19 API is used to retrieve data for all countries.
- The API provides country-specific data such as total cases, total deaths, and total recovered.

## **Resources Used**

- Chart.js library: **[https://www.chartjs.org/](https://www.chartjs.org/)**
- Axios library: **[https://axios-http.com/](https://axios-http.com/)**
- COVID-19 API: **[https://covid19api.com/](https://covid19api.com/)**

## **How to Use**

- Open the HTML file in a web browser.
- Select a country from the dropdown menu.
- Click the "Update Chart" button to update the chart with the selected country's data.

## **Limitations**

- The code only displays data for the total number of cases, deaths, and recovered individuals in a country.
- The chart does not update in real-time.
- The API used is not the most up-to-date source of COVID-19 data.

### **Link to Live Demo**

The live demo for this code portfolio can be accessed at [Click here](https://mikiyaas.github.io/COVID19-Dashboard-/).
