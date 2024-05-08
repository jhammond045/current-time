# current-time

This tiny web application displays the current time in a specified timezone. You can specify the timezone in the URL parameters to see the time in different parts of the world.

## Usage

To use the web app, simply visit the hosted page and specify the timezone in the URL parameters.

Example URL format:

https://yourusername.github.io/current-time/?timezone=America/Los_Angeles

Replace `yourusername` with your actual GitHub username and `America/Los_Angeles` with the desired timezone (you can find a list of supported timezones [here](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones)).

If no timezone is specified, the default timezone will be used (which is set to America/New_York in the code).

## Hosted Page

You can access the hosted page [here](https://jhammond045.github.io/current-time/).

## How it Works

The web app is a simple HTML page with embedded JavaScript. It retrieves the current time using the browser's local time and converts it to the specified timezone using the Intl.DateTimeFormat API.

## Contributing

Contributions are welcome! Feel free to fork this repository, make changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
