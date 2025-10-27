# Operating-Platforms

1.	Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
   
The Gaming Room wanted to create a web-based version of their game Draw It or Lose It. Their goal was to allow multiple teams and players to compete online from different devices while keeping everything organized and responsive. Each game, team, and player needed a unique ID, and the system had to ensure there was only one instance of the game service in memory at a time. The client wanted something scalable, secure, and easy to maintain so it could grow with future demand.

2.	What did you do particularly well in developing this documentation?

I think I did well describing the architecture and explaining how the object-oriented design supported the client’s needs. My write-up clearly showed how each class and relationship fit together, including how the Singleton pattern maintained centralized control of the game data. I also did a good job outlining the pros and cons of each operating system for both client and server use, showing how a dual-platform approach made sense for development and deployment.

3.	What about the process of working through a design document did you find helpful when developing the code?

Working through the design document helped me slow down and think through how everything connected before jumping into coding. It gave me a clear plan to follow and made the development phase much smoother. By laying out the system architecture, UML diagram, and requirements early on, I was able to spot potential issues ahead of time. It also helped keep the project organized and gave me a reference to check back on whenever decisions needed to be made.

4.	If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I were to revise anything, I would expand the section on scalability and distributed systems. I touched on cloud-based deployment and load balancing, but I could add more detail about handling real-time communication and performance monitoring. Including visuals like a network topology diagram or sequence diagram could make those ideas even clearer.

5.	How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

I interpreted the user’s needs by breaking down their main goals into specific requirements. For example, they wanted multiple teams and players to interact smoothly, so the design included unique identifiers and controlled access through the Singleton pattern. It’s important to keep the user’s needs front and center because the design should solve their problem, not just meet technical expectations. Building around the user experience helps ensure the product is useful, reliable, and enjoyable to interact with.

6.	How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

I approached this project by focusing on object-oriented design and scalability from the start. Techniques like encapsulation, inheritance, and polymorphism helped organize the structure and reduce repetition. I also used UML diagrams to visualize relationships and data flow. In the future, I’ll continue using this kind of structured approach while adding more cloud architecture planning and testing considerations early in the design process. It helps build stronger systems that can grow and adapt without needing major redesigns later.
