<pre>
     _            _    ____          _
  __| | __ _ _ __| | _|  _ \ ___  __| |
 / _` |/ _` | '__| |/ / |_) / _ \/ _` |
| (_| | (_| | |  |   <|  _ <  __/ (_| |
 \__,_|\__,_|_|  |_|\_\_| \_\___|\__,_|
_______[darkTheme for NODE-RED]________

[ABOUT]
    
The intention of 'darkRed' is not to be a nice-theme, but a practical-theme.
The idea was to make heavy use of NODE-RED for some time and feel
the difference with predominant black color on my screen
in the day to day (code editor, shell, etc).
To my eyes, it was a small impact.
I hope this little hack can help
any lover of development over dark environment.

[INSTALLATION]
   
1. Copy 'dark.css' on your desire route

2. Call 'dark.css' from your 'settings.js'

   // Customising the editor
   editorTheme: {
       page : {
       css: '/myRoute/dark.css'
       } 
   }

3. Overwrite your 'theme-tomorrow.js' with content of 'theme-tomorrow-mod.js'
   > location : 'node-red-folder/node_modules/node-red/public/vendor/ace/theme-tomorrow.js'
   > final name must be 'theme-tomorrow.js'

[NOTES]

** Remember change '/' for '\' in your routes (if you use windows os)
** If you desire conserve code-editor style (white background, etc) simply omit step 3.
** This is a basic version while all the details are added, I'm sorry.
</pre>
<img src="./screenshot_darkred.png">  

