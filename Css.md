body{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    min-height: 100vh;
}

.vs-container{
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    margin: 0 auto;
    
}

body {
    margin: 0;
    min-height: 100vh;

    
    background: linear-gradient(
        180deg,
        #1E3A8A 0%,
        #312E81 100%
    );

    color: white;
}

/* ===========================
   SHARED STYLING
   =========================== */

   .handCards{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
}

/* ===========================
   PLAYER 1 INFO
   =========================== */

.player1Info {
    flex: 0.5;

    background: rgba(96, 165, 250, 0.15);

    border-bottom: 1px solid #93C5FD;

    box-shadow:
        0 0 10px #38BDF8;
}

/* ===========================
   PLAYER 1 CARD AREA
   =========================== */

#player1Box {
    flex: 3.5;
    background: rgba(59, 130, 246, 0.15);
    backdrop-filter: blur(8px);
}

.player1TextInfo{
    display: flex;
}

.card{
    width: 120px;
    height: 150px;
    border: 1px solid black;
}

/* ===========================
   BATTLE AREA
   =========================== */

.battleArena {
    flex: 3.5;
    background: rgba(250, 204, 21, 0.08);
}

.battleArenaSection{
    display: flex;
}

.shuffleCard{
    width: 120px;
    height: 150px;
    border: 1px solid black;
}

.vs-section{
    display: flex;
    justify-content: center;
    align-items: center;
}

/* ===========================
   PLAYER 2 CARD AREA
   =========================== */

#player2Box {
    flex: 3.5;
    background: rgba(239, 68, 68, 0.15);
    backdrop-filter: blur(8px);
}

/* ===========================
   PLAYER 2 INFO
   =========================== */

.player2Info {
    flex: 0.5;
    background: rgba(248, 113, 113, 0.15);


}
