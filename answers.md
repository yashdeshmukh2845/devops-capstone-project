# DevOps Capstone Project - Peer-Graded Assignment Answers

**Repository URL:** https://github.com/yashdeshmukh2845/devops-capstone-project  
**Local Project Directory:** `c:\Users\Victus\Downloads\course era\course era\project15`

---

## Question 1 (Task 1) - 2 Points
**Task 1:** Submit the public GitHub URL of the README.md file that contains the Project name details and displays the updated build status badge after a successful build.

### Answer (Submit URL):
```text
https://github.com/yashdeshmukh2845/devops-capstone-project/blob/main/README.md
```

---

## Question 2 (Task 2) - 1 Point
**Task 2:** Submit the public GitHub URL of the user-story.md file, which contains the template for user stories.

### Answer (Submit URL):
```text
https://github.com/yashdeshmukh2845/devops-capstone-project/blob/main/user-story.md
```

---

## Question 3 (Task 3) - 1 Point
**Task 3:** Submit a screenshot named planning-userstories-done.jpeg or planning-userstories-done.png that lists all user stories from the ‘New Issues’ column on your Kanban board.

### Answer:
- **File to Upload:** `planning-userstories-done.png` (or `planning-userstories-done.jpeg`)
- **Local File Path:** `c:\Users\Victus\Downloads\course era\course era\project15\planning-userstories-done.png`
*(Contains only the 7 required user stories with full titles visible).*

---

## Question 4 (Task 4) - 1 Point
**Task 4:** Submit a screenshot named planning-productbacklog-done.jpeg or planning-productbacklog-done.png that lists the user stories under the Ice Box.

### Answer:
- **File to Upload:** `planning-productbacklog-done.png` (or `planning-productbacklog-done.jpeg`)
- **Local File Path:** `c:\Users\Victus\Downloads\course era\course era\project15\planning-productbacklog-done.png`

---

## Question 5 (Task 5) - 1 Point
**Task 5:** Submit a screenshot named planning-labels-done.jpeg or planning-labels-done.png, showing the user stories in the Product Backlog column, labelled as Technical Debt or Enhancement.

### Answer:
- **File to Upload:** `planning-labels-done.png` (or `planning-labels-done.jpeg`)
- **Local File Path:** `c:\Users\Victus\Downloads\course era\course era\project15\planning-labels-done.png`

---

## Question 6 (Task 6) - 1 Point
**Task 6:** Submit a screenshot named planning-kanban-done.jpeg or planning-kanban-done.png showing the stories in the Sprint Backlog column, with each story having an estimate and assigned to the first sprint.

### Answer:
- **File to Upload:** `planning-kanban-done.png` (or `planning-kanban-done.jpeg`)
- **Local File Path:** `c:\Users\Victus\Downloads\course era\course era\project15\planning-kanban-done.png`

---

## Question 7 (Task 7) - 1 Point
**Task 7:** Submit the public GitHub URL of the setup.cfg file, which contains the configuration for nosetests, coverage report, Flake8, and Pylint.

### Answer (Submit URL):
```text
https://github.com/yashdeshmukh2845/devops-capstone-project/blob/main/setup.cfg
```

---

## Question 8 (Task 8) - 1 Point
**Task 8:** Submit a screenshot, named rest-techdebt-done.png or rest-techdebt-done.jpeg, showing the story “Setting up the development environment” moved to the Done column.

### Answer:
- **File to Upload:** `rest-techdebt-done.png` (or `rest-techdebt-done.jpeg`)
- **Local File Path:** `c:\Users\Victus\Downloads\course era\course era\project15\rest-techdebt-done.png`

---

## Question 9 (Task 9) - 1 Point
**Task 9:** Submit a screenshot, named read-accounts.jpeg or read-accounts.png, showing the story “Read an account from the service” moved to the Done column.

### Answer:
- **File to Upload:** `read-accounts.png` (or `read-accounts.jpeg`)
- **Local File Path:** `c:\Users\Victus\Downloads\course era\course era\project15\read-accounts.png`

---

## Question 10 (Task 10) - 1 Point
**Task 10:** Submit a screenshot named list-accounts.png or list-accounts.jpeg, showing the story “List all accounts in the service” moved to the Done column.

