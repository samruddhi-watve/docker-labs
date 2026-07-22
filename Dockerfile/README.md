# 📄 Dockerfile

A Dockerfile contains instructions to build a Docker image.

---

## Example

```dockerfile
FROM python:3.11-slim

WORKDIR /app

COPY . .

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 5000

CMD ["python","app.py"]
```

---

## Dockerfile Instructions

| Instruction | Purpose |
|------------|---------|
| FROM | Base Image |
| WORKDIR | Working Directory |
| COPY | Copy Files |
| RUN | Execute Commands |
| EXPOSE | Expose Port |
| CMD | Run Application |

---

## Learning Outcome

Understand how Docker builds images.
