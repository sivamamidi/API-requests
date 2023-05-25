# Random User API Data Extraction

This repository contains code to extract information from the Random User API using Python and the requests library. The code demonstrates how to make requests to the API endpoint and retrieve data in JSON format. It also showcases how to extract specific information from the JSON response.

## Code Explanation

1. Making a Request to the API:
   - The code uses the `requests.get()` function to make a GET request to the Random User API endpoint.
   - The response is stored in the `response` variable.

2. Extracting Information from the JSON Response:
   - The JSON response is converted to a Python dictionary using `response.json()`.
   - The relevant data is extracted from the dictionary by accessing nested keys.
   - The extracted information includes the user's name, last name, gender, and email.

3. Printing the Extracted Information:
   - The code iterates over the results in the response and prints the extracted information for each user.
   - The user's name, gender, and email are displayed using formatted print statements.

4. Optional: Filtering Users by Gender:
   - The code demonstrates an optional step to filter the API response by gender.
   - By appending a query parameter to the API endpoint URL (e.g., `?gender=female`), you can retrieve users of a specific gender.

## Usage

1. Clone the Repository:
git clone https://github.com/your-username/your-repo.git

2. Install Dependencies:
- Make sure you have Python and the requests library installed.
- You can install the required dependencies using pip:
  ```
  pip install requests
  ```

3. Run the Code:
- Open the cloned repository in your preferred Python environment.
- Run the code in a Python script or Jupyter Notebook.
- Modify the code as needed for your specific use case.

Feel free to explore and adapt the code to suit your requirements. Enjoy extracting data from the Random User API!

