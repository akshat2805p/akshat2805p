<div align="center">
  <h1>⚙️ akshat-pandey@VIT Bhopal</h1>
  <p><i>"Passionate about Historiography and Photography outside of the terminal."</i></p>
</div>

---

```ini
[Unit]
Description=Akshat Pandey - Software Engineer & System Architect
Documentation=[https://resume-portfolio-sandy.vercel.app/](https://resume-portfolio-sandy.vercel.app/)
Wants=software-engineering-internship.service
After=education.target

[Service]
Type=notify
User=akshat_pandey
WorkingDirectory=/opt/vit-bhopal/btech-cse-2027

# Contact & Endpoints
Environment="EMAIL=akshatpandeygit28@gmail.com"
Environment="LINKEDIN=[https://linkedin.com/in/akshatpandey28](https://linkedin.com/in/akshatpandey28)"
Environment="LEETCODE=[https://leetcode.com/u/akshatpandey28/](https://leetcode.com/u/akshatpandey28/)"

# Current Active Process
ExecStart=/usr/bin/run_fossee_fellow --location="IIT Bombay (Remote)" \
          --task="Optimizing SPICE simulation accuracy in eSim (Ngspice/KiCad)" \
          --collaborators="IIT Bombay Faculty"

# Standard Output / Overview
ExecStartPre=/bin/echo "Computer Science undergraduate (VIT Bhopal, 2027) with hands-on experience in C++, Python, AI inference pipelines, full-stack development, and CI/CD automation."

# Achievements Execution Protocol
ExecStartPost=/bin/echo "🏆 Hackathon Winner: Best Project Award at Devpost Google Gemini Hackathon."
ExecStartPost=/bin/echo "📜 Certification: IBM AI Engineering Professional Certificate verified expertise."
ExecStartPost=/bin/echo "⚔️ Problem Solving: 260+ problems solved on LeetCode across DSA, DP, and graphs."

Restart=always
RestartSec=3

[Install]
WantedBy=multi-user.target
