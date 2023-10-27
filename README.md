# Pyourly

## Efficient Air-Quality Index Monitoring System

### Abstract

The Pyourly project aims to revolutionize the way individuals monitor and protect themselves from exposure to harmful air pollutants by developing a portable, high-quality Air Quality Index (AQI) sensor and monitoring system that provides _real-time feedback_. Pyourly sets itself apart from existing solutions by offering _offline_ capabilities and addressing the limitations of current techniques, while highlighting the _critical health risks_ associated with prolonged exposure to poor air quality.

### Shortcomings of Current Techniques

Current techniques for monitoring air quality often fall short in several ways. Traditional stationary AQI monitoring stations are expensive, limited in scope, and cannot offer personalized information to individuals. Portable monitors are often inaccurate or unreliable, while mobile apps may rely on a constant internet connection, limiting their utility in areas with poor connectivity. These limitations hinder individuals' ability to make informed decisions about their exposure to harmful air pollutants.

### Health Risks Associated with Air Pollution

Exposure to poor air quality poses both short-term and long-term health risks. Short-term effects include aggravated respiratory conditions, allergic reactions, headaches, and fatigue. Prolonged exposure increases the risk of developing chronic health issues such as asthma, cardiovascular diseases, and even certain types of cancer. Therefore, the importance of monitoring and avoiding overexposure to bad air quality cannot be overstated.

### Features

1. Highly sensitive and **portable** sensing system with continuous readings of Air Quality Index (AQI) throughout the day, to monitor the user's risk fo over-exposure to air pollution.
2. Detects over-exposure and sends a personable warning notification to the user, enough to alert them, but not stress them out.
3. Display a history of the user's surrounding AQI and analysis and visualization of the same.
4. While the integrated sensor reads the AQI inside the room, AQI of the surroundings is fetched from [OpenWeatherMap API](https://openweathermap.org/api/air-pollution) and the comparison is displayed to the user, through a graphical visualization of the surrounding area, marking the different AQIs.
5. The integrated sensor data is synced on [Microsoft Azure Cloud](https://azure.microsoft.com/) for storage and analysis, securely, protecting the user's privacy.
6. With the hardware, based on a **Raspberry Pi**, the UI for the software is available as a beautiful, interactive, easy-to-use and mobile-friendly web-app, which is light to download.

### Technologies Used

1. Raspberry Pi Microprocessor
2. An Air Quality Sensor
3. **IoT** - ThingSpeak API to post and fetch the air quality data.
4. ReactJS, Progressive Web App (PWA), HTML, CSS
5. Python, used for coding Raspberry Pi
6. Microsoft Azure for user authentication and storage of data.

### What sets us apart?

Here's how Pyourly is a cut above similar apps in the segment:

1. **Low Latency & Optimized System**: The standalone system is optimized for low latency readings to be available to the user about the air quality conditions nearby.
2. **Better UI/UX**: Pyourly stands out with its interactive user interface which keeps users engaged and also informs them about the indoor and outdoor air quality and how can they get pure and good air.
3. **Low Cost**: Because of the selection of the most suitable hardware i.e., Raspberry Pi and an Air Quality Sensor, we reduce the price of the product.
4. **Accurate Measurements**: The use of quality sensors and data validation techniques to identify and eliminate erroneous or inconsistent data points, ensuring that only accurate measurements are considered.
5. **User Privacy and Security**: The user data and history would be stored with encryption retrieved securely, without leaking and additional information about the user. Also, 2FA ensures a safe option for users to log in.

### Offline Features of the App:

Storing data locally when there is no internet connectivity, providing historical data and trends, allowing users to set up alerts for certain air quality thresholds, and offering educational content on air quality and its impact on health.

### Our Motto

With PYourly, our aim is to help users efficiently monitor their surrounding air quality and at the same time spread awareness about respiratory health issues related to air pollution, while encouraging users to pratice habits to create a future with cleaner air, healthier lungs and where each breath brings a smile to people's faces.
