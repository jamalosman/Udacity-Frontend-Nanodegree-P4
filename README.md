## Website Performance Optimization portfolio project

In order to meet the 90 page score, I optimised the Critcal Rendering Path by
- Using the async attribute for non-render critical scripts (print.css)
- compressed images to reduce file size 
- Removed the web fonts (they were causing too much slow-down)
Pagespeed score was 90+ for mobile and desktop

In the Pizza page, I made some code optimizations to some thecode
- remove forced synchrounous layout inducing code from loops
- decrease the number moving pizzas to they just about fill the screen
- factor our determineDx()

To run the project, simply:
- Deploy locally (using pythons SimpleHTTPServer or any other tool)
- install ngrok and tunnel your http server port
- get the link from ngrok and paste it into PageSpeedInsights
- open pizza.html in the broswer, check out chrome's dev tools and measure the speed