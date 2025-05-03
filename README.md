
This code creates a user directory application with the following core functionalities:

Fetches user data from an API (https://dummyjson.com/users).
Filters users by name, city, and age.
Highlights the oldest user in each city.
Displays data in a user-friendly interface (including loading/error states).
Technologies Used
React + TypeScript
API calls with axios
Performance optimization using useMemo and useEffect
Purpose
Data Filtering & Analysis

Search users by name or city.
Identify oldest users per city (e.g., for regional age statistics in a company).
User Experience

Implements debounce to prevent unnecessary API calls during searches.
Shows loading animations and error messages for clarity.
React Best Practices

Component-based structure.
Controlled state management and side effects.
Key Features
Dynamic City Filter: Auto-populates cities from API data.
Performance: Optimized filtering/calculations with useMemo.
Responsive Design: Mobile/desktop compatibility via grid layout.
Use Cases:

Internal employee directories.
Demographic analysis tools.
Educational material for API integration examples.
