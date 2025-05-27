Google Dorking Tool & Educational Guide
Overview
This project is an educational website designed to inform users about Google Dorking (also known as Google Hacking), an advanced search technique that leverages Google's search operators to find specific information, such as files, vulnerabilities, or exposed data. The website provides a comprehensive guide on Google Dorking, including common operators, the Google Hacking Database (GHDB), and a tool to generate dorking queries. The project emphasizes ethical use and is intended for security professionals and educational purposes only.
Features

Educational Content: Detailed explanations of Google Dorking, its uses, and ethical considerations.
Search Operators Guide: A table of common Google Dorking operators (e.g., site:, filetype:, intitle:) with descriptions and examples.
Google Hacking Database (GHDB): Information on accessing and using the GHDB responsibly, including categories like Files Containing Usernames, Sensitive Directories, and more.
Dorking Tool: An interactive tool allowing users to:
Select predefined dorking techniques (site:, filetype:, intitle:, inurl:, intext:, or custom queries).
Specify domains, file types, or keywords.
Generate and execute Google search queries, with support for opening multiple custom queries in new tabs.


Ethical Guidelines: Clear warnings about the legal and ethical implications of Google Dorking, emphasizing responsible use and proper disclosure practices.

Requirements

A modern web browser (e.g., Chrome, Firefox, Edge) to view and interact with the website.
JavaScript enabled for the dorking tool to function.
Internet access to perform Google searches and access the GHDB at https://www.exploit-db.com/google-hacking-database.

Installation

Clone or download the project repository to your local machine.
Place the GD-Website.html file in a web server directory or open it directly in a browser for local testing.
For local testing, open the file using a file:// URL or a local server (e.g., using Python's http.server module: python -m http.server).


Ensure your browser allows popups for the website if using the custom query feature, as it opens multiple tabs.

Usage

Access the Website:

Open GD-Website.html in a web browser.
Navigate through sections (Introduction, Search Operators, Google Hacking DB, Dorking Tool) using the navigation bar.


Explore Educational Content:

Read the Introduction to understand Google Dorking and its applications.
Review the Search Operators section for a list of operators and examples of complex queries.
Learn about the Google Hacking Database (GHDB) and how to use it responsibly.


Use the Dorking Tool:

Select a dorking technique from the dropdown (e.g., site:, filetype:, intitle:, inurl:, intext:, or Custom Query).
Enter relevant inputs:
For site:, provide a domain (e.g., example.com).
For filetype:, choose a file type (e.g., PDF, DOC, SQL) from the dropdown.
For Custom Query, enter one or more queries (one per line) in the textarea.
Add keywords in the provided input field.


Click the Search button to generate a query (displayed under "Generated Query") and redirect to Google search results.
For custom queries, each query opens in a new browser tab (ensure your popup blocker is disabled if tabs don't open).


Example Queries:

Search for PDFs on a specific site: Select site:, enter example.com, choose filetype: PDF, and add keywords like confidential.
Find login pages: Select inurl:, enter login, and add keywords like admin.
Custom query: Enter site:example.com filetype:pdf intext:"confidential" -policy in the custom query field to search for specific PDFs excluding the word "policy".



Ethical Considerations

Legal Notice: Google Dorking is a legitimate technique for security research but can be illegal and unethical if used to access protected or private information without authorization. Always obtain explicit permission before testing systems you do not own.
Responsible Use:
Use this tool and knowledge for educational purposes or authorized security assessments only.
Report vulnerabilities through proper channels, following responsible disclosure practices.
Do not access, download, or exploit sensitive information.


GHDB Usage: When using the Google Hacking Database, adhere to ethical guidelines and only test systems you have permission to access.

Notes

The dorking tool relies on JavaScript to generate queries and open search results in Google. Ensure JavaScript is enabled in your browser.
If multiple tabs do not open for custom queries, check your browser's popup blocker settings.
The website is designed for educational purposes and does not store or process user data.

Disclaimer
This project is for educational purposes only. The creators are not responsible for any misuse of the information or tools provided. Always adhere to legal and ethical guidelines when using Google Dorking techniques.
Acknowledgments

The Google Hacking Database is maintained by Offensive Security and hosted at https://www.exploit-db.com/google-hacking-database.
This project is inspired by the need to educate security professionals and enthusiasts about safe and ethical search techniques.

