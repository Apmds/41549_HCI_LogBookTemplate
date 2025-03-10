[Back to main Logbook Page](../hci_logbook.md)

---
# C. Requirement Definition
>	Based on all the gathered context, including an understanding of current practices, competitors, and user feedback and expectations: 
>	- summarize the user characteristics, context, and motivations using Personas
>	- explain your vision for a novel solution that will target user motivations using Scenarios
>	- identify requirements


## Persona: Emma Walton 
### Summary 
| Attribute        | Details                                       |
| ---------------- | --------------------------------------------- |
| **Photo**        | <img src="personas/persona2.jpg" width="80">  |
| **Name**         | Emma Walton                                |
| **Age**          | 30                               |
| **Occupation**   | Travel Blogger                           |
| **Location**     | London, UK                               |
| **Goals**        | Find new exciting reads without the burden of carrying around too many books           |
| **Pain Points**  | Logistics of tranporting books              |
| **Motivation**   | Make reading part of her jouney in a practical way              |
| **Full Profile** | [📄 Read More](personas/persona2_Emma.md) |

---
## Persona: Peter Smith
### Summary 
| Attribute        | Details                                       |
| ---------------- | --------------------------------------------- |
| **Photo**        | <img src="personas/persona3.jpeg" width="80">  |
| **Name**         | Peter Smith                              |
| **Age**          | 58                                |
| **Occupation**   | Bartender                           |
| **Location**     | Quebec, Canada                               |
| **Goals**        | Find new books to read and free up space taken by old ones. |
| **Pain Points**  | Difficult schedule to trade books. Not tech-savvy. |
| **Motivation**   | Give new use to old books and read new ones. |
| **Full Profile** | [📄 Read More](personas/persona3_Peter.md) |

---
## Persona: Maya Wu
### Summary 
| Attribute        | Details                                       |
| ---------------- | --------------------------------------------- |
| **Photo**        | <img src="personas/persona1.jpeg" width="80">  |
| **Name**         | Maya Wu                              |
| **Age**          | 22                                |
| **Occupation**   | Student                           |
| **Location**     | Jacarta, Indonesia                               |
| **Goals**        | Save money and give new use to academic books not used anymore. |
| **Pain Points**  | Difficulty in finding afordable and accessible books for her classes. |
| **Motivation**   | Save time searching for books so she can focus in the main goal: studying. |
| **Full Profile** | [📄 Read More](personas/persona1_Maya.md) |

---



# Scenarios

## Scenario 1: Exploring local literature in Buenos Aires
Emma Walton, a travel blogger and book lover, is visiting Buenos Aires, Argentina, for two weeks, for explore its literary and cultural heritage. She has heard that Buenos Aires has a deep literary history, with famous authors like *Jorge Luis Borges*, and she wants to dive into their works. She visits El Ateneo Grand Splendid, a famous book store hoping to find a book by an Argentine author in English. But since she is always traveling, **it's difficult to carry many books with her**, so she prefers to exchange a book from her last trip instead of buying a new one.

She goes into the app and searches for the book *Ficciones* she found in the bookstore. A few results appear and she chooses one, which happens to be by a literature student from Germany who is also exploring Argentina. They chat through the app and agree to meet at a nearby cafe later to swap books.


## Scenario 3: Peter drops off a book
Since Peter works late hours, meeting up with people to trade books becomes tricky. When searching for an interesting book, he finds out that the app has special **drop-off spots** - locations such as cafés or grocery shops.

After finding a book that seemed interesting, he struck a deal by offering one of his old detective novels in the trade. They then decided to use one of the cities cafés as the drop-off spot, each giving an estimate of when they could **deliver** the books there. After an agreement was made, the trade was scheduled.

The next day, Peter decides to leave in the morning to deliver his book to the café. After arriving, he **confirms his identity** to the attendant and leaves his novel with them. Later in the afternoon, his phone recieves a **notification** - the book he was to recieve in the trade has arrived in the café and is ready to be **picked up**. So, before going to work, he passes by the café to pick up his new book. The cashier asks him again for his identity and hands him the book, making him recieve **another notification** on his phone that the trade was completed successfully.


## Scenario 4: Maya exchanges school books
Maya has just started a new semester, and her professors have released the list of required textbooks. She checks the prices online and quickly realizes that **buying them all brand new would be far too expensive**. She sighs and opens a few second-hand book marketplaces but finds that many of the listings are outdated or already sold.

Frustrated, she decides to check the university library, but unfortunately, **only a limited number of copies are available**, and all have **already been borrowed**. She doesn’t have the time to wait on a long reservation list. Maya then spends an hour searching for free digital versions, but the PDFs she finds are either incomplete or unreliable.

Feeling overwhelmed, she finds out about our book trading app and starts searching for her required textbooks, finding other students who are looking for her last year's textbooks. After setting up meetings with them, she is able to aquire most of the books, but some of them are still missing.

She then sees an option in the app for a **whishlist**, and decides to add the books she needs for her classes to hers. The next day, her phone vibrates, sending her a notification that Dharma.
After finding a couple people who also want her books she chats with them and sets up a meeting where they will exchange their books, saving both of them money they can spend on better things while getting the books they need.

---


# Requirements


## C.1. Functional requirements

- Create an account.
    - Username.
    - Password.
    - General location.
    - Favourite genres.

- Search books by name.
- Search books by categories (genre, length, distance to owner).
- Sort search results.

- Send and recieve text and audio messages to/from another user in real time.
- Schedule a meeting place/drop-off spot for the trade.
- Review another user after executing a trade with them.
- Create posts.
    - Add a title.
    - Add a description.
    - Add images.
    - Set information about the book. (number of pages, condition) 

- Add a book to a wishlist.
- Notify the user:
    - When a post about a book from the wishlist exists nearby.
    - When the book from a trade is available at the drop-off spot.
    - When someone messages them.

- Block a user.
- Report a user for one or more reasons.

## C.2. Non-functional requirements
- The UI must be easy to navigate for people of all levels of technical proficiency.
- The system should be available without downtime during the day, having room for downtime during the night.
- The system should support multiple chats simulatenously.
- The users information should be stored in a cryptographycally secured way.

---
[Back to main Logbook Page](../hci_logbook.md)