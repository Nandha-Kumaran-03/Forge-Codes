# Forge-Codes

Requirement: Send WhatsApp messages to multiple contacts personalized according to the group they have been assigned to.

Example Whatsapp Message:
Hi [Name],
You have been alloted to [Group Number],
Your teammates are [teammates names]

What's done:
- The Python scripts uses selenium and chrome web driver to open Whatsapp web in a new chrome session which requies whatsapp login every single time.
- It opens the chat using the link so there is no need to save the number. 
- Sleep time of 10 seconds is set for the chat to load, then the message box is found using the xpath and the message is pasted. 
- Xpath of send button is used to send the message. There is a sleep time of 3 seconds.

- It takes 1 min 13 seconds to send 5 messages. Which implies it would take more than 1 hour for 400 contacts. 

What's to be optimized:
- The time taken for each message to be sent
