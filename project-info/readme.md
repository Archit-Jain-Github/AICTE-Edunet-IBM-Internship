### How I Created a WhatsApp Chatbot for College Using IBM Cloud and Twilio

#### Step 1: Signing Up to IBM Cloud

**Navigating to IBM Cloud:**

   - I started by creating an IBM Cloud account.
   - After verifying my email address, I completed the registration process and logged in.

#### Step 2: Creating Watson Assistant

**Accessing the IBM Cloud Catalog:**

   - Once logged in, I navigated to the "Catalog" option in the top navigation bar of IBM Cloud.

**Searching for Watson Assistant:**

   - In the catalog search bar, I typed "Watsonx Assistant" and pressed enter.
   - From the search results, I selected "Watsonx Assistant."

**Creating the Watson Assistant Instance:**

   - I reviewed the service details and accepted the license agreement.
   - I clicked on the "Create" button to create a new instance of Watsonx Assistant.

**Launching Watson Assistant:**

   - After the instance was created, I saw a new screen with a "Launch Watson Assistant" button.
   - I clicked on this button to open the Watson Assistant interface.

**Configuring Watson Assistant:**

   - I followed the on-screen prompts to set up my assistant.
   - I provided a name for my chatbot, "My College" and a description, "A chatbot to assist with college information and queries."
   - I selected the option for "Deploying assistant to web."
   - I filled in my details and specified my motive for building the chatbot.

**Customizing the Chatbot Design:**

   - I customized the chatbot’s design, including colors, and other visual elements to match my college's branding.
   - I clicked "Create" to finalize the configuration.

#### Step 3: Defining Actions for the Chatbot

**Creating Actions:**

   - In the Watson Assistant interface, I went to the left-hand panel and clicked on "Actions."
   - I selected "Create" to start defining actions for my chatbot.
   - I defined actions for various intents such as:
     - What Courses are offered?
     - Facility information
     - What Student Support services are available?
     - How can I apply?
     - How can I access counseling services?
     - How do I register for classes?
     - Important academic dates
     - etc...

**Previewing and Testing:**

   - After defining all necessary actions, I went to the "Preview" section.
   - I tested each action to ensure the chatbot responded correctly to various queries.
   - I made adjustments to the actions based on the test results to improve accuracy.

**Publishing the Chatbot:**

   - Once I was satisfied with the chatbot’s performance, I navigated to the "Publish" section.
   - I clicked on the "Publish" button to make my chatbot live.

#### Step 4: Integrating with Twilio for WhatsApp

**Setting Up Twilio Integration in IBM Cloud:**

   - In the Watson Assistant panel, I went to "Environments."
   - I clicked on "Browse Catalog" and searched for "WhatsApp with Twilio."
   - I selected the appropriate integration service and clicked "Create."

**Signing Up to Twilio:**

   - I opened a new browser tab and went to the Twilio website.
   - I clicked on "Sign Up" and followed the on-screen prompts to create a new Twilio account.
   - After verifying my email address, I completed the registration process.
   - I saved my Twilio Account SID and Auth Token for later use.

**Configuring Twilio in IBM Cloud:**

   - I returned to the IBM Cloud tab.
   - I followed the on-screen prompts to enter my Twilio Account SID and Auth Token.
   - I saved the webhook URL provided by IBM Cloud.

**Setting Up WhatsApp in Twilio:**

   - I went back to the Twilio tab.
   - From the left-hand panel, I navigated to "Messaging."
   - I selected "Try it out" under WhatsApp to send a test message.
   - I scanned the QR code provided to link WhatsApp with Twilio.

**Configuring Webhook in Twilio:**

   - I went to "Sandbox Settings" in Twilio.
   - In the "When a message comes in" field, I replaced the existing URL with the webhook URL copied from IBM Cloud.
   - I saved the changes.

#### Step 5: Final Testing and Launch

**Testing the WhatsApp Chatbot:**

   - I sent a test message to my WhatsApp number to ensure the chatbot responded correctly.
   - I tested various queries related to the different intents defined in Watson Assistant to ensure comprehensive functionality.
   - I officially launched the chatbot for use.

---

This is the final output and how the project looks, chatbot for addressing various queries related to college.

![WhatsApp SS](./whatapp-ss/1.jpg)
![WhatsApp SS](./whatapp-ss/2.jpg)
![WhatsApp SS](./whatapp-ss/3.jpg)
![WhatsApp SS](./whatapp-ss/4.jpg)
![WhatsApp SS](./whatapp-ss/5.jpg)

---
