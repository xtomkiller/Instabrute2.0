# Instabrute2.0

This Python code is a script for brute-forcing Instagram account passwords. Here's a summary of its functionality and key features:

User Interface: The script provides a simple command-line interface for interacting with the user.
Banner Display: It displays a banner with the title "Instagram Brute Force" using ASCII art when the script starts.
Internet Connection Check: It checks whether the internet connection is available or not. If the internet connection is online, it displays a message in green font; otherwise, it displays a message in red font and exits the script.
Username Validation: It checks whether the provided target username is valid or not by making a request to the Instagram login page. If the username is invalid (not found on Instagram), the script stops further execution.
Wordlist Attack: It performs a brute-force attack on the Instagram account using a provided wordlist of passwords. It iterates through the wordlist and tries each password until the correct one is found or the list is exhausted.
Proxy Support: It supports the use of proxies for anonymizing the requests. Proxies can be specified in a file, and the script rotates through them during the attack to avoid detection.
Password Guessing: It generates password candidates based on the current timestamp and tries them in combination with other parameters in an attempt to guess the correct password.
Response Handling: It handles various types of responses from the Instagram server, such as successful authentication, incorrect password, and other error messages.
Feedback to User: It provides feedback to the user during the attack, indicating progress, status, and any errors encountered.
Output Logging: It logs the tried passwords and any successful hacks to respective files for later reference.
Overall, this script provides a basic framework for performing a brute-force attack on Instagram accounts, incorporating features for user interaction, response handling, and error management.
