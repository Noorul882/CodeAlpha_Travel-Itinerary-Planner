# Travel Itinerary Planner

## Overview

`TravelItineraryPlanner` is a Java application designed to help users plan their travel itineraries. The program allows users to input travel destinations, dates, travel style, accommodation preferences, and estimated costs. It then calculates the total budget for the trip and displays a detailed itinerary including cost estimates.

## Features

- **Destinations Input:** Allows users to list their travel destinations.
- **Date Input:** Prompts users for the start and end dates of their trip.
- **Preference Input:** Collects information on travel style, accommodation preferences, and budget estimates.
- **Budget Calculation:** Calculates the total estimated cost for food, activities, and transportation based on user inputs.
- **Itinerary Display:** Outputs a summary of the travel itinerary and budget estimates.

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- A command-line interface (CLI) for running the Java application

## Installation

1. Clone this repository to your local machine using Git:
   ```sh
   git clone https://github.com/yourusername/TravelItineraryPlanner.git

2. Navigate to the project directory:
   cd TravelItineraryPlanner

## Usage

1. Compile the Java Program:
   javac TravelItineraryPlanner.java

2. Run the Compiled Java Program:
   java TravelItineraryPlanner

3. Follow the Prompts:
   -Enter travel destinations separated by commas.
   -Input start and end dates in the format yyyy-MM-dd.
   -Provide your travel style, accommodation preference, and cost estimates.

4. View Results: The program will output a detailed travel itinerary and budget breakdown.

## Example

Enter your travel destinations (separate by commas):
Paris, London, Rome

Enter start date (yyyy-MM-dd):
2024-05-01

Enter end date (yyyy-MM-dd):
2024-05-10

Enter your travel style (e.g., Adventure, Relaxation):
Adventure

Enter your accommodation preference (e.g., Hotel, Hostel):
Hostel

Enter your daily food budget (in USD):
50

Enter the estimated cost of activities per day (in USD):
100

Enter the estimated daily transportation cost (in USD):
30

--- Travel Itinerary ---
Destinations:
- Paris
- London
- Rome
Travel Style: Adventure
Accommodation Preference: Hostel
Start Date: 2024-05-01
End Date: 2024-05-10
Total Number of Days: 10

--- Budget Calculation ---
Estimated Food Cost: $500.00
Estimated Activity Cost: $1000.00
Estimated Transportation Cost: $300.00
Total Estimated Budget: $1800.00

## Error Handling

-Ensure that dates are entered in the yyyy-MM-dd format.
-Enter numeric values for costs and budgets.
