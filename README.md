# FlareSolverr on Render

This repo deploys [FlareSolverr](https://github.com/FlareSolverr/FlareSolverr) directly to [Render](https://render.com/) using Docker.

## 🚀 Deploy

1. Fork this repo
2. Go to [Render Dashboard](https://dashboard.render.com/)
3. Click **New > Web Service**
4. Connect your forked repo
5. Render will build and deploy automatically

## 🌍 Usage
Your FlareSolverr API will be available at:

```
https://<your-service-name>.onrender.com/v1
```

### Test:
```bash
curl -X POST "https://<your-service-name>.onrender.com/v1"   -H "Content-Type: application/json"   -d '{"cmd":"sessions.create"}'
```
