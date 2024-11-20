<p align="center">
 <h2 align="center">Game Recommendation System with Apache Airflow</h2>
 <p align="center">This project analyzes user behavior from Steam game data and YouTube activity to suggest personalized game recommendations. It combines data science with game analytics for a user-focused solution💌 </p>
</p>
<p align="center">
    <a href="https://github.com/varick8/Swap-n-Share/graphs/contributors">
       <img src="https://img.shields.io/badge/contributors-3-green" alt="contributors"/>
    </a>

<p align="center">
 <img width="500px" src="Images/End to End.png" align="center" alt="Members" />
 <h2 align="center">This is Our Teams</h2>
 <p align="center">We’re the tech wizards with hearts of gold;</p>
 <p align="center">we’ve got the code and the compassion to make anything happen. 🧙‍♂️💻</p>
</p>

<p align="center">
 <p align="center">Ketua Kelompok   : Rani Nirmala Prakoso    - 22/493982/TK/54153</p>
 <p align="center">Anggota 1        : Muhammad Luthfi Attaqi  - 22/496427/TK/54387</p>
 <p align="center">Anggota 2        : Varick Zahir Sarjiman   - 22/496418/TK/54384</p>
</p>

# Background 💖
Fakultas kami berhasil meraih prestasi di Porsenigama, sebuah ajang kompetisi bergengsi antar fakultas di universitas kami. Untuk merayakan pencapaian ini dan mendalami keterampilan data, kami memilih untuk mengerjakan proyek End-to-End Data Engineering dengan topik analisis data game di platform Steam. 

# Bubbly Backdrop 🌱 
Aplikasi ini dibuat untuk memenuhi tugas Rekayasa Data Departemen Teknik Elektro dan Teknologi Informasi Universitas Gadjah Mada tahun ajaran 2024/2025.

# Docummentation ✍️
1. Notion 
2. Video

### [Modeling Steam API - Steam Web Scraping](https://github.com/.....)

- Brief overview:Membuat prediksi game selanjutnya yang mungkin dimainkan oleh user
- Source:
  1. [Steam User API](https://api.steampowered.com/ISteamUser/GetFriendList/v1/)
  2. [Steam User Data API](https://api.steampowered.com/IPlayerService/GetOwnedGames/v1/)
  3. [Steam Game API](https://store.steampowered.com/api/appdetails?appids={app_id})
  4. [Web Steam (Scraping)](https://steamcharts.com/top)

 ### [Modeling Steam API - Steam Web Scraping - Youtube](https://github.com/.....)

- Brief overview:Membuktikan apakah popularitas game pada YouTube sesuai dengan Peak Players per harinya.
- [Power BI](https://app.powerbi.com/view?r=eyJrIjoiNzFkMDMxZDEtYjEyNi00NDM4LWIwYWEtOGY0YTg0ODc2Yzg5IiwidCI6ImFmMmMwNzM0LWNiNDItNDY0Zi1iNmJmLTJhMjQxYjZhZGE1NiIsImMiOjEwfQ%3D%3D)
- Source:
  1. [Youtube API V3](https://console.cloud.google.com/)
  2. [Steam Game API](https://store.steampowered.com/api/appdetails?appids={app_id})
  3. [Web Steam (Scraping)](https://steamcharts.com/top)

<p align="center">
 <h2 align="center">How to Use & Clone?</h2>
</p>

1. Install `git` if you don't already have it, and check out the `documentation` repo as follows:
```
$ git clone https://github.com/ranisedangbekerja/Game-Recommendation-System-with-Apache-Airflow.git
$ cd documentation
```
2.  Open Windows PowerShell as an administrator and install `astro` if you don't already have it, and restart your visual studio code:
```
winget install -e --id Astronomer.Astro
```
3. Running Airflow Locally
```
$ astro dev start
```
4. If you have a trouble when setup the 'astro environment' let go check https://www.astronomer.io/docs/astro/
5. Install `docker` if you don't already have it https://www.docker.com/products/docker-desktop/
6. Setting your own connection of 'docker-compose.yml'
```
version: '13'
services:
  postgres:
    image: postgres:13
    container_name: postgressteam_db
    environment:
      POSTGRES_USER: postgressteam
      POSTGRES_PASSWORD: postgressteam 
      POSTGRES_DB: postgres
    ports:
    - "5433:5432" 
    volume:
    - postgres_data:var/lib/postgresql/postgres_data
  
  volumes:
  postgres_data:
```

<p align="center">
 <h2 align="center">How to Setting the Apache Airflow?</h2>
</p>

1. Click and SignIn suitable with your terminal output, will be similiar like below:
```
Airflow webserver : http//localhost:<port>
Postgres Database: localhost:<port>/postgres
The default Airflow UI credentials are: admin:<admin>
The default Postgres DB credentials are: postgres:<postgres>
```
2. Click 'connection' in Airflow Page Navbar, let's go setting let yours

# Tools
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=Apache%20Airflow&logoColor=white) ![VSCode](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white) ![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue) ![PoweBI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=white) ![GColab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252) ![Astro](https://img.shields.io/badge/Astro-0C1222?style=for-the-badge&logo=astro&logoColor=FDFDFE) ![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)




<hr>
<p align="center">
Developed with ❤️ in Indonesia (IDN)
</p>
