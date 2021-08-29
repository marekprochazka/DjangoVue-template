# DjangoVue template
<br />

## Description
These templates are base on my favorite implementation of Vue.js into Python Django. In this project Vue and Django are somehow separated from themself, but they are running on one port which can be an advantage while deploying on the server. 

## Frontend:
Basic vue app that is emmited into base-vue.html on backend/templates. 
On dev vue app runs on localhost:8080. In production app will be build in backend static/vue.
Frotnend has it's own router and TS support. 

## Backend:
Backend has prepared settings modules for local, staging and production.
Supports .env 
Default databse is sqllite but I recommend to use different.
In urls.py are set routes to frontend. 
BE urls such as DRF enpoints are still usable even with hash routing from vue. 
To access be routes just type them whitout hash.

### Installation:
1. clone repository and choose prefered branch
2. In project repository:
    1. python -m venv venv
    2. cd 

## Versions: 

<br />

Description | Status
--- | ---
Django3-Vue3 | Done ✔
Django3-Vue3-Dockera | Soon ❌
Django3-Vue3-DRF (+ axios) | Soon ❌
Django3-Vue3-JWTAuth | Soon ❌ 
Django3-Vue3-Docker-DRF-JWTAuth | Soon ❌

