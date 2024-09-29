FROM python:3.8-slim-buster

COPY movie_review_classification.py /

RUN pip install --no-cache-dir scikit-learn

CMD [ "python", "./movie_review_classification.py" ]