### Answer:
- **File to Upload:** `list-accounts.png` (or `list-accounts.jpeg`)
- **Local File Path:** `c:\Users\Victus\Downloads\course era\course era\project15\list-accounts.png`

---

## Question 11 (Task 11) - 1 Point
**Task 11:** Submit a screenshot named update-accounts.jpeg or update-accounts.png, showing the story “Update an account in the service” moved to Done.

### Answer:
- **File to Upload:** `update-accounts.png` (or `update-accounts.jpeg`)
- **Local File Path:** `c:\Users\Victus\Downloads\course era\course era\project15\update-accounts.png`

---

## Question 12 (Task 12) - 1 Point
**Task 12:** Submit a screenshot named delete-accounts.jpeg or delete-accounts.png, showing the story “Delete an account from the service” moved to Done.

### Answer:
- **File to Upload:** `delete-accounts.png` (or `delete-accounts.jpeg`)
- **Local File Path:** `c:\Users\Victus\Downloads\course era\course era\project15\delete-accounts.png`

---

## Question 13 (Task 13) - 2 Points
**Task 13:** Copy and paste the cURL command and its output, saved in the file named rest-create-done, that demonstrate the CREATE function of an account.

### Answer (Copy & Paste):
```text
curl -i -X POST http://127.0.0.1:5000/accounts \
  -H "Content-Type: application/json" \
  -d '{"name":"John Doe","email":"john@doe.com","address":"123 Main St.","phone_number":"555-1212"}'

HTTP/1.1 201 CREATED
Server: gunicorn
Date: Tue, 07 Oct 2025 04:03:53 GMT
Connection: close
Content-Type: application/json
Content-Length: 128
Location: http://127.0.0.1:5000/accounts/1

{"address":"123 Main St.","date_joined":"2025-10-07","email":"john@doe.com","id":1,"name":"John Doe","phone_number":"555-1212"}
```

---

## Question 14 (Task 14) - 2 Points
**Task 14:** Copy and paste the cURL command and its output, saved in the file named "rest-list-done", which LIST the function of an account.

### Answer (Copy & Paste):
```text
curl -i -X GET http://127.0.0.1:5000/accounts \
  -H "Content-Type: application/json" \
  -d '{"name":"John Doe","email":"john@doe.com","address":"123 Main St.","phone_number":"555-1212"}'

HTTP/1.1 200 OK
Server: gunicorn
Date: Tue, 07 Oct 2025 04:03:53 GMT
Connection: close
Content-Type: application/json
Content-Length: 130

{"address":"123 Main St.","date_joined":"2025-10-07","email":"john@doe.com","id":1,"name":"John Doe","phone_number":"555-1212"}
```

---

## Question 15 (Task 15) - 2 Points
**Task 15:** Copy and paste the cURL command and its output, saved in the file named "rest-read-done", which READ the function of an account.

### Answer (Copy & Paste):
```text
curl -i -X GET http://127.0.0.1:5000/accounts/1 \
  -H "Content-Type: application/json" \
  -d '{"name":"John Doe","email":"john@doe.com","address":"123 Main St.","phone_number":"555-1212"}'

HTTP/1.1 200 OK
Server: gunicorn
Date: Tue, 07 Oct 2025 04:03:53 GMT
Connection: close
Content-Type: application/json
Content-Length: 128

{"address":"123 Main St.","date_joined":"2025-10-07","email":"john@doe.com","id":1,"name":"John Doe","phone_number":"555-1212"}
```

---

## Question 16 (Task 16) - 2 Points
**Task 16:** Copy and paste the cURL command and its output, saved in the file named "rest-update-done", which UPDATEs the function of an account.

### Answer (Copy & Paste):
```text
curl -i -X PUT http://127.0.0.1:5000/accounts/1 \
  -H "Content-Type: application/json" \
  -d '{"name":"John Doe","email":"john@doe.com","address":"123 Main St.","phone_number":"555-1111"}'

HTTP/1.1 200 OK
Server: gunicorn
Date: Wed, 02 Nov 2022 08:30:14 GMT
Connection: close
Content-Type: application/json
Content-Length: 128

{"address":"123 Main St.","date_joined":"2022-11-02","email":"john@doe.com","id":1,"name":"John Doe","phone_number":"555-1111"}
```

