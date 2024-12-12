# Weather Extension

#### Video Demo: [Add Your Video URL Here]

---

## **Description**

The Weather Extension is a lightweight browser extension that provides users with real-time weather updates for any location worldwide. It integrates seamlessly into your browser, offering a quick and reliable way to check the current weather conditions and forecasts without needing to open a separate app or website.

### Key Features
- **Real-Time Weather Updates:** Instantly displays the current temperature, humidity, and weather conditions for your chosen location.
- **Search Functionality:** Easily search for weather details by city name or geolocation.
- **Customizable Interface:** Choose between light and dark themes for better visibility.
- **Detailed Forecasts:** View hourly and weekly forecasts at a glance.

The project addresses the need for quick, accessible weather information, making it perfect for daily planning and travel.

---

## **Technology Stack**

- **Programming Languages:** JavaScript, HTML, CSS
- **Frameworks/Libraries:** None (Vanilla JS used for simplicity)
- **API:** OpenWeatherMap API for fetching real-time weather data
- **Tools:** Visual Studio Code, Chrome Developer Tools

---

## **Directory Structure**

```plaintext
weather-extension/
├── README.md          # Documentation for the project
├── manifest.json      # Extension manifest file
├── popup.html         # HTML for the extension popup
├── popup.js           # JavaScript logic for the popup
├── styles.css         # Styling for the extension
├── icons/             # Icons used for the extension

```

---

## **Setup Instructions**

To install and use the Weather Extension:

1. **Clone the Repository:**
   ```bash
   git clone [repository-url]
   ```
2. **Navigate to the Project Directory:**
   ```bash
   cd weather-extension
   ```
3. **Load the Extension in Your Browser:**
   - Open your browser and navigate to the extensions page (e.g., `chrome://extensions/` for Chrome).
   - Enable "Developer mode."
   - Click "Load unpacked" and select the `weather-extension/` folder.

4. **Test the Extension:**
   - Click on the extension icon in your browser toolbar.
   - Enter a city name or allow location access to fetch the weather data.

---

## **Design Choices**

- **API Selection:** OpenWeatherMap was chosen for its comprehensive and reliable weather data.
- **User Interface:** Designed with simplicity in mind, ensuring a clean and intuitive experience for all users.
- **Responsiveness:** The popup layout adjusts to various screen sizes, enhancing usability across devices.

---

## **Challenges Faced**

1. **API Rate Limits:** Implemented caching to minimize unnecessary API calls.
2. **Browser Compatibility:** Tested and resolved issues across different browsers to ensure consistent functionality.
3. **Dynamic Data Rendering:** Used JavaScript efficiently to update the UI in real-time based on API responses.

---

## **Future Enhancements**

- Add severe weather alerts and notifications.
- Integrate air quality index data.
- Allow users to save multiple favorite locations.
- Support additional languages for a broader audience.

---

## **Acknowledgments**

- **OpenWeatherMap API:** For providing the weather data.
- **MDN Web Docs:** For invaluable resources on web development.
- **CS50x Staff:** For their guidance and support throughout the course.

---

### **Contact**

For any questions or feedback, feel free to reach out:

- **Name:** [Your Name]
- **GitHub:** [Your GitHub Username]
- **Email:** [Your Email Address]

---

> **Disclaimer:** This project was created for educational purposes as part of the CS50x program and is not intended for commercial use.
