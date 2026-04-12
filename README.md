Final-year **Computer Science (Co-op)** student at **Concordia University**. Prev @ **BMO**.

### 🧰 Tech I reach for
**Languages:** Java · Python · C++ · JavaScript/TypeScript · SQL · C
**Backend:** Spring Boot · Node.js · Express · REST · Microservices
**Cloud & Infra:** AWS (Lambda, Bedrock, S3, EC2) · Docker · Kubernetes · Jenkins · Ansible
**Data:** MS SQL Server · MongoDB · MySQL · PostgreSQL · Liquibase · Pandas

### 📫 Reach me
[LinkedIn](https://linkedin.com/in/asifurrahman7) · asifur.rahman@mail.concordia.ca

---

*Open to SWE, Cloud, and Data Engineering internships.*

---

## Projects

### [3D Rendering Engine with Multi-Light Shadow Mapping](https://github.com/asifur-rahman9/whack-a-mole-cpp)
**C++ · OpenGL · GLSL**
A real-time 3D game built from scratch for Concordia's computer graphics course (COMP371). No game engine, no asset loaders — just raw OpenGL and a custom OBJ parser feeding vertex buffers directly to the GPU. The interesting parts: multi-pass shadow mapping that renders depth from each light's POV before sampling those textures in the main fragment shader, hierarchical matrix transformations driving a two-joint articulated hammer arm via forward kinematics, and a C++ shader abstraction layer wrapping the GLSL compile-link-uniform lifecycle. Cubemap skybox and a GPU-instanced particle system round it out. Built with a partner.

---

### [Full-Stack Service Booking Platform](https://github.com/asifur-rahman9/fullstack-services-app)
**React · Node.js · Express · MongoDB · JWT**
A full-stack web app for booking and managing services with separate flows for clients and providers. The React frontend handles protected routes and form validation; the Express backend exposes a REST API with middleware-based auth, request validation, and centralized error handling. Auth is a stateless JWT flow with refresh token rotation. MongoDB schemas are indexed on lookup fields to keep query latency low under realistic usage. Built as a learning vehicle for production-style backend patterns — middleware composition, schema design, and clean separation of concerns.

---

### [Montreal BIXI Demand Forecasting](https://github.com/asifur-rahman9/bike-station-monitor)
**Python · scikit-learn · Pandas · Streamlit**
An ML pipeline that predicts hourly bike demand across Montreal's BIXI network. Five years of public ridership records get joined with weather and station metadata, then engineered into temporal features (hour-of-day, day-of-week, rolling demand windows) before training a RandomForestRegressor tuned via grid search. The trained model is served through a Streamlit dashboard with a map view of predicted demand per station. Engineered as a real project, not a notebook dump — modular `src/models/tests/` layout, pytest coverage on the feature pipeline, and joblib model serialization.

---

### [H5P OER Plugin](https://github.com/asifur-rahman9/custom-h5p-plugin)
**PHP · JavaScript · CSS · WordPress Plugin API**
A Pressbooks plugin that injects scoped CSS into H5P interactive activities, giving non-technical faculty a way to enforce accessibility and visual consistency across open educational resources without touching code. Ships as a standard WordPress plugin with a settings panel for toggling presets like high contrast, larger text, and stronger focus indicators. Built during my OER Web Developer role at Concordia and used in production on the university's Pressbooks instance.

---

### [Station Signal Analyzer](https://github.com/asifur-rahman9/station-signal-analyzer)
**Python · NumPy · Matplotlib**
A small data analysis tool that ingests raw station signal data, runs cleanup and aggregation routines, and produces matplotlib visualizations for diagnosing performance trends over time. Built as an exercise in turning messy time-series data into something a non-engineer could actually read.

---

### [Simple CRUD App (Backend)](https://github.com/asifur-rahman9/simple-crud-app-backend)
**Node.js · Express · MongoDB**
A minimal Express + MongoDB backend demonstrating clean CRUD patterns — modular route handlers, Mongoose models, and a RESTful endpoint structure. Built early as a reference implementation for the architecture I now use in larger projects.