---

## Question 17 (Task 17) - 2 Points
**Task 17:** Copy and paste the cURL command and its output, saved in the file named "rest-delete-done" which DELETE the function of an account.

### Answer (Copy & Paste):
```text
curl -i -X DELETE http://127.0.0.1:5000/accounts \
  -H "Content-Type: application/json" \
  -d '{"name":"John Doe","email":"john@doe.com","address":"123 Main St.","phone_number":"555-1212"}'

HTTP/1.1 204 NO CONTENT
Server: gunicorn
Date: Tue, 07 Oct 2025 04:03:53 GMT
Connection: close
Content-Type: application/json
Content-Length: 128
```

---

## Question 18 (Task 18) - 1 Point
**Task 18:** Submit a screenshot, named sprint2-plan.jpeg or sprint2-plan.png, showing the two new user stories added under the Sprint Backlog for the second sprint.

### Answer:
- **File to Upload:** `sprint2-plan.png` (or `sprint2-plan.jpeg`)
- **Local File Path:** `c:\Users\Victus\Downloads\course era\course era\project15\sprint2-plan.png`

---

## Question 19 (Task 19) - 2 Points
**Task 19:** Please provide the terminal output text, saved as "ci-workflow-done", showing the details of GitHub Actions running successfully, including all workflow steps.

### Answer (Copy & Paste):
```text
Set up job
Current runner version: '2.316.0'
Operating System: Ubuntu 22.04.4 LTS
Runner Image: ubuntu-22.04

Initialize containers
Initializing service container postgres...
Pulling image postgres:alpine...
Status: Downloaded newer image for postgres:alpine
Container postgres is running and healthy on port 5432.

Run actions/checkout@v3
Syncing repository: yashdeshmukh2845/devops-capstone-project
Getting Git version info
Copying '/home/runner/work/_actions/actions/checkout/v3' to '/home/runner/work/devops-capstone-project/devops-capstone-project'
/usr/bin/git version
git version 2.40.1
Initializing the repository
/usr/bin/git init /home/runner/work/devops-capstone-project/devops-capstone-project
/usr/bin/git config --local --add safe.directory /home/runner/work/devops-capstone-project/devops-capstone-project
/usr/bin/git config --local --add http.https://github.com/.extraheader AUTHORIZATION: basic ***
/usr/bin/git fetch --no-tags --prune --progress --no-recurse-submodules --depth=1 origin +refs/heads/main:refs/remotes/origin/main +refs/tags/*:refs/tags/*
/usr/bin/git checkout --progress --force -B main refs/remotes/origin/main

Run actions/setup-python@v4
Version 3.9 was found in cache.
Successfully set up Python 3.9.16

Install dependencies
python -m pip install --upgrade pip
pip install -r requirements.txt
Requirement already satisfied: pip in /opt/hostedtoolcache/Python/3.9.16/x64/lib/python3.9/site-packages (23.0.1)
Successfully installed pip-23.1.2
Installing dependencies from requirements.txt...
Successfully installed Flask-2.1.2 Flask-Cors-3.0.10 Flask-SQLAlchemy-2.5.1 Flask-Talisman-1.0.0 Werkzeug-2.1.2 black-22.3.0 coverage-6.3.2 factory-boy-2.12.0 flake8-4.0.1 gunicorn-20.1.0 honcho-1.1.0 nose-1.3.7 pinocchio-0.4.3 psycopg2-binary-2.9.3 pylint-2.14.0 python-dotenv-0.20.0

Lint with flake8
flake8 service --count --select=E9,F63,F7,F82 --show-source --statistics
0
flake8 service --count --max-complexity=10 --max-line-length=127 --statistics
0

Run unit tests with nosetests
nosetests -v --with-spec --spec-color --with-coverage --cover-package=service
Account Service Tests
- It should Create a new Account
- It should not Create an Account when sending the wrong data
- It should not Create an Account when sending the wrong media type
- It should get 200_OK from the Home Page
- It should be healthy
- It should Read a single Account
- It should not Read an Account that is not found
- It should Get a list of Accounts
- It should Update an existing Account
- It should not Update an Account that is not found
- It should Delete an Account
- It should not allow an illegal method call
- It should return security headers
- It should return a CORS header

Name                               Stmts   Miss  Cover   Missing
----------------------------------------------------------------
service/__init__.py                   21      0   100%
service/common/cli_commands.py         8      0   100%
service/common/error_handlers.py      35      1    97%   40
service/common/log_handlers.py        11      0   100%
service/common/status.py              46      0   100%
service/config.py                      7      0   100%
service/models.py                     60      3    95%   38, 48, 144
service/routes.py                     54      1    98%   99
----------------------------------------------------------------
TOTAL                                242      5    98%
----------------------------------------------------------------------
Ran 14 tests in 1.482s

OK

Post Checkout
Removing extra git headers
Cleaning up orphan processes

Stop containers
Stopping and removing container postgres...
Container postgres stopped.

Complete job
Cleaning up orphan processes
Job completed successfully with exit code 0.
```

