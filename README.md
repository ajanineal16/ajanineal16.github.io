# ajanineal16.github.io
Resume 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Business Analyst & AI Enthusiast</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            line-height: 1.6;
            color: #1a1a1a;
            background: #f8fafc;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 2rem;
        }

        /* Header */
        header {
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
            color: white;
            padding: 4rem 0 6rem;
        }

        .header-content {
            display: flex;
            flex-direction: column;
            gap: 1.5rem;
        }

        h1 {
            font-size: 3.5rem;
            font-weight: 700;
            line-height: 1.2;
        }

        .subhead {
            font-size: 1.25rem;
            color: #94a3b8;
            max-width: 600px;
        }

        .badge-container {
            display: flex;
            gap: 1rem;
            flex-wrap: wrap;
            margin-top: 1rem;
        }

        .badge {
            background: rgba(255, 255, 255, 0.1);
            padding: 0.5rem 1rem;
            border-radius: 100px;
            font-size: 0.875rem;
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        /* Sections */
        section {
            padding: 4rem 0;
        }

        section:nth-child(even) {
            background: white;
        }

        h2 {
            font-size: 2rem;
            margin-bottom: 2rem;
            color: #0f172a;
        }

        /* Cards */
        .card-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .card {
            background: white;
            border-radius: 12px;
            padding: 2rem;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
            border: 1px solid #e2e8f0;
            transition: transform 0.2s;
        }

        .card:hover {
            transform: translateY(-4px);
        }

        .card h3 {
            font-size: 1.25rem;
            margin-bottom: 1rem;
            color: #0f172a;
        }

        .card-meta {
            color: #64748b;
            font-size: 0.875rem;
            margin-bottom: 1rem;
            display: flex;
            gap: 0.5rem;
            flex-wrap: wrap;
        }

        .tag {
            background: #e2e8f0;
            padding: 0.25rem 0.75rem;
            border-radius: 100px;
            font-size: 0.75rem;
            color: #475569;
        }

        /* Skills */
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }

        .skill-category {
            background: white;
            padding: 1.5rem;
            border-radius: 12px;
            border: 1px solid #e2e8f0;
        }

        .skill-category h3 {
            margin-bottom: 1rem;
            color: #0f172a;
        }

        .skill-list {
            list-style: none;
        }

        .skill-list li {
            margin-bottom: 0.75rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .skill-list li::before {
            content: "▹";
            color: #3b82f6;
        }

        /* Experience */
        .experience-item {
            margin-bottom: 2rem;
            padding-bottom: 2rem;
            border-bottom: 1px solid #e2e8f0;
        }

        .experience-item:last-child {
            border-bottom: none;
        }

        .experience-header {
            display: flex;
            justify-content: space-between;
            align-items: baseline;
            flex-wrap: wrap;
            margin-bottom: 0.5rem;
        }

        .experience-title {
            font-weight: 600;
            font-size: 1.125rem;
            color: #0f172a;
        }

        .experience-company {
            color: #3b82f6;
        }

        .experience-date {
            color: #64748b;
            font-size: 0.875rem;
        }

        /* Projects */
        .project-card {
            background: white;
            border-radius: 12px;
            overflow: hidden;
            border: 1px solid #e2e8f0;
        }

        .project-content {
            padding: 1.5rem;
        }

        .project-links {
            margin-top: 1rem;
            display: flex;
            gap: 1rem;
        }

        .button {
            display: inline-block;
            padding: 0.5rem 1rem;
            background: #0f172a;
            color: white;
            text-decoration: none;
            border-radius: 6px;
            font-size: 0.875rem;
            transition: background 0.2s;
        }

        .button:hover {
            background: #1e293b;
        }

        .button-outline {
            background: transparent;
            border: 1px solid #0f172a;
            color: #0f172a;
        }

        .button-outline:hover {
            background: #f8fafc;
        }

        /* Footer */
        footer {
            background: #0f172a;
            color: white;
            padding: 3rem 0;
            text-align: center;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 2rem;
            margin-bottom: 2rem;
        }

        .social-links a {
            color: white;
            text-decoration: none;
            font-size: 1.25rem;
        }

        /* Responsive */
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5rem;
            }
            
            .container {
                padding: 0 1rem;
            }
            
            .header-content {
                padding: 2rem 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="header-content">
                <h1>Your Full Name</h1>
                <p class="subhead">Business Administration Student | Financial Management | Aspiring AI Systems Builder</p>
                <div class="badge-container">
                    <span class="badge">QuickBooks Expert</span>
                    <span class="badge">Payroll Management</span>
                    <span class="badge">Excel Advanced</span>
                    <span class="badge">Logistics Coordinator</span>
                    <span class="badge">Sales Professional</span>
                </div>
            </div>
        </div>
    </header>

    <!-- Summary Section -->
    <section>
        <div class="container">
            <h2>About Me</h2>
            <div class="card" style="max-width: 800px;">
                <p style="font-size: 1.125rem; margin-bottom: 1rem;">Detail-oriented Business Administration student with hands-on experience in financial management, logistics, and customer-facing roles. Skilled in QuickBooks, Excel, and operational coordination with a strong aptitude for structured problem-solving and systems thinking.</p>
                <p style="color: #475569;">Currently pursuing Associate's Degree in Business Administration at Saint John's Junior College, combining academic knowledge with 5+ years of practical experience in accounting, payroll, and operations management.</p>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section style="background: white;">
        <div class="container">
            <h2>Skills & Expertise</h2>
            <div class="skills-grid">
                <div class="skill-category">
                    <h3>Financial Management</h3>
                    <ul class="skill-list">
                        <li>QuickBooks (5+ years)</li>
                        <li>Payroll Processing</li>
                        <li>Tax Filings</li>
                        <li>Bank Reconciliation</li>
                        <li>Financial Reporting</li>
                    </ul>
                </div>
                <div class="skill-category">
                    <h3>Operations & Logistics</h3>
                    <ul class="skill-list">
                        <li>Inventory Management</li>
                        <li>Supply Chain Coordination</li>
                        <li>Shipping & Receiving</li>
                        <li>Vendor Management</li>
                    </ul>
                </div>
                <div class="skill-category">
                    <h3>Technical & Soft Skills</h3>
                    <ul class="skill-list">
                        <li>Advanced Excel</li>
                        <li>VNC & Computer Literacy</li>
                        <li>Customer Service</li>
                        <li>Problem-Solving</li>
                        <li>Time Management</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Portfolio Projects -->
    <section>
        <div class="container">
            <h2>Portfolio Projects</h2>
            <p style="margin-bottom: 2rem; color: #475569;">Concept projects demonstrating skills relevant to AI voice agents and data systems</p>
            
            <div class="card-grid">
                <div class="card">
                    <h3>Financial Maturity Scoring Model</h3>
                    <div class="card-meta">
                        <span class="tag">Excel</span>
                        <span class="tag">Heuristics</span>
                        <span class="tag">Data Normalization</span>
                    </div>
                    <p>Designed a scoring tool that maps financial health indicators (payroll accuracy, reconciliation speed) to a 1-6 maturity scale. Demonstrates structured thinking and data normalization capabilities relevant to the DCAM Assessment engine.</p>
                </div>

                <div class="card">
                    <h3>Payroll Dashboard Prototype</h3>
                    <div class="card-meta">
                        <span class="tag">Excel</span>
                        <span class="tag">Data Viz</span>
                        <span class="tag">Reporting</span>
                    </div>
                    <p>Created a mock dashboard visualizing payroll trends, tax filing status, and reconciliation metrics. Showcases ability to design reporting pipelines and present complex financial data clearly.</p>
                </div>

                <div class="card">
                    <h3>Stakeholder Interview Flow</h3>
                    <div class="card-meta">
                        <span class="tag">Conversational Design</span>
                        <span class="tag">Miro</span>
                        <span class="tag">Flowcharts</span>
                    </div>
                    <p>Developed an adaptive interview script for financial process discovery. Includes branching logic based on responses — directly applicable to AI voice agent conversation design.</p>
                </div>

                <div class="card">
                    <h3>Sales-to-Systems Case Study</h3>
                    <div class="card-meta">
                        <span class="tag">Reflection</span>
                        <span class="tag">UX Research</span>
                        <span class="tag">Communication</span>
                    </div>
                    <p>Written analysis of how 6 months in sales taught active listening, response adaptation, and customer data tracking — mapping these skills to AI voice agent design principles.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Work Experience -->
    <section style="background: white;">
        <div class="container">
            <h2>Professional Experience</h2>
            
            <div class="experience-item">
                <div class="experience-header">
                    <span class="experience-title">Accountant / Bookkeeper & Financial Controller</span>
                    <span class="experience-date">2019 – Present</span>
                </div>
                <div class="experience-company">Two Gas Stations, Punta Gorda, Belize</div>
                <ul style="margin-top: 1rem; margin-left: 1.5rem; color: #475569;">
                    <li>Manage payroll processing, tax filings, and bank reconciliations for multiple locations</li>
                    <li>Maintain accurate financial records using QuickBooks</li>
                    <li>Prepare financial reports and ensure compliance with accounting standards</li>
                </ul>
            </div>

            <div class="experience-item">
                <div class="experience-header">
                    <span class="experience-title">Sales Representative</span>
                    <span class="experience-date">6 months</span>
                </div>
                <div class="experience-company">Casanagent</div>
                <ul style="margin-top: 1rem; margin-left: 1.5rem; color: #475569;">
                    <li>Engaged with customers to understand needs and recommend appropriate products</li>
                    <li>Maintained detailed records of client interactions and follow-ups</li>
                    <li>Collaborated on improving sales scripts and outreach strategies</li>
                    <li>Developed strong listening and adaptability skills in fast-paced environments</li>
                </ul>
            </div>

            <div class="experience-item">
                <div class="experience-header">
                    <span class="experience-title">Payroll Administrator / Document Filing Clerk</span>
                    <span class="experience-date">2 years</span>
                </div>
                <div class="experience-company">Zitro</div>
                <ul style="margin-top: 1rem; margin-left: 1.5rem; color: #475569;">
                    <li>Processed payroll for employees and maintained accurate payroll records</li>
                    <li>Organized and filed important company documents</li>
                </ul>
            </div>

            <div class="experience-item">
                <div class="experience-header">
                    <span class="experience-title">Logistics Coordinator</span>
                    <span class="experience-date">2 years</span>
                </div>
                <div class="experience-company">Bluzen, Caye Caulker, Belize</div>
                <ul style="margin-top: 1rem; margin-left: 1.5rem; color: #475569;">
                    <li>Managed shipping, receiving, and inventory logistics</li>
                    <li>Coordinated with suppliers and customers to ensure timely deliveries</li>
                </ul>
            </div>

            <div class="experience-item">
                <div class="experience-header">
                    <span class="experience-title">Mechanic</span>
                    <span class="experience-date">1 year</span>
                </div>
                <div class="experience-company">King Motors</div>
                <ul style="margin-top: 1rem; margin-left: 1.5rem; color: #475569;">
                    <li>Performed vehicle maintenance and repairs</li>
                    <li>Diagnosed mechanical issues and provided solutions</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Education -->
    <section>
        <div class="container">
            <h2>Education</h2>
            <div class="card-grid" style="grid-template-columns: repeat(2, 1fr);">
                <div class="card">
                    <h3>Associate's Degree in Business Administration</h3>
                    <p style="color: #3b82f6; margin-bottom: 0.5rem;">Saint John's Junior College</p>
                    <p style="color: #64748b;">Currently Pursuing</p>
                </div>
                <div class="card">
                    <h3>High School Diploma</h3>
                    <p style="color: #3b82f6; margin-bottom: 0.5rem;">Saint John's College</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact & Footer -->
    <footer>
        <div class="container">
            <div class="social-links">
                <a href="#">LinkedIn</a>
                <a href="#">GitHub</a>
                <a href="#">Email</a>
            </div>
            <p style="color: #94a3b8;">Available for opportunities in AI-driven financial systems and voice agent development</p>
            <p style="margin-top: 2rem; color: #64748b;">© 2024 Your Name. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
