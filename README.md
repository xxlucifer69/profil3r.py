💡 Prerequisite
Python 3
Installation
Install PyInquirer, jinja2 and bs4 :
pip3 install PyInquirer jinja2 bs4
Install Profil3r :
git clone https://github.com/Rog3rSm1th/Profil3r.git
cd Profil3r/
sudo python3 setup.py install
Features
📙 Domain
 TLD (.com, .org, .net, etc...)
 ✉️ Emails
  Data leaks
 Emails
 🌐 Social
 Service	Profile Scraping
Instagram	Yes ✔️
Facebook	No
Twitter	Yes ✔️
Tiktok	No
Pinterest	No
Linktr.ee	Yes ✔️
MySpace	 Yes ✔️
Flickr	 Yes ✔️
🎵 MusicService	Profile Scraping
Soundcloud	No
Spotify	No
‍💻 Programming
Service	Profile Scraping
Github	Yes ✔️
 Pastebin	Yes ✔️
 Repl.it	No
Cracked.to	No
💬 Forum
Service	Profile Scraping
0x00sec.org	No
Hackernews	Yes ✔️
Jeuxvideo.com	Yes ✔
🗣️ Tchat
Service	Profile Scraping
Skype	No
📺 Entertainment
Service	Profile Scraping
Dailymotion	No
Vimeo	No
🚫 Porn
Service	Profile Scraping
PornHub	Yes ✔
RedTube	No
XVideos	No
💸 Money
Service	Profile Scraping
BuyMeACoffee	No
Patreon	No
Report
JSON
A report in JSON format is automatically generated in the reports/json folder

CSV
A report in CSV format is automatically generated in the reports/csv folder

HTML
A report in HTML format is automatically generated in the reports/html folder, you can access it in your webbrowser



⚙️ The config.json file
You can modify the paths of the reports, the separators and the services Profil3r will search by default in the config.json file
Field	Type	Default	Description
report_elements	Array	["email", "facebook", "twitter"]	List of the services for which profil3r will search
json_report_path	String	"./reports/json/{}.json"	The path of the report's JSON file, this path must include a {} which corresponds to the file name
html_report_path	String	"./reports/html/{}.html"	The path of the report's HTML file, this path must include a {} which corresponds to the file name
csv_report_path	String	"./reports/csv/{}.csv"	The path of the report's CSV file, this path must include a {} which corresponds to the file name
separators	Object	{"Dot": ".", "Dash": "-", "Underscore": "_"}	List of separators to separate items, for example: john.doe, john-doe, john_doe

📚 Example
python3 profil3r.py -p john doe
📝 License
This project is under the MIT license.
Contact
twitter https://twitter.com/Technicalsadiig
