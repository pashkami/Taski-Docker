# Taski Docker

Educational Docker project for a task planning application.

## What this project demonstrates

- Containerization of a Python backend service.
- Multi-stage Docker build for a frontend application.
- nginx-based frontend runtime image.
- Basic separation of backend and frontend build contexts.

## Confirmed stack

- Docker
- Python 3.10 backend
- Node.js 18 frontend build stage
- nginx alpine runtime image

## Repository structure

- `backend/Dockerfile` - backend image based on Python 3.10.
- `frontend/Dockerfile` - frontend multi-stage build with Node.js and nginx.

## Portfolio positioning

This is a compact educational repository. It is useful as supporting evidence for Docker basics, but it should not be the main DevOps portfolio project. Stronger portfolio links are the CI/CD, GitOps and DBOps repositories.

## Notes

The repository is kept intentionally small. It shows basic Dockerfile structure and service packaging rather than a complete production deployment pipeline.
