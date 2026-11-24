Project Title: The College Experience Game

Members of Team 3 Jamboree (Group 3):
Evan Digles
Gavin Robson
Nkechiyem Molokwu
Jacqueline Luis-Valle
Kevin Anderson

You will need node.js to run this code.
After you have node.js installed, follow the directions below.

Entering API Keys:
create .env file in root directory with the following variables:
DATABASE_URL               = <database_url>
DIRECT_URL                 = <direct_url>
NEXTAUTH_SECRET            = "SECRET" #Literally
NEXTAUTH_JWT_SECRET        = "SECRET" #Literally
NEXT_PUBLIC_OPENAI_API_KEY = <openai_api_key>

To run the code do the following in terminal:
npm i [to install necessary dependencies if you already installed node.js]
npx prisma generate [Sets up the database stuff]
npm run dev [to start the game]
[Then you should follow whatever link it gives you, usually localhost:3000, to play the game in browser.]
ctrl + c [Literal key presses here, to end the program.]


---

About this copy

The College Experience Game is a browser game in which the player fights off
incoming assignments, quizzes and exams. It was built by Team 3 Jamboree for
COSC 412 (Software Engineering) at Towson University, Fall 2024, using
Next.js, Phaser, Prisma, NextAuth and the OpenAI API.

This repository is a copy of the team's original repository,
https://github.com/GavinRobson/Team3Jamboree, with its full commit history.

Evan Digles's contributions:
- The sprite animation system in components/game/GameScene.js
- Sprite sheets for the player, paper, soda, quiz and exam enemies
- The example enemy class (components/game/classes/ExampleEnemy.js)
- This Readme and the running instructions

Changes made for this copy:
- The .env file has been removed from the repository and its history, and
  one hardcoded key in an early version of data/getEnemyMessage.js was
  replaced with a placeholder. Create your own .env as described above.
- This "About this copy" section was written with Claude.
