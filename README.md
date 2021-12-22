# weather
weather forecast
<!DOCTYPE html>

<html lang="en">

  <head>

    <meta charset="UTF-8" />

    <title>Weatherly</title>

    <link rel="stylesheet" href="style.css" />

  </head>

  <body>

    <div class="container">

      <div class="app-title">

        <p>Weather forcast</p>

        <input

          id="search"

          type="text"

          placeholder="Enter city..."

          autocomplete="off"

        />

        <div class="location-icon">

          <img src="location.jpg" alt="" />

        </div>

      </div>

      <div class="notification"></div>

      <div class="weather-container"></div>

        <div class="temperature-value">

          <p>- °<span>C</span></p>

        </div>

        <div class="temperature-description">

          <p>-</p>

        </div>

        <div class="location">

          <p>-</p>

        </div>

      </div>

    </div>

    <script src="app.js"></script>

  </body>

</html>
