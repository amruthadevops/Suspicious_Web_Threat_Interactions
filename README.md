
# Suspicious Web Threat Interactions
This project aims to detect and analyze patterns in web interactions to identify suspicious or potentially harmful activities. By leveraging AWS CloudWatch logs and data visualization tools, we can uncover hidden threats and enhance cybersecurity measures


## Overview

With the increasing complexity of web-based threats, it's crucial to monitor and analyze web traffic to detect anomalies. This project utilizes AWS CloudWatch logs to identify patterns indicative of malicious activities, such as:

Unusual HTTP status codes

Frequent access attempts from specific IP addresses

Suspicious URL patterns

Anomalous user-agent strings

## Project Structure
```bash
Suspicious_Web_Threat_Interactions/
├── CloudWatch_Traffic_Web_Attack.csv
├── Suspicious_Web_Threat_Interactions_Analysis_Report.pbix
├── main.ipynb
├── requirements.txt
└── README.md
```
CloudWatch_Traffic_Web_Attack.csv: Dataset containing web traffic logs.

Suspicious_Web_Threat_Interactions_Analysis_Report.pbix: Power BI report for data visualization.

main.ipynb: Jupyter Notebook containing data analysis and threat detection logic.

requirements.txt: List of Python dependencies
## Installation

1. Clone the repository:
```bash
  git clone https://github.com/amruthadevopsSuspicious_Web_Threat_Interactions.git
  cd Suspicious_Web_Threat_Interactions
```

2. Set up a virtual environment (optional but recommended):
```bash
  python3 -m venv venv
  source venv/bin/activate  # On Windows:venv\Scripts\activate

```
3. Install the required dependencies:

```bash
  pip install -r requirements.txt
```
## Usage/Examples
1. Open the Jupyter Notebook:

```bash

jupyter notebook main.ipynb
```
2. Run the cells sequentially:

    Load and preprocess the dataset.

    Perform exploratory data analysis (EDA).

    Identify and flag suspicious activities based on predefined rules and patterns.

3. Review the findings:

    Analyze the output to understand the nature and frequency of detected threats.

## 📓 Analysis & Results

The analysis focuses on identifying anomalies in web traffic, such as:

    1.Repeated failed login attempts:

    2.Detecting IP addresses with multiple failed login attempts within a short time frame.

    3.Access to sensitive endpoints:

    4.Monitoring requests to endpoints like /admin, /login, /wp-admin, etc.

    5.Unusual user-agent strings:

    6.Identifying requests made using tools like curl, wget, or outdated browsers.

    7.High frequency of requests:

    8.Flagging IP addresses that make an unusually high number of requests in a given period.

Example visualization:
1. Heatmap for the correlation matrix

    ![Image](https://github.com/user-attachments/assets/9956c222-011a-4492-bf2c-1ec666cb9e68)
3. Stacked Bar Chart for Detection Types by Country
   
   ![Image](https://github.com/user-attachments/assets/58c04298-ec79-46b2-b20f-936c89f97239)
5. Plotting the training history

   ![Image](https://github.com/user-attachments/assets/69e21313-4e18-4d35-8dff-90114ea6d6e9)
   ![Image](https://github.com/user-attachments/assets/afd47bf2-a233-44a0-9875-90380b21ce72)
   ![Image](https://github.com/user-attachments/assets/1bda15bb-cab3-42b7-9c5c-f519586eadfc)
   ![Image](https://github.com/user-attachments/assets/e6da267c-3729-40f5-8243-0ab7cd426673)

## 📊 Power BI Dashboard
The Suspicious_Web_Threat_Interactions_Analysis_Report.pbix file presents the same data in an interactive format using Power BI.

  ![Image](https://github.com/user-attachments/assets/3b185e55-c61f-41b3-b621-c80b8a296c92)



Contributing
Contributions are welcome! Please follow these steps:

1. Fork the repository.

2. Create a new branch:

```bash

git checkout -b feature/your-feature-name
```
3. Commit your changes:
```
git commit -m "Add your message here"
```
4. Push to the branch:
```
git push origin feature/your-feature-name
```
6. Open a pull request.



## Authors

- [AMRUTHA C](https://www.linkedin.com/in/amrutha-c-4a2362280/)
  
.NET Developer | Python Data Analyst | Power BI Enthusiast
