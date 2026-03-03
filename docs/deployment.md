# Deployment Guide

## AWS (Recommended)
1. Configure Terraform variables
2. Run `terraform apply`
3. Deploy with Helm: `helm install flowforge ./helm/flowforge`

## Docker Compose (Development)
```bash
docker-compose up -d
```
