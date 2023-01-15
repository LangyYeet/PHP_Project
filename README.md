# Password Generator API
- This is a simple API for generating random passwords. 
- The API has one endpoint "/generate_password" which accepts two parameters "length" and "include_symbols". 
- The output is returned as a JSON object containing the generated password.

# Requirements
- PHP 7.0 or higher
- Web server software (such as Apache or Nginx)

# Installing
- Clone or download the repository to your local machine.
- Place the contents of the repository in the document root directory of your web server.
- Make sure that the web server is configured to handle PHP files.

# Usage
To use the API, make a GET request to the endpoint "/generate_password.php" with the following query parameters:
- "length": an integer representing the length of the generated password.
- "include_symbols": a boolean value indicating if the password should include symbols or not.
