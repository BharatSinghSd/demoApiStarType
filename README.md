# demoApiStarType

This is a demo for the FastAPI as covered in W4S3

## Initial setup steps for this:

### setup a virtual environment

- here my env name is **envStarType**

**For Mac OS (if windows version doesn't work)**

- python3 -m venv envStarType

**For windows**

- python -m venv envStarType

---

## Activate the V environment

**For Mac OS**

- source envStarType/bin/activate

**For windows**

- python -m venv environment name

---

## install the dependencies from the requirements file

pip install -r requirements.txt

(install them while in the desired env)

---

## running the api using uvicorn server:

uvicorn main:app
