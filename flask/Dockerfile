FROM python:3.9
WORKDIR /app
COPY . .
RUN python -m pip install Flask --trusted-host=pypi.python.org --trusted-host=pypi.org --trusted-host=files.pythonhosted.org 
COPY . .
EXPOSE 3000
CMD ["python","app.py"]