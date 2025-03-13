FROM python:3.12

# Change le répertoire de travail
WORKDIR /workspace

COPY ../backend /workspace/backend

# Installer les dépendances dans l'environnement virtuel
RUN pip install --no-cache-dir -r /workspace/backend/requirements.txt

CMD ["flask", "run", "--host=0.0.0.0", "--port=5000"]