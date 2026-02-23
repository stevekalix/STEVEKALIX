<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Manikandan S | DevOps Engineer</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #0d1117;
            color: #ffffff;
            line-height: 1.6;
        }

        .container {
            width: 90%;
            max-width: 1100px;
            margin: auto;
            padding: 40px 0;
        }

        h1, h2, h3 {
            color: #ED8B00;
        }

        header {
            text-align: center;
            padding: 60px 20px;
            border-bottom: 1px solid #30363d;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2rem;
            color: #8b949e;
        }

        section {
            margin-top: 50px;
        }

        .skills, .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }

        .card {
            background-color: #161b22;
            padding: 20px;
            border-radius: 10px;
            border: 1px solid #30363d;
        }

        .card ul {
            padding-left: 20px;
        }

        .highlight {
            color: #58a6ff;
        }

        .contact a {
            color: #58a6ff;
            text-decoration: none;
        }

        .contact a:hover {
            text-decoration: underline;
        }

        footer {
            text-align: center;
            margin-top: 60px;
            padding: 20px;
            border-top: 1px solid #30363d;
            color: #8b949e;
        }

        @media (max-width: 600px) {
            header h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>

<body>

<header>
    <h1>Manikandan S</h1>
    <p>Aspiring DevOps Engineer | Spring Boot & Microservices Specialist</p>
</header>

<div class="container">

    <section>
        <h2>Professional Summary</h2>
        <p>
            Computer Science graduate transitioning into 
            <span class="highlight">DevOps Engineering</span> 
            with strong expertise in 
            <span class="highlight">Spring Boot</span> and 
            <span class="highlight">Microservices Architecture</span>. 
            Experienced in building CI/CD pipelines, Infrastructure as Code, and 
            deploying scalable cloud-native systems.
        </p>
    </section>

    <section>
        <h2>Technical Skills</h2>
        <div class="skills">
            <div class="card">
                <h3>Backend & Architecture</h3>
                <ul>
                    <li>Java, Python</li>
                    <li>Spring Boot, Spring Cloud, FastAPI</li>
                    <li>Microservices, REST APIs</li>
                </ul>
            </div>

            <div class="card">
                <h3>DevOps & Cloud</h3>
                <ul>
                    <li>Docker, Kubernetes, Helm</li>
                    <li>Terraform, Ansible</li>
                    <li>GitHub Actions, Jenkins</li>
                    <li>AWS (EC2, EKS, S3, Lambda)</li>
                </ul>
            </div>

            <div class="card">
                <h3>Monitoring & Data</h3>
                <ul>
                    <li>Prometheus, Grafana</li>
                    <li>ELK Stack</li>
                    <li>MySQL, PostgreSQL, MongoDB</li>
                    <li>Kafka, RabbitMQ</li>
                </ul>
            </div>
        </div>
    </section>

    <section>
        <h2>Featured Projects</h2>
        <div class="projects">

            <div class="card">
                <h3>Enterprise Microservices Platform</h3>
                <p><strong>Tech:</strong> Spring Boot, Docker, Kubernetes, Kafka</p>
                <ul>
                    <li>Designed API Gateway & Service Discovery</li>
                    <li>Implemented CI/CD with GitHub Actions</li>
                    <li>Deployed with Kubernetes & Helm</li>
                    <li>Achieved 99.9% uptime</li>
                </ul>
            </div>

            <div class="card">
                <h3>Infrastructure Automation Suite</h3>
                <p><strong>Tech:</strong> Terraform, Ansible, AWS, Jenkins</p>
                <ul>
                    <li>Provisioned AWS infrastructure using Terraform</li>
                    <li>Automated configuration with Ansible</li>
                    <li>Implemented monitoring dashboards</li>
                    <li>100% Infrastructure as Code</li>
                </ul>
            </div>

            <div class="card">
                <h3>Cloud-Native Deployment on EKS</h3>
                <p><strong>Tech:</strong> Docker, Kubernetes, AWS EKS, Istio</p>
                <ul>
                    <li>Zero-downtime deployments</li>
                    <li>Implemented service mesh</li>
                    <li>Integrated Prometheus & Grafana</li>
                    <li>Optimized infrastructure cost by 40%</li>
                </ul>
            </div>

        </div>
    </section>

    <section class="contact">
        <h2>Contact</h2>
        <p>
            📧 Email: <a href="mailto:manirevathi404@gmail.com">manirevathi404@gmail.com</a><br>
            🔗 GitHub: <a href="https://github.com/stevekalix" target="_blank">github.com/stevekalix</a><br>
            💼 LinkedIn: <a href="https://www.linkedin.com/in/manikandan-s-133179364/" target="_blank">LinkedIn Profile</a>
        </p>
    </section>

</div>

<footer>
    © 2026 Manikandan S | DevOps Engineer Portfolio
</footer>

</body>
</html>
