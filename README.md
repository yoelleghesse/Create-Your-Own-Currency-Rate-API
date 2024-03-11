The Currency Rate API is a Flask-based web service that provides real-time exchange rates between currencies. It utilizes web scraping techniques to fetch exchange rate data from the X-Rates website and exposes a simple API for querying exchange rates between different currency pairs.

- Fetches exchange rate data from X-Rates website.
- Supports querying exchange rates between different currency pairs.
- Exposes a RESTful API for easy integration with other applications.

Clone the repo:

``git clone https://github.com/your-username/currency-rate-api.git``

Install the dependencies:

``pip install Flask BeautifulSoup4 requests``

Run the app:
``python app.py``

Access the API endpoint in your web browser or make HTTP requests to it:
Example URL: http://localhost:5000/api/v1/usd-eur
(This will fetch the exchange rate from USD to EUR.)

The application is configured to run on localhost by default. You can modify the app.run() call in app.py to change the host and port settings.
