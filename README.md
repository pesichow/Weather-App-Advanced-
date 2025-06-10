# Weather-App-Advanced-
This submission completes the requirements for Tech Assessment 2 of the AI Engineer Intern position at Product Manager Accelerator.

🔧 Tech Stack Used:
- HTML, CSS, JavaScript (Frontend)
- Node.js + Express.js (Backend)
- MongoDB (NoSQL Database)
- OpenWeatherMap API (Weather data)
- Additional APIs (Optional): Google Maps, YouTube
- JSON/CSV export functionality
- Optional: Bootstrap for layout/styling

🚀 Features Implemented:

✅ 2.1 CRUD Operations (Mandatory Requirement)
----------------------------------------------
✔️ CREATE:
- Users can enter a location (City name, ZIP, GPS, etc.) and a date range.
- The app fetches temperature data for that range using OpenWeatherMap API.
- Data is validated and saved in MongoDB (location, date, weather info).

✔️ READ:
- Users can view all weather logs stored in the database, including past entries.
- Entries are displayed in a readable format on a /logs route.

✔️ UPDATE:
- Users can update any weather log (e.g., change location, date range).
- Input validation ensures updates are accurate and locations are real.

✔️ DELETE:
- Users can delete any saved weather entry from the database with a single click.

✅ 2.2 Optional API Integrations
----------------------------------------------
- Integrated YouTube API: Shows travel/weather-related videos for the selected location.
- Integrated Google Maps API: Displays a map view of the entered or matched location.
- Fuzzy location matching is implemented for flexible user input.

✅ 2.3 Optional Data Export
----------------------------------------------
- Weather data can be exported in the following formats:
  - JSON
  - CSV (Comma-separated)
  - Markdown (Optional)

💡 Additional Notes:
- Includes browser geolocation support to fetch current location weather.
- All routes and operations include basic error handling for failed API calls, invalid dates, or location issues.
- Interface includes:
  - My full name: **Pallapothu Prasad**
  - An info button linking to PM Accelerator's LinkedIn page.

📁 Files Included:
- `index.html`, `style.css`, `script.js`
- `server.js` (Express backend)
- `weatherController.js`, `weatherModel.js` (MongoDB schema + logic)
- `routes.js` (CRUD routes)
- `README.md`, `package.json`, `.env.example` (API key usage)

📝 PMA Requirement:
- Info button provided on UI linking to PM Accelerator LinkedIn page.
- Clear mention of developer name "Pallapothu Prasad" in both UI and code.

🎥 Demo Video:
- A screen recording video link showing the app in action will be shared in the submission form as required.

Let me know if you need any help running the app or reviewing the code.