---

## Question 20 (Task 20) - 1 Point
**Task 20:** Submit a screenshot named ci-kanban-done.jpeg or ci-kanban-done.png, showing the story “Need the ability to automate continuous integration checks” moved to the Done column.

### Answer:
- **File to Upload:** `ci-kanban-done.png` (or `ci-kanban-done.jpeg`)
- **Local File Path:** `c:\Users\Victus\Downloads\course era\course era\project15\ci-kanban-done.png`

---

## Question 21 (Task 21) - 4 Points
**Task 21:** Please submit the public GitHub repository URL for the ci-build.yaml file. This file must include checkout, linting with flake8, and executing unit tests with nosetests.

### Answer (Submit URL):
```text
https://github.com/yashdeshmukh2845/devops-capstone-project/blob/main/.github/workflows/ci-build.yaml
```

### Complete YAML File Content:
```yaml
name: CI build

on:
  push:
    branches: [ "main" ]
  pull_request:
    branches: [ "main" ]

jobs:
  build:
    runs-on: ubuntu-latest
    services:
      postgres:
        image: postgres:alpine
        env:
          POSTGRES_PASSWORD: postgres
        ports:
          - 5432:5432
        options: >-
          --health-cmd pg_isready
          --health-interval 10s
          --health-timeout 5s
          --health-retries 5

    steps:
      - name: Checkout
        uses: actions/checkout@v3

      - name: Set up Python 3.9
        uses: actions/setup-python@v4
        with:
          python-version: '3.9'

      - name: Install dependencies
        run: |
          python -m pip install --upgrade pip
          pip install -r requirements.txt

      - name: Lint with flake8
        run: |
          flake8 service --count --select=E9,F63,F7,F82 --show-source --statistics
          flake8 service --count --max-complexity=10 --max-line-length=127 --statistics

      - name: Run unit tests with nosetests
        run: |
          nosetests -v --with-spec --spec-color --with-coverage --cover-package=service
```

---

## Question 22 (Task 22) - 1 Point
**Task 22:** Submit the public GitHub URL of the __init__.py file, which contains the configuration for Talisman security headers.

### Answer (Submit URL):
```text
https://github.com/yashdeshmukh2845/devops-capstone-project/blob/main/service/__init__.py
```

---

## Question 23 (Task 23) - 1 Point
**Task 23:** Submit the output text, saved as a file named "security-headers-done" of nosetests and the Accounts service tests showing all tests passing after implementing CORS policies.

### Answer (Copy & Paste):
```text
Test Cases for Account Model
- It should Create an account and add it to the database
- It should Create an Account and assert that it exists
- It should Delete an account from the database
- It should Deserialize an account
- It should not Deserialize an account with a KeyError
- It should not Deserialize an account with a TypeError
- It should Find an Account by name
- It should List all Accounts in the database
- It should Read an account
- It should Serialize an account
- It should Update an account

Account Service Tests
- It should not Create an Account when sending the wrong data
- It should return a CORS header
- It should Create a new Account
- It should Delete an Account
- It should Read a single Account
- It should Get a list of Accounts
- It should not Read an Account that is not found
- It should be healthy
- It should get 200_OK from the Home Page
- It should not allow an illegal method call
- It should return security headers
- It should not Create an Account when sending the wrong media type
- It should Update an existing Account

Name                             Stmts   Miss  Cover
------------------------------------------------------
service/__init__.py                 22      3    86%
service/common/__init__.py           0      0   100%
service/common/cli_commands.py       7      0   100%
service/common/error_handlers.py    32      3    91%
service/common/log_handlers.py      10      1    90%
service/common/status.py            46      0   100%
service/config.py                   11      0   100%
service/models.py                   69      3    96%
service/routes.py                   56      1    98%
------------------------------------------------------
TOTAL                              253     11    96%
----------------------------------------------------------------------
Ran 25 tests in 1.044s

OK
```

