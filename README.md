# python_image_scraper

A python program that scrapes a url and returns the image urls of all images on the page

You must first install requests and bs4 in the folder you're using the scraper in.
"pip install requests"
"pip install bs4"

You must run "imagescraper.py" in the same folder as "input.json"

The input format is this:
{

  "COMMAND": "SCRAPE",
  "TARGET": "https://www.geeksforgeeks.org/"
  
}

The image urls will be exported to a file that is created that is called "output.json"

It's format:
{"COMMAND": "SCRAPE_SUCCESS", "URLS": ["https://media.geeksforgeeks.org/wp-content/cdn-uploads/write_ndi_20210312.svg", "https://media.geeksforgeeks.org/wp-content/cdn-uploads/practice_ndi_20210312.svg", "https://media.geeksforgeeks.org/wp-content/cdn-uploads/premium_ndi_20210312.svg", "https://media.geeksforgeeks.org/wp-content/cdn-uploads/jobs_ndi_20210312.svg", "https://media.geeksforgeeks.org/wp-content/uploads/20211101150314/GetHiredWithGeeksforGeeksandWinExcitingRewards.png", "https://videocdn.geeksforgeeks.org/geeksforgeeks/BuildingaTicTacToeGameinFlutter/BuildingaTicTacToeGameinFlutter20211106191155-small.png", "https://videocdn.geeksforgeeks.org/geeksforgeeks/HowtoImplementRESTAPIinFlutterApplication/HowtoImplementRESTAPIinFlutterApplication20211102200103-small.png", "https://videocdn.geeksforgeeks.org/geeksforgeeks/RecyclerViewinAndroidwithExample/RecyclerViewinAndroidwithExample20211031214811-small.png", "https://videocdn.geeksforgeeks.org/geeksforgeeks/HowtoImplementLottieAnimationinFlutterApplication/HowtoImplementLottieAnimationinFlutterApplication20211031121548-small.png", "https://videocdn.geeksforgeeks.org/geeksforgeeks/HowtoChangetheWholeAppLanguageinAndroid/HowtoChangetheWholeAppLanguageinAndroid20211029185259-small.png", "https://videocdn.geeksforgeeks.org/geeksforgeeks/LanguageTranslatorUsingGoogleAPIinPython/LanguageTranslatorUsingGoogleAPIinPython20211105203021-small.png", "https://videocdn.geeksforgeeks.org/geeksforgeeks/SendingEmailsusingPython/SendingEmailsusingPython20211101213836-small.png", "https://videocdn.geeksforgeeks.org/geeksforgeeks/SimplePlagiarismDetectionusingPython/SimplePlagiarismDetectionusingPython20211028104548-small.png", "https://videocdn.geeksforgeeks.org/geeksforgeeks/FloatingActionButtoninFlutterwithAnimation/FloatingActionButtoninFlutterwithAnimation20211024200045-small.png", "https://videocdn.geeksforgeeks.org/geeksforgeeks/HowtoUploadaProjectonGitHubFromAndroidStudio/HowtoUploadProjectonGitHubfromAndroidStudio20211023202303-small.png", "https://media.geeksforgeeks.org/wp-content/cdn-uploads/20210609101834/GC-LIve-Icon-1.png", "https://media.geeksforgeeks.org/wp-content/cdn-uploads/20210727192049/CP_ad_icon.png", "https://media.geeksforgeeks.org/wp-content/cdn-uploads/20211025231638/CIP_Icon1.png", ""]}
