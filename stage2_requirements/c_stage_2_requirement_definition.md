[Back to main Logbook Page](../hci_logbook.md)

---
# C. Requirement Definition

---
## Persona: Peter Walton
### Summary 
| Attribute        | Details                                       |
| ---------------- | --------------------------------------------- |
| **Photo**        | <img src="personas/persona.jpeg" width="80">  |
| **Name**         | Peter Walton                              |
| **Age**          | 58                                |
| **Occupation**   | Bartender                           |
| **Location**     | Quebec, Canada                               |
| **Goals**        | Find new books to read and free up space taken by old ones. |
| **Pain Points**  | Difficult schedule to trade books. Not tech-savvy. |
| **Motivation**   | Give new use to old books and read new ones. |
| **Full Profile** | [📄 Read More](personas/persona_Peter.md) |

---


# Scenarios

## Scenario 1: Peter explores Quebec's local literature
Peter’s interest in detective fiction has recently led him to explore classic Canadian and French-language authors. While browsing in the local library, he notices a section featuring regional literature. Unfortunately, the library does not have **English translations** for most of the books he wants.

Back at home, he opens the book trading app and searches for ***The Crime on Cote des Neiges***, a local detective story he saw at the library. He finds a few listings and notices one from another local user who recently finished the book and is looking for a **Raymond Chandler** novel, which Peter has just finished.

He then messages the user through the app they meet up the next day. They agree to do the swap at the bar Peter works at, right before his shift. The next day the trade is completed smoothly, and Peter gets to enjoy his new read.

Afterward, he leaves the user a generous review.


## Scenario 2: Peter drops off a book
Since Peter works late hours, meeting up with people to trade books becomes tricky. When searching for an interesting book, he finds out that the app has special **drop-off spots** - locations such as cafés or grocery shops.

After finding a book that seemed interesting, he struck a deal by offering one of his old detective novels in the trade. They then decided to use one of the cities cafés as the drop-off spot, each giving an estimate of when they could **deliver** the books there. After an agreement was made, the trade was scheduled.

The next day, Peter decides to leave in the morning to deliver his book to the café. After arriving, he **confirms his identity** to the attendant and leaves his novel with them. Later in the afternoon, his phone recieves a **notification** - the book he was to recieve in the trade has arrived in the café and is ready to be **picked up**. So, before going to work, he passes by the café to pick up his new book. The cashier asks him again for his identity and hands him the book, making him recieve **another notification** on his phone that the trade was completed successfully. Peter then gives a  review to the other person since his book arrived on time and was in good condition.


## Scenario 3: Peter adds new books to his wishlist
During a quiet shift at the bar, Peter hears a conversation about a new collection of **Detective Jordan Carr** books. After engaging with the people talking, he becomes interested in the main plot points and reminds himself to look for them.

Back at home, he finds the **ISBN** of the new books and goes **searching** for them in the book trading app. As the books are new, nobody has put them up for trading on the app yet.

Not wanting to buy even more books, he decides to open the app's **wishlist** and adds all the books of the collection there.

A week later, while browsing Facebook, his phone buzzes with a **notification**: the first book of the collection was posted by another user in Quebec!

After opening the app again, he starts chatting and both settle on a trade that day at the bar, while Peter is working. Finnaly, he can start this new collection without paying for anything.

---


# Requirements


## C.1. Functional requirements

- Create an account.
    - Username.
    - Password.
    - General location.
    - Favourite genres.


- Allow login and logout of an account.
- Have the possibility to reset the password.
- Permanently delete the account.
- Edit profile informations (name, photo, localization, favourite genres).

- Search books by name.
- Search books by categories (genre, book length, distance to owner, ISBN).
- Sort search results.

- Send and recieve text and audio messages to/from another user in real time.
- Allow user to know if a message has been seen by the receiver.
- Allow user to offer one of their books to trade.
- Schedule a meeting place/drop-off spot for the trade.
- See the history of trades.
- Check the status of a trade (pending, ongoing, done).
- Review another user after executing a trade with them.
- Create posts.
    - Add a title.
    - Add a description.
    - Add images.
    - Set information about the book. (number of pages, condition). s

- Add a book to a wishlist.
- Notify the user:
    - When a post about a book from the wishlist exists nearby.
    - When the book from a trade is available at the drop-off spot.
    - When someone messages them.

- Block a user.
- Report a user for one or more reasons.
- Cancel a trade.
- See all current active trades.

## C.2. Non-functional requirements
- The UI must be easy to navigate for people of all levels of technical proficiency.
- The system should be available without downtime during the day, having room for downtime during the night.
- The system should support multiple chats simultaneously.
- The users information should be stored in a cryptographycally secured way.
- The system should do regular backups to prevent losses of information
- The application must be available on mobile devices

---
[Back to main Logbook Page](../hci_logbook.md)