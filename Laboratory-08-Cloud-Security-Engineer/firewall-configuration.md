# Firewall Configuration Documentation

## Commands Used to Secure the Server

1. **Allow SSH Access:**
   ```bash
   sudo ufw allow ssh
Description: This command permanently opens port 22 so that administrators can keep managing the server remotely without getting locked out.

2. Set Default Deny Policy:
sudo ufw default deny incoming
sudo ufw default allow outgoing
Description: These commands configure the foundational firewall rules to automatically block all incoming traffic by default while allowing all outgoing traffic.

3. Allow Port 8080 (Web Application):
sudo ufw allow 8080/tcp
Description: This command creates a specific rule to let legitimate web users access our Nginx application running on port 8080.
