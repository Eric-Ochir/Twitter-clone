Twitter Clone

I developed this project as part of the Scrimba Front-End Career Path to explore dynamic data rendering and interactive state management. The goal was to build a functional social media feed where users can interact with content (Like, Retweet, Reply) and publish new posts in real-time.

Technical Highlights

Implemented a centralized data model in data.js where the UI is a direct reflection of the application state. Any interaction (liking or retweeting) updates the underlying data object before triggering a re-render to ensure data-view synchronization.

Optimized performance by using a single global event listener on the document to handle all user interactions via data-* attributes. This approach reduces memory overhead compared to attaching individual listeners to every tweet and icon.

Integrated the uuid library to generate unique keys for every new tweet, ensuring that interactions target the specific data object without collisions.

Developed logic to dynamically toggle visibility for nested reply sections and apply conditional CSS classes based on the boolean state of specific tweet properties (e.g., isLiked, isRetweeted)

Tech Stack:

HTML5, 
CSS3, 
JavaScript(ES6+), 
Font Awesome, 
Google Fonts
