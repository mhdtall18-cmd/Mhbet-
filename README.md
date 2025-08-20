<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Paris Sportifs - Moderne</title>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <style>
        body { background-color: #f3f4f6; }
        .card { transition: transform 0.3s, box-shadow 0.3s; }
        .card:hover { transform: translateY(-5px); box-shadow: 0 8px 20px rgba(0,0,0,0.2); }
        .pulse { animation: pulse 0.5s ease-in-out; }
        @keyframes pulse { 0%{ transform: scale(1); } 50%{ transform: scale(1.05); } 100%{ transform: scale(1); } }
    </style>
</head>
<body class="p-4">

    <h1 class="text-3xl font-bold text-center mb-6 text-gray-800">Paris Sportifs Modernes</h1>

    <section>
        <h2 class="text-2xl font-semibold mb-4">Matchs Disponibles</h2>
        <div id="matches-container" class="grid md:grid-cols-2 gap-4"></div>
        <button id="simulate-btn" class="mt-4 px-6 py-3 bg-gradient-to-r from-blue-500 to-cyan-400 text-white rounded-xl font-bold shadow-lg hover:scale-105 transition-transform" onclick="simulateAllResults()">Simuler tous les résultats</button>
    </section>

    <section class="mt-8">
        <h2 class="text-2xl font-semibold mb-4">Mes Paris</h2>
        <div id="bets-container" class="grid md:grid-cols-2 gap-4"></div>
    </section>

    <section class="mt-8">
        <h2 class="text-2xl font-semibold mb-4">Statistiques</h2>
        <p id="total-bets" class="font-medium">Total parié : 0</p>
        <p id="total-won" class="font-medium">Total gagné : 0</p>
        <p id="win-rate" class="font-medium">Taux de réussite : 0%</p>
        <canvas id="bets-chart" class="mt-4 bg-white rounded-xl p-2 shadow-lg"></canvas>
    </section>

    <script src="script.js"></script>
</body>
</html>https://cdn.jsdelivr.net/npm/chart.jsindex.html1script.js# Mhbet-
Pari sportif 
