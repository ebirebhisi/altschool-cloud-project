ALT School Africa – Second Semester Cloud Project

 Project Title: Future of Smart Cities: Urban Innovation, Connected Living

This is a dynamic landing page deployed on AWS EC2 using Ubuntu, NGINX, and Tailwind CSS. It showcases real-world cloud engineering skills including server provisioning, web deployment, and Linux administration.



 Author: Ebirebhisi Moren  
Role: Cloud Engineer (Trainee)  
Track: Cloud Engineering – ALT School Africa  



 Project Pitch
 
 Envisions a transformed urban landscape where technology, data, and community converge to create more efficient, sustainable, and livable environments for all.
This project will focus on the integration of IoT (Internet of Things), AI, data analytics, green infrastructure, and urban planning to create interconnected ecosystems where transportation, energy, communication, and public services operate in harmony. By reimagining how cities function, we seek to enhance quality of life, reduce environmental impact, and empower communities through equitable access to resources.

professional Bio

Ebirebhisi Moren is a dedicated and proactive Cloud Engineer (Trainee), building a robust skill set at ALT School Africa in the Cloud Engineering track. With a deep enthusiasm for the transformative power of cloud technology, Ebirebhisi focuses on mastering core cloud infrastructure, DevOps methodologies, and system administration.

Skills & Expertise:

Cloud Platforms: AWS EC2,S3, VPC, IAM.
Web Servers: Nginx,Apache 
Operating Systems: Ubuntu (Linux Administration)
Version Control: Git, GitHub
Frontend: HTML, CSS, Tailwind CSS
Others- Scripting (Bash/Python), Docker, CI/CD tools, Monitoring.

Select Projects:

'Future of Smart Cities: Urban Innovation, Connected Living': Spearheaded the deployment of a dynamic web application prototype on AWS EC2, demonstrating proficiency in server provisioning, Nginx configuration, and public web hosting.
 other relevant past projects includes developing a Python script for automated AWS resource and also Contributed to a team project involving containerized application deployment.
 
Education:

Cloud Engineering Student – ALT School Africa (Current)
BSC.Industrial Mathemaics – University of Benin,Benin city.
Ebirebhisi is committed to becoming one of Africa's leading female engineers, driven by a desire to contribute to a future where technology fosters more efficient, sustainable, and connected living.


 Screenshot

[screenshot](screenshot.png)



  Public IP

> http://54.154.89.106


### How It Was Built

1.  **Provisioned Ubuntu EC2 server (AWS):** An Ubuntu 22.04 LTS instance was launched on Amazon Web Services (AWS) EC2.
2.  **Installed and configured Nginx:** The Nginx web server was installed and configured to serve the landing page content.
3.  **Deployed a Tailwind-based HTML landing page:** A personalized HTML landing page, styled using the Tailwind CSS framework, was deployed to the Nginx web server.
4.  **Networking & Security:**
    * Traffic was allowed over **Port 80 (HTTP)** to enable web access.
    * **Port 443 (HTTPS)** was also opened in the security group to allow for future SSL configuration.

---

### Future Enhancements / Next Steps

* **Implement HTTPS with Let's Encrypt SSL:** Acquire and configure an SSL certificate (using Certbot) to enable secure HTTPS access over Port 443, eliminating the "Not secure" warning. This requires a registered domain name.
* **Obtain a Custom Domain:** Register a custom domain name (e.g., `smartcitiesinnovation.com`) and point it to the EC2 instance's public IP address.
* **Explore Dynamic Content Generation:** Integrate a backend application (e.g., Node.js, Python Flask) with Nginx acting as a reverse proxy, to serve truly dynamic content beyond static HTML.

---

