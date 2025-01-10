<p align="center">
  <a href="./">
    <picture>
      <source height="125" media="(prefers-color-scheme: dark)" srcset="">
      <img height="125" alt="Fiber" src="./assets/oel2.png">
    </picture>
  </a>
  <br>
</p>
<p align="center">
  <em><b>En mere tak!</b> Når du har brug for en ekstra opfyldning... </em>
</p>

### App'en er under udvikling! 🥳 🚀

# 🧐 Projektbeskrivelse
Et projekt udviklet for at fikse et klart hul i markedet. Eller måske fordi det virkede som en sjov idé.

Projektet bygger på 

# 👨‍💻 Tech stack
Et hurtigt overblik over de teknologier der går ind i projektet:

- DigitalOcean
- Python
- PostgreSQL / Postgis
- DuckDB
- FastAPI

Størstedelen af rutelogikken er opbygget ved hjælp af pgRouting tilføjelsen til Postgresql og Postgis. Hertil bruges nogen indbyggede rutealgoritmer der gør det muligt at tilføje nodes i sit netværk on-the-fly. 

Python binder som sædvanlig det hele sammen

FastAPI bruges til at koble frontend sammen med backend. 

Opdatering af data foregår nu vha. DuckDB der har en indbygget metode til at arbejde med OSM data. Tidligere skulle der bruges en række værktøjer der hovedsageligt virker fra Ubuntu såsom Osmium.

Data er udelukkende leveret af Openstreet Map <3

# ✍️ To do
* Færdiggør UI
*

# 💛
Også lavet med kærlighed