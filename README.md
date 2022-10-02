<div align="center">
<img src="https://cdn.pixabay.com/photo/2016/08/08/10/49/watercolour-1578076_960_720.jpg" alt="" width="700" />

# The PillowTweezers WA Bot

</div>

> Welcome to our humble and nice little Whatsapp bot!
It was written in mind of the users and participants of the group and tries to comply as much as possible with WhatsApp bs anti-bot/anti-fun rules.

# Features

| Covid-19 | Availability |
| :------: | :----------: |
| Covid statistics | ✔ |
| Covid statistics on a settlement| ✔ ️|
| Covid statistics on a country| ✔ ️|

| Sticker Maker | Availability |
| :-----------: | :----------: |
| Image to sticker | ✔ ️|
| Video to sticker | ✔ ️|
| GIF to sticker | ✔ ️|

| Admin Tools | Availability |
| :-----------: | :----------: |
| Tag-All | ✔ ️|
| Block user | ✔ |
| Unblock user | ✔ |

| Games | Availability |
| :---: | :----------: |
| Trivia | ✔ |



| Fun Commands | Availability |
| :----------: | :----------: |
| Random Number | ✔ |
| Sentiment processing<br>of message | ✔ | 
| Generate random name<br>from Israel's records | ✔ | 
| Gimatria equivalents<br>finder | ✔ | 
| Joke generator | ✔ |
| Love calculator | ✔ |
| Tip generator | ✔ |
| TV schedule | ✔ |
| Scouts job generator | ✔ |

| Other Commands | Availability |
| :------------: | :----------: |
| Help menu | ✔ |
| Failsafe command | ✔ |
| Alarm command | ✔ |
| Whatsapp surveys | ✔ |
| Translate command | ✔ |
| Wikipedia article extractor | ✔ |
| Dictionary definition command | ✔ |

| Utility Commands | Availability |
| :--------------: | :----------: |
| Weather report for<br>settlement | ✔ |
| Recording to text | ✔ |
| Text to recording | ✔ |
| Breaking news | ✔ |
| Survey command | ✔ |
& Much more.
# Installation and Usage

### Dependencies:

- Node.js (Only latest is tested)
- Python 3.7 (May work with later versions too)

### Installation:
**tested on win 11 pro** 
**important** install git from [here ](https://git-scm.com/downloads) AND FFmpeg from [here ]( https://github.com/BtbN/FFmpeg-Builds/releases)and also you need to add ffempg to path here is a [tutorial](https://www.thewindowsclub.com/how-to-install-ffmpeg-on-windows-10) 


Clone this project

```bash
> git clone https://github.com/Schwartzblat/sockBot.git
> cd sockbot
```

Install dependencies

```bash
> npm i
```


### Special commands preparation:
#### WhoIs command:
1. Install "me" app on an android device.
2. Install burp on your computer.
3. Use the proxy option and extract from the http requests this tokens: Authorization-token and pwd-token.
4. Put them in the config

#### Api commands:
Just create users in rapid-api and all the sites in the ```config/apiKeys.json```<br>
and subscribe to these APIes (all of them are free).
1. http://www.voicerss.org
2. https://openweathermap.org
3. https://rapidapi.com/spamakashrajtech/api/corona-virus-world-and-india-data
4. https://rapidapi.com/fyhao/api/text-sentiment-analysis-method


### Usage

Start with npm

```bash
> npm start
```

Or with node

```bash
> node lib/bot.js
```
# בעיות אפשריות בהתקנה
לא כל החבילות הותקנו כמו שצריך ולכן אם ההתקלה נכשלת רצוי לנסות להתקין את החבילות שוב **שורה בכל פעם** 

> 
> `npm i @adiwajshing/baileys`
> `pip install SpeechRecognition`
> `pip3 install pydub`

ייתכן שהפקודה `!עצלן` לא תעבוד כראוי אם ה FFmpeg לא מוגדר כמו שצריך במשתנים של ווינדוס ולכן חשוב לעבוד אחרי המדריך [הזה](https://www.thewindowsclub.com/how-to-install-ffmpeg-on-windows-10)



# בדיקת תקינות ההתקנה
הקלד באמצעות מספר טלפון **אחר** את המילה `!עזרה` למספר שעליו רשום הבוט
במידה והכל פעל כשורה תקבלו את הפלט הבא:
רשימת פקודות לבוט:
ו--------------------------------ו
פקודות קורונה
● !קורונה
● !קורונה <ישוב>
● !קורונה <מדינה>
ו--------------------------------ו
יוצר סטיקרים
● !סטיקר- הופך תמונה/סרטון/גיף לסטיקר
● !אהבה @מישהו
● !אהבה @מישהו1 @מישהו2
ו--------------------------------ו
פקודות כיף
● !מספר <n> <n>
● !בדיחה
● !שם
● !גימטריה <ערך>
● !מזל- משפטים של עוגיית מזל
ו--------------------------------ו
פקודות שמגיבים להודעה
● !מחק
● !תוצאות (לסקרים)
● !מכשיר
● !ניתוח - מנתח את הרגשות בהודעה
● !פוליגרף
● !תרגם- מתרגם לעברית
● !הגב <אימוג'י>
ו--------------------------------ו
אחר
● !קוד- לקבלת הקוד לבוט
● !סקר "שאלה" "אופציה א" "אופציה ב"
● !חשב <ביטוי>
● !מיזה <טלפון>
● !אוטו <מספר רישוי>
● !ויקי <ערך>
● !ויקי <מספר> <ערך>
● !פירוש <מילה>
● !מבזק <מספר>
● !תרגם <טקסט>
● !אזעקה <יישוב>
● !עזרה
● !הרשאות
ו--------------------------------ו
כלי עזר
● !תחזית <עיר>
● !עצלן- תמלול הקלטה
ו--------------------------------ו
פקודות משחקים
● !סוף_משחק - מסיים כל משחק
● !בול_פגיעה
● !טריוויה <מספר שאלות>
● !בלקג'ק (רק בפרטי)
ו--------------------------------ו
פקודות מנהלי קבוצות
● !צרף <מספר>
● !הסר <מספר>
● !תייג- מתייג את כל הקבוצה
ו--------------------------------ו
פקודות אדמינים של הבוט
● !הסר <מספר>
● !תגיד <טקסט>
● !כנס- מכניס את הבוט לקישור/הזמנה לקבוצה
● !חסום <מספר>
● !התר <מספר>
● !חירום- מכבה את הבוט


# Thanks

I want to thank my Mama and Pa.
 
