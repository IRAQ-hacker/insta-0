# Insta-0 Tool

# closed for 6 Month ok (:

The Insta-0 Tool gets a range of information from an Instagram account that you normally wouldn't be able to get
from just looking at their profile

The information includes:


1. Username
2. Profile Name
3. URL
4. Followers
5. Following
6. Number of Posts
7. Bio
8. Profile Picture URL
9. Is Business Account?
10. Connected to a FB account?
11. External URL
12. Joined Recently?
13. Business Category Name
14. Is private?
15. Is Verified?
16. Downloads Public Photos

# Usage
Note: You must use python3.6 or greater due to the use of "f" strings

1. `pip3 install -r requirements.txt`
2. `python3 main.py --username USERNAME`


Please note that InstagramOSINT.py is for importing as python module, this is for use in custom applications and not to be run from the command line



# Output

The output format is a dict/json inside of a txt file in the directory created for the profile that you scanned


# API insta-0 Usage

This is useful when trying to apply this codebase to any projects. The API is really simple to use and uses python features to make it easier to use such as indexing

Examples:

`from InstagramOSINT import *`

`instagram = InstagramOSINT(username='USERNAMEHERE')`

`print(instagram.profile_data)`

`print(instagram['Username'])`

`instagram.print_profile_data()`

`instagram.save_data()`

`instagram.scrape_posts()`


follow me in :

[![30%](https://img.shields.io/badge/account%20-%20telegram-blue)](https://t.me/iiwiw)

[![30%](https://img.shields.io/badge/channel-intelegram-yellow)](https://t.me/professional_school)

[![30%](https://img.shields.io/badge/subscribe%20-%20YouTube-red)](https://youtube.com/channel/UCCgmIKpPgUOQauZ3IvrchBA)

- Dev ReKuShE


# Disclaimer 

I am not responsible for anything you do with this tool that could be considered illegal. Do not break the law!
