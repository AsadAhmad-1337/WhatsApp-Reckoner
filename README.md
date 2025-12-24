# WhatsApp-Reckoner-v1.1
A WhatsApp number scanner that generates pakistani mobile numbers randomly and then checks if the generated numbers are registered on WhatsApp if found then it fetches corresponding profile pictures, profile names along with number.

This tool is a poc based on this article: 

https://www.wired.com/story/a-simple-whatsapp-security-flaw-exposed-billions-phone-numbers

![Image Alt](https://github.com/AsadAhmad-1337/WhatsApp-Reckoner/blob/4f8c2fb9ac7db7cf14ade31840803540d3ea8d76/whatsapp-reckoner.png)

# Features

   # </> Number Generation

   ➔ Random area code (300–349)

   ➔ Random digits for uniqueness


   # ⚠︎ WhatsApp Data Checking


   ➔ Extracts profile pictures 

   ➔ Extracts the user’s WhatsApp display name
   
   ➔ Extracts the user’s WhatsApp number 
   

   # 👥 Image Handling

   ➔ Downloads profile images

   ➔ Checks if image already exists (existing_images) to avoid duplicates

   ➔ Saves images to IMAGES_DIR

   # ❯❯❯❯ Persistent Progress

   ➔ Progress is saved in progress.json

   ➔ Keeps track of found_profiles

   ➔ no_img.json stores numbers that have no images

   ➔ Ensures that when the script is restarted, progress resumes from the last saved state  


   # 👩🏻‍💻 GUI 

   ➔ Found Profiles

   ➔ Downloaded Images

   ➔ Progress bar with percentage.

   ➔ Verbosity window: Shows logs for each number scanned.
