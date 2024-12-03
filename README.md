# errand_mapper_essay
Erran Mapper Essay


Every day, people face the challenge of planning efficient routes for errands. Tools like Google Maps and Waze are great at providing directions but fall short in offering flexibility when it comes to chain stores. For example, if you need to visit a McDonald’s, Macy’s, Walmart, and Home Depot, these tools require you to input specific addresses, leaving you to figure out the most efficient sequence manually. Recognizing this pain point, I created Errand Mapper, a tool that simplifies errand planning by automatically finding the optimal route while accounting for chain store flexibility.

Errand Mapper allows users to input general destinations, like chain store names, without needing to specify exact locations. Using APIs such as Overpass and OpenStreetMap, the program identifies nearby branches of the selected chains. Then, leveraging the Open Source Routing Machine (OSRM), it calculates the most efficient route. This approach eliminates the need for tedious manual planning, saving users time and effort.

From a technical perspective, building Errand Mapper was a rewarding challenge. I integrated multiple APIs to handle geocoding, routing, and mapping data. For instance, the Overpass API provided up-to-date store locations, while OSRM solved the complex problem of optimizing routes among flexible destinations. On the frontend, I used React to design an intuitive user interface that makes the application easy to use, even for non-technical users.

Errand Mapper’s impact has been meaningful, especially for friends and family who tested the app. They appreciated the simplicity of inputting chain store names and receiving a fully optimized route without having to search for addresses. This feedback reinforced the value of addressing real-world problems through technology.

Looking ahead, I plan to expand Errand Mapper by developing a mobile app and adding features like calendar integration, reminders, and user preferences. Ultimately, this project taught me the importance of combining technical expertise with a clear understanding of user needs, and it remains one of the most fulfilling endeavors I’ve undertaken.
