cat > README.md <<'EOF'
# my-fullstack-app

Simple fullstack demo: Flask backend + static frontend served by Nginx.

Local:
- `docker-compose up --build`
Production (EC2):
- use docker images from Docker Hub and `docker-compose -f docker-compose.prod.yml up -d`
EOF
