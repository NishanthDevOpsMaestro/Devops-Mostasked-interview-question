What is a Stateful Application?
Stateful applications save info about the user’s “state” by keeping track of what they do. This information, like login information and user choices, affects how the user feels about the site. Here are some popular examples of stateful applications:

Online shopping carts that keep track of what you put in them
Banking systems that keep track of account information
Social media sites that display information based on user’s preferences
Now that you know what stateful apps are, let’s talk about their pros and cons.

Pros:

They use the information they’ve saved to give customers what they want, which increases customer engagement.
Remember what the user was doing before and pick up where they left off, retaining useful information and improving the customer journey.
Secure apps save user login and session data, which protects important information.
Cons:

Developers have to work harder to keep state info, which makes it challenging to develop and maintain stateful apps.
Creating a stateful app is not an easy task. It’s hard to keep track of state info across instances.
Stateful apps use more resources, especially memory, and storage, which slows them down.
In the event of a loss, it is hard to get the application back to the way it was because you also have to recover the lost data.
What is a Stateless Application?
Stateless software applications are those applications that do not save information about previous interactions, user sessions, or events. These applications do not preserve context or state between requests in a stateless design.

Some examples of stateless applications are:

HTTP: HTTP is a stateless internet data transfer protocol. Each client-server request and response is treated independently. Cookies and session management are used to keep user data across requests.
RESTful APIs: Networked applications often use Representational State Transfer (REST) architecture. RESTful APIs are stateless; thus, each request has all the information the server needs to process it without relying on prior requests.
Stateless microservices: Stateless microservices perform specified activities without storing state information. Since each instance processes requests independently, adding instances can scale these services horizontally.
