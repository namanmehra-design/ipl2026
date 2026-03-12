<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>IPL Mega Auction Room - LIVE</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;900&display=swap');

        :root {
            --bg-gradient: linear-gradient(135deg, #0f172a 0%, #020617 100%);
            --glass-bg: rgba(255, 255, 255, 0.05);
            --glass-border: rgba(255, 255, 255, 0.1);
            --cream: #F5E6CC;
            --cream-hover: #e0d0b5;
            --text-main: #f8fafc;
            --text-muted: #94a3b8;
            --success: #10b981;
            --danger: #ef4444;
            --brand: #3b82f6;
        }

        body { font-family: 'Inter', sans-serif; background: var(--bg-gradient); background-attachment: fixed; margin: 0; padding: 20px; color: var(--text-main); min-height: 100vh; -webkit-tap-highlight-color: transparent; }
        h1 { text-align: center; margin-bottom: 20px; text-shadow: 0 2px 10px rgba(245, 230, 204, 0.2); font-size: 1.8rem; color: var(--cream); }
        h2 { color: var(--cream); font-weight: 600; margin-top: 0; }

        .glass-panel { background: var(--glass-bg); backdrop-filter: blur(16px); border: 1px solid var(--glass-border); border-radius: 16px; box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3); padding: 25px; }
        
        .nav-tabs { display: flex; gap: 10px; margin-bottom: 20px; padding: 10px; justify-content: center; flex-wrap: wrap; }
        .nav-tabs button { flex: 1; min-width: 100px; background: rgba(255, 255, 255, 0.05); color: var(--text-muted); border: 1px solid transparent; padding: 12px 10px; border-radius: 8px; font-weight: 600; transition: all 0.2s; cursor: pointer; font-size: 0.9rem; }
        .nav-tabs button.active { background: var(--cream); color: #0f172a; box-shadow: 0 4px 15px rgba(245, 230, 204, 0.3); }

        .tab-content { display: none; animation: fadeIn 0.3s ease-in-out; }
        .tab-content.active { display: block; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(5px); } to { opacity: 1; transform: translateY(0); } }

        .form-group { margin-bottom: 15px; width: 100%; }
        label { font-weight: 600; display: block; margin-bottom: 6px; color: var(--text-muted); font-size: 0.9rem;}
        input, select { width: 100%; padding: 14px; background: rgba(0, 0, 0, 0.3); border: 1px solid var(--glass-border); border-radius: 10px; color: var(--text-main); font-family: inherit; font-size: 1rem; box-sizing: border-box; appearance: none; }
        input:focus, select:focus { outline: none; border-color: var(--cream); }
        select option { background: #0f172a; color: var(--text-main); }

        button { touch-action: manipulation; }
        button.primary-btn { width: 100%; background-color: var(--cream); color: #0f172a; border: none; cursor: pointer; padding: 16px 20px; font-weight: 700; border-radius: 10px; transition: background 0.2s; font-size: 1.1rem; }
        button.primary-btn:active { transform: scale(0.98); }
        button.danger-btn { width: 100%; background-color: rgba(239, 68, 68, 0.1); color: var(--danger); border: 1px solid var(--danger); cursor: pointer; padding: 16px 20px; font-weight: 700; border-radius: 10px; font-size: 1.1rem; }
        button.action-btn { background: var(--brand); color: white; border: none; padding: 12px 20px; border-radius: 8px; font-weight: 600; width: 100%; margin-top: 10px; cursor: pointer;}

        .auction-block { text-align: center; padding: 30px 15px; border: 2px dashed var(--glass-border); border-radius: 16px; margin-bottom: 20px; background: rgba(0,0,0,0.4); }
        .player-name-huge { font-size: 2.2rem; font-weight: 900; color: var(--cream); margin: 0 0 5px 0; text-transform: uppercase; line-height: 1.1;}
        .player-meta { font-size: 1rem; color: var(--text-muted); margin-bottom: 15px; }
        .base-price { font-size: 1.2rem; color: var(--text-muted); font-weight: 600; margin-bottom: 5px; }
        
        .live-bid-display { font-size: 3rem; font-weight: 900; color: var(--success); margin: 15px 0; font-variant-numeric: tabular-nums; }
        .quick-bid-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px; margin-bottom: 20px; }
        .quick-bid-btn { background: rgba(255,255,255,0.1); color: var(--text-main); border: 1px solid var(--glass-border); padding: 15px 0; border-radius: 8px; font-weight: 700; font-size: 1.1rem; cursor: pointer; transition: background 0.1s; }
        .quick-bid-btn:active { background: rgba(255,255,255,0.3); }

        .bidding-controls { background: rgba(255,255,255,0.02); padding: 20px; border-radius: 12px; }
        .action-grid { display: grid; grid-template-columns: 2fr 1fr; gap: 15px; margin-top: 15px; }

        .team-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px; }
        .team-card { padding: 20px; border-top: 4px solid var(--cream); }
        .budget-display { font-size: 1.4rem; font-weight: bold; color: var(--success); margin-bottom: 10px; }
        .team-card ul { padding: 0; margin: 10px 0 0 0; list-style: none; max-height: 200px; overflow-y: auto; }
        .team-card li { display: flex; justify-content: space-between; padding: 8px 0; border-bottom: 1px solid rgba(255,255,255,0.05); font-size: 0.9rem; }

        .table-container { overflow-x: auto; -webkit-overflow-scrolling: touch; }
        table { width: 100%; border-collapse: collapse; min-width: 500px; }
        th, td { padding: 12px; text-align: left; border-bottom: 1px solid var(--glass-border); font-size: 0.9rem;}
        th { color: var(--cream); background: rgba(0,0,0,0.3); white-space: nowrap; }

        .alert { color: white; font-weight: 600; padding: 15px; background: var(--danger); border-radius: 8px; display: none; margin-top: 15px; text-align: center; z-index: 1000; position: relative;}
        .overseas-badge { background: rgba(245, 230, 204, 0.15); color: var(--cream); border: 1px solid var(--cream); padding: 2px 6px; border-radius: 8px; font-size: 0.7em; }

        .live-indicator { display: inline-block; width: 10px; height: 10px; background: var(--success); border-radius: 50%; margin-left: 10px; animation: pulse 2s infinite; }
        @keyframes pulse { 0% { box-shadow: 0 0 0 0 rgba(16, 185, 129, 0.7); } 70% { box-shadow: 0 0 0 10px rgba(16, 185, 129, 0); } 100% { box-shadow: 0 0 0 0 rgba(16, 185, 129, 0); } }

        @media (max-width: 600px) {
            body { padding: 10px; }
            .glass-panel { padding: 15px; }
            .player-name-huge { font-size: 1.8rem; }
            .live-bid-display { font-size: 2.5rem; }
            .action-grid { grid-template-columns: 1fr; }
            .setup-grid { display: grid; grid-template-columns: 1fr; gap: 0; }
        }
    </style>
