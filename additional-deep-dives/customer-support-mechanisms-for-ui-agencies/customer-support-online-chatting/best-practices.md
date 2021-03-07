# Best practices

### User Experience and Visual Design

* **Availability:** For your chat system to have the most impact, you should make sure that the chat is available on any/all pages of your site \(or sites!\) that get meaningful traffic by people who might be looking for help with unemployment insurance. This would include any separate sites you might have for: 
  * UI Agency administration
  * Standard/PEUC UI management
  * PUA UI management
  * Re-employment services and support
* **Some design basics:**
  * Don't call it "live" if it's a bot or virtual agent, either in the chat itself or in content that references it. This sets the wrong expectation for people and might lead them to be more likely to provide private information even if it is not appropriate for them to do so. 
  * The first message from the system should be short and to the point. Make sure that it is fully visible within the interface without the customer having to scroll. This means that the chat's "header" should be relatively narrow, and that there aren't large images or large blocks of text.
  * If content is split into multiple messages, then leave some time in between message sends for the person to at least register that there are multiple messages, if not fully read one message before the next one gets sent
  * For prompted chats, make it easy for users to get back to the "main menu" so that people can get multiple questions answered or change their mind about an answer response.

### Data-informed implementation and iteration

When implementing a chat or chat-like experience for your UI agency, you need to prepare a list of likely questions and acceptable answers. This Q&A list is used to build the decision tree and responses for Prompted Chat, to prepare agents for Live chat, to prepare Free-text chat to understand a variety of inputs, and to provide answers for all those chat types as well as "support chat.

You should prepare your system to handle 15-20 questions or scenarios very well, and have clear paths for people to find more information on other topics. There are many kinds of data you can leverage to inform this initial Q&A set, for example:

* **From your IVR system:** what branches are most commonly used?
* **From your call center:** what are common topics of calls? What questions are they answering over and over again?
* **From your claims agents:** what mistakes are they seeing people make, or misunderstandings people have?

All of this data is useful in other ways, too, as you look to make more fundamental improvements to your UI system. E.g., if people frequently ask about their claim status, you could consider prioritizing work to make that possible online \(or if it's already possible, to move it to a more expected location or change the language around it to make it clearer\).

Regardless of the type of chat, you should make sure to have metrics in place to track the effectiveness of the tool and make changes moving forward. As economic conditions, policies, and your benefits website change, the chat experience needs to be kept up-to-date.

* **Effectiveness measures:**
  * CSAT for tracking people's satisfaction with the response they got
  * After the chat thinks it has done its job, you can have it ask, "Did that answer your question?" For making changes, you should keep an eye in particular on the sequence of back-and-forths that lead up to someone's question _not_ being answered - though don't forget to celebrate all the times that it did answer someone's question!
* **"Engagement" metrics:** e.g., button clicks, messages sent, clicks on outbound links
* Time spent: for chats other than live chat, how much time are people spending interacting with the tool?
* **Language analysis:** for chats that let users input any text they want - what are they asking for that the system doesn't understand?

