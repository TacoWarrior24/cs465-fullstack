# CS465-fullstack
SNHU CS 465 fullstack development with MEAN

# Architecture

This project utilized the Handlebars templating framework, which allowed us to create individual HTML pages. This architecture was highly effective in easily creating a functional website. Personally, I favored the Single Page Application (SPA) I developed using Angular. As for the database choice, MongoDB was implemented because of noSQL functionality. This type of database is particularly well-suited for managing unstructured documents, which aligns with the requirements of this project.

# Functionality

JSON, short for JavaScript Object Notation, is a versatile format that offers readability for both machines and humans. In the context of this website, the data is commonly converted to JSON format, serving as a crucial link between the backend and the displayed content on the front end. In the development of the Single Page Application (SPA), several features underwent refactoring into components. For example, the navigation bar was extracted into its own distinct component, as was the trip card, which encapsulates the trip's contents within a card structure. This approach enables the reuse of different parts as needed. By utilizing the trip card component, it becomes possible to create a single component that can wrap multiple trips seamlessly.

# Testing

The majority of testing done for this project involved utilizing Postman to test various API endpoints. Due to certain features relying on additional components to be fully displayed on the front end, using Postman proved to be a more efficient approach. It allowed for thorough verification of the functionality of the implemented API endpoints. When incorporating security measures, an additional layer of complexity arises. It becomes necessary to have a verified user in order to adequately test the effectiveness of the implemented security measures.

# Reflection

I can truly say I learned a lot throughout this course. As someone who had zero prior Angular experience, I found myself enjoying learning about Anuglar and its functionality. However, the most significant lesson I have learned from this course relates to backend development. While I had some prior understanding of backend concepts, this project provided me with a wealth of new information, particularly regarding API endpoints. Considering my career aspirations as a full-stack engineer or front-end engineer, this class has proven to be invaluable in helping me achieve those goals.
