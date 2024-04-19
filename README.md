## [SDF10] API Learning Reflection 🧠

Welcome to the [SDF10] API Learning Reflection! Through this exercise, you will reflect on key concepts, practical experiences, and the tools you've encountered or used in API interactions.

1. **Understanding and Application**: Reflecting on the key concepts, can you explain in your own words what an API is and its significance in software development? Provide an example of how you have used or encountered an API in a project or a practical scenario.

[Your answer goes here]
APIs are appilication programming interfaces. They are a set of rules, protocols and tools that allow different software appliication to communicate with each other. They play a crucial role in software development as they are used down to the bit level. As a computer only interprets comands on the bit level, languages are used to allow us to maniputlate commands in a more understandable fashion to humans. As a consequence, there has to be a bridge between what is  input from the requesters side to ultimatlely the bit commands the computer runs. These bridges are APIs. AN example would be this keyboard used to edit this READMe file. An API is being used by  pressing a key to display a symbol on the screen. It takes this takes the keystroke command and relays it to the computer in a fashion that it will understand (bits) without us needing to know the nitty gritty of such bit commands. 

2. **Conceptual Distinctions**: How would you differentiate between an interface and an API? 

[Your answer goes here]
Interface is a more proder term and typically applies to user to server interface. Whereas APIs are interfaces specifically used to allow for the server side tasks to be requested in a simpler, more understandable and quiker manner and are generally server to server intefaces. 

3. **Components and Types of APIs**: Can you identify the main components of an API and describe their roles? Reflect on the different types of APIs mentioned (e.g., Web APIs, RESTful APIs) and discuss which type you find most intriguing or useful, and why.

[Your answer goes here]
The main components of an API are:
-Endpionts:
  these are URLs that are used to interact with an API, sepcifically with a functionality or a   resource that the API provides. For example, google maps api will likely have an endpiont      for points of interest or for landmarks.
-Request Methods: 
  AKA HTTP methods. These specify the action to be performed on a resources.   These inlcude     methods such as GET(fetches data), POST(creates new data), PUT (amends       existing data),   and DELETE (removes data).
-Reponse:
  the data retuned by the api after processing a request
-Query Parameters:
  Additional information that can be sent with a request to an API endpoint to provide           specificty for results. This includes filtering or sorting results.
-Headers:
  provide additional informations about the request or the response, such as content type, authentication credentials, or caching directives.
-Authentication:
  APIs can require authentication for use through use of tokens, API keys, etc. this is to 
  provide security over who can access or change certain aspects of an API.
-Error Handling:
  Error messages that display information on troubleshooting. usually in the form of error       status codes, a human-readable message and perhaps suggestions.
There are different types of APIs such as web APIs that are accessed over the web using web protocols and enable communication between different software systems or services over the internet. The architecure under which they are build will be dependent on their use, with the RESTful structure being the predominate style used. Others being GraphQL (query language for APIs that allows for specific data requests) and SOAP. RESTful interests me due to its extensive use in the industry while mainting a simplicty when it comes to designing, maintaining and implementing APIs. It clearly show a seperation between client and server and  the statlessness allows for caching which can impove performance and scalabiity. It seems to be the best overall use case for building flexible web services
   

4. **Practical Application and Tools**: Reflect on your experience with API exploration and implementation. Have you used any specific tools (such as Curl or API exploration tools) or libraries to interact with APIs? 

[Your answer goes here]


5. **Learning and Improvement**: Considering the key concepts and your practical experiences, identify one area related to APIs where you feel confident and one area where you see a need for improvement. What steps will you take to enhance your understanding and skills in the area you wish to improve?

[Your answer goes here]
I feel confident in the function of an API but need beter understanding when it come to the implementaion of it. I will enhance my understanding by continuing to practice using and eventually making them
