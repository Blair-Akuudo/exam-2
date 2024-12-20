# exam-2
2nd semester alt school exam
# Web Prototype Landing Page
## Public IP Address

- You can view the landing page here: [http://<Public_IP_Address>](http://<34.254.252.254>)

## Public IP Address
- Access the web page: [http://<Public_IP_Address>](http://<34.254.252.254>)
- (Optional) HTTPS: [https://<Public_IP_Address>](https://<https://blessingjonah.mooo.com>)

## Project Description
This repository demonstrates the setup of a web server with a simple HTML landing page. 

## Screenshot
Here’s how the landing page looks:

![Landing Page Screenshot](screenshot1.png.png)

## How to Build the Project
Here’s how the project was created:

1. **Provision a Server**:
   - Used AWS EC2 to create an Ubuntu Linux server.
   - Allowed HTTP and SSH traffic in the security group.

2. **Set Up a Web Server**:
   - Installed Apache2 on the server.
   - Replaced the default Apache page with a custom HTML page.

3. **Deploy the Landing Page**:
   - Created a simple `index.html` file with my bio and project information.
   - Saved it in the `/var/www/html` folder to be served by Apache.

4. **Tested the Page**:
   - Opened a browser and visited `http://<34.254.252.254>` to confirm everything worked.
## Bonus: Added HTTPS
To secure the web server:
1. Installed Certbot to handle SSL certificates.
2. Used Let’s Encrypt to obtain a free SSL certificate.
3. Configured Apache to serve the site over HTTPS.
