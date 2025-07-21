# 👋 Hello, I'm Gaurav Butke

🎯 **Business Analyst | Data Enthusiast | Insight Seeker**

---

## 💼 About Me

🔹 I am a detail-oriented **Business Analyst** with a passion for transforming data into actionable insights.  
🔹 I thrive on solving business problems using data, dashboards, and storytelling.  
🔹 My goal is to help businesses make smarter, data-driven decisions.  

---

## 🎓 Education & Skills

🎓 Master's Degree  
📊 Tools of Expertise:
- **Microsoft Excel** (Advanced)
- **SQL** (Complex queries, Joins, CTEs)
- **Power BI** (Dynamic dashboards, DAX)
- **Tableau** (Visual storytelling, Interactive dashboards)

🛠️ Data Cleaning | Visualization | Dashboard Design | Reporting | KPIs & Metrics

---

## 💡 Projects

📁 **Sales Performance Dashboard (Power BI)**  
Designed a dynamic dashboard tracking regional sales performance, monthly trends, and top-selling products.
* 📂 Projects: [Super Market (Dashboard)](https://public.tableau.com/views/Dashboard1_17408118468570/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


📁 **Customer Segmentation Analysis (SQL + Tableau)**  
Performed in-depth segmentation of customer base to identify retention opportunities and revenue drivers.

---

## 🔍 What I’m Working On

- Learning **Python** for data analysis  
- Exploring **Advanced Power BI techniques**  
- Reading about **data-driven decision making**

---

## 🌐 Let's Connect

🔗 [LinkedIn](https://www.linkedin.com/in/gauravbutke)  
📧 E-Mail(gauravbutke4@email.com) 
📍 Based in India | Open to global opportunities

---

## 🚀 GitHub Stats

![Gaurav's GitHub stats](https://github-readme-stats.vercel.app/api?username=gauravbutke&show_icons=true&theme=radical)

---

## 🧠 Fun Fact

I believe that **every dataset has a story**—and I love telling that story through impactful visuals.

---

_Thanks for visiting! Feel free to explore my repositories._  
⭐️ _If you like what you see, give a star and let’s connect!_



<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Business Analyst Dashboard</title>
  <meta name="description" content="Business Dashboard by Gaurav Butke" />
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet"/>
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
  <style>
    body {
      background-color: #f4f6f9;
    }
    .dashboard-header {
      background-color: #343a40;
      color: white;
      padding: 2rem 1rem;
      text-align: center;
    }
    footer {
      background-color: #dee2e6;
      padding: 1rem;
      text-align: center;
      margin-top: 2rem;
    }
    .card {
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }
  </style>
</head>
<body>

  <header class="dashboard-header">
    <h1>Business Analyst Dashboard</h1>
    <p>Created by Gaurav Butke</p>
  </header>

  <main class="container mt-4">
    <div class="row text-center mb-4">
      <div class="col-md-4">
        <div class="card text-bg-primary mb-3">
          <div class="card-body">
            <h5 class="card-title">Total Revenue</h5>
            <p class="card-text fs-4">$1.5M</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card text-bg-success mb-3">
          <div class="card-body">
            <h5 class="card-title">Active Users</h5>
            <p class="card-text fs-4">5,230</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card text-bg-warning mb-3">
          <div class="card-body">
            <h5 class="card-title">Conversion Rate</h5>
            <p class="card-text fs-4">4.3%</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Chart Section -->
    <div class="row">
      <div class="col-md-12">
        <div class="card mb-4">
          <div class="card-header">Monthly Sales Overview</div>
          <div class="card-body">
            <canvas id="salesChart" height="100"></canvas>
          </div>
        </div>
      </div>
    </div>
  </main>

  <footer>
    Contact: <a href="mailto:gauravbutke4@gmail.com">gauravbutke4@gmail.com</a> <br>
    &copy; 2025 Business Dashboard
  </footer>

  <!-- Chart.js Configuration -->
  <script>
    const ctx = document.getElementById('salesChart').getContext('2d');
    new Chart(ctx, {
      type: 'bar',
      data: {
        labels: ['Jan', 'Feb', 'Mar', 'Apr', 'May', 'Jun', 'Jul'],
        datasets: [{
          label: 'Sales in USD',
          data: [12000, 19000, 17000, 22000, 24000, 28000, 26000],
          backgroundColor: 'rgba(54, 162, 235, 0.6)',
          borderColor: 'rgba(54, 162, 235, 1)',
          borderWidth: 1
        }]
      },
      options: {
        responsive: true,
        scales: {
          y: {
            beginAtZero: true
          }
        }
      }
    });
  </script>

</body>
</html>