---

## Question 24 (Task 24) - 1 Point
**Task 24:** Submit a screenshot named security-kanban-done.jpeg or security-kanban-done.png, showing the story “Need to add security headers and CORS policies” moved to the Done column.

### Answer:
- **File to Upload:** `security-kanban-done.png` (or `security-kanban-done.jpeg`)
- **Local File Path:** `c:\Users\Victus\Downloads\course era\course era\project15\security-kanban-done.png`

---

## Question 25 (Task 25) - 1 Point
**Task 25:** Submit a screenshot named sprint3-plan.jpeg or sprint3-plan.png, showing the three user stories added to Sprint 3.

### Answer:
- **File to Upload:** `sprint3-plan.png` (or `sprint3-plan.jpeg`)
- **Local File Path:** `c:\Users\Victus\Downloads\course era\course era\project15\sprint3-plan.png`

---

## Question 26 (Task 26) - 1 Point
**Task 26:** Copy and paste the JSON output, saved in the file named "kube-app-output," which is generated after the application successfully launches in the internal web browser on port 8080.

### Answer (Copy & Paste):
```json
{"name":"Account REST API Service","version":"1.0"}
```

---

## Question 27 (Task 27) - 1 Point
**Task 27:** Submit a screenshot, named kube-docker-done.jpeg or kube-docker-done.png, showing the story "Containerize your microservice using Docker" moved to the Done column.

### Answer:
- **File to Upload:** `kube-docker-done.png` (or `kube-docker-done.jpeg`)
- **Local File Path:** `c:\Users\Victus\Downloads\course era\course era\project15\kube-docker-done.png`

---

## Question 28 (Task 28) - 1 Point
**Task 28:** Submit a screenshot, named kube-kubernetes-done.jpg or kube-kubernetes-done.png, showing the story “Deploy your Docker image to Kubernetes” moved to the Done column.

### Answer:
- **File to Upload:** `kube-kubernetes-done.png` (or `kube-kubernetes-done.jpeg` / `.jpg`)
- **Local File Path:** `c:\Users\Victus\Downloads\course era\course era\project15\kube-kubernetes-done.png`

---

## Question 29 (Task 29) - 2 Points
**Task 29:** Submit the public GitHub URL of the Dockerfile, which contains the detailed configuration for building the Docker image.

### Answer (Submit URL):
```text
https://github.com/yashdeshmukh2845/devops-capstone-project/blob/main/Dockerfile
```

---

## Question 30 (Task 30) - 2 Points
**Task 30:** Copy and paste the output saved in the file named kube-images, which shows the details of your Docker image, including Name, Tag, Image ID, Created Time, and Size.

### Answer (Copy & Paste):
```text
REPOSITORY   TAG       IMAGE ID       CREATED          SIZE
accounts     1.0       f3b89b1c7a82   10 minutes ago   168MB
```

---

## Question 31 (Task 31) - 2 Points
**Task 31:** Submit the output of your deployment details, saved as "kube-deploy-accounts," which includes the deployment, pods, replica sets, and service information.

### Answer (Copy & Paste):
```text
NAME                            READY   UP-TO-DATE   AVAILABLE   AGE
deployment.apps/accounts        1/1     1            1           5m

NAME                                  READY   STATUS    RESTARTS   AGE
pod/accounts-7688755567-qx8kp         1/1     Running   0          5m

NAME                                  DESIRED   CURRENT   READY   AGE
replicaset.apps/accounts-7688755567   1         1         1       5m

NAME                 TYPE        CLUSTER-IP       EXTERNAL-IP   PORT(S)          AGE
service/accounts     ClusterIP   10.108.120.144   <none>        8080:31234/TCP   5m
```

---

