# Aayush Kaushik

**Software engineer · Backend and data engineering · Heilbronn, Germany**

I build backend services and data pipelines in Python and SQL. At Bosch Rexroth I spent over a year
developing data-driven software for industrial testing: my applications replaced a licensed third-party
tool and cut reporting cycles from several days to under an hour. M.Sc. Electrical Engineering & IT
(Automation), Hochschule Darmstadt, November 2025.

**Looking for:** junior roles in backend development, data engineering or cloud engineering in Germany.
Full work authorization in Germany, no sponsorship needed.

## Experience

**Bosch Rexroth AG, Murrhardt** · Software Engineer, master's thesis · Apr 2025 – Sep 2025

*Thesis: Software Development for Machine Capability Testing of Next-Generation Tightening Tools*

- Replaced a licensed third-party tool with CapTIS, a C#/.NET and SQL application the development team
  now uses daily, removing recurring licence costs.
- Scaled it from 52 to 1,000 measurement points per run without re-architecting, through modular
  components developed on Git feature branches with code review.
- Validated the analysis logic to under 1 % deviation from industry reference tools, clearing it for
  production use.

**Bosch Rexroth AG, Murrhardt** · Software & Automation Engineer, internship · Aug 2024 – Feb 2025

- Cut report turnaround for eight protocol types from more than two days to under an hour with a Python
  tool that automates data extraction, processing and PDF generation.
- Reduced dashboard preparation from hours to minutes with an internal Python service for trend analysis
  and automated validation.

**Federal-Mogul Goetze (India) Ltd., Patiala** · Automation Engineer, internship · Jan 2021 – Jun 2021

- Supported quality assurance on two- and four-stroke piston lines with daily checks on PLC-controlled
  assembly equipment.
- Analysed production data to find the main causes of scrap as a basis for process improvements.

## Projects

### [Deutsche Bahn Punctuality Lakehouse](https://github.com/AayushKaushik07/db-punctuality-lakehouse)
*Python · PySpark · Spark SQL · Delta Lake · scikit-learn · Streamlit · Docker · GitHub Actions*

- Lakehouse over about 24 million real Deutsche Bahn stop events from twelve months, in an idempotent
  bronze/silver/gold PySpark pipeline on Delta Lake with incremental loading of the raw data.
- 60 automated data-quality checks per run, faulty rows quarantined with their reason, and results
  cross-checked against Deutsche Bahn's official punctuality figures.
- Leak-free gradient boosting model that predicts arrivals 6+ minutes late: ROC-AUC 0.79 against 0.72
  for the baseline, served with all KPIs in a Streamlit dashboard.

### [Event Ticketing Service](https://github.com/AayushKaushik07/event-ticketing-service)
*Python · FastAPI · MySQL · SQLAlchemy · Alembic · Docker · GitHub Actions*

- Booking API with JWT authentication and role-based access that separates organisers and customers.
- No overselling under concurrent purchases: row-level locking, proven by a test that sends ten parallel
  requests for the last ticket.
- CI pipeline with 25 integration tests against a real MySQL database; multi-stage, non-root Docker
  image published from CI.

### [German Grid Analytics](https://github.com/AayushKaushik07/german-grid-analytics)
*Python · PostgreSQL · SQLAlchemy · dbt · Power BI · Docker Compose · GitHub Actions*

- Over 1.4 million records from two public APIs (electricity and weather data) in one analytics
  warehouse, with loads that can be re-run safely without creating duplicates.
- Multi-month backfills that complete despite API rate limits, without manual restarts.
- SQL analysis showing the renewable share of demand steady at about 57 % despite a 29-point monthly
  swing, presented in a three-page Power BI report.

### Autonomous mobile robot for warehouse management
*University project, Hochschule Darmstadt · ROS · Python · YOLOv8 · scikit-learn · LIDAR*

- Modular ROS system that lets a mobile robot drive warehouse aisles on its own and detect and count
  colour-coded bins.
- Raised the YOLOv8 instance segmentation detection rate from 92–97 % to 100 % without false detections
  through dataset expansion and targeted augmentation; mask annotation automated with Segment Anything.

## Skills

| Area | Tools |
| --- | --- |
| Languages | Python, C#/.NET, SQL, C++, Bash |
| Backend & APIs | REST API design (FastAPI), JWT authentication, role-based access control, layered architecture, OOP, TCP/IP services, concurrency and transaction management |
| Databases | MySQL, PostgreSQL, SQLAlchemy, Alembic migrations, schema design, row-level locking, query optimisation |
| Data | pandas, NumPy, scikit-learn, PySpark, Spark SQL, Delta Lake, dbt, ETL pipelines, Power BI, statistical analysis |
| Robotics & vision | ROS, LIDAR data processing, YOLOv8 instance segmentation, OpenCV |
| Infrastructure | Docker (multi-stage, non-root), Docker Compose, Linux, GitHub Actions CI/CD, pytest, Git, Agile/Scrum, Azure fundamentals |

## Education

- **M.Sc. Electrical Engineering & IT** (Automation), Hochschule Darmstadt · 2022 – 2025 · grade 2.1
- **B.E. Mechatronics**, Thapar Institute of Engineering & Technology, Patiala · 2018 – 2022 · CGPA 8.90/10

## Languages

English (C1) · German (B1) · Hindi (native)

## Contact

[LinkedIn](https://linkedin.com/in/aayushkaushik0704) · aayushkaushik0704@gmail.com
