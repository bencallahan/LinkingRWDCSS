LinkingRWDCSS
=============

Linking RWD CSS, Examples

These are four ways to link RWD styles.

#Single CSS File
- Simple to implement
- Single request
- Doesn’t require a preprocessor
- Requires JS to serve large layout to old IE if starting with small layouts 
- Large sites can be difficult to maintain because of the size of
the single file


#Multiple CSS Files
(http://adactio.com/journal/4494/)
- Doesn’t require a preprocessor
- At least two requests
- Requires you to separate layout from other styles
- Allows you to start with small layouts and serve a single large layout to old IE without JS (requests go up if you use multiple MQs)


#Breakpoint Based Partials
- Allows you to start with small layouts and serve large layout to old IE without JS
- Only 1 or 2 requests
- Requires preprocessor
- Maintenance can be complex


#Module Based Partials
- Single Request
- Easy Maintenance
- Allows you to start with small layouts and serve large layout to old IE without JS
- Single request for all
- Requires Preprocessor