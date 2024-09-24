<h1 align="center"><strong>FindMyClothes API</strong></h1>

### welcome to my API project! Here you can find an optimized code for the 'FindMyClothes' API:

<h1 align="center"><strong>OVERVIEW OF THE PROJECT:</strong></h1>

The **FindMyClothes** API is an AI-powered app, specifically designed to interactively and effectively improve users online shopping experience.

<h1 align="center"><strong>FEATURES:</strong></h1>

- **AI-Powered Analysis:** Utilizes OpenAI to extract and analyze clothing details from HTML.
- **Web Scraping:** Automates the retrieval of product details using Selenium and BeautifulSoup.
- **Google Search Integration:** Leverages Google Search for finding product links and store locations.
- **Image Analysis:** Converts images to base64 and integrates with OpenAI for clothing analysis.
- **Localization Support:** Detects user's location to suggest nearby stores.

<h1 align="center"><strong>SKILLS I MANAGED TO USE IN THIS PROJECT:</strong></h1>

* **Web Scraping with Selenium and BeautifulSoup:** Automating web browsing, handling dynamic content, and parsing HTML to extract relevant data.
* **Leveraging LLM Models (like OpenAI GPT-4):** For analyzing and extracting information from HTML and images, including prompt engineering.
* **Integration of External APIs:** Including Google Search API, IPinfo API for location services, and Google Maps API for finding stores.
* **Image Processing:** Opening, displaying, and encoding images in base64 for transmission and analysis.
* **Error Handling and Data Validation:** Ensuring robust script execution and accurate data processing.
* **Interactive user inputs:** Making the user experience simplier and detailed
* **Division into Classes and corresponding functions:** 

<h1 align="center"><strong>ADDITIONAL INFO:</strong></h1>

### Ensure you have your environment variables set in a **.env file**
### Example of **.env** file:
OPENAI_API_KEY=your_openai_api_key
GOOGLE_KEY=your_google_maps_api_key
ACCESS_TOKEN=your_ipinfo_access_token

<h1 align="center"><strong>CONTACT:</strong></h1>

### linkedIn profile: [Kacper Dudzik](https://www.linkedin.com/in/kacper-dudzik-b54480293/)
### Instagram account: [Kacper Dudzik](https://www.linkedin.com/in/kacper-dudzik-b54480293/)
### Twitter account: [Kacper Dudzik](https://www.linkedin.com/in/kacper-dudzik-b54480293/)

<h1 align="center"><strong>CODE EXPLANATION:</strong></h1>

HOW WOULD A **FUNCTION** AND PARTICULAR **CODE** EXPLANATION LOOK LIKE: 
```python
# here we create an interactive function for user inputs
def get_valid_input(prompt, valid_responses):
    response = input(prompt).strip()
    while response not in valid_responses: # till our input is not in the range of acceptable answers, then the loop is keep going
        print(f"Invalid choice! Please enter one of: {', '.join(valid_responses)}.")
        response = input(prompt).strip()
    return response
```

<h1 align="center"><strong>Explanation of the presented function :</strong></h1>

| Function       | Description                                                                                      |
|----------------|--------------------------------------------------------------------------------------------------|
| `get_valid_input(prompt, valid_responses)` | Prompts the user for input and validates it against a list of acceptable responses. |
| `webscraping_and_llm(web)` | Scrapes a webpage using Selenium and processes the HTML with an LLM to extract specific data. |
| `check_link_validity(link)` | Validates a link by performing a search to confirm its accuracy and accessibility. |
| `encode_image(image_path)` | Encodes an image in base64 format, which is useful for embedding images in JSON. |
| `search_IP()` | Retrieves the user's location based on their IP address using the IPinfo API. |
| `google_search_for_stores_in_shopping_mall()` | Performs a Google Places API search to find stores in a specified shopping mall. |
| `selenium_with_google_search(keyword)` | Uses Selenium to perform a Google search for a keyword and retrieves relevant URLs. |
| `convert_llm_response_to_accessible_list(llm_response)` | Converts the response from an LLM into a structured list format. |
| `checking_validity_of_all_instances()` | Checks and validates the information obtained from an LLM, comparing it with reference values. |



<h1 align="center"><strong>USEFUL LINKS FOR DOCUMENTATION:</strong></h1>

**DOCUMENTATION:**
### [openai api](https://platform.openai.com/docs/api-reference/introduction?lang=python)
### [google search api](https://developers.google.com/webmaster-tools?hl=pl)
### [IP location api](https://github.com/ipinfo/python)
### [selenium documentation](https://www.selenium.dev/documentation/)
### [string manipulation documentation](https://docs.python.org/3/library/string.html)

<h1 align="center"><strong>PHOTOS OF RESULTS:</strong></h1>

<div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/KacperDudzik/findmyclothes-API/blob/main/test%20-%20clothing5.jpg" alt="Image 2" width="300"/>
    <img src="https://github.com/KacperDudzik/findmyclothes-API/blob/main/test%20-%20clothing7.jpg" alt="Project Logo" width="300"/>
    <img src="https://github.com/KacperDudzik/findmyclothes-API/blob/main/test%20-%20clothing9.jpg" alt="Image 3" width="300"/>
</div>


<h1 align="center"><strong>FURTHER USAGE OF THE CODE:</strong></h1>

### this code is restricted from copy rights under the **LICENSE.txt** file!
