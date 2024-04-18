# Introduction : 

HackQuest presents itself as an innovation in the realm of serious games, drawing inspiration from the iconic television game show "Who Wants to Be a Millionaire?". Its mission is to raise players' awareness of the complexity of cybersecurity challenges. Accessible via a user-friendly web interface, this game offers an immersive dive into scenarios of cyberattacks designed with striking realism, propelling players to the forefront of contemporary digital issues.

The ambition of HackQuest is to provide interactive education, immersing participants in realistic virtual situations related to information systems security. To progress, they must navigate through a series of strategically ordered questions by difficulty level, addressing a variety of cyber threats, from service interruptions such as DoS and DDoS, to spoofing and phishing. As the game's development progresses, the goal is to broaden this range to include a wider spectrum of virtual threats. HackQuest employs playful mechanisms that stimulate not only learning but also knowledge retention, offering an innovative teaching method to approach topics often perceived as challenging or highly technical.

The realization of this project relied on a diverse range of web technologies and data management systems. The frontend of the site, built with standard tools such as HTML, CSS, Bootstrap, and JavaScript, ensures an optimal user experience, fluid and adaptable to various devices. On the backend, the platform relies on a local server orchestrated by Python Flask, associated with SQLite3 for database management. This combination ensures efficient management of user profiles, game history, as well as the database centralizing questions and their answers. This technological choice ensures a stable, secure, and easy-to-maintain platform.

As for the gameplay of HackQuest, it is designed to be intuitive: a clear and streamlined interface accompanies players throughout the steps of account creation or login, opening the doors to their personal space. This space is a true dashboard that summarizes game history and invites players to embark on new challenges. Animated transitions between different questions enrich the visual experience and captivate players' attention, keeping them engaged throughout their gaming journey.

HackQuest also stands out for its strong educational content. Each answer is accompanied by a detailed explanation, whether correct or incorrect, thus deepening the understanding of defense strategies against cyber threats. This educational approach makes HackQuest a powerful awareness tool, transforming each game into a practical lesson on current cybersecurity issues.

This report unveils the meticulous design, rigorous development, and careful implementation of HackQuest, highlighting the challenges overcome and the innovative solutions adopted to shape a first-class educational serious game. We will also evaluate user feedback and the potential impact of this game on raising awareness of cybersecurity among a diverse audience, underscoring the crucial importance of such educational initiatives in today's cybersecurity landscape.

# Objectives and Pedagogical Contributions : 

At the heart of HackQuest, the objective is to generate a revolution in the way individuals perceive and learn cybersecurity. The game is designed to be a vector of knowledge, cleverly disguised as captivating entertainment. By using the interactive dynamics of a game, HackQuest immerses players in realistic cyberattack situations, forcing them to apply concrete solutions to progress through levels. This immersive educational strategy allows players to experience the consequences of their actions in real-time, thus reinforcing the acquisition of essential skills and understanding of cybersecurity in a practical and stimulating environment.

The educational contribution of HackQuest is manifold and distinctive. Firstly, it demystifies cybersecurity, making its fundamental principles and technical complexities accessible to a wide range of users. Players are guided through computer security concepts that are often barricaded behind technical jargon, offering them a clear and usable understanding in their daily and professional lives. Secondly, HackQuest adapts to the user, offering personalized question levels that ensure both beginners and advanced users find a challenge suitable for their expertise.

HackQuest also enriches the learning experience with engaging game mechanics. Players earn points and rewards for correct answers, providing tangible motivation to continue learning and improving. Scenarios based on real-life cyberattacks add a degree of realism and urgency, preparing players to anticipate and respond to digital threats in a real-world context.

Finally, HackQuest serves as a platform for proactive cybersecurity education. By exposing players to diverse and sometimes unpredictable situations, the game encourages the development of critical thinking and problem-solving skills. Each gaming session is an opportunity for players to reflect, analyze, and implement effective defense strategies, thus arming them against current and future digital threats.

