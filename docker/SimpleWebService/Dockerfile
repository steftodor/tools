FROM python:3.8

WORKDIR /usr/src/app

EXPOSE 8000

ENV PYTHONUNBUFFERED=1

# Run python server on container start
CMD ["python", "-m", "http.server", "8000", "--directory", "public_html"]
