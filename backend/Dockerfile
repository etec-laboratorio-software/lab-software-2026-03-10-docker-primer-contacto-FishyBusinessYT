FROM python:3.13
RUN pip install uv --root-user-action
WORKDIR /app
COPY pyproject.toml uv.lock ./
RUN uv sync

COPY . .
EXPOSE 3001
CMD ["uv", "run", "app.py"]
