# Nginx EC2 Deployment Project
Networking Based Project demonstrating EC2 deployment of Nginx with a custom domain via Cloudflare.

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
- Nginx webpage successfully running on my custom domain (https://www.nufan.uk)
- Learned real-world networking, DNS, and server troubleshooting
  
<img width="959" height="539" alt="Screenshot 2025-11-08 182327" src="https://github.com/user-attachments/assets/07a8e330-942e-423f-8bbc-094f8e9d0f21" />





