<p align="center">

  <img src="https://drive.google.com/uc?export=view&id=1W2QKxaTIvY17qPVfIZuYhuUroqIhTSP7" alt="LOGO" width="350" />
</p>

<p align="center">

  **Theft Prediction: A Motion and Gesture Sensor for Identifying Suspicious Activities**
</p>

<p align="center">

  See the [documentation](https://drive.google.com/file/d/13JfqGKbeYx3t3D2HC0iH9tSk4r64igUF/view?usp=sharing) for more info.
</p>

## 📂 Requirements
Make sure you have the following installed on your computer/device:
- ✅ Visual Studio Code ([download here](https://code.visualstudio.com/)).
- ✅ Composer ([download here](https://getcomposer.org/)).
- ✅ Node.js ([download here](https://nodejs.org/en)).
- ✅ XAMPP ([download here](https://www.apachefriends.org/)).
- ✅ Python ([download here](https://www.python.org/downloads/)).
- ✅ Git ([download here](https://git-scm.com/downloads)).

## 👉 Get Started | Run Project Locally

<details>
<summary><h4>1. Open XAMPP Software</h4></summary>

  > Choose these modules to start:
  > 
  > ![xampp](https://drive.google.com/uc?export=view&id=1MaZx_BNTGF825tGRqm4aav16ggfK3gMp)
  > 
  > After that, click **Admin** action in **MySQL** module.
  >
  > If the window appears as shown in the browser, proceed to the next step.
  >
  > ![phpmyadmin](https://drive.google.com/uc?export=view&id=1eWiUBuPAoPiUPQTM8rTGlCcvTxMKCDrZ)
</details>
<details>
<summary><h4>2. Clone the Project</h4></summary>

  > **In your Desktop, open a command prompt of your choice (git bash, cmd, or any)**
  > ```bash
  > git clone https://link-to-project
  > cd project-name
  > ```
  > Open folder to VS Code
  > ```bash
  > code .
  > ```
</details>
<details>
<summary><h4>3. Start Flask Server (Camera API)</h4></summary>

  > **Open a terminal inside VS Code**
  > Go to ALGORITHM folder
  > ```bash
  > cd algorithm
  > ```
  > Install modules
  > ```bash
  > pip install 'C:\{**your-download-directory**}\requirements.txt'
  > ```
  > Load the motions and Start the Server 
  > ```bash
  > python app.py
  > ```
</details>
<details>
<summary><h4>4. Install Dependencies for Laravel (Back-End)</h4></summary>

  > **Open another terminal inside VS Code**
  > Go to API folder
  > ```bash
  > cd api
  > ```
  > Install modules
  > ```bash
  > composer install
  > ```
  > Copy the .env file
  > ```bash
  > cp .env.example .env
  > ```
  > Generate application key
  > ```bash
  > php artisan key:generate
  > ```
  > **Migrate**, **Seed** all tables and type 'yes' to create **Database**
  > ```bash
  > php artisan migrate --seed
  > ```
  > Run the server
  > ```bash
  > php artisan serve
  > ```
</details>
<details>
<summary><h4>5. Install Dependencies for Nuxt (Front-End)</h4></summary>

  > **Open another terminal inside VS Code**
  > Go to VIEW folder
  > ```bash
  > cd view
  > ```
  > Install modules
  > ```bash
  > npm install
  > ```
  > Fix compatibilities
  > ```bash
  > npm audit fix
  >```
 > Run the server
  > ```bash
  > npm run dev
  > ```
</details>

### ⭐ That's it! The project is now ready to use. Enjoy Dark-mode Theme. ⭐

Go to the link - (http://localhost:3000/)

![landing-page](https://drive.google.com/uc?export=view&id=17uKbu88C3i3U5fEAU_o6aHezuaVQSuxZ)

## 🧑‍💻 Developers
This project was developed by:
- [Luis Suizo](https://github.com/evander092002)
- [Kent Escoto](https://github.com/KJLEscoto)
- [Rochele Cocjin](https://github.com/iochel)
- [Reynaldo Baja Jr.](https://github.com/rey-cloud)
- [Ralph Hernandez](https://github.com/yourboiralph)

## ❔ Where to ask for help?
You can send a message on our following socials:
> Email: **sti.bscs.thesis@gmail.com**
>
> Discord Channel: [Thesis701](https://discord.gg/CBUbE33zPF)

## ©️ Copyright
Copyright 2024 | Bachelor of Science in Computer Science | Batch 2025 🎓


