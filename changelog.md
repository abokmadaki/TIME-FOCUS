# Changelog
## Changes made
### script.js:
- [Major] Removed "SetInterval(ShowTime, 1000) from showTime function which caused infinite calls to this function and crashed the webpage after a while. SetInterval was moved to "// Run" section.
- Removed white space between "MM:" and "SS" (HH:MM:SS instead of HH:MM: SS)
### index.html
- Changed main page title from "Document" to "TimeFocus"
- Added " min" after focus input field to make it more understandable for the user