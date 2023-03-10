# EmailScarper
Extracting emails from any given website.
Once you input a URL, the code begins processing each URL in the queue ( i put a limit of 100 but you can change that)
For each URL, the code sends an HTTP request and extracts emails. It also uses the BeautifulSoup library to parse the HTML response and extract all anchor tags. It then appends any new URLs found on the current page to the queue for further processing.
Finally, the code prints out all the emails that were extracted from the website.

DISCLAIMER : The code provided above is intended for educational purposes only. The use of this code for any unauthorized or malicious activity is strictly prohibited. The author of this code assumes no liability for any damages or harm caused by the misuse or improper use of this code. It is the responsibility of the user to ensure that any actions taken using this code comply with all applicable laws and regulations. Use at your own risk.
