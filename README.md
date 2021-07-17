# Burp-Suite--Try-Hack-me
#Task 4



# Q: Which tool in Burp Suite can we use to perform a 'diff' on responses and other pieces of data?

A:Comparer

# Q:What tool could we use to analyze randomness in different pieces of data such as password reset tokens?

A:Sequencer

# Q:Which tool can we use to set the scope of our project?

A:Target

# Q:While only available in the premium versions of Burp Suite, which tool can we use to automatically identify different vulnerabilities in the application we are examining?

A:Scanner

# Q:Encoding or decoding data can be particularly useful when examining URL parameters or protections on a form, which tool allows us to do just that?

A:Decoder

# Q:Which tool allows us to redirect our web traffic into Burp for further examination?

A:Proxy 

# Q:Simple in concept but powerful in execution, which tool allows us to reissue requests?

A:Repeater

# Q:With four modes, which tool in Burp can we use for a variety of purposes such as field fuzzing?

A:Intruder

# Q:Last but certainly not least, which tool allows us to modify Burp Suite via the addition of extensions?

A:Extender 

#Task 6

# Q:By default, the Burp Suite proxy listens on only one interface. What is it? Use the format of IP:PORT

A:127.0.0.1:8080

# Q : Return to your web browser and navigate to the web application hosted on the VM we deployed just a bit ago. Note that the page appears to be continuously loading. Change back to Burp Suite, we now have a request that's waiting in our intercept tab. Take a look at the actions, which shortcut allows us to forward the request to Repeater?

A:Ctrl-R

# Q: How about if we wanted to forward our request to Intruder?

A: Ctrl-I

#Q: Burp Suite saves the history of requests sent through the proxy along with their varying details. This can be especially useful when we need to have proof of our actions throughout a penetration test or we want to modify and resend a request we sent a while back. What is the name of the first section wherein general web requests (GET/POST) are saved?


A: HTTP history

# Q: Defined in RFC 6455 as a low-latency communication protocol that doesn't require HTTP encapsulation, what is the name of the second section of our saved history in Burp Suite? These are commonly used in collaborate application which require real-time updates (Google Docs is an excellent example here).

A: websocket history

# Q: Before we move onto exploring our target definition, let's take a look at some of the advanced customization we can utilize in the Burp proxy. Move over to the Options section of the Proxy tab and scroll down to Intercept Client Requests. Here we can apply further fine-grained rules to define which requests we would like to intercept. Perhaps the most useful out of the default rules is our only AND rule. What is it's match type?

A: URL

Q: How about it's 'Relationship'? In this situation, enabling this match rule can be incredibly useful following target definition as we can effectively leave intercept on permanently (unless we need to navigate without intercept) as it won't disturb sites which are outside of our scope - something which is particularly nice if we need to Google something in the same browser.

A: Is in target scope  // I knew in Target scope but this answer format is so....

# Task 7
# Q: What is the term for browsing the application as a normal user prior to examining it further?

A: site map

# Q: What is the term for browsing the application as a normal user prior to examining it further?

A: happy path

# Q: The issue definitions found here are how Burp Suite defines issues within reporting. While getting started, these issue definitions can be particularly helpful for understanding and categorizing various findings we might have. Which poisoning issue arises when an application behind a cache process input that is not included in the cache key?

A: Web Cache Poisoning

# Task 8

# Q: Try logging in with invalid credentials. What error is generated when login fails?

A: Invalid email or password

# Q: Now that we've sent the request to Repeater, let's try adjusting the request such that we are sending a single quote (') as both the email and password. What error is generated from this request?

A: SQLITE_ERROR

# Q: What field do we have to modify in order to submit a zero-star review?

A: rating

# Task 9

# Q: Which attack type allows us to select multiple payload sets (one per position) and iterate through them simultaneously?

A: Pitchfork

# Q: How about the attack type which allows us to use one payload set in every single position we've selected simultaneously?

A: Battering Ram 

# Q: Which attack type allows us to select multiple payload sets (one per position) and iterate through all possible combinations?

A:  Cluster Bomb

# Q: Perhaps the most commonly used, which attack type allows us to cycle through our payload set, putting the next available payload in each position in turn?

A: Sniper

# Q: Finally, click 'Start attack'. What is the first payload that returns a 200 status code, showing that we have successfully bypassed authentication?

A: a' or 1=1--

# Task 10

# Q: Parse through the results. What is the effective estimated entropy measured in?

A: bits

# Q: In order to find the usable bits of entropy we often have to make some adjustments to have a normalized dataset. What item is converted in this process?

A: token

# TASK 11

# Q: What character does the %20 in the request we copied into Decoder decode as?

A: space

# Q: Similar to CyberChef, Decoder also has a 'Magic' mode where it will automatically attempt to decode the input it is provided. What is this mode called? 

A:smart decode

# Q: What can we load into Comparer to see differences in what various user roles can access? This is very useful to check for access control issues.

A: site maps

# Q: Comparer can perform a diff against two different metrics, which one allows us to examine the data loaded in as-is rather than breaking it down into bytes?

A:words

# TASK 12

# Q: Which extension allows us too bookmark various requests?

A: Bookmark

# TASK 13

# Q:Download the report attached to this task. What is the only critical issue?

A: Cross-origin resource sharing: arbitrary origin trusted

# Q: How many 'Certain' low issues did Burp find?

A: 12

# TASK 14

# Q: Done


