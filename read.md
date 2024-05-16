# PHP Server Setup and Wireshark Command

## Starting PHP Server
To start the PHP server locally, use the following command:

php -S localhost:8000
This command will start a PHP server on localhost (127.0.0.1) on port 8000. You can then access your PHP files via a web browser at http://localhost:8000.

Wireshark Command for POST Requests
If you want to filter POST requests in Wireshark, you can use the following display filter:

Wireshark Command
http.request.method == "POST"

This filter will display only HTTP packets where the request method is POST. You can apply this filter in Wireshark to analyze POST requests in your network traffic.
