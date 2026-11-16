# Flask DevOps Project

A simple Flask web app I'm taking from code to cloud, step by step,
to practice real DevOps workflows.

## Endpoints
- `/` returns a welcome message
- `/health` returns the app's health status (used by load balancers and Kubernetes)

## Run locally

1. Clone the repo
```bash
git clone https://github.com/0xJoba/flask-devops-project.git
cd flask-devops-project
```

2. Create and activate a virtual environment
```bash
python -m venv venv
source venv/bin/activate        # Mac/Linux
source venv/Scripts/activate    # Windows (Git Bash)
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Run the app
```bash
python app.py
```

5. Visit `http://localhost:5000` and `http://localhost:5000/health`

## Roadmap
- [x] Flask app with health check
- [ ] CI pipeline with GitHub Actions
- [ ] Docker
- [ ] Kubernetes
- [ ] Terraform on AWS
- [ ] Monitoring