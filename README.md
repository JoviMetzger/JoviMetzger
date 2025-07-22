<h1 align="left">🌻 Hey there, I'm Jovi 🌻 </h1>

*I'm a student at Codam (42 The Network), passionate about graphic design and illustration.<br>
I enjoy exploring new programming languages and immersing myself in various coding challenges.*

<p align="left">
   <a href="https://github.com/JoviMetzger?tab=repositories"><img alt="Portfolio" src="https://github.com/user-attachments/assets/2ffee099-d0d1-410d-a54a-0b7a7ab417bf" style="width: 20px; height: 20px;"></a>
    &ensp;
   <a href="https://www.linkedin.com/in/jovimetzger"><img alt="LinkedIn" src="https://github.com/user-attachments/assets/cab4cf7a-a8e5-4be5-b6b7-86c2a28b3991" style="width: 20px; height: 20px;"></a>
    &ensp;
   <a href="https://www.freecodecamp.org/JoviMetzger"><img alt="freeCodeCamp" src="https://github.com/user-attachments/assets/8ae43b3e-036c-41fc-a0de-578af6d704db" style="width: 20px; height: 20px;"></a>
</p>

---

&ensp; 🐝 &ensp; **Student at Codam** 🇳🇱 <br>
&ensp; 🥑 &ensp; **I’m currently working on:** Transcendence <br>
&ensp; 🌱 &ensp; **I’m currently learning:** C, C++, Kotlin <br>
&ensp; 🍄 &ensp; **Hobbies:** Food, Sleep, Music, Series/Movies *(I'm very boring)* <br>

---

<a href="https://github.com/JoviMetzger">
   <img height="150px" src="https://github-readme-stats.vercel.app/api?username=JoviMetzger&show_icons=true&hide_title=true&hide_border=true&theme=slateorange" />
   <img height="150px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JoviMetzger&show_icons=true&layout=compact&langs_count=6&hide_title=true&hide_border=true&theme=slateorange" />
</a>


---

<!--
![snake animation](https://github.com/JoviMetzger/blob/output/github-contribution-grid-snake2.svg)
-->

<!--
**JoviMetzger/JoviMetzger** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->



<!--
# Transcendence

Transcendence is a full-stack web application where users can <br>
create an account and play **3D Pong** or **2D Snake** games. <br>
This project was developed in collaboration with [Julius]() and [Acco]() .<br> 

## Table of Contents
- [About](#About)
- [Docker](#Docker)
- [Backend](#Backend)
- [Frontend](#Frontend)
	- [Refresh Pages](#Refresh-Pages)
	- [HTTPS](#HTTPS)
	- [CSS Tailwind](#CSS-Tailwind)
	- [HTML - dompurify](#HTML-dompurify)
	- [Languages](#Languages)
- [Installation](#Installation) 



## About
Transcendence covers most things in full-stack webapplication. <br>
**The application is simple.**  <br>
User creates and acount, unless already created then just needs to loggin. <br>
The user can see there *stats* and a *leaderboard* displaying the top 3 players for each game. <br>
The user can choose for both games if he/she wants to play a tournemnet or with a freind. <br>
The user can aswell find their and from other users the history matchtes. <br>
user has a settings side, where Avatar, username, alias name, password can be changed. <br>
The user can view their given data, has the option to delete their account. <br>

The subject wants you to choose **7 Major modlues** *(two Minor modlues equal one Major module)*
<details>
  <summary><strong>We choose:</strong></summary>
  <br>

## We choose:

- **Major** : Use a framework to build the backend 	<br>
&emsp;&emsp;&emsp;&ensp; - Required framework **->** **Typscript** <br>
					
- **Major** : Implementing Advanced 3D Techniques <br>
&emsp;&emsp;&emsp;&ensp;- Reqiured tool is **babylon**	<br>
&emsp;&emsp;&emsp;&ensp;- We implemented a fully 3D version of the classic Pong game <br>

- **Major** : Standard user management, authentication, users across tournaments. <br>
&emsp;&emsp;&emsp;&ensp;- Registration with username, alias, password, and avatar. <br>
&emsp;&emsp;&emsp;&ensp;- Secure login. <br>
&emsp;&emsp;&emsp;&ensp;- Multiplayer support across tournaments. <br>
&emsp;&emsp;&emsp;&ensp;- Match history available to all users. <br>

- **Major** : Add another game with user history and matchmaking <br>
&emsp;&emsp;&emsp;&ensp;- Added Snake *(Snek)*, has a match history with scores, wins, and losses. <br>

- **Minor** : Use a framework or toolkit to build the front-end <br>	
&emsp;&emsp;&emsp;&ensp;- Tools: **HTML + Tailwind CSS**	<br>

- **Minor** : Use a database for the backend <br>
&emsp;&emsp;&emsp;&ensp;- We used **SQLite** <br>
&emsp;&emsp;&emsp;&ensp;- If you have a backend, it makes sence to use a database, <br> 
&emsp;&emsp;&emsp;&ensp;&ensp;because you can store user data, match history, scores, and more. <br>

- **Minor** : Expanding browser compatibility <br>
&emsp;&emsp;&emsp;&ensp;- Compatible with Chrome, Firefox, and other major browsers. <br>
&emsp;&emsp;&emsp;&ensp;- *Easy module, becuase that happends automtally*	<br>

- **Minor** : Supports multiple languages <br>
&emsp;&emsp;&emsp;&ensp;- User can switch for different languages <br>
&emsp;&emsp;&emsp;&ensp;- Could probably use a toolkit, but we used the **data-i18n** attribute for simple <br>
&emsp;&emsp;&emsp;&ensp;&ensp;multilingual support. <br>

- **Minor** : User and game stats dashboards <br>
&emsp;&emsp;&emsp;&ensp;- ***Dashboards shows:*** <br>
&emsp;&emsp;&emsp;&ensp;&emsp;&emsp;- Highest scores <br>
&emsp;&emsp;&emsp;&ensp;&emsp;&emsp;- Wins and losses <br>
&emsp;&emsp;&emsp;&ensp;&emsp;&emsp;- Leaderboards for top 3 players <br>

- **Minor** : GDPR compliance options with user anonymization, <br> local data management, and account deletion.	<br>
&emsp;&emsp;&emsp;&ensp;- User can delete account/ their data. <br>
&emsp;&emsp;&emsp;&ensp;- User can edit their data *(username, alias, password, avatar)* <br>	
&emsp;&emsp;&emsp;&ensp;- User can view their data. <br>
&emsp;&emsp;&emsp;&ensp;- **GDRP** *(General Data Protection Regulation)* : <br> 
&emsp;&emsp;&emsp;&ensp;&ensp;We have a privicy policy, so the user knows what will happend with their data <br>
&emsp;&emsp;&emsp;&ensp;&ensp; *(Ensures transparency and control over personal information)*

<br> <br>
</details>

<br><br>


## Docker

### Docker Compose Files
We used two different docker compose files.
- `docker-compose-dev.yml` **->** used during **development**.
- `docker-compose.yml` **->** Used for **production**.

***Why two files?*** <br>
The docker-compose-dev.yml file was created to streamline the development process. <br>
It allows live updates without needing to rebuild the entire Docker image after every change. <br>

*For example:*
- When editing HTML or frontend code, changes are reflected immediately.
- This drastically reduces development time by skipping unnecessary recompilation steps.

The docker-compose.yml file is optimized for production and includes the final setup with all necessary build steps and configurations.

***How to get a development and productio environment?*** <br>
In the docker-compose look for the backend environment:
- Development Option:
```
environment:
      - NODE_ENV=development
```
- Production Option:
```
environment:
    - NODE_ENV=production
```

### Containers
- **Frontend Container** <br>
  Serves the user interface built with HTML, Tailwind CSS, and TypeScript.
- B**ackend Container** <br>
   Runs the TypeScript-based backend server that handles authentication, <br>
   matchmaking, and game logic.

### Volumes
We use two Docker volumes:
- **Database Volume**
  - Persists the SQLite database file.
  - Ensures that data is not lost between container restarts.
- **Cookie Volume**
  - Stores session and authentication cookies.
  - Keeps user login data across sessions.


^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

- backend
I'm sorry don't know much about the backend.

besides we had Swagger UI (localhost:3000/docs)
It was nice for the frontend to use, you could see what route you need to call and what you need to send to th ebackend and what you will recive back.
Was also nice for the backend because you could test the route over the webside in a more visual way, without printing in the console everything.





- frontend
The supject requireds you to use a single web application, wich means only one html page is being used. 
We always reloaded the body of the html with the new content we needed.

Things that might be usefull:
call to the backend
took us a while to understand how we call the backend, but is pretty simple.
the string that you get from your html input needs to stringefid. 
export function inputToContent(input: string[]): string {
	const obj: Record<string, string> = {};

	input.forEach(id => {
		const elem = document.getElementById(id) as HTMLInputElement | null;
		if (elem)
		{
			const rawInput = elem.value;
			const sanitizedInput = DOMPurify.sanitize(rawInput); // Removes unsafe HTML
			obj[elem.id] = sanitizedInput;
		}
	});

	const jsonStr = JSON.stringify(obj);
	return jsonStr;
}

const content = inputToContent(["username", "password"]);
			const body = requestBody("POST", content, "application/json");

			try {
				const response = await connectFunc("/user/login", body);
      export async function connectFunc(url: string, request: RequestInit): Promise<Response> {
	
	// console.log("Connect To " + url + " Using:")
	// console.log(request)

	const response = await httpGet("https://localhost:3000" + url, request);
	if (response.status === 402) {
		window.history.pushState({}, '', '/logIn');
		setupLogIn(); // Redirect to logIn
	}
	return response
}






html - dompurify
languages
https







^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^


## Installing
**1. Step:**  Create a *.env*
<details>
  <summary><strong>📝 My .env</strong></summary>
  <br>

## 📝 .env

```
# random
ADMIN=admin
PASSWORD=iamadmin

# frontend
FRONTEND_PORT=5173

# backend variables
BACKEND_PORT=3000
LOG_LEVEL=info

# API protection
PUBLIC_KEY=asdfghjk
PRIVATE_KEY=qwertyuio
```

<br> <br>
</details>
<br>

**2. Step:** Start the Docker
```
make prod
```
<br>

**3. Step:**  Go to your web browser
```
https://localhost:5173
```
❗ If You using **FireFox**, Please [add the certificates]() to browser first. <br> <br>


**4. Extra Info:** <br>
`make prod` **-> Start the Docker** <br>
`make push` **-> Updates the database & applies any pending changes to the actual database structure** <br>
`make clean` **-> Remove all containers and volumes** <br>
`make deepclean` **-> Reset. Removes containers, volumes, network, certificates, directories**
<br>
<br>
<br>
-->
