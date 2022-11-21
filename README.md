# SocialHistorian
Utilities to aid social network portability.

## Manifesto
[Human-centric networking](https://scafaria.com/planning-the-human-centric-web-1bcd2b275a81) requires portability of our social connections. Social networks are required by the laws of multiple countries to give you access to an archive of your data. However, after waiting up to a day for your archive file (if it ever arrives), you will find (in the case of Twitter) that it contains only IDs of the relationships that you forged. Those IDs are only usable within the system itself, falling short of the requirement to repatriate your data.

Sure, there are third-party applications who will provide your own data back to you, usually for a fee. All you have to do is trust them with access to your account. This is crazy. You're scrolling through your data every day. It would be securely preserved for free if you (a) had a photographic memory or (b) took a recording of yourself scrolling through your follower lists. 

## So What is This?
This is open-source free-to-use code to scroll through your follower list while recording the account names *solely for yourself*; as you'll see from reviewing the code, no data leaves your computer. 

## How to extract Twitter follower/following lists
1. (optional) Consider using a special-purpose twitter account instead of your main account.
2. (optional) Open an incognito or private-browsing tab. 
3. Navigate to a page such as https://twitter.com/scafaria/following
4. Open your browser's [console window](https://appuals.com/open-browser-console/) or via the key combination Ctrl + Shift + I for windows or Command + Option + K for Mac.
5. Copy the code from [here](https://raw.githubusercontent.com/PositiveSumNet/SocialHistorian/main/Twitter/follows.txt) to your clipboard. 
6. Reminder to review code carefully before running it. As you'll see, this code sends *no data* externally. 
7. Place your cursor at the console run line as indicated [here](https://github.com/PositiveSumNet/SocialHistorian/issues/1).
8. Paste the code that's on your clipboard and hit Enter to run it!
9. If you're using Firefox, you'll be asked to consent to pasting code. If you're using Chrome or Edge, you'll be asked (within about a minute) whether to allow downloading multiple files. Please agree to continue.
10. Once you're done scrolling through your list, TADA! You should have a set of files in your 'downloads' folder. Coming soon - we'll help you get this list into an Excel format and to connect with your friends even when they use other networks!

## Manual option
The most conservative approach from a terms-of-use standpoint is to scroll manually. If you're a stickler, you can achieve this by finding the lines that start with
"window.scrollBy" and add to slashes in front of them "// window.scrollBy". Then sroll a bit manually every second or so. 