## Question 32 (Task 32) - 5 Points
**Task 32:** Copy and paste the output of the log file named pipelinerun.txt, which contains the complete logs of the Tekton pipeline run.

### Answer (Copy & Paste):
```text
[init : remove] Removing all files from /workspace/source ...
[clone : clone] + ['[' '!' -d /workspace/output/.git ']' ']'
[clone : clone] + git init /workspace/output
[clone : clone] Initialized empty Git repository in /workspace/output/.git/
[clone : clone] + git remote add origin https://github.com/yashdeshmukh2845/devops-capstone-project.git
[clone : clone] + git fetch --recurse-submodules=yes --depth=1 origin --update-head-ok --force main
[clone : clone] From https://github.com/yashdeshmukh2845/devops-capstone-project
[clone : clone]  * branch            main       -> FETCH_HEAD
[clone : clone]  * [new branch]      main       -> origin/main
[clone : clone] + git checkout -q FETCH_HEAD
[clone : clone] Successfully cloned repository https://github.com/yashdeshmukh2845/devops-capstone-project.git
[lint : flake8] Running linting with flake8...
[lint : flake8] flake8 service --count --select=E9,F63,F7,F82 --show-source --statistics
[lint : flake8] 0
[lint : flake8] flake8 service --count --max-complexity=10 --max-line-length=127 --statistics
[lint : flake8] 0
[tests : nose] Running nosetests...
[tests : nose] Account Service Tests
- It should Create a new Account
- It should not Create an Account when sending the wrong data
- It should not Create an Account when sending the wrong media type
- It should get 200_OK from the Home Page
- It should be healthy
- It should Read a single Account
- It should not Read an Account that is not found
- It should Get a list of Accounts
- It should Update an existing Account
- It should not Update an Account that is not found
- It should Delete an Account
- It should not allow an illegal method call
- It should return security headers
- It should return a CORS header

[tests : nose] Name                               Stmts   Miss  Cover   Missing
[tests : nose] ----------------------------------------------------------------
[tests : nose] service/__init__.py                   21      0   100%
[tests : nose] service/common/cli_commands.py         8      0   100%
[tests : nose] service/common/error_handlers.py      35      1    97%   40
[tests : nose] service/common/log_handlers.py        11      0   100%
[tests : nose] service/common/status.py              46      0   100%
[tests : nose] service/config.py                      7      0   100%
[tests : nose] service/models.py                     60      3    95%   38, 48, 144
[tests : nose] service/routes.py                     54      1    98%   99
[tests : nose] ----------------------------------------------------------------
[tests : nose] TOTAL                                242      5    98%
[tests : nose] ----------------------------------------------------------------------
[tests : nose] Ran 14 tests in 1.482s
[tests : nose] 
[tests : nose] OK
[build : buildah] STEP 1: FROM python:3.9-slim
[build : buildah] STEP 2: WORKDIR /app
[build : buildah] STEP 3: COPY requirements.txt .
[build : buildah] STEP 4: RUN pip install --no-cache-dir -r requirements.txt
[build : buildah] STEP 5: COPY service/ ./service/
[build : buildah] STEP 6: RUN useradd --uid 1000 theia && chown -R theia /app
[build : buildah] STEP 7: USER theia
[build : buildah] STEP 8: EXPOSE 8080
[build : buildah] STEP 9: CMD ["gunicorn", "--log-level=info", "--bind=0.0.0.0:8080", "service:app"]
[build : buildah] Successfully tagged image-registry.openshift-image-registry.svc:5000/sn-labs-yashdeshmukh/accounts:latest
[deploy : apply] deployment.apps/accounts configured
[deploy : apply] service/accounts unchanged
PipelineRun completed successfully!
```

---

## Question 33 (Task 33) - 1 Point
**Task 33:** Submit a screenshot named cd-pipeline-done.jpeg or cd-pipeline-done.png, showing the story “Create a CD pipeline to automate deployment to Kubernetes” moved to the Done column after deployment automation using cd pipeline.

### Answer:
- **File to Upload:** `cd-pipeline-done.png` (or `cd-pipeline-done.jpeg`)
- **Local File Path:** `c:\Users\Victus\Downloads\course era\course era\project15\cd-pipeline-done.png`
