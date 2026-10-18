# Nonchalant-stuff

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Card game</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

        <div class="vs-container">
            <!-- ===========================
            PLAYER 1 CARD AREA
            ===========================  -->
            <section id="player1Box" aria-label="Computer hand">
                <!-- Player 1 info  -->
                <div class="player1TextInfo">
                    <span class="name">COMPUTER -</span>
                    <span class="score">10</span>
                </div>

                <!-- Player 1 card hand set -->
                <div class="handCards">
                    <div class="card">Card 1</div>
                    <div class="card">Card 2</div>
                    <div class="card">Card 3</div>
                    <div class="card">Card 4</div>
                    <div class="card">Card 5</div>
                </div>
                
            </section>
            
            <!-- ===========================
            BATTLE AREANA
            ===========================  -->
            <section class="battleArena" aria-label="Battle Arena">
                <div class="battleArenaSection">
                    
                    <div class="shuffleCard">Shuffle Card</div>
                    
                    <div class="vs-section">
                        <div class="card">Card 4</div>
                        <span class="VS-text">VS</span>
                        <div class="card">Card 4</div>
                    </div>
                </div>
            </section>
            
            <!-- ===========================
            PLAYER 2 CARD AREA
            ===========================  -->
            <section id="player2Box" aria-label="User hand">
                <!-- Player 2 info  -->
                <div class="player2TextInfo">
                    <span class="name">USER -</span>
                    <span class="score">10</span>
                </div>
                <!-- Player 2 card hand set -->
                <div class="handCards">
                    <div class="card">Card 1</div>
                    <div class="card">Card 2</div>
                    <div class="card">Card 3</div>
                    <div class="card">Card 4</div>
                    <div class="card">Card 5</div>
                </div>
            </section>
            
    </div>


    
    <script src="script.js"></script>
</body>
</html>
