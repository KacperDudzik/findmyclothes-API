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

<h1 align="center"><strong>Some of the most important function distribution:</strong></h1>

| Function       | Description                                                                                      | Example Code                                                                                                                                                                                                                                                                   |
|----------------|--------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `get_valid_input(prompt, valid_responses)` | Prompts the user for input and validates it against a list of acceptable responses. | <code>def get_valid_input(prompt, valid_responses):<br>&nbsp;&nbsp;&nbsp;&nbsp;response = input(prompt).strip()<br>&nbsp;&nbsp;&nbsp;&nbsp;while response not in valid_responses:<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;print(f"Invalid choice!")<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;response = input(prompt).strip()<br>&nbsp;&nbsp;&nbsp;&nbsp;return response</code> |
| `webscraping_and_llm(web)` | Scrapes a webpage using Selenium and processes the HTML with an LLM to extract specific data.  | <code>def webscraping_and_llm(web):<br>&nbsp;&nbsp;&nbsp;&nbsp;options = Options()<br>&nbsp;&nbsp;&nbsp;&nbsp;options.add_argument("--lang=en")<br>&nbsp;&nbsp;&nbsp;&nbsp;driver = webdriver.Chrome(options=options)<br>&nbsp;&nbsp;&nbsp;&nbsp;driver.get(web)<br>&nbsp;&nbsp;&nbsp;&nbsp;# Further processing...</code> |
| `check_link_validity(link)` | Validates a link by performing a search to confirm its accuracy and accessibility.  | <code>def check_link_validity(link):<br>&nbsp;&nbsp;&nbsp;&nbsp;driver = webdriver.Chrome(options=chrome_options)<br>&nbsp;&nbsp;&nbsp;&nbsp;driver.get('https://www.google.com')<br>&nbsp;&nbsp;&nbsp;&nbsp;search_box.send_keys(link)<br>&nbsp;&nbsp;&nbsp;&nbsp;# Further validation...</code> |
| `encode_image(image_path)` | Encodes an image in base64 format, which is useful for embedding images in JSON. | <code>def encode_image(image_path):<br>&nbsp;&nbsp;&nbsp;&nbsp;with open(image_path, "rb") as image_file:<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;return base64.b64encode(image_file.read()).decode('utf-8')</code> |


<h1 align="center"><strong>USEFUL LINKS:</strong></h1>

### [Link Text](https://example.com)
<a href="https://example.com">Click here to visit example.com</a>

<h1 align="center"><strong>PHOTOS OF RESULTS:</strong></h1>

<div style="display: flex; justify-content: space-between;">
    <img src="https://github.com/KacperDudzik/findmyclothes-API/blob/main/test%20-%20clothing5.jpg" alt="Image 2" width="300"/>
    <img src="https://github.com/KacperDudzik/findmyclothes-API/blob/main/test%20-%20clothing7.jpg" alt="Project Logo" width="300"/>
    <img src="https://github.com/KacperDudzik/findmyclothes-API/blob/main/test%20-%20clothing9.jpg" alt="Image 3" width="300"/>
</div>


<h1 align="center"><strong>FURTHER USAGE OF THE CODE:</strong></h1>

### this code is restricted from copy rights under the **LICENSE.txt** file!
