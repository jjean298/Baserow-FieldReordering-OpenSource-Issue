# 🧩 Baserow Open Source Contribution (In Progress)

**Project:** [Baserow](https://gitlab.com/baserow)  
**Issue:** [#3723 ](https://gitlab.com/baserow/baserow/-/issues/3723) - Editors are able to trigger the api call to change the order of fields \
**Status:** In Progress  
**Team:** Baserow B x FIU Tech Talent Academy  
**Date:** Fall 2025

## 🧠 Overview
Collaborating with a team to debug and implement a fix in Baserow, an open-source no-code database built with **Django**, **Vue.js**, and **PostgreSQL**.  
The issue affects the **field reordering feature**, where users with Editor or lower permissions receive unclear error messages instead of proper authorization feedback.

## Tech Stack 
Python, Vue, JavaScript, SCSS, HTML, Shell, etc.

## ⚙️ Work Completed So Far
- Reproduced the bug using Docker Compose and local environment setup.  
- Investigated **Vuex store**, **API request flow**, and **Django permission logic**.  
- Documented behavior patterns and began mapping the 401 error handling chain.  
- Collaborating on implementing explicit error messaging for restricted roles.

## 🚧 Current Blockers
- 401 error message not surfacing correctly in Vue.
- Permissions logic unclear between frontend and backend.
- Reproducibility inconsistencies in Docker environment.

## ✅ Resolved Issues
- Fixed Docker build failure by updating image path in `compose.yaml`.
- Retrieved Adanced Baserow subscription for role based access control and reproduction of issue
- Found file responsible for error handling.

## 🎯 Next Steps
- Finalize 401 response handler in frontend.  
- Submit merge request for review on GitLab.  
- Conduct QA testing across roles (Admin, Editor, Viewer).

## 🧾 References
- 🔗 [Baserow GitLab Repository](https://gitlab.com/jjean298/baserow/) 