</head>
<body>

    <h1>IPL Mega Auction <span class="live-indicator" id="connectionDot" style="background: red;"></span></h1>

    <div class="nav-tabs glass-panel" id="navTabs">
        <button id="btn-setup" class="active" onclick="window.switchTab('setup')">⚙️ Setup</button>
        <button id="btn-auction" onclick="window.switchTab('auction')">🔨 Auction</button>
        <button id="btn-teams" onclick="window.switchTab('teams')">📋 Purses</button>
        <button id="btn-roster" onclick="window.switchTab('roster')">📊 Ledger</button>
    </div>

    <div id="globalAlert" class="alert"></div>

    <div id="setup-tab" class="tab-content glass-panel active">
        <h2>Auction Setup <span style="font-size: 0.5em; color: var(--danger);">(Admin Only)</span></h2>
        <p style="color: var(--warning); font-size: 0.9em; margin-bottom: 20px;">⚠️ Warning: Clicking "Initialize" will erase all current auction data and start fresh for everyone.</p>
        <div class="setup-grid" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 15px;">
            <div class="form-group">
                <label>Teams (Max 10):</label>
                <input type="number" id="numTeams" min="2" max="10" value="4" onchange="window.generateTeamInputs()">
            </div>
            <div class="form-group">
                <label>Max Players/Team:</label>
                <input type="number" id="playersPerTeam" min="15" max="25" value="20">
            </div>
            <div class="form-group">
                <label>Purse (Total Cr):</label>
                <input type="number" id="teamBudget" min="10" value="100" step="1">
            </div>
        </div>
        
        <div id="teamNamesContainer" style="margin-top: 10px;"></div>
        <button class="primary-btn" onclick="window.startAuction()" style="margin-top: 20px;">Initialize / Reset LIVE Database</button>
    </div>

    <div id="auction-tab" class="tab-content glass-panel">
        <div class="form-group">
            <select id="manualPlayerSelect">
                <option value="">-- Search / Pull Specific Player --</option>
            </select>
            <button class="action-btn" onclick="window.pullSpecificPlayer()">Call to Block</button>
        </div>

        <div class="auction-block" id="auctionBlockDisplay">
            <h3 style="color: var(--text-muted); margin: 40px 0;">Waiting for Auctioneer...</h3>
        </div>

        <div class="bidding-controls" id="biddingControls" style="display: none;">
            <div style="text-align: center;">
                <div style="color: var(--text-muted); font-weight: 600; text-transform: uppercase; font-size: 0.8rem;">Current Bid (Cr)</div>
                <div class="live-bid-display" id="liveBidText">₹0.00</div>
            </div>

            <div class="quick-bid-grid" id="quickBidGrid"></div>

            <div class="form-group">
                <label>Select Winning Team:</label>
                <select id="winningTeamSelect"></select>
            </div>
            
            <div class="action-grid">
                <button class="primary-btn" onclick="window.sellPlayer()">🔨 SOLD!</button>
                <button class="danger-btn" onclick="window.markUnsold()">Pass</button>
            </div>
        </div>
        
        <button class="primary-btn" onclick="window.pullRandomPlayer()" style="margin-top: 25px; background: rgba(255,255,255,0.1); color: white; border: 1px solid var(--glass-border);">🎲 Bring Up Random Player</button>
    </div>

    <div id="teams-tab" class="tab-content glass-panel">
        <h2>Franchise Purses</h2>
        <div class="team-grid" id="teamGrid"></div>
    </div>

    <div id="roster-tab" class="tab-content glass-panel">
        <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 15px;">
            <h2>Ledger</h2>
            <button class="action-btn" style="width: auto; margin:0;" onclick="window.exportCSV()">Export CSV</button>
        </div>
        <div class="table-container">
            <table id="globalRosterTable">
                <thead>
                    <tr>
                        <th>Player</th>
                        <th>Role / Origin</th>
                        <th>Base (Cr)</th>
                        <th>Status</th>
                        <th>Sold (Cr)</th>
                    </tr>
                </thead>
                <tbody></tbody>
            </table>
        </div>
    </div>

    <script type="module">
        import { initializeApp } from "https://www.gstatic.com/firebasejs/10.8.1/firebase-app.js";
        import { getDatabase, ref, set, onValue, update } from "https://www.gstatic.com/firebasejs/10.8.1/firebase-database.js";

        const firebaseConfig = {
            apiKey: "AIzaSyDacQ47RW-LXCx_FEvGW933q5pEEWnW4Fw",
            authDomain: "ipl-2026-auction.firebaseapp.com",
            databaseURL: "https://ipl-auction-26-default-rtdb.firebaseio.com/",
            projectId: "ipl-2026-auction",
            storageBucket: "ipl-2026-auction.firebasestorage.app",
            messagingSenderId: "616761866734",
            appId: "1:616761866734:web:90cfd8c934c62e6800b6ff",
            measurementId: "G-Q2QNGD1ZLM"
        };

        const app = initializeApp(firebaseConfig);
        const db = getDatabase(app);

        // Indicate connection established
        document.getElementById('connectionDot').style.background = 'var(--success)';

        const rawData = [
            {n:"Ruturaj Gaikwad", r:"Batter", o:false}, {n:"Ayush Mhatre", r:"Batter", o:false}, {n:"Dewald Brevis", r:"Batter", o:true}, {n:"MS Dhoni", r:"Wicketkeeper", o:false}, {n:"Urvil Patel", r:"Wicketkeeper", o:false}, {n:"Shivam Dube", r:"All-Rounder", o:false}, {n:"Jamie Overton", r:"All-Rounder", o:true}, {n:"Ramakrishna Ghosh", r:"Bowler", o:false}, {n:"Noor Ahmad", r:"Bowler", o:true}, {n:"Khaleel Ahmed", r:"Bowler", o:false}, {n:"Anshul Kamboj", r:"All-Rounder", o:false}, {n:"Gurjapneet Singh", r:"Bowler", o:false}, {n:"Nathan Ellis", r:"Bowler", o:true}, {n:"Shreyas Gopal", r:"Bowler", o:false}, {n:"Mukesh Choudhary", r:"Bowler", o:false}, {n:"Sanju Samson", r:"Wicketkeeper", o:false}, {n:"Akeal Hosein", r:"Bowler", o:true}, {n:"Prashant Veer", r:"All-Rounder", o:false}, {n:"Kartik Sharma", r:"Batter", o:false}, {n:"Matthew Short", r:"All-Rounder", o:true}, {n:"Aman Khan", r:"All-Rounder", o:false}, {n:"Sarfaraz Khan", r:"Batter", o:false}, {n:"Matt Henry", r:"Bowler", o:true}, {n:"Rahul Chahar", r:"Bowler", o:false}, {n:"Zak Foulkes", r:"All-Rounder", o:true},
            {n:"Rohit Sharma", r:"Batter", o:false}, {n:"Suryakumar Yadav", r:"Batter", o:false}, {n:"Tilak Varma", r:"Batter", o:false}, {n:"Robin Minz", r:"Wicketkeeper", o:false}, {n:"Ryan Rickelton", r:"Wicketkeeper", o:true}, {n:"Hardik Pandya", r:"All-Rounder", o:false}, {n:"Naman Dhir", r:"All-Rounder", o:false}, {n:"Mitchell Santner", r:"All-Rounder", o:true}, {n:"Will Jacks", r:"All-Rounder", o:true}, {n:"Corbin Bosch", r:"All-Rounder", o:true}, {n:"Raj Bawa", r:"All-Rounder", o:false}, {n:"Trent Boult", r:"Bowler", o:true}, {n:"Jasprit Bumrah", r:"Bowler", o:false}, {n:"Deepak Chahar", r:"Bowler", o:false}, {n:"Ashwani Kumar", r:"Bowler", o:false}, {n:"Raghu Sharma", r:"Bowler", o:false}, {n:"AM Ghazanfar", r:"Bowler", o:true}, {n:"Shardul Thakur", r:"All-Rounder", o:false}, {n:"Sherfane Rutherford", r:"Batter", o:true}, {n:"Mayank Markande", r:"Bowler", o:false}, {n:"Quinton de Kock", r:"Wicketkeeper", o:true}, {n:"Danish Malewar", r:"Batter", o:false}, {n:"Mohammad Izhar", r:"Batter", o:false}, {n:"Atharva Ankolekar", r:"All-Rounder", o:false}, {n:"Mayank Rawat", r:"All-Rounder", o:false},
            {n:"Ajinkya Rahane", r:"Batter", o:false}, {n:"Angkrish Raghuvanshi", r:"Batter", o:false}, {n:"Anukul Roy", r:"All-Rounder", o:false}, {n:"Harshit Rana", r:"Bowler", o:false}, {n:"Manish Pandey", r:"Batter", o:false}, {n:"Ramandeep Singh", r:"All-Rounder", o:false}, {n:"Rinku Singh", r:"Batter", o:false}, {n:"Rovman Powell", r:"Batter", o:true}, {n:"Sunil Narine", r:"All-Rounder", o:true}, {n:"Umran Malik", r:"Bowler", o:false}, {n:"Vaibhav Arora", r:"Bowler", o:false}, {n:"Varun Chakravarthy", r:"Bowler", o:false}, {n:"Cameron Green", r:"All-Rounder", o:true}, {n:"Matheesha Pathirana", r:"Bowler", o:true}, {n:"Mustafizur Rahman", r:"Bowler", o:true}, {n:"Tejasvi Singh", r:"Bowler", o:false}, {n:"Rachin Ravindra", r:"All-Rounder", o:true}, {n:"Finn Allen", r:"Batter", o:true}, {n:"Tim Seifert", r:"Wicketkeeper", o:true}, {n:"Akash Deep", r:"Bowler", o:false}, {n:"Rahul Tripathi", r:"Batter", o:false}, {n:"Daksh Kamra", r:"Bowler", o:false}, {n:"Sarthak Ranjan", r:"Batter", o:false}, {n:"Prashant Solanki", r:"Bowler", o:false}, {n:"Kartik Tyagi", r:"Bowler", o:false},
            {n:"Shubman Gill", r:"Batter", o:false}, {n:"Rashid Khan", r:"Bowler", o:true}, {n:"Kagiso Rabada", r:"Bowler", o:true}, {n:"Pat Cummins", r:"Bowler", o:true}, {n:"Mitchell Starc", r:"Bowler", o:true}, {n:"Rishabh Pant", r:"Wicketkeeper", o:false}, {n:"KL Rahul", r:"Wicketkeeper", o:false}, {n:"Virat Kohli", r:"Batter", o:false}
        ];

        const tier1 = ["Virat Kohli", "Rohit Sharma", "Jasprit Bumrah", "Hardik Pandya", "Suryakumar Yadav", "Rishabh Pant", "KL Rahul", "Pat Cummins", "Mitchell Starc", "Rashid Khan", "Trent Boult", "Sanju Samson", "Shubman Gill"];
        const tier2 = ["Ruturaj Gaikwad", "Shivam Dube", "Quinton de Kock", "Cameron Green", "Matheesha Pathirana", "Rinku Singh", "Sunil Narine", "Kagiso Rabada"];

        let globalState = null; 

        window.switchTab = function(tabId) {
            document.querySelectorAll('.tab-content').forEach(el => el.classList.remove('active'));
            document.querySelectorAll('.nav-tabs button').forEach(el => el.classList.remove('active'));
            document.getElementById(tabId + '-tab').classList.add('active');
            document.getElementById('btn-' + tabId).classList.add('active');
        };

        window.generateTeamInputs = function() {
            const num = document.getElementById('numTeams').value;
            const container = document.getElementById('teamNamesContainer');
            container.innerHTML = '';
            for (let i = 1; i <= num; i++) {
                container.innerHTML += `<div class="form-group"><input type="text" id="teamName${i}" value="Franchise ${i}"></div>`;
            }
        };

        window.showAlert = function(msg) {
            const alertBox = document.getElementById('globalAlert');
            alertBox.innerText = msg;
            alertBox.style.display = 'block';
            setTimeout(() => { alertBox.style.display = 'none'; }, 5000);
        };

        // --- FIREBASE WRITE ACTIONS ---

        window.startAuction = function() {
            const num = document.getElementById('numTeams').value;
            const maxPlayers = parseInt(document.getElementById('playersPerTeam').value);
            const budget = parseFloat(document.getElementById('teamBudget').value);
            const multiplier = budget / 100;

            let dbPlayers = {};
            rawData.forEach((p, i) => {
                let base = 0.2; 
                if (tier1.includes(p.n)) base = 2.0;
                else if (tier2.includes(p.n)) base = 1.5;
                else if (p.o) base = 0.5; 
                else if (p.r === "All-Rounder") base = 0.3; 

                dbPlayers[i] = { id: i, name: p.n, role: p.r, isOverseas: p.o, basePrice: base * multiplier, status: 'available' };
            });

            let dbTeams = {};
            for (let i = 1; i <= num; i++) {
                const name = document.getElementById(`teamName${i}`).value || `Franchise ${i}`;
                dbTeams[name] = { name: name, budget: budget, roster: [] }; 
            }

            set(ref(db, '/'), {
                setup: { isStarted: true, maxPlayers: maxPlayers, budgetMultiplier: multiplier },
                players: dbPlayers,
                teams: dbTeams,
                currentBlock: { active: false }
            }).then(() => {
                window.switchTab('auction');
                window.showAlert("Database Initialized Successfully!");
            }).catch(error => {
                window.showAlert("FIREBASE ERROR: Permission Denied. Check your Firebase Rules tab!");
                console.error(error);
            });
        };

        window.pullRandomPlayer = function() {
            if(!globalState) return;
            const available = Object.values(globalState.players).filter(p => p.status === 'available');
            if (available.length === 0) return alert("No more available players.");
            const p = available[Math.floor(Math.random() * available.length)];
            
            update(ref(db, '/currentBlock'), { active: true, playerId: p.id, currentBid: p.basePrice })
                .catch(e => window.showAlert("Sync Error: " + e.message));
        };

        window.pullSpecificPlayer = function() {
            if(!globalState) return;
            const id = document.getElementById('manualPlayerSelect').value;
            if (!id) return;
            const p = globalState.players[id];
            
            update(ref(db, '/currentBlock'), { active: true, playerId: p.id, currentBid: p.basePrice })
                .catch(e => window.showAlert("Sync Error: " + e.message));
        };

        window.addBid = function(increment) {
            if(!globalState || !globalState.currentBlock.active) return;
            let newBid = globalState.currentBlock.currentBid + increment;
            update(ref(db, '/currentBlock'), { currentBid: newBid })
                .catch(e => window.showAlert("Sync Error: " + e.message));
        };

        window.sellPlayer = function() {
            if(!globalState || !globalState.currentBlock.active) return;
            
            const teamName = document.getElementById('winningTeamSelect').value;
            const bidAmount = globalState.currentBlock.currentBid;
            const pId = globalState.currentBlock.playerId;
            const player = globalState.players[pId];
            
            if(!teamName) return window.showAlert("Please select a winning franchise!");

            const team = globalState.teams[teamName];
            const roster = team.roster || []; 

            if (team.budget < bidAmount) return window.showAlert(`Insufficient funds! ${teamName} only has ₹${team.budget.toFixed(2)} Cr.`);
            if (roster.length >= globalState.setup.maxPlayers) return window.showAlert(`${teamName} is full.`);
            
            if (player.isOverseas) {
                const osCount = roster.filter(p => p.isOverseas).length;
                if (osCount >= 8) return window.showAlert(`${teamName} has max 8 overseas players.`);
            }

            let updates = {};
            roster.push({ name: player.name, role: player.role, isOverseas: player.isOverseas, soldPrice: bidAmount });
            updates[`/teams/${teamName}/roster`] = roster;
            updates[`/teams/${teamName}/budget`] = team.budget - bidAmount;
            updates[`/players/${pId}/status`] = 'sold';
            updates[`/players/${pId}/soldTo`] = teamName;
            updates[`/players/${pId}/soldPrice`] = bidAmount;
            updates['/currentBlock'] = { active: false, lastAction: `sold_${pId}_${teamName}_${bidAmount}` };

            update(ref(db, '/'), updates).catch(e => window.showAlert("Sync Error: " + e.message));
        };

        window.markUnsold = function() {
            if(!globalState || !globalState.currentBlock.active) return;
            const pId = globalState.currentBlock.playerId;
            
            let updates = {};
            updates[`/players/${pId}/status`] = 'unsold';
            updates['/currentBlock'] = { active: false, lastAction: 'unsold' };
            
            update(ref(db, '/'), updates).catch(e => window.showAlert("Sync Error: " + e.message));
        };

        window.exportCSV = function() {
            if(!globalState) return;
            let csvContent = "data:text/csv;charset=utf-8,Player Name,Role,Origin,Base Price (Cr),Status,Sold To,Winning Bid (Cr)\n";
            Object.values(globalState.players).forEach(p => {
                let row = `"${p.name}","${p.role}","${p.isOverseas ? 'Overseas' : 'Indian'}","${p.basePrice}","${p.status}","${p.soldTo || ''}","${p.soldPrice || ''}"`;
                csvContent += row + "\n";
            });
            const encodedUri = encodeURI(csvContent);
            const link = document.createElement("a");
            link.setAttribute("href", encodedUri);
            link.setAttribute("download", "ipl_auction_live_ledger.csv");
            document.body.appendChild(link);
            link.click();
            document.body.removeChild(link);
        };

        // --- FIREBASE READ LISTENER (SYNC MAGIC) ---

        onValue(ref(db, '/'), (snapshot) => {
            const data = snapshot.val();
            if (!data) return; 
            globalState = data;

            if(data.teams) {
                const teamSelect = document.getElementById('winningTeamSelect');
                const prevSelected = teamSelect.value;
                teamSelect.innerHTML = '<option value="">-- Select Winner --</option>';
                
                const grid = document.getElementById('teamGrid');
                grid.innerHTML = '';

                Object.values(data.teams).forEach(team => {
                    let opt = document.createElement('option');
                    opt.value = team.name;
                    opt.textContent = team.name;
                    teamSelect.appendChild(opt);

                    const roster = team.roster || [];
                    let osCount = roster.filter(p => p.isOverseas).length;
                    let html = `<div class="team-card glass-panel">
                        <h3 style="margin: 0 0 5px 0;">${team.name}</h3>
                        <div class="budget-display">₹${team.budget.toFixed(2)} Cr</div>
                        <div style="display:flex; justify-content: space-between; font-size: 0.8em; color: var(--text-muted); border-bottom: 1px solid rgba(255,255,255,0.1); padding-bottom: 8px;">
                            <span>Players: ${roster.length}/${data.setup.maxPlayers}</span>
                            <span style="color: ${osCount >= 8 ? 'var(--danger)' : 'inherit'}">OS: ${osCount}/8</span>
                        </div><ul>`;
                    roster.forEach(p => {
                        html += `<li><span>${p.name} ${p.isOverseas ? '<span class="overseas-badge">OS</span>' : ''}</span> 
                            <span style="font-weight:bold; color:var(--cream);">₹${p.soldPrice.toFixed(2)}</span></li>`;
                    });
                    html += `</ul></div>`;
                    grid.innerHTML += html;
                });
                teamSelect.value = prevSelected; 
            }

            if(data.players) {
                const select = document.getElementById('manualPlayerSelect');
                select.innerHTML = '<option value="">-- Search / Pull Specific Player --</option>';
                
                const tbody = document.querySelector('#globalRosterTable tbody');
                tbody.innerHTML = '';

                let available = Object.values(data.players).filter(p => p.status === 'available' || p.status === 'unsold').sort((a,b) => a.name.localeCompare(b.name));
                available.forEach(p => {
                    let opt = document.createElement('option');
                    opt.value = p.id;
                    opt.textContent = `${p.name} (${p.status === 'unsold' ? 'Unsold' : 'Available'})`;
                    select.appendChild(opt);
                });

                Object.values(data.players).forEach(p => {
                    let statusHtml = p.status === 'available' ? 'Available' : (p.status === 'unsold' ? '<span style="color:var(--danger)">Unsold</span>' : `<span style="color:var(--success)">${p.soldTo}</span>`);
                    tbody.innerHTML += `<tr>
                        <td style="font-weight: 600;">${p.name}</td>
                        <td>${p.role} ${p.isOverseas ? '✈️' : '🇮🇳'}</td>
                        <td>₹${p.basePrice.toFixed(2)}</td>
                        <td>${statusHtml}</td>
                        <td style="font-weight:700; color:var(--cream);">${p.soldPrice ? '₹' + p.soldPrice.toFixed(2) : '-'}</td>
                    </tr>`;
                });
            }

            const block = document.getElementById('auctionBlockDisplay');
            const controls = document.getElementById('biddingControls');
            
            if (data.currentBlock && data.currentBlock.active) {
                const player = data.players[data.currentBlock.playerId];
                controls.style.display = 'block';
                document.getElementById('liveBidText').innerText = `₹${data.currentBlock.currentBid.toFixed(2)}`;

                const m = data.setup.budgetMultiplier;
                const increments = [0.1 * m, 0.5 * m, 1.0 * m];
                document.getElementById('quickBidGrid').innerHTML = `
                    <button class="quick-bid-btn" onclick="window.addBid(${increments[0]})">+ ₹${increments[0].toFixed(1)}</button>
                    <button class="quick-bid-btn" onclick="window.addBid(${increments[1]})">+ ₹${increments[1].toFixed(1)}</button>
                    <button class="quick-bid-btn" onclick="window.addBid(${increments[2]})">+ ₹${increments[2].toFixed(1)}</button>
                `;

                block.innerHTML = `
                    <div style="display:inline-block; padding: 4px 12px; background: rgba(255,255,255,0.1); border-radius: 20px; margin-bottom: 10px; font-size:0.8rem;">Player #${player.id + 1}</div>
                    <h2 class="player-name-huge">${player.name}</h2>
                    <div class="player-meta">${player.role} | ${player.isOverseas ? '✈️ Overseas' : '🇮🇳 Indian'}</div>
                    <div class="base-price">Base: ₹${player.basePrice.toFixed(2)} Cr</div>
                `;
            } else {
                controls.style.display = 'none';
                if(data.currentBlock && data.currentBlock.lastAction) {
                    if (data.currentBlock.lastAction === 'unsold') {
                        block.innerHTML = `<h2 style="color: var(--danger); font-size: 2.2rem; margin: 0;">❌ UNSOLD</h2><p style="color: var(--text-muted);">Ready for next player...</p>`;
                    } else if (data.currentBlock.lastAction.startsWith('sold')) {
                        const parts = data.currentBlock.lastAction.split('_');
                        block.innerHTML = `<h2 style="color: var(--success); font-size: 2.2rem; margin: 0;">🔨 SOLD!</h2>
                        <p style="font-size: 1.1rem; margin: 5px 0;">To ${parts[2]}</p>
                        <p style="font-size: 1.5rem; font-weight: bold; color: var(--cream); margin:0;">₹${parseFloat(parts[3]).toFixed(2)} Cr</p>`;
                    }
                } else {
                    block.innerHTML = `<h3 style="color: var(--text-muted); margin: 40px 0;">Ready to begin</h3>`;
                }
            }
        });

        window.generateTeamInputs();

    </script>
</body>
</html>
