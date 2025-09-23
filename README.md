# Aquvia
Html code for Aquvia Development works
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AQUVIA Development Works | Infographic</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
        }
        .bg-hero {
            background-image: linear-gradient(rgba(0, 63, 92, 0.9), rgba(0, 63, 92, 0.8)), url('https://googleusercontent.com/contentFetchId/uploaded:WhatsApp Image 2025-09-23 at 23.49.20_3f5bbd50.jpg-ab07fdce-189b-4303-be2b-f6be5f4b4664');
            background-size: 100px;
            background-repeat: repeat;
            background-position: center;
        }
        .brand-text-primary { color: #003F5C; }
        .brand-text-secondary { color: #366E8A; }
        .brand-bg-primary { background-color: #003F5C; }
        .brand-bg-secondary { background-color: #A5D8E4; }
        .brand-accent { background-color: #6B9DB3; }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 500px;
            margin-left: auto;
            margin-right: auto;
            height: 300px;
            max-height: 400px;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 350px;
            }
        }
    </style>
</head>
<body class="bg-gray-50">

    <header class="bg-hero text-white text-center py-20 px-4">
        <div class="max-w-4xl mx-auto">
            <img src="https://googleusercontent.com/contentFetchId/uploaded:WhatsApp Image 2025-09-23 at 23.49.20_3f5bbd50.jpg-ab07fdce-189b-4303-be2b-f6be5f4b4664" alt="Aquvia Development Works Logo" class="w-96 h-auto mx-auto mb-4">
            <h1 class="text-5xl font-bold mb-2">AQUVIA DEVELOPMENT WORKS</h1>
            <p class="text-xl font-light">Empowering Water, Finance, and Communities for Resilient Growth</p>
        </div>
    </header>

    <main class="container mx-auto px-6 py-12">
        <section id="about" class="mb-16">
            <div class="max-w-3xl mx-auto text-center">
                <h2 class="text-4xl font-bold brand-text-primary mb-4">The Nexus of Progress</h2>
                <p class="text-lg text-gray-700">
                    Aquvia Development Works transforms rural water and agricultural systems into resilient, investment-ready enterprises. We operate at the critical intersection of water, finance, agriculture, and climate to forge a sustainable and prosperous future for communities across Kenya.
                </p>
            </div>
        </section>

        <section id="experience" class="mb-16">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
                <div class="bg-white p-6 rounded-lg shadow-lg">
                    <span class="text-5xl font-bold brand-text-secondary">10+</span>
                    <p class="text-gray-600 mt-2">Years of Expertise in Sustainable Water Systems</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-lg">
                    <span class="text-5xl font-bold brand-text-secondary">8+</span>
                    <p class="text-gray-600 mt-2">Counties with Successful PPCP Implementations</p>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-lg">
                    <span class="text-5xl font-bold brand-text-secondary">100%</span>
                    <p class="text-gray-600 mt-2">Focus on Climate Resilient Models</p>
                </div>
            </div>
        </section>

        <section id="finance-model" class="mb-16 bg-white p-8 rounded-lg shadow-lg">
             <div class="text-center mb-8">
                <h2 class="text-4xl font-bold brand-text-primary">De-Risking Investment, Securing Communities</h2>
                <p class="text-lg text-gray-700 max-w-3xl mx-auto mt-2">Our blended finance models create safe, impactful pathways for investors. By combining catalytic capital with private investment, we unlock potential in rural water and agricultural infrastructure.</p>
            </div>
            <div class="flex flex-col md:flex-row items-center justify-center space-y-4 md:space-y-0 md:space-x-4 text-center">
                <div class="p-6 bg-blue-50 rounded-lg shadow-md w-full md:w-1/4">
                    <h3 class="text-xl font-semibold brand-text-secondary">Catalytic & Public Capital</h3>
                    <p class="text-sm">Initial Funding to Mitigate Risk</p>
                </div>
                <div class="text-4xl brand-text-primary font-mono">&rarr;</div>
                <div class="p-6 bg-blue-100 rounded-lg shadow-md w-full md:w-1/4">
                    <h3 class="text-xl font-semibold brand-text-secondary">Private Investment</h3>
                     <p class="text-sm">Securitized for Safe Returns</p>
                </div>
                <div class="text-4xl brand-text-primary font-mono">&rarr;</div>
                 <div class="p-6 brand-bg-secondary rounded-lg shadow-md w-full md:w-1/4">
                    <h3 class="text-xl font-semibold text-white">Resilient Enterprises</h3>
                     <p class="text-sm text-white">Water & Agri-Businesses</p>
                </div>
            </div>
        </section>
        
        <section id="focus-areas" class="mb-16">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
                <div class="bg-white p-8 rounded-lg shadow-lg">
                    <h2 class="text-3xl font-bold brand-text-primary mb-4">Holistic Project Focus</h2>
                    <p class="text-gray-700 mb-6">Our approach balances infrastructure development with sustainable agriculture and robust community governance. This ensures long-term success and equitable benefit sharing, making our projects both profitable and impactful.</p>
                     <div class="chart-container">
                        <canvas id="focusAreaChart"></canvas>
                    </div>
                </div>
                <div class="bg-white p-8 rounded-lg shadow-lg">
                    <h2 class="text-3xl font-bold brand-text-primary mb-4">Building Community Resilience</h2>
                    <p class="text-gray-700 mb-6">Every model we deliver enhances climate resilience. Our water-smart systems and agroecology practices directly support adaptation, reduce climate risks, and build a foundation for long-term growth and food security.</p>
                    <div class="chart-container">
                        <canvas id="resilienceChart"></canvas>
                    </div>
                </div>
            </div>
        </section>

        <section id="framework" class="mb-16">
            <div class="max-w-4xl mx-auto text-center mb-8">
                <h2 class="text-4xl font-bold brand-text-primary mb-4">Our Approach – Turning Vision into Practice</h2>
                <p class="text-lg text-gray-700">
                    We address the structural weaknesses of rural water systems — poor governance, fragmented operations, lack of finance — by creating frameworks that transform them into commercially viable, community-owned enterprises.
                </p>
            </div>
            <div class="max-w-5xl mx-auto grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <div class="bg-white p-6 rounded-lg shadow-md flex items-start space-x-4">
                    <span class="text-3xl brand-text-secondary">1️⃣</span>
                    <div>
                        <h3 class="font-bold text-xl brand-text-primary mb-1">Strategy</h3>
                        <p class="text-gray-700">Integrate finance innovation and community resilience with blended finance, catalytic capital, and agroecology to scale solutions.</p>
                    </div>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md flex items-start space-x-4">
                    <span class="text-3xl brand-text-secondary">2️⃣</span>
                    <div>
                        <h3 class="font-bold text-xl brand-text-primary mb-1">Systems</h3>
                        <p class="text-gray-700">Design fit-for-purpose financial and operational systems with digital billing and performance dashboards for long-term viability.</p>
                    </div>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md flex items-start space-x-4">
                    <span class="text-3xl brand-text-secondary">3️⃣</span>
                    <div>
                        <h3 class="font-bold text-xl brand-text-primary mb-1">Staffing</h3>
                        <p class="text-gray-700">Quantify and optimize labor by training local youth and women in financial management and technical operations.</p>
                    </div>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md flex items-start space-x-4">
                    <span class="text-3xl brand-text-secondary">4️⃣</span>
                    <div>
                        <h3 class="font-bold text-xl brand-text-primary mb-1">Skills</h3>
                        <p class="text-gray-700">Embed critical skills in finance literacy, governance, and climate-smart resource management for community growth.</p>
                    </div>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md flex items-start space-x-4">
                    <span class="text-3xl brand-text-secondary">5️⃣</span>
                    <div>
                        <h3 class="font-bold text-xl brand-text-primary mb-1">Style</h3>
                        <p class="text-gray-700">Maintain a collaborative, inclusive, and catalytic leadership style that empowers communities as equal partners.</p>
                    </div>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md flex items-start space-x-4">
                    <span class="text-3xl brand-text-secondary">6️⃣</span>
                    <div>
                        <h3 class="font-bold text-xl brand-text-primary mb-1">Shared Value</h3>
                        <p class="text-gray-700">Structure public-private-community partnerships to align incentives for investors, communities, and governments.</p>
                    </div>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md flex items-start space-x-4">
                    <span class="text-3xl brand-text-secondary">7️⃣</span>
                    <div>
                        <h3 class="font-bold text-xl brand-text-primary mb-1">Synergy</h3>
                        <p class="text-gray-700">Create synergy between water and agriculture, finance and climate resilience, building mutually beneficial ecosystems.</p>
                    </div>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md flex items-start space-x-4">
                    <span class="text-3xl brand-text-secondary">8️⃣</span>
                    <div>
                        <h3 class="font-bold text-xl brand-text-primary mb-1">Sustainability</h3>
                        <p class="text-gray-700">Design every model to be financially, socially, and environmentally sustainable through blended finance and inclusive governance.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="partnership" class="brand-bg-primary text-white p-12 rounded-lg shadow-lg text-center">
            <h2 class="text-4xl font-bold mb-4">Why Partner With Us?</h2>
            <p class="max-w-3xl mx-auto text-lg mb-8">We offer a unique partnership opportunity that delivers financial returns while creating lasting positive change.</p>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-xl font-bold text-cyan-200">Safe Landing for Investors</h3>
                    <p>Secure, low-risk entry into high-impact rural development.</p>
                </div>
                <div>
                    <h3 class="text-xl font-bold text-cyan-200">Sustainable Community Systems</h3>
                    <p>Focus on long-term viability ensures projects thrive.</p>
                </div>
                <div>
                    <h3 class="text-xl font-bold text-cyan-200">Risk Reduction in Finance</h3>
                    <p>Innovative models mitigate common infrastructure risks.</p>
                </div>
                <div>
                    <h3 class="text-xl font-bold text-cyan-200">Long-Term Agri-Growth</h3>
                    <p>Empowering food security and economic prosperity.</p>
                </div>
            </div>
        </section>
    </main>

    <footer class="bg-gray-800 text-white py-8 text-center">
        <img src="https://googleusercontent.com/contentFetchId/uploaded:WhatsApp Image 2025-09-23 at 23.49.20_3f5bbd50.jpg-ab07fdce-189b-4303-be2b-f6be5f4b4664" alt="Aquvia Development Works Logo" class="w-48 h-auto mx-auto mb-2">
        <p>Contact us to learn more:</p>
        <p>info@aquvia.dev | +254 729 469 504 | Nairobi, Kenya</p>
    </footer>

    <script>
        function wrapLabels(label, maxWidth) {
            const words = label.split(' ');
            let lines = [];
            let currentLine = '';
            words.forEach(word => {
                if ((currentLine + ' ' + word).length > maxWidth) {
                    lines.push(currentLine);
                    currentLine = word;
                } else {
                    currentLine = currentLine ? currentLine + ' ' + word : word;
                }
            });
            lines.push(currentLine);
            return lines;
        }

        const tooltipTitleCallback = (tooltipItems) => {
            const item = tooltipItems[0];
            let label = item.chart.data.labels[item.dataIndex];
            if (Array.isArray(label)) {
                return label.join(' ');
            }
            return label;
        };
        
        const focusAreaCtx = document.getElementById('focusAreaChart').getContext('2d');
        new Chart(focusAreaCtx, {
            type: 'doughnut',
            data: {
                labels: ['Water Systems Infrastructure', 'Regenerative Agriculture', 'Community Governance (PPCP)'],
                datasets: [{
                    label: 'Project Focus Allocation',
                    data: [45, 35, 20],
                    backgroundColor: ['#003F5C', '#366E8A', '#6B9DB3'],
                    borderColor: '#FFFFFF',
                    borderWidth: 2
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                plugins: {
                    legend: {
                        position: 'bottom',
                    },
                    tooltip: {
                        callbacks: {
                            title: tooltipTitleCallback
                        }
                    }
                }
            }
        });

        const resilienceCtx = document.getElementById('resilienceChart').getContext('2d');
        const originalLabels = ['Year 1: Baseline Assessment', 'Year 2: Infrastructure Dev', 'Year 3: Agroecology Training', 'Year 4: Market Linkages', 'Year 5: Full System Maturity'];
        const wrappedLabels = originalLabels.map(label => wrapLabels(label, 16));

        new Chart(resilienceCtx, {
            type: 'line',
            data: {
                labels: wrappedLabels,
                datasets: [{
                    label: 'Community Climate Resilience Index',
                    data: [20, 45, 60, 75, 90],
                    backgroundColor: 'rgba(165, 216, 228, 0.2)',
                    borderColor: '#366E8A',
                    tension: 0.3,
                    fill: true
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                scales: {
                    y: {
                        beginAtZero: true,
                        max: 100
                    }
                },
                plugins: {
                     legend: {
                        display: false,
                    },
                    tooltip: {
                        callbacks: {
                           title: tooltipTitleCallback
                        }
                    }
                }
            }
        });
    </script>
</body>
</html>
