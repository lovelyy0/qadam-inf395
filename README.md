# Qadam - IT Career Platform

## How to run system
1. Install dependencies: `pip install -r requirements.txt`
2. Initialize database: `python init_db_simple.py`
3. Run server: `uvicorn app.main:app --reload`
4. Open browser: `http://localhost:8000/docs`

## Group member roles
- Nursaule -Fullstack Developer (Backend Development, H3 Integration, API Design) 
- Adina - UX/UI Designer (System Design, Data Visualization, User Flow)
- Medina- System Designer (Architecture Design, Database Modeling, Security)
- Shugyla - Project Manager (Documentation, Testing, Coordination)

## How H3 is used in the system
- Each internship has an H3 index (resolution 8) generated from coordinates
- H3 enables efficient geospatial search for nearby internships
- Regional analytics aggregated by H3 regions
- Used in endpoints: `/api/h3/nearby`, `/api/h3/regions`, `/api/h3/region/{index}`
