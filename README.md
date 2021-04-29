# What is this?
*A jar extension (also called module) for the MacroKeybindingMod, compiled for the minecraft version '1.12.x'.*

*Place the '.jar'-file of this module in the directory '.minecraft/liteconfig/common/macros' to inject the corresponding actions and variables into the JVM at the start of the game.*

# Documentation
*The 'char();'-action stores the respective unicode of an integer value (2nd parameter) within a string variable (first parameter, or return value).*

## Added Actions
><p>char(&str,\<intCharValue\>);</p>
><p>&str = char(\<intCharValue\>);</p>

## Added Environmental Variables
><p>// Returns 'True' if the module has been installed and loaded correctly.</p>
><p>%MODULECHARICE%</p>  
>
><p>// Shortcut for the 'paragraph'-character ('char(167);').</p>
><p>%P%</p>

><p>// Returns a single dollar-character ('$').</p>
><p>%DOLLAR%</p>

><p>// Returns two dollar-chracters ('$$').</p>
><p>%DOLLARS%</p>





