# Cost-Optimizer-AI-Agent

<img width="425" height="292" alt="Screenshot 2025-08-05 113304" src="https://github.com/user-attachments/assets/47a52d43-7e61-4cab-966f-c3eadae01f85" />


<h1>Cost Optimizer AI Agent for Cloud Infrastructure</h1>
Developed an AI-powered cost optimization agent using CrewAI and the OpenAI API to analyze cloud infrastructure spending and recommend targeted cost-saving strategies.

The project leverages multi-agent collaboration, where one agent identifies inefficiencies in cloud services (AWS, Azure, GCP), and another agent provides actionable optimization recommendations without impacting system performance.

Built in Python with secure API key management via .env files and executed in a controlled Windows + Python virtual environment using PowerShell.

<h2>Key Features</h2>
- Multi-Agent Architecture: Dedicated analysis and recommendation agents powered by CrewAI.

- Cloud Cost Analysis: Detects high-cost services and potential waste.

- Optimization Recommendations: Suggests resource downsizing, service removal, and savings plan options.

- Secure API Integration: OpenAI API key stored securely in .env and loaded via python-dotenv.

- Extensible Design: Ready for integration with AWS Cost Explorer, Azure Cost Management, or GCP Billing APIs for real-time data.


  
<h2>Environments and Technologies Used</h2>

- Python Virtual Environment
- Visual Studio Code (VS Code)
- Python 3.x
- PowerShell
- CrewAI
- OpenAI API
- python-dotenv


<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10/11 (21H2)
- Python Virtual Environment (costOptimizerEnv)

<h2>High-Level Deployment and Configuration Steps</h2>

- PHASE 1: SETUP ENVIRONMENT
- PHASE 2: PROJECT STRUCTURE
- PHASE 3: DEFINE ENV VARIABLES (.env) (API KEY)
- PHASE 4: DEFINE AGENTS
- PHASE 5: DEFINE TASKS
- PHASE 6: UTILITIES
- PHASE 7: MAIN SCRIPT
- PHASE 8: RUN THE AGENT




<h2>Deployment and Configuration Steps</h2>

PHASE 1: SETUP ENVIRONMENT

- Here I just created the virtual enviornment.

<img width="968" height="361" alt="Screenshot 2025-08-05 090457" src="https://github.com/user-attachments/assets/38947a6e-b868-4b27-bc2c-78569f6ed81d" />

- Here I installed CrewAI and the Python Packages needed

<img width="973" height="292" alt="Screenshot 2025-08-05 093558" src="https://github.com/user-attachments/assets/6f10254b-d05a-40ab-85f5-51dd14f9b74d" />
<img width="956" height="289" alt="Screenshot 2025-08-05 093612" src="https://github.com/user-attachments/assets/9afbe9e1-35d2-4d81-99e9-3484a67ac3d7" />

PHASE 2: PROJECT STRUCTURE

This step is where I create the folders and files for the project so I can organize the code before I start typing anything into them.

<img width="881" height="926" alt="Screenshot 2025-08-05 094112" src="https://github.com/user-attachments/assets/9695bf98-51e8-4e7d-941c-538da9627116" />
<img width="959" height="853" alt="Screenshot 2025-08-05 094131" src="https://github.com/user-attachments/assets/a4cabc34-1a3b-480a-8dc9-33d878676364" />

PHASE 3: DEFINE ENV VARIABLES (.env) (API KEY)

- For security reasons, I'm not going to show my actual API key here.

<img width="1125" height="769" alt="Screenshot 2025-08-05 095115" src="https://github.com/user-attachments/assets/2139927e-9321-4193-967b-0c0ab10d05f0" />

PHASE 4: DEFINE AGENTS

Here I develop the Python script to create the AI Agents.

<img width="1053" height="330" alt="Screenshot 2025-08-05 095922" src="https://github.com/user-attachments/assets/96aed906-5077-403d-bf4b-de121fe6869a" />
<img width="992" height="267" alt="Screenshot 2025-08-05 095933" src="https://github.com/user-attachments/assets/b05399bf-d4d2-4d7e-bc82-4821964be39a" />

PHASE 5: DEFINE TASKS

Here I used a Python script to develop the tasks.

<img width="975" height="406" alt="Screenshot 2025-08-05 101151" src="https://github.com/user-attachments/assets/d2affd8e-122a-4a64-8d5f-a6ae5f858111" />

PHASE 6: UTILITIES

Here I just created extra helpers for the project, in a real case scenario, this will be replaced with actual AWS Cost Explorer

<img width="932" height="314" alt="Screenshot 2025-08-05 101719" src="https://github.com/user-attachments/assets/44e88552-86cd-495b-ae29-7b8ce3a51cb2" />

PHASE 7: MAIN SCRIPT

Here is the main script that will bring everything together.

<img width="1009" height="754" alt="Screenshot 2025-08-05 111128" src="https://github.com/user-attachments/assets/6842ca85-bdf1-4999-9d1d-cd4ef2470d5e" />


PHASE 8: RUN THE AGENT

Here we run the script and watch the agents perform tasks and communicate with each other.

<img width="1506" height="937" alt="Screenshot 2025-08-05 111618" src="https://github.com/user-attachments/assets/5f7ad7b6-596b-4c70-a965-45e6087f32cd" />
<img width="1520" height="564" alt="Screenshot 2025-08-05 111643" src="https://github.com/user-attachments/assets/4906a1e1-0212-4cd1-aea3-58ad2153c2da" />
<img width="1489" height="566" alt="Screenshot 2025-08-05 111658" src="https://github.com/user-attachments/assets/66c40cca-4277-4311-b1ce-f674ab26431c" />
<img width="1498" height="661" alt="Screenshot 2025-08-05 111716" src="https://github.com/user-attachments/assets/ab6a2bb6-ed94-4603-9527-48c6b739a582" />
<img width="1505" height="274" alt="Screenshot 2025-08-05 111737" src="https://github.com/user-attachments/assets/85348044-face-4a93-803d-f9b258d20fdb" />
<img width="1493" height="674" alt="Screenshot 2025-08-05 111751" src="https://github.com/user-attachments/assets/f90ed030-131a-4be6-a305-f0f08ea3f6d7" />
<img width="1515" height="595" alt="Screenshot 2025-08-05 111811" src="https://github.com/user-attachments/assets/f3bb53ec-80bd-4459-8c6a-a13974e3d4c3" />





























































