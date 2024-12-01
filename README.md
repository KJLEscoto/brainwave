<div align="center">
  <br />
    <img src="https://drive.google.com/uc?export=view&id=1W2QKxaTIvY17qPVfIZuYhuUroqIhTSP7" alt="LOGO" width="350" />
  <br />

  <h3 align="center">Theft Prediction: A Motion and Gesture Sensor for Identifying Suspicious Activities</h3>

  <div align="center">
    Read 
    <a href="https://drive.google.com/file/d/13JfqGKbeYx3t3D2HC0iH9tSk4r64igUF/view?usp=sharing" target="_blank"><b>documentation</b></a> for more info.
  </div>
</div>

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
<summary><code>1. Open XAMPP Software</code></summary>

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
<summary><code>2. Clone the Project</code></summary>

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
<summary><code>3. Start Flask Server (Camera API)</code></summary>

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
<summary><code>4. Install Dependencies for Laravel (Back-End)</code></summary>

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
<summary><code>5. Install Dependencies for Nuxt (Front-End)</code></summary>

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

<hr />

<div align="center">
  <h3 align="center">⭐ That's it! The system is now running. Enjoy Dark-mode Theme. ⭐</h3>

  <p>Start Monitoring - <a href="http://localhost:3000/" target="_blank">http://localhost:3000/</a></p>
</div>

![landing-page](https://drive.google.com/uc?export=view&id=17uKbu88C3i3U5fEAU_o6aHezuaVQSuxZ)

<h4>🔑 User Login Credentials</h4>
<p>Use this accounts to access the system. <span color="red">NOTE:</span> Each role has unique functionalities.</p>

<details>
<summary><code>Client</code></summary>

  > **username**: client
  > **password**: client123
</details>

<details>
<summary><code>Admin</code></summary>

  > **username**: admin
  > **password**: admin123
</details>

<details>
<summary><code>Superadmin</code></summary>

  > **username**: Superadmin
  > **password**: superadmin123
</details>

<hr />

## 🧑‍💻 Developers
This project was developed by:
- [Luis Suizo](https://github.com/evander092002)
- [Rochele Cocjin](https://github.com/iochel)
- [Reynaldo Baja Jr.](https://github.com/rey-cloud)
- [Ralph Hernandez](https://github.com/yourboiralph)
- [Kent Joemar Escoto](https://github.com/KJLEscoto)

## ❔ Where to ask for help?
You can send a message to our following socials:
> Email: sti.bscs.thesis@gmail.com
>
> Discord Channel: [Thesis701](https://discord.gg/CBUbE33zPF)

## ©️ Copyright
Copyright 2024 | Bachelor of Science in Computer Science | Batch 2025 🎓