HackQuest is not just a game; it is a revolution in digital education, a tool that transforms learning into an adventure and awareness into action. This report will continue to explore the meticulously designed aspects of HackQuest, revealing how this serious game can become a cornerstone in cybersecurity education for all audiences.

# Choice of Technologies Used : 

The choice of technologies used in the development of HackQuest is crucial to ensure the quality, performance, and security of the platform. Here is an overview of each technology and its advantages in this context:

## Frontend :
- ** HTML (HyperText Markup Language) :** It is the standard markup language for creating web pages. It allows structuring the content of the page.
- ** CSS (Cascading Style Sheets) :** This is a style sheet language used to define the presentation of an HTML document. It controls layout, colors, fonts, etc.
- ** Bootstrap :** Bootstrap is a CSS framework developed by Twitter. It offers a responsive layout grid and predefined components to accelerate development.
- ** JavaScript :** It is a scripting programming language mainly used to make web pages interactive. It is used to create dynamic features on the frontend.

## Backend :
- ** Python Flask :** Flask is a lightweight web micro-framework in Python. It is lightweight and easy

 to use, making it ideal for small web applications like HackQuest.
- ** SQLite3 :** SQLite is a built-in relational database engine. It is simple to set up and use, making it an excellent choice for lightweight web applications.

## Database Management:
- ** SQLite3 :** SQLite is a built-in relational database engine. It is simple to set up and use, making it an excellent choice for lightweight web applications.
- ** JSON :** The use of JSON is crucial for HackQuest, as it allows storing all the game's questions in an easily accessible and manipulable format.

# Gameplay of HackQuest :  

## Description of the Game and its Functioning : 

HackQuest positions itself as a pedagogical revolution in the world of serious games. From the very beginning, the player is immersed in an interactive and personalized dashboard, reflecting their successes and journey in the game. The interface, rich and intuitive, allows navigation between game history, earnings tracking, and global ranking.

## Objectives and Rules of the Game : 

The primary objective of HackQuest is to raise awareness among players about cyber threats through a fun and educational format. The game unfolds in a series of thematic quizzes, each aiming to test players' knowledge on specific subjects such as attacks, DoS, DDoS, phishing, and spoofing. The rules are simple but designed to stimulate learning: correctly answer questions of increasing difficulty to accumulate points and climb the ranks.

## Game Mechanics : 
HackQuest's game mechanics are finely crafted. They include help systems inspired by "Who Wants to Be a Millionaire?", allowing players to ask a friend, eliminate half of the answers, or poll the audience. Each successful question results in the award of points in the form of money and a detailed explanation, while each mistake only provides the detailed explanation, thus promoting an active and continuous learning cycle.

## Quizzes : 

Quizzes are the heart of the HackQuest experience. Through varied and contextualized questions, players explore the depth and complexity of the cybersecurity domain. Screenshots illustrate the quiz interface, where pointed questions invite thoughtful consideration, and where each choice of answer can be an opportunity for valuable learning.

## Score : 

The scoring system is designed to reward perseverance and accuracy. Each correct answer increases the player's balance, visible on the dashboard, which also displays recent earnings and offers the opportunity to convert these earnings into real or virtual rewards. This approach reinforces the rewarding aspect of the game and encourages players to invest more in learning.

## Competition : 

Competition is a central element of HackQuest. Players are not only competing with themselves, seeking to surpass their previous scores, but also with the community. The ranking, highlighted in the screenshots, shows real-time tracking of the top players, injecting a healthy and motivating spirit of competition.

## Synthesis : 

HackQuest, through its thoughtful gameplay, offers an immersive experience that merges intellectual challenges and entertainment. It succeeds in popularizing often complex cybersecurity concepts, making them accessible and engaging. Gamification elements are intelligently integrated to transform learning into a memorable adventure. With an engaging interface and a game structure that values progression and education, HackQuest emerges as an essential tool in the educational arsenal of technology enthusiasts, security professionals, and digital enthusiasts. In summary, this serious game is a feat that combines pedagogical depth with the excitement of gaming.
