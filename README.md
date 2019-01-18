# C2Pin
JS将中文转化为拼音首字母字符串的小插件

# Installation #
 **Direct download**

Download the script here and include it (unless you are packaging scripts somehow else):

`<script src="/path/to/c2pin/index.js"></script>`

**Package Managers**

C2Pin supports npm and Bower under the name  c2pin

**Import the library**

`import C2Pin from 'c2pin'`

# Basic Usage 



Transfer Chinese to Pinyin with first letter

`C2Pin.firstChar()`

Transfer Chinese to Pinyin with full letter

`C2Pin.fullChar()`


# Namespace conflicts

If there is any danger of a conflict with the namespace C2Pin, the noConflict method will allow you to define a new namespace and preserve the original one.

    // Assign the C2Pin api to a different variable and restore the original "window.C2Pin"
    var C2PinCopy = C2Pin.noConflict();
    C2Pin.firstChar();