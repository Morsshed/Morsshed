
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Live Message</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: #f0f0f0;
    }
    h1 {
      color: #2c3e50;
      font-size: 2em;
      animation: fadeIn 2s ease-in-out;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <h1 id="message"></h1>

  <script>
    const message = "Hi, I am Morshed and a Business Intelligence Analyst";
    let i = 0;
    const display = document.getElementById("message");

    function typeWriter() {
      if (i < message.length) {
        display.innerHTML += message.charAt(i);
        i++;
        setTimeout(typeWriter, 100); // Adjust speed here
      }
    }

    typeWriter();
  </script>
</body>
</html>


## 👋 Hi, I'm **Morshed**
###  Business Intelligence Developer | Data Analyst | Insight Builder

I'm a **Microsoft certified Business Intelligence Analyst** with a strong passion for transforming data into meaningful insights that support smarter, faster decision-making. I specialize in designing scalable **BI solutions**, building interactive **dashboards**, and creating efficient **data models** that help organizations understand their performance and uncover new opportunities.


## 🛠️ Tech Stack

### BI & Visualization
![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Metabase](https://img.shields.io/badge/Metabase-Business%20Intelligence-509EE3?style=for-the-badge&logo=metabase&logoColor=white)

### ETL / Data Integration
![Power BI Dataflows](https://img.shields.io/badge/Dataflows-ETL%20Pipelines-FFCA28?style=for-the-badge&logo=powerbi&logoColor=black)
![Azure Data Factory](https://img.shields.io/badge/Azure%20Data%20Factory-ETL%20Integration-0078D7?style=for-the-badge&logo=microsoftazure&logoColor=white)

### Databases
![SQL Server](https://img.shields.io/badge/SQL%20Server-Database-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-Cloud%20Warehouse-4285F4?style=for-the-badge&logo=googlebigquery&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Relational%20DB-336791?style=for-the-badge&logo=postgresql&logoColor=white)

### Spreadsheets & Analytics
![Excel](https://img.shields.io/badge/Microsoft%20Excel-Data%20Analysis-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)


### 🔧 Skills in Technologies

            Power BI        🟥🟥🟥🟥🟥🟥🟥🟥⬜⬜      

            Metabase        🟧🟧🟧🟧🟧🟧🟧⬜⬜⬜      

            Dataflows       🟨🟨🟨🟨🟨🟨🟨⬜⬜⬜   

            SQL             🟦🟦🟦🟦🟦🟦🟦🟦🟦⬜

            Excel           🟪🟪🟪🟪🟪🟪🟪🟪⬜⬜

            Google Sheets   🟫🟫🟫🟫🟫🟫🟫🟫⬜⬜
            
### 💡 What I Do
- Develop end-to-end BI dashboards and analytics solutions  
- Build robust data models using SQL, DAX, and ETL pipelines  
- Translate business requirements into insightful visualizations  
- Improve reporting workflows and automate manual processes  
- Collaborate with teams to solve business and data challenges  

### 🎯 My Focus
Creating data solutions that are accurate, scalable, and easy to use — enabling teams to make confident, data-driven decisions.

# Contact Details
Email: binislam70@gmail.com
Linkedin : https://www.linkedin.com/in/morshed-bin-islam-718976301/


