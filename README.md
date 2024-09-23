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

### linkedIn profile: **Kacper Dudzik**

<h1 align="center"><strong>CODE EXPLANATION:</strong></h1>

```python
def get_valid_input(prompt, valid_responses):
    response = input(prompt).strip()
    while response not in valid_responses:
        print(f"Invalid choice! Please enter one of: {', '.join(valid_responses)}.")
        response = input(prompt).strip()
    return response
```

# Python Code in a Table

| Function       | Description                 | Example Code                            |
|----------------|-----------------------------|------------------------------------------|
| `greet(name)`  | Prints a greeting message   | `print(f"Hello, {name}!")`               |
| `add(a, b)`    | Returns the sum of `a` and `b` | `return a + b`                          |
| `factorial(n)` | Computes factorial of `n`   | <code>def factorial(n):<br>&nbsp;&nbsp;&nbsp;&nbsp;if n == 0:<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;return 1<br>&nbsp;&nbsp;&nbsp;&nbsp;else:<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;return n * factorial(n-1)</code> |

<h1 align="center"><strong>USEFUL LINKS:</strong></h1>

### [Link Text](https://example.com)
<a href="https://example.com">Click here to visit example.com</a>

<h1 align="center"><strong>PHOTOS OF RESULTS:</strong></h1>

#### ![Alt Text](https://github.com/KacperDudzik/findmyclothes-API/blob/main/test%20-%20clothing7.jpg)
<img src="https://github.com/KacperDudzik/findmyclothes-API/blob/main/test%20-%20clothing7.jpg" alt="Project Logo" width="300"/>

<h1 align="center"><strong>FURTHER USAGE OF THE CODE:</strong></h1>

### this code is restricted from copy rights under the **LICENSE.txt** file!
