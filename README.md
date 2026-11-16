# Flask DevOps Project

A simple Flask web app I'm taking from code to cloud, step by step,
to practice real DevOps workflows.

## Endpoints
- `/` returns a welcome message
- `/health` returns the app's health status (used by load balancers and Kubernetes)

## Run locally
pip install -r requirements.txt
python app.py

## Roadmap
- [x] Flask app with health check
- [ ] CI pipeline with GitHub Actions
- [ ] Docker
- [ ] Kubernetes
- [ ] Terraform on AWS
- [ ] Monitoring