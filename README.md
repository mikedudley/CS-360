# CS-360

## Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The Weight Tracker app was developed to help users monitor their progress toward a weight-loss or fitness goal. Users can create an account, securely log in, record their weight, update existing entries, delete records, and receive optional SMS notifications when they come within one pound of their goal weight. The application was designed to provide an organized and convenient way for users to track their progress over time.

## What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The application includes a login screen, a weight tracking screen, and an SMS notification settings screen. The login screen allows users to create an account or sign in, while the weight tracking screen provides an easy way to add, update, and delete weight entries displayed in a table. The SMS screen allows users to enable notifications if they choose. The interface was designed to be simple, intuitive, and easy to navigate by grouping related features together and using clear labels and buttons. These design choices helped create a user-friendly experience.

## How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

I approached the project by developing one feature at a time instead of attempting to build the entire application at once. I first implemented user authentication, then created the SQLite database, followed by the CRUD functionality and SMS notifications. Building and testing each component individually made debugging much easier. This incremental development approach can be applied to larger software projects because it helps reduce complexity and makes it easier to identify problems.

## How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

I tested the application frequently using the Android Emulator throughout development. After implementing each feature, I verified that it functioned correctly before moving on to the next task. I tested creating user accounts, logging in, adding weight entries, updating entries, deleting records, and confirming that data remained in the database after restarting the application. I also tested both granting and denying SMS permissions to verify that the application behaved correctly in each situation. This testing process helped identify issues early and ensured that all required functionality worked as expected.

## Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

One of the biggest challenges was connecting the SQLite database to the weight tracking table so that the information displayed dynamically instead of using static sample data. I solved this by generating table rows programmatically and connecting them to the database, allowing users to create, update, and delete entries while keeping the user interface organized. Breaking the problem into smaller tasks helped me successfully complete this portion of the project.

## In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I believe the strongest part of my application was the SQLite database implementation. Successfully creating persistent user accounts, implementing CRUD operations for weight entries, and connecting the database to the user interface demonstrated my understanding of Android development concepts. This project also strengthened my experience with user interface design, activity navigation, runtime permissions, and testing, giving me greater confidence in developing mobile applications.
