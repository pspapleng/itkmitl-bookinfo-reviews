## How to run with Docker

```bash
# Build Docker Image for review service
docker build -t reviews .

# Run reviews service on port 8082
docker run -d --name my-running-reviews -p 8082:9080 reviews
```

* Test with path `/reviews/1` and `/health`