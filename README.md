# djangoparser
Tool designed to help identify incorrectly configured Django applications that are exposing sensitive information.

 # Usage
 
Usage: python3 djangohunter.py --key {shodan}

Dorks: 'DisallowedHost', 'KeyError', 'OperationalError', 'Page not found at /'

# Requirements
- Shodan  
- Pyfiglet  
- Requests  
- BeautifulSoup  

pip install -r requirements.txt

# Disclaimer
Code samples are provided for educational purposes. Adequate defenses can only be built by researching attack techniques available to malicious actors. Using this code against target systems without prior permission is illegal in most jurisdictions. The authors are not liable for any damages from misuse of this information or code.
