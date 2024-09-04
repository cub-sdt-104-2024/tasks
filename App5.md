# Bot Fighter

Imagine a stream of web site visit logs, with the IP addresses, timestamps and visited page urls. Some of the visits are made by humans, and some by bots, whose behavior is different from the humans. 
Humans usually follow the same path through the web site pages, e.g. they first access the landing page, spend approximately the same considerable time reading the landing page text and then proceed to the 
signup page or to the pricing, where either stop or also spend approximately the same considerable amount of time before going to the other pages.

The bots are rather dumb, and they access the site pages pretty randomly, and spend less time than humans on the site pages.

The task is to detect anomalies in real time and plot the graphs with the total number of all, human and bot visits in the last 5 minutes window. 
Once the application sees that there has been more bots than humans on the site in the last 5 minutes, it should print a message.

