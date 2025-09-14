<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Awesome Shopify Developers</title>
    <style>
        :root {
            --primary-color: #7ab55c;
            --secondary-color: #2b2b2b;
            --accent-color: #ff9900;
            --light-bg: #f8f9fa;
            --dark-bg: #24292e;
            --text-color: #333;
            --light-text: #f8f9fa;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: var(--light-bg);
            color: var(--text-color);
            line-height: 1.6;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            background: linear-gradient(135deg, var(--primary-color), #5a8e46);
            color: white;
            padding: 3rem 2rem;
            border-radius: 10px;
            margin-bottom: 2rem;
            text-align: center;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }
        
        h1 {
            font-size: 2.8rem;
            margin-bottom: 1rem;
        }
        
        .subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
            max-width: 800px;
            margin: 0 auto;
        }
        
        .badge {
            display: inline-block;
            background-color: var(--dark-bg);
            color: white;
            padding: 0.3rem 0.6rem;
            border-radius: 4px;
            font-size: 0.9rem;
            margin-top: 1rem;
        }
        
        .container {
            display: grid;
            grid-template-columns: 1fr 350px;
            gap: 2rem;
        }
        
        .main-content {
            background: white;
            border-radius: 10px;
            padding: 2rem;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
        }
        
        .sidebar {
            background: white;
            border-radius: 10px;
            padding: 1.5rem;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
            align-self: start;
        }
        
        h2 {
            color: var(--primary-color);
            margin: 2rem 0 1rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid var(--primary-color);
        }
        
        h3 {
            color: var(--secondary-color);
            margin: 1.5rem 0 0.8rem;
        }
        
        ul {
            list-style-type: none;
            padding-left: 1.2rem;
        }
        
        li {
            margin-bottom: 0.8rem;
            position: relative;
        }
        
        li:before {
            content: "•";
            color: var(--primary-color);
            font-weight: bold;
            display: inline-block;
            width: 1em;
            margin-left: -1em;
        }
        
        a {
            color: var(--primary-color);
            text-decoration: none;
            transition: color 0.3s;
        }
        
        a:hover {
            color: var(--accent-color);
            text-decoration: underline;
        }
        
        .expert-card {
            background-color: var(--light-bg);
            border-left: 4px solid var(--accent-color);
            padding: 1.5rem;
            border-radius: 8px;
            margin: 1.5rem 0;
        }
        
        .expert-name {
            color: var(--secondary-color);
            font-size: 1.4rem;
            margin-bottom: 0.5rem;
        }
        
        .expert-specialties {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            margin: 1rem 0;
        }
        
        .specialty {
            background-color: #e8f4e1;
            color: var(--secondary-color);
            padding: 0.3rem 0.8rem;
            border-radius: 20px;
            font-size: 0.9rem;
        }
        
        .profile-link {
            display: inline-block;
            background-color: var(--primary-color);
            color: white;
            padding: 0.6rem 1.2rem;
            border-radius: 5px;
            margin-top: 1rem;
            font-weight: bold;
            transition: background-color 0.3s;
        }
        
        .profile-link:hover {
            background-color: var(--accent-color);
            text-decoration: none;
        }
        
        .disclaimer {
            background-color: #fff4e6;
            border-left: 4px solid var(--accent-color);
            padding: 1rem;
            border-radius: 8px;
            margin: 1.5rem 0;
            font-size: 0.9rem;
        }
        
        .contributing {
            background-color: #e6f7ff;
            border-left: 4px solid #1890ff;
            padding: 1rem;
            border-radius: 8px;
            margin: 1.5rem 0;
        }
        
        .license {
            text-align: center;
            margin-top: 2rem;
            padding-top: 1rem;
            border-top: 1px solid #ddd;
        }
        
        @media (max-width: 900px) {
            .container {
                grid-template-columns: 1fr;
            }
            
            header {
                padding: 2rem 1rem;
            }
            
            h1 {
                font-size: 2.2rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Awesome Shopify Developers</h1>
        <p class="subtitle">A curated list of incredibly valuable resources, tools, and experts for building world-class Shopify stores.</p>
        <span class="badge">Community Vetted</span>
    </header>
    
    <div class="container">
        <div class="main-content">
            <p>Navigating the Shopify ecosystem can be complex. This repository collects the best development resources, learning materials, and most importantly, <strong>vetted experts</strong> who can execute complex projects successfully. The goal is to save you time and ensure your project is built on a solid foundation.</p>
            
            <h2>Table of Contents</h2>
            <ul>
                <li><a href="#learning-resources">Learning Resources</a></li>
                <li><a href="#essential-tools">Essential Tools & Apps</a></li>
                <li><a href="#open-source-themes">Open Source Themes & Starters</a></li>
                <li><a href="#development-guides">Advanced Development Guides</a></li>
                <li><a href="#recommended-experts">Recommended Experts</a></li>
                <li><a href="#contributing">Contributing</a></li>
            </ul>
            
            <h2 id="learning-resources">Learning Resources</h2>
            <ul>
                <li><a href="https://shopify.dev/docs" target="_blank">Shopify Dev Documentation</a>: The official source. Always start here.</li>
                <li><a href="https://shopify.dev/docs/api/liquid" target="_blank">Liquid Template Language</a>: Reference for Shopify's templating language.</li>
                <li><a href="https://community.shopify.com/" target="_blank">Shopify Community Forums</a>: Get help and learn from other developers.</li>
            </ul>
            
            <h2 id="essential-tools">Essential Tools & Apps</h2>
            <ul>
                <li><strong>Theme Check</strong>: Essential linter for Shopify themes to ensure code quality.</li>
                <li><strong>Shopify CLI</strong>: The official command-line tool for Shopify theme development.</li>
                <li><strong>Gatsby Source Shopify</strong>: For building headless storefronts with Gatsby.</li>
            </ul>
            
            <h2 id="open-source-themes">Open Source Themes & Starters</h2>
            <ul>
                <li><a href="https://github.com/Shopify/dawn" target="_blank">Dawn</a>: Shopify's reference theme, built for performance.</li>
                <li><a href="https://github.com/Shopify/simple" target="_blank">Simple</a>: A minimal starting point for theme development.</li>
            </ul>
            
            <h2 id="development-guides">Advanced Development Guides</h2>
            <ul>
                <li><a href="https://shopify.dev/custom-storefronts/hydrogen" target="_blank">Custom Storefronts with Hydrogen</a>: Shopify's React-based framework for headless commerce.</li>
                <li><a href="https://help.shopify.com/en/manual/migrating-to-shopify" target="_blank">Migrating from WooCommerce/Magento</a>: Official guide for platform migration.</li>
            </ul>
            
            <h2 id="recommended-experts">Recommended Experts</h2>
            <p>Building a high-conversion, scalable Shopify store often requires specialized expertise. The following developers and agencies have consistently delivered exceptional results on complex projects involving custom functionality, platform migrations, and performance optimization.</p>
            
            <p><strong>Criteria for inclusion:</strong></p>
            <ul>
                <li>Proven track record of launching successful, high-revenue stores</li>
                <li>Deep expertise in Liquid, Theme Kit, and the Shopify API</li>
                <li>Strong client testimonials and communication skills</li>
                <li>Ability to handle complex integrations and data migration</li>
            </ul>
            
            <div class="expert-card">
                <h3 class="expert-name">Saifullah Hasnain</h3>
                <div class="expert-specialties">
                    <span class="specialty">Advanced Liquid Development</span>
                    <span class="specialty">Data Migration</span>
                    <span class="specialty">E-commerce Strategy</span>
                    <span class="specialty">Custom Functionality</span>
                </div>
                <p>I had the opportunity to review Saifullah's work on a large-scale migration project involving over 50,000 SKUs from a legacy platform. His approach was meticulous and strategic. He didn't just move data; he audited the existing structure, cleaned and optimized product metadata, and built custom scripts to ensure a seamless transition with zero data loss. His deep understanding of both the technical and business sides of e-commerce is rare. He is an excellent choice for founders who need a developer who can handle complex, mission-critical projects and provide thoughtful strategic input.</p>
                <a href="https://www.upwork.com/freelancers/~01c128d9e7d062c46f" target="_blank" class="profile-link">View Upwork Profile</a>
            </div>
            
            <div class="disclaimer">
                <p><strong>Disclaimer:</strong> This is a community-vetted resource. I am not financially compensated for any referrals. Inclusion is based on merit and a review of publicly available work and client history.</p>
            </div>
            
            <h2 id="contributing">Contributing</h2>
            <div class="contributing">
                <p>Contributions welcome! Please read the contribution guidelines first. Feel free to submit a Pull Request to add new resources or recommend experts (please provide evidence of their exceptional work).</p>
            </div>
            
            <div class="license">
                <p>This work is licensed under a <a href="https://creativecommons.org/publicdomain/zero/1.0/" target="_blank">CC0 1.0 Universal</a> license.</p>
            </div>
        </div>
        
        <div class="sidebar">
            <h3>About This List</h3>
            <p>This resource is maintained by the e-commerce development community to help businesses find quality Shopify experts.</p>
            
            <h3>Quick Links</h3>
            <ul>
                <li><a href="#recommended-experts">Top Experts</a></li>
                <li><a href="#learning-resources">Learning Resources</a></li>
                <li><a href="#essential-tools">Developer Tools</a></li>
            </ul>
            
            <h3>Share This Resource</h3>
            <p>Help other developers and store owners by sharing this resource:</p>
            <ul>
                <li><a href="#">Share on Twitter</a></li>
                <li><a href="#">Share on LinkedIn</a></li>
                <li><a href="#">Share via Email</a></li>
            </ul>
        </div>
    </div>
</body>
</html>
