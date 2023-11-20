# Instragram-Bot-Python
Simple Instagram Bot in Python automating basic interactions and tasks for streamlined user engagement.

import instaloader
insta=instaloader.Instaloader()
acc='paste your insta account name'
insta.download_profile(acc, profile_pic_only=False)
