# Jenkins Declarative Pipeline for Movie DB

This is an example of CICD Pipeline with Security Checks in Python flask application.

- The Job will build [https://github.com/PrabhuVignesh/movie-crud-flask.git](https://github.com/PrabhuVignesh/movie-crud-flask.git)
- Runs Unit Test with `pytest`
- Runs Static application security Testing SAST
	- Common Security Test with `bandit`
	- Dependency Check Scan with python `safety`
	- Static Analysis with `python-taint`