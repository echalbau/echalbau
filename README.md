### Hi, I'm Esteban 👋

Data engineer with a particle physics background. I build pipelines and ML systems that turn large, noisy datasets into reliable results, along with the validation that makes them trustworthy.

For the last 5 years I've worked on some of the largest datasets in science, first at LIP (Portugal) and now at CERN with the ATLAS experiment:

- Refactored a sequential legacy codebase into parallel SLURM array jobs, scaling processing from 500K to 16M records per run (32×).
- Ingested, cleaned and validated 300M+ heterogeneous records in Python and SQL, with automated data-quality checks.
- Built and maintain an automated batch pipeline on CERN's HTCondor grid: templated jobs, large parameter sweeps and reproducible runs.
- Trained gradient-boosted and deep learning models for rare-event detection in noisy, highly imbalanced data.

I've also processed multi-constellation GNSS data (Galileo, BeiDou) in the aerospace sector at Active Space Technologies.

#### What I'm building

- 🚧 **[iberian-grid-platform](https://github.com/echalbau/iberian-grid-platform)**: batch data platform for the Iberian power grid (Red Eléctrica, ENTSO-E, weather data) with Airflow, PySpark, dbt and Terraform on AWS, including a case study of the April 2025 Iberian blackout.
- 🚧 **[gnss-interference-monitor](https://github.com/echalbau/gnss-interference-monitor)**: real-time monitoring of GNSS reference stations and interference detection, streaming RTCM3 data through Kafka and Spark Structured Streaming, with MLflow and Grafana.
- **[gnss-agent-pipeline](https://github.com/echalbau/gnss-agent-pipeline)**: agentic GNSS post-processing with LangGraph. LLM agents orchestrate RINEX quality control, IGS product retrieval, RTKLIB PPP/RTK positioning and a precision-check loop, with deterministic fallbacks, a FastAPI interface and an auto-generated report.
- **[apagon-mvp](https://github.com/echalbau/apagon-mvp)**: early warnings of power outages in Venezuela from open data (social media reports and weather), with baseline comparisons and alerts through a Telegram bot.

🚧 = in progress

#### Toolkit

**Day to day:** Python (pandas, NumPy, scikit-learn, PyTorch) · SQL · C++ · Bash · HTCondor · SLURM · FastAPI · MongoDB · Linux · Git/GitLab

**Currently building with:** Apache Spark · Airflow · dbt · Kafka · Docker · Terraform · AWS · MLflow · LangGraph

#### Currently

Finishing my PhD in particle physics and looking for **Data Engineer** and **ML Engineer** roles starting **March 2027**, in Spain (Madrid, Barcelona) or remote across the EU. Especially interested in space, GNSS, energy and data-intensive companies. EU resident · Employee or B2B.

🌍 English · Español · Português
💼 [LinkedIn](https://www.linkedin.com/in/esteban-chalbaud) · 📧 chalbaudesteban@gmail.com
