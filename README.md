# darkRed
A dark theme for node-red editor

     _            _    ____          _
  __| | __ _ _ __| | _|  _ \ ___  __| |
 / _` |/ _` | '__| |/ / |_) / _ \/ _` |
| (_| | (_| | |  |   <|  _ <  __/ (_| |
 \__,_|\__,_|_|  |_|\_\_| \_\___|\__,_|
_______[darkTheme for NODE-RED]________

    1. Copy 'dark.css' on your desire route
    
    2. Call 'dark.css' from your 'settings.js'
    
        // Customising the editor
        editorTheme: {
            page : {
            css: '/myRoute/dark.css'
            } 
        }
        
    3. Overwrite your 'theme-tomorrow.js' with content of 'theme-tomorrow-mod.js'
         location : 'node-red-folder/node_modules/node-red/public/vendor/ace/theme-tomorrow.js'
         

    
    ** Remember change '/' for '\' in your routes (if you use windows os)
    ** If you desire conserve code-editor style (white background, etc) simply omit step 3.
