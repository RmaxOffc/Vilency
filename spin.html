<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spin Pemain Beban FF / Spar</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #1a2a6c, #b21f1f, #fdbb2d);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }
        
        .container {
            background-color: rgba(255, 255, 255, 0.95);
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
            width: 100%;
            max-width: 800px;
            padding: 30px;
            text-align: center;
        }
        
        h1 {
            color: #333;
            margin-bottom: 10px;
            font-size: 2.5rem;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
        }
        
        .subtitle {
            color: #666;
            margin-bottom: 30px;
            font-size: 1.2rem;
        }
        
        .player-list {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 15px;
            margin-bottom: 30px;
        }
        
        .player-card {
            background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
            border-radius: 10px;
            padding: 15px;
            color: white;
            font-weight: bold;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s;
        }
        
        .player-card:hover {
            transform: translateY(-5px);
        }
        
        .selected-players {
            margin: 30px 0;
            padding: 20px;
            background-color: #f8f9fa;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .selected-players h2 {
            color: #333;
            margin-bottom: 20px;
        }
        
        .selected-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
        }
        
        .selected-player {
            background: linear-gradient(135deg, #ff9a9e 0%, #fecfef 100%);
            border-radius: 10px;
            padding: 15px 20px;
            color: white;
            font-weight: bold;
            font-size: 1.2rem;
            min-width: 150px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        
        .spin-button {
            background: linear-gradient(135deg, #ff416c, #ff4b2b);
            color: white;
            border: none;
            padding: 15px 40px;
            font-size: 1.2rem;
            font-weight: bold;
            border-radius: 50px;
            cursor: pointer;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
            transition: all 0.3s;
            margin-top: 20px;
        }
        
        .spin-button:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.4);
        }
        
        .spin-button:active {
            transform: translateY(1px);
        }
        
        .history {
            margin-top: 30px;
            padding: 20px;
            background-color: #f8f9fa;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .history h2 {
            color: #333;
            margin-bottom: 15px;
        }
        
        .history-list {
            max-height: 200px;
            overflow-y: auto;
            text-align: left;
        }
        
        .history-item {
            padding: 10px;
            border-bottom: 1px solid #ddd;
        }
        
        @media (max-width: 600px) {
            .container {
                padding: 20px;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            .player-list {
                grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
            }
            
            .selected-container {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Spin Pemain Beban FF / Spar</h1>
        <p class="subtitle">Pilih 4 pemain secara acak untuk tim Anda</p>
        
        <div class="player-list">
            <!-- Daftar pemain akan diisi oleh JavaScript -->
        </div>
        
        <button class="spin-button" id="spinButton">SPIN PEMAIN</button>
        
        <div class="selected-players">
            <h2>Pemain Terpilih</h2>
            <div class="selected-container" id="selectedContainer">
                <!-- Pemain terpilih akan ditampilkan di sini -->
            </div>
        </div>
        
        <div class="history">
            <h2>Riwayat Pemilihan</h2>
            <div class="history-list" id="historyList">
                <!-- Riwayat pemilihan akan ditampilkan di sini -->
            </div>
        </div>
    </div>

    <script>
        // Daftar pemain
        const players = [
            "Adit 8a",
            "Ketu 8a",
            "Momot",
            "Abil 8a",
            "Anton 8d",
            "Diyas 8A",
            "Faza 8a",
            "KANIP SUKA MENINGGI 🧊",
            "Meimei 8a",
            "Rmax Official",
            "Yoga RMAX 8a"
        ];
        
        // Elemen DOM
        const playerListElement = document.querySelector('.player-list');
        const selectedContainer = document.getElementById('selectedContainer');
        const spinButton = document.getElementById('spinButton');
        const historyList = document.getElementById('historyList');
        
        // Menampilkan daftar pemain
        players.forEach(player => {
            const playerCard = document.createElement('div');
            playerCard.className = 'player-card';
            playerCard.textContent = player;
            playerListElement.appendChild(playerCard);
        });
        
        // Fungsi untuk memilih 4 pemain secara acak
        function selectRandomPlayers() {
            // Salin array pemain untuk menghindari modifikasi array asli
            const availablePlayers = [...players];
            const selectedPlayers = [];
            
            // Pilih 4 pemain secara acak
            for (let i = 0; i < 4; i++) {
                if (availablePlayers.length === 0) break;
                
                const randomIndex = Math.floor(Math.random() * availablePlayers.length);
                selectedPlayers.push(availablePlayers[randomIndex]);
                availablePlayers.splice(randomIndex, 1);
            }
            
            return selectedPlayers;
        }
        
        // Fungsi untuk menampilkan pemain terpilih
        function displaySelectedPlayers(selectedPlayers) {
            // Kosongkan kontainer
            selectedContainer.innerHTML = '';
            
            // Tambahkan setiap pemain terpilih
            selectedPlayers.forEach(player => {
                const playerElement = document.createElement('div');
                playerElement.className = 'selected-player';
                playerElement.textContent = player;
                selectedContainer.appendChild(playerElement);
            });
        }
        
        // Fungsi untuk menambahkan riwayat
        function addToHistory(selectedPlayers) {
            const historyItem = document.createElement('div');
            historyItem.className = 'history-item';
            
            const timestamp = new Date().toLocaleTimeString();
            historyItem.textContent = `${timestamp}: ${selectedPlayers.join(', ')}`;
            
            // Tambahkan ke atas daftar riwayat
            historyList.insertBefore(historyItem, historyList.firstChild);
            
            // Batasi riwayat hingga 10 entri
            if (historyList.children.length > 10) {
                historyList.removeChild(historyList.lastChild);
            }
        }
        
        // Event listener untuk tombol spin
        spinButton.addEventListener('click', () => {
            // Animasi tombol
            spinButton.style.transform = 'scale(0.95)';
            setTimeout(() => {
                spinButton.style.transform = '';
            }, 150);
            
            // Pilih dan tampilkan pemain
            const selectedPlayers = selectRandomPlayers();
            displaySelectedPlayers(selectedPlayers);
            addToHistory(selectedPlayers);
        });
        
        // Pilih pemain secara otomatis saat halaman dimuat
        window.addEventListener('load', () => {
            const initialSelection = selectRandomPlayers();
            displaySelectedPlayers(initialSelection);
            addToHistory(initialSelection);
        });
    </script>
</body>
</html>
