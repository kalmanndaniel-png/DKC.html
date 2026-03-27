<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Daniel Kalmann Consultancy</title>

<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        color: #333;
        background-color: #f5f5f5;
    }

    header {
        background: #2f3e46;
        color: white;
        padding: 20px 40px;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    header img {
        height: 50px;
    }

    nav a {
        color: white;
        margin-left: 20px;
        text-decoration: none;
        font-weight: bold;
    }

    nav a:hover {
        color: #84a98c;
    }

    .hero {
        background: linear-gradient(135deg, #354f52, #52796f);
        color: white;
        padding: 80px 40px;
        text-align: center;
    }

    .hero h1 {
        font-size: 40px;
        margin-bottom: 20px;
    }

    .hero p {
        font-size: 18px;
        max-width: 800px;
        margin: auto;
    }

    section {
        padding: 60px 40px;
        max-width: 1100px;
        margin: auto;
    }

    h2 {
        color: #2f3e46;
        margin-bottom: 20px;
    }

    .pillars {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 30px;
    }

    .card {
        background: white;
        padding: 25px;
        border-radius: 10px;
        box-shadow: 0 4px 10px rgba(0,0,0,0.08);
    }

    .card h3 {
        color: #52796f;
    }

    .about {
        display: flex;
        flex-wrap: wrap;
        gap: 40px;
        align-items: center;
    }

    .about img {
        width: 250px;
        border-radius: 10px;
    }

    .footer {
        background: #2f3e46;
        color: white;
        text-align: center;
        padding: 40px 20px;
    }

    .highlight {
        color: #52796f;
        font-weight: bold;
    }

</style>
</head>

<body>

<header>
    <img src="logo.png" alt="Logo">
    <nav>
        <a href="#expertise">Expertise</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <h1>Unlocking Procurement Excellence through Digital Transformation</h1>
    <p>
        Independent consultant helping organizations optimize processes, implement digital solutions, 
        and achieve sustainable savings — without turning your team into robots (unless they want to).
    </p>
</section>

<section id="expertise">
    <h2>Expertise – The Excellence Pillars</h2>
    <p>Focused service offerings designed to transform your procurement operations into a strategic value driver.</p>

    <div class="pillars">
        <div class="card">
            <h3>Digital Procurement Strategy</h3>
            <p>Roadmap development, tool selection (SaaS), and GenAI for procurement. Aligning technology with business goals.</p>
            <ul>
                <li>Roadmap Development</li>
                <li>Tool Selection (SaaS)</li>
                <li>GenAI Integration</li>
            </ul>
        </div>

        <div class="card">
            <h3>Procurement Excellence</h3>
            <p>Strategy-to-execution, taxonomy restructuring, and operating model advisory to elevate your procurement function.</p>
            <ul>
                <li>Operating Model Advisory</li>
                <li>Taxonomy Restructuring</li>
                <li>Strategy Execution</li>
            </ul>
        </div>

        <div class="card">
            <h3>Process Optimization</h3>
            <p>Source-to-Pay (S2P) implementations, P2P optimization, and automation for maximum efficiency.</p>
            <ul>
                <li>S2P Implementation</li>
                <li>P2P Optimization</li>
                <li>Automation & Efficiency</li>
            </ul>
        </div>
    </div>
</section>

<section id="about">
    <h2>About Me</h2>

    <div class="about">
        <img src="profile.jpg" alt="Daniel Kalmann">

        <div>
            <h3>Daniël Kalmann</h3>
            <p>
                With over <span class="highlight">10 years of experience</span> in Procurement Excellence and Digital Transformation, 
                I have built a career on bridging the gap between complex business processes and high-end digital solutions.
            </p>

            <p>
                My approach is strategic, results-oriented, but always focused on the people who use the tools. 
                Because let’s be honest: even the best system fails if nobody actually wants to use it.
            </p>

            <p>
                I believe that digital transformation is <span class="highlight">20% technology and 80% change management</span>.
            </p>

            <h4>Beyond the Boardroom</h4>
            <ul>
                <li>Avid Cyclist</li>
                <li>Boxing Enthusiast</li>
                <li>Proud Dad</li>
                <li>Based in Haarlem, NL</li>
            </ul>
        </div>
    </div>
</section>

<section id="contact">
    <h2>Daniël Kalmann Consultancy</h2>
    <p>
        Transforming procurement into a strategic powerhouse through digital innovation and process excellence.  
        Let’s discuss how I can help your organization.
    </p>

    <p><strong>Email:</strong> Kalmann.Daniel@gmail.com</p>
    <p><strong>Phone:</strong> +31 (0) 6 8268 7009</p>
    <p><strong>Location:</strong> Haarlem, The Netherlands</p>
</section>

<div class="footer">
    <p>© 2026 Daniel Kalmann Consultancy — Built with clarity, strategy, and just enough caffeine.</p>
</div>

</body>
</html>
