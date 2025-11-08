# Nginx EC2 Deployment Project
Project demonstrating EC2 deployment of Nginx with a custom domain via Cloudflare.

## Goals
- Deploy an EC2 instance running Nginx
- Connect a custom domain via Cloudflare
- Troubleshoot connectivity issues (Cloudflare 521 error)

## Steps Taken
1. Launched Ubuntu EC2 instance and installed Nginx on it.
2. Configured security group to allow ports 22, 80, 443
3. Purchased domain via Cloudflare and added A record pointing to EC2 public IP
4. Resolved Cloudflare 521 error by setting SSL/TLS mode to Flexible
5. Verified website accessible via `www.nufan.uk`

## Outcome
- Nginx webpage successfully running on my custom domain
- Learned real-world networking, DNS, and server troubleshooting

https://github.com/user-attachments/assets/fdf833f8-2c1e-448b-8927-cb005483213d



