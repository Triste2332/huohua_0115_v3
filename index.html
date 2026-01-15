<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>36格翻牌抽奖系统</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', 'Microsoft YaHei', sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0f0c29 0%, #302b63 50%, #24243e 100%);
            color: #fff;
            min-height: 100vh;
            padding: 12px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        header {
            text-align: center;
            margin-bottom: 15px;
            padding: 12px;
            background: rgba(0, 0, 0, 0.4);
            border-radius: 10px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.4);
            border: 1px solid rgba(255, 255, 255, 0.1);
            position: relative;
            overflow: hidden;
        }
        
        header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 2px;
            background: linear-gradient(90deg, #ff9a00, #ff6a00, #ff9a00);
        }
        
        h1 {
            font-size: 1.8rem;
            margin-bottom: 6px;
            background: linear-gradient(90deg, #ff9a00, #ff6a00);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 1px 2px rgba(0, 0, 0, 0.3);
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }
        
        .subtitle {
            font-size: 0.9rem;
            color: #aaa;
            margin-bottom: 12px;
        }
        
        .currency-display {
            display: flex;
            justify-content: center;
            gap: 25px;
            margin-top: 12px;
            flex-wrap: wrap;
        }
        
        .currency {
            display: flex;
            align-items: center;
            background: rgba(0, 0, 0, 0.6);
            padding: 6px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 3px 8px rgba(0, 0, 0, 0.3);
        }
        
        .currency i {
            margin-right: 6px;
            font-size: 1rem;
        }
        
        .exploration-coin i {
            color: #00c3ff;
            text-shadow: 0 0 5px #00c3ff;
        }
        
        .spark-coin i {
            color: #ffcc00;
            text-shadow: 0 0 5px #ffcc00;
        }
        
        .stats-info {
            display: flex;
            justify-content: center;
            gap: 25px;
            margin-top: 12px;
            flex-wrap: wrap;
        }
        
        .stats {
            display: flex;
            align-items: center;
            background: rgba(0, 0, 0, 0.6);
            padding: 6px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 3px 8px rgba(0, 0, 0, 0.3);
        }
        
        .stats i {
            margin-right: 6px;
            font-size: 1rem;
            color: #ff6b6b;
        }
        
        .game-tools {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 12px;
            flex-wrap: wrap;
        }
        
        .tool-btn {
            padding: 6px 12px;
            font-size: 0.8rem;
            border: none;
            border-radius: 15px;
            cursor: pointer;
            font-weight: bold;
            transition: all 0.2s ease;
            display: flex;
            align-items: center;
            gap: 5px;
            box-shadow: 0 3px 6px rgba(0, 0, 0, 0.3);
        }
        
        .tool-btn.add-spark {
            background: linear-gradient(90deg, #ffcc00, #ff9900);
            color: #333;
        }
        
        .tool-btn.reset {
            background: linear-gradient(90deg, #ff6b6b, #ff5252);
            color: white;
        }
        
        .tool-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.4);
        }
        
        .main-content {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        
        .layer-selector {
            flex: 1;
            min-width: 250px;
            background: rgba(0, 0, 0, 0.4);
            border-radius: 10px;
            padding: 15px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.4);
            border: 1px solid rgba(255, 255, 255, 0.1);
            position: relative;
            overflow: hidden;
        }
        
        .layer-selector::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 4px;
            height: 100%;
            background: linear-gradient(to bottom, #ff9a00, #ff6a00);
        }
        
        .layer-selector h2 {
            text-align: center;
            margin-bottom: 15px;
            font-size: 1.3rem;
            color: #4dabf7;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
        }
        
        .layers {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        
        .layer-item {
            background: rgba(0, 0, 0, 0.5);
            padding: 12px;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.3s ease;
            border: 1px solid transparent;
            position: relative;
            overflow: hidden;
        }
        
        .layer-item:hover {
            transform: translateY(-3px);
            background: rgba(0, 0, 0, 0.7);
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.3);
        }
        
        .layer-item.active {
            border-color: #4dabf7;
            background: rgba(77, 171, 247, 0.1);
            box-shadow: 0 0 10px rgba(77, 171, 247, 0.5);
        }
        
        .layer-item.completed {
            border-color: #51cf66;
        }
        
        .layer-item.locked {
            cursor: not-allowed;
            opacity: 0.6;
        }
        
        .layer-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 6px;
        }
        
        .layer-title {
            font-size: 1.1rem;
            font-weight: bold;
        }
        
        .layer-status {
            font-size: 0.75rem;
            padding: 3px 8px;
            border-radius: 15px;
        }
        
        .status-locked {
            background: linear-gradient(90deg, #ff6b6b, #ff8787);
        }
        
        .status-active {
            background: linear-gradient(90deg, #4dabf7, #339af0);
        }
        
        .status-completed {
            background: linear-gradient(90deg, #51cf66, #40c057);
        }
        
        .layer-rewards {
            display: flex;
            align-items: center;
            gap: 10px;
            font-size: 0.8rem;
            color: #ccc;
            margin-top: 6px;
            flex-wrap: wrap;
        }
        
        .layer-info {
            font-size: 0.75rem;
            color: #aaa;
            margin-top: 5px;
        }
        
        .game-area {
            flex: 2;
            min-width: 300px;
            background: rgba(0, 0, 0, 0.4);
            border-radius: 10px;
            padding: 15px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.4);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .current-layer-info {
            text-align: center;
            margin-bottom: 15px;
            padding-bottom: 12px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .current-layer-info h3 {
            font-size: 1.3rem;
            margin-bottom: 6px;
            color: #ff9a00;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
        }
        
        .cards-container {
            display: grid;
            grid-template-columns: repeat(6, 1fr);
            gap: 4px;
            margin-bottom: 15px;
            padding: 5px;
            background: rgba(0, 0, 0, 0.2);
            border-radius: 8px;
        }
        
        .card {
            aspect-ratio: 1;
            background: linear-gradient(145deg, #2d3748, #1a202c);
            border-radius: 4px;
            display: flex;
            justify-content: center;
            align-items: center;
            cursor: pointer;
            transition: all 0.4s ease;
            transform-style: preserve-3d;
            position: relative;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.4);
            border: 1px solid rgba(255, 255, 255, 0.05);
        }
        
        .card:hover {
            transform: scale(1.05);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
            z-index: 10;
        }
        
        .card.flipped {
            transform: rotateY(180deg) scale(1);
            cursor: default;
        }
        
        .card.flipped:hover {
            transform: rotateY(180deg) scale(1);
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.4);
        }
        
        .card-front, .card-back {
            position: absolute;
            width: 100%;
            height: 100%;
            backface-visibility: hidden;
            border-radius: 4px;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            padding: 2px;
            text-align: center;
        }
        
        .card-front {
            background: linear-gradient(145deg, #2d3748, #1a202c);
            color: #4dabf7;
            font-size: 0.7rem;
        }
        
        .card-back {
            background: linear-gradient(145deg, #1e3c72, #2a5298);
            transform: rotateY(180deg);
            color: white;
            font-size: 0.5rem;
        }
        
        .card-back.normal {
            background: linear-gradient(145deg, #667eea, #764ba2);
        }
        
        .card-back.special {
            background: linear-gradient(145deg, #f093fb, #f5576c);
        }
        
        .card-back.jackpot {
            background: linear-gradient(145deg, #f6d365, #fda085);
            animation: jackpotGlow 1.5s infinite alternate;
        }
        
        @keyframes jackpotGlow {
            0% { box-shadow: 0 0 5px #f6d365; }
            100% { box-shadow: 0 0 15px #fda085, 0 0 20px #ff9a00; }
        }
        
        .card-value {
            font-size: 0.6rem;
            font-weight: bold;
            margin-bottom: 1px;
            line-height: 1.1;
        }
        
        .card-text {
            font-size: 0.4rem;
            line-height: 1;
        }
        
        .controls {
            display: flex;
            justify-content: center;
            gap: 12px;
            margin-top: 15px;
        }
        
        .btn {
            padding: 8px 15px;
            font-size: 0.8rem;
            border: none;
            border-radius: 20px;
            cursor: pointer;
            font-weight: bold;
            transition: all 0.2s ease;
            display: flex;
            align-items: center;
            gap: 6px;
            box-shadow: 0 3px 6px rgba(0, 0, 0, 0.3);
        }
        
        .btn-primary {
            background: linear-gradient(90deg, #ff9a00, #ff6a00);
            color: white;
        }
        
        .btn-secondary {
            background: linear-gradient(90deg, #4dabf7, #339af0);
            color: white;
        }
        
        .btn-success {
            background: linear-gradient(90deg, #51cf66, #40c057);
            color: white;
        }
        
        .btn-special {
            background: linear-gradient(90deg, #f093fb, #f5576c);
            color: white;
        }
        
        .btn:disabled {
            opacity: 0.5;
            cursor: not-allowed;
        }
        
        .btn:hover:not(:disabled) {
            transform: translateY(-2px);
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.4);
        }
        
        .jackpot-choice {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 10px;
            display: none;
        }
        
        .jackpot-message {
            text-align: center;
            background: rgba(255, 215, 0, 0.2);
            padding: 10px;
            border-radius: 8px;
            margin: 10px 0;
            border: 1px solid rgba(255, 215, 0, 0.5);
            display: none;
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0% { box-shadow: 0 0 0 0 rgba(255, 215, 0, 0.4); }
            70% { box-shadow: 0 0 0 10px rgba(255, 215, 0, 0); }
            100% { box-shadow: 0 0 0 0 rgba(255, 215, 0, 0); }
        }
        
        .progress-container {
            margin-top: 12px;
            background: rgba(0, 0, 0, 0.5);
            padding: 10px;
            border-radius: 6px;
        }
        
        .progress-text {
            display: flex;
            justify-content: space-between;
            margin-bottom: 6px;
            font-size: 0.85rem;
        }
        
        .progress-bar {
            height: 8px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 4px;
            overflow: hidden;
        }
        
        .progress-fill {
            height: 100%;
            background: linear-gradient(90deg, #ff9a00, #ff6a00);
            border-radius: 4px;
            width: 0%;
            transition: width 0.5s ease;
            position: relative;
            overflow: hidden;
        }
        
        .progress-fill::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.2), transparent);
            animation: shimmer 2s infinite;
        }
        
        @keyframes shimmer {
            0% { transform: translateX(-100%); }
            100% { transform: translateX(100%); }
        }
        
        .recent-rewards {
            margin-top: 15px;
            padding: 12px;
            background: rgba(0, 0, 0, 0.5);
            border-radius: 8px;
        }
        
        .recent-rewards h3 {
            margin-bottom: 8px;
            color: #ffcc00;
            display: flex;
            align-items: center;
            gap: 6px;
            font-size: 0.9rem;
        }
        
        .reward-list {
            display: flex;
            gap: 8px;
            flex-wrap: wrap;
        }
        
        .reward-item {
            background: rgba(255, 255, 255, 0.1);
            padding: 5px 8px;
            border-radius: 4px;
            font-size: 0.7rem;
            flex: 1;
            min-width: 150px;
        }
        
        .reward-item.jackpot {
            background: rgba(255, 215, 0, 0.2);
            border-left: 2px solid #ffd700;
        }
        
        @media (max-width: 1100px) {
            .cards-container {
                grid-template-columns: repeat(6, 1fr);
            }
        }
        
        @media (max-width: 800px) {
            .cards-container {
                grid-template-columns: repeat(6, 1fr);
            }
            
            .main-content {
                flex-direction: column;
            }
            
            .layer-selector {
                width: 100%;
            }
        }
        
        @media (max-width: 600px) {
            .cards-container {
                grid-template-columns: repeat(6, 1fr);
                gap: 3px;
            }
            
            .currency-display, .stats-info {
                flex-direction: column;
                gap: 8px;
                align-items: center;
            }
            
            .controls {
                flex-direction: column;
                align-items: center;
                gap: 8px;
            }
            
            .btn, .tool-btn {
                width: 100%;
                justify-content: center;
                padding: 6px 12px;
            }
            
            .jackpot-choice {
                flex-direction: column;
                align-items: center;
                gap: 8px;
            }
            
            h1 {
                font-size: 1.5rem;
            }
        }
        
        @media (max-width: 400px) {
            .cards-container {
                grid-template-columns: repeat(6, 1fr);
                gap: 2px;
            }
            
            .card-front {
                font-size: 0.6rem;
            }
            
            .card-back {
                font-size: 0.4rem;
            }
            
            .card-value {
                font-size: 0.5rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1><i class="fas fa-chess-board"></i> 36格翻牌抽奖系统</h1>
            <p class="subtitle">抽到大奖可选择继续抽或进入下一层</p>
            
            <div class="currency-display">
                <div class="currency exploration-coin">
                    <i class="fas fa-coins"></i>
                    <span>探险币: <span id="exploration-coin">0</span></span>
                </div>
                <div class="currency spark-coin">
                    <i class="fas fa-fire"></i>
                    <span>火花币: <span id="spark-coin">2851</span></span>
                </div>
            </div>
            
            <div class="stats-info">
                <div class="stats">
                    <i class="fas fa-money-bill-wave"></i>
                    <span>已花费: <span id="total-spent">0</span> 火花币</span>
                </div>
                <div class="stats">
                    <i class="fas fa-history"></i>
                    <span>重置次数: <span id="reset-count">0</span></span>
                </div>
            </div>
            
            <div class="game-tools">
                <button class="tool-btn add-spark" id="add-spark-btn">
                    <i class="fas fa-plus-circle"></i> 添加100火花币
                </button>
                <button class="tool-btn reset" id="reset-btn">
                    <i class="fas fa-redo"></i> 重置游戏
                </button>
            </div>
        </header>
        
        <div class="main-content">
            <div class="layer-selector">
                <h2><i class="fas fa-layer-group"></i> 探险排行</h2>
                <div class="layers" id="layer-list">
                    <!-- 层级将通过JS动态生成 -->
                </div>
            </div>
            
            <div class="game-area">
                <div class="current-layer-info">
                    <h3><i class="fas fa-chess-board"></i> 第 <span id="layer-number">1</span> 层 (6×6)</h3>
                    <p>抽到大奖后可选择继续或进入下一层</p>
                    <div id="jackpot-message" class="jackpot-message"></div>
                    <div class="progress-container">
                        <div class="progress-text">
                            <span>当前进度</span>
                            <span id="progress-text">0/36</span>
                        </div>
                        <div class="progress-bar">
                            <div class="progress-fill" id="progress-fill"></div>
                        </div>
                    </div>
                </div>
                
                <div class="cards-container" id="cards-container">
                    <!-- 36个格子将通过JS动态生成 -->
                </div>
                
                <div id="jackpot-choice" class="jackpot-choice">
                    <button class="btn btn-special" id="continue-btn">
                        <i class="fas fa-redo"></i> 继续抽奖
                    </button>
                    <button class="btn btn-success" id="next-layer-btn">
                        <i class="fas fa-arrow-right"></i> 进入下一层
                    </button>
                </div>
                
                <div class="controls">
                    <button class="btn btn-primary" id="flip-one">
                        <i class="fas fa-redo"></i> 探一次 (10火花币)
                    </button>
                    <button class="btn btn-secondary" id="flip-five">
                        <i class="fas fa-sync-alt"></i> 探五次 (50火花币)
                    </button>
                    <button class="btn btn-success" id="next-layer" disabled>
                        <i class="fas fa-arrow-right"></i> 下一层
                    </button>
                </div>
                
                <div class="recent-rewards">
                    <h3><i class="fas fa-gift"></i> 最近奖励</h3>
                    <div class="reward-list" id="recent-rewards">
                        <div class="reward-item jackpot">「残**」星光灿灿头像框*1天</div>
                        <div class="reward-item">「风**」梦幻海星</div>
                        <div class="reward-item">「龙**」琥珀香水</div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <script>
        // 游戏数据
        const gameData = {
            explorationCoin: 0,
            sparkCoin: 2851,
            currentLayer: 1,
            maxLayer: 5,
            cardCount: 36, // 每层36个格子
            jackpotFound: false, // 是否找到大奖
            jackpotIndex: -1, // 大奖的位置
            totalSpent: 0, // 总花费火花币
            resetCount: 0, // 重置次数
            layers: [
                {
                    id: 1,
                    name: "第1层",
                    cardCount: 36,
                    requiredFlips: 36,
                    completed: false,
                    unlocked: true,
                    normalRewards: ["梦幻海星", "琥珀香水", "爱你鸭", "万圣节聊天气泡", "谢谢鸭"],
                    jackpotReward: "星光灿灿头像框*1天",
                    rewards: [] // 初始化时为空，稍后生成
                },
                {
                    id: 2,
                    name: "第2层",
                    cardCount: 36,
                    requiredFlips: 36,
                    completed: false,
                    unlocked: false,
                    normalRewards: ["南瓜小怪", "女王桂冠", "恋爱弓箭", "暴富鸭", "芒果冻冻"],
                    jackpotReward: "暗夜恶魔头像框*7天",
                    rewards: []
                },
                {
                    id: 3,
                    name: "第3层",
                    cardCount: 36,
                    requiredFlips: 36,
                    completed: false,
                    unlocked: false,
                    normalRewards: ["爱心烟雾", "魔法书", "甜蜜蛋糕", "爱你鸭", "萌萌小虎"],
                    jackpotReward: "极光天使头像框",
                    rewards: []
                },
                {
                    id: 4,
                    name: "第4层",
                    cardCount: 36,
                    requiredFlips: 36,
                    completed: false,
                    unlocked: false,
                    normalRewards: ["暗夜糖喵座驾*1天", "幽静密堡", "土神兽", "小鹿乱撞", "南瓜小怪"],
                    jackpotReward: "诡夜誓约限定礼物",
                    rewards: []
                },
                {
                    id: 5,
                    name: "第5层",
                    cardCount: 36,
                    requiredFlips: 36,
                    completed: false,
                    unlocked: false,
                    normalRewards: ["海底星空", "南瓜烟花", "木神兽", "汉堡精灵", "柠檬物语"],
                    jackpotReward: "小猪捏捏乐限定信物",
                    rewards: []
                }
            ],
            flippedCards: 0,
            currentLayerCards: [],
            recentRewards: []
        };

        // 生成奖励配置 - 确保每个层级只有一个大奖
        function generateRewards(layer) {
            const rewards = [];
            
            // 生成35个奖励（确保只有一个大奖）
            // 生成34个常规奖励（随机从normalRewards中选择）
            for (let i = 0; i < 34; i++) {
                const randomIndex = Math.floor(Math.random() * layer.normalRewards.length);
                rewards.push({
                    type: "normal",
                    value: layer.normalRewards[randomIndex]
                });
            }
            
            // 生成1个特殊奖励（探险币）
            rewards.push({
                type: "special",
                value: `探险币 x${Math.floor(Math.random() * 50 * layer.id) + 20}`
            });
            
            // 生成1个大奖 - 确保只有一个
            rewards.push({
                type: "jackpot",
                value: layer.jackpotReward
            });
            
            // 总共36个奖励
            return rewards;
        }

        // DOM元素
        const explorationCoinEl = document.getElementById('exploration-coin');
        const sparkCoinEl = document.getElementById('spark-coin');
        const totalSpentEl = document.getElementById('total-spent');
        const resetCountEl = document.getElementById('reset-count');
        const layerListEl = document.getElementById('layer-list');
        const cardsContainerEl = document.getElementById('cards-container');
        const layerNumberEl = document.getElementById('layer-number');
        const progressTextEl = document.getElementById('progress-text');
        const progressFillEl = document.getElementById('progress-fill');
        const flipOneBtn = document.getElementById('flip-one');
        const flipFiveBtn = document.getElementById('flip-five');
        const nextLayerBtn = document.getElementById('next-layer');
        const recentRewardsEl = document.getElementById('recent-rewards');
        const jackpotMessageEl = document.getElementById('jackpot-message');
        const jackpotChoiceEl = document.getElementById('jackpot-choice');
        const continueBtn = document.getElementById('continue-btn');
        const nextLayerBtn2 = document.getElementById('next-layer-btn');
        const addSparkBtn = document.getElementById('add-spark-btn');
        const resetBtn = document.getElementById('reset-btn');

        // 初始化游戏
        function initGame() {
            // 为每个层级生成奖励
            gameData.layers.forEach(layer => {
                layer.rewards = generateRewards(layer);
            });
            
            updateCurrencyDisplay();
            updateStatsDisplay();
            renderLayerList();
            loadLayer(gameData.currentLayer);
            updateProgress();
        }

        // 更新货币显示
        function updateCurrencyDisplay() {
            explorationCoinEl.textContent = gameData.explorationCoin;
            sparkCoinEl.textContent = gameData.sparkCoin;
        }

        // 更新统计显示
        function updateStatsDisplay() {
            totalSpentEl.textContent = gameData.totalSpent;
            resetCountEl.textContent = gameData.resetCount;
        }

        // 添加火花币功能
        function addSparkCoins(amount) {
            gameData.sparkCoin += amount;
            updateCurrencyDisplay();
            
            // 显示提示
            showMessage(`成功添加 ${amount} 火花币！`, 'success');
        }

        // 显示消息提示
        function showMessage(message, type = 'info') {
            // 创建消息元素
            const messageEl = document.createElement('div');
            messageEl.textContent = message;
            messageEl.style.cssText = `
                position: fixed;
                top: 20px;
                right: 20px;
                padding: 10px 15px;
                border-radius: 8px;
                color: white;
                font-weight: bold;
                z-index: 1000;
                animation: slideIn 0.3s ease, fadeOut 0.3s ease 1.7s forwards;
                ${type === 'success' ? 'background: linear-gradient(90deg, #51cf66, #40c057);' : 
                  type === 'warning' ? 'background: linear-gradient(90deg, #ffcc00, #ff9900); color: #333;' : 
                  'background: linear-gradient(90deg, #4dabf7, #339af0);'}
            `;
            
            document.body.appendChild(messageEl);
            
            // 3秒后移除
            setTimeout(() => {
                if (messageEl.parentNode) {
                    messageEl.parentNode.removeChild(messageEl);
                }
            }, 2000);
        }

        // 重置游戏功能
        function resetGame() {
            if (!confirm("确定要重置游戏吗？所有进度和奖励将丢失！")) {
                return;
            }
            
            // 重置游戏数据
            gameData.explorationCoin = 0;
            gameData.sparkCoin = 2851;
            gameData.currentLayer = 1;
            gameData.jackpotFound = false;
            gameData.jackpotIndex = -1;
            gameData.flippedCards = 0;
            gameData.currentLayerCards = [];
            gameData.recentRewards = [];
            gameData.resetCount++;
            
            // 重置所有层级
            gameData.layers.forEach(layer => {
                layer.completed = false;
                layer.unlocked = layer.id === 1; // 只有第一层解锁
                layer.rewards = generateRewards(layer); // 重新生成奖励
            });
            
            // 隐藏大奖选择界面
            jackpotMessageEl.style.display = 'none';
            jackpotChoiceEl.style.display = 'none';
            
            // 清空最近奖励列表（除了示例数据）
            recentRewardsEl.innerHTML = `
                <div class="reward-item jackpot">「残**」星光灿灿头像框*1天</div>
                <div class="reward-item">「风**」梦幻海星</div>
                <div class="reward-item">「龙**」琥珀香水</div>
            `;
            
            // 更新显示
            updateCurrencyDisplay();
            updateStatsDisplay();
            renderLayerList();
            loadLayer(gameData.currentLayer);
            
            // 显示重置成功消息
            showMessage('游戏已重置！', 'success');
        }

        // 渲染层级列表
        function renderLayerList() {
            layerListEl.innerHTML = '';
            
            gameData.layers.forEach(layer => {
                const layerItem = document.createElement('div');
                layerItem.className = 'layer-item';
                
                if (layer.id === gameData.currentLayer) {
                    layerItem.classList.add('active');
                }
                
                if (layer.completed) {
                    layerItem.classList.add('completed');
                }
                
                if (!layer.unlocked) {
                    layerItem.classList.add('locked');
                }
                
                let statusText, statusClass;
                if (layer.completed) {
                    statusText = '已完成';
                    statusClass = 'status-completed';
                } else if (layer.id === gameData.currentLayer) {
                    statusText = '进行中';
                    statusClass = 'status-active';
                } else if (!layer.unlocked) {
                    statusText = '已锁定';
                    statusClass = 'status-locked';
                } else {
                    statusText = '未开始';
                    statusClass = 'status-active';
                }
                
                layerItem.innerHTML = `
                    <div class="layer-header">
                        <div class="layer-title">${layer.name}</div>
                        <div class="layer-status ${statusClass}">${statusText}</div>
                    </div>
                    <div class="layer-info">
                        <p>6×6 共36格 | 大奖: ${layer.jackpotReward}</p>
                        <p>常规奖励: ${layer.normalRewards.slice(0, 3).join('、')}...</p>
                    </div>
                `;
                
                if (layer.unlocked && !layer.completed) {
                    layerItem.addEventListener('click', () => {
                        switchLayer(layer.id);
                    });
                }
                
                layerListEl.appendChild(layerItem);
            });
        }

        // 切换层级
        function switchLayer(layerId) {
            if (layerId > gameData.currentLayer && !gameData.layers[layerId-2].completed) {
                alert('请先完成当前层级！');
                return;
            }
            
            gameData.currentLayer = layerId;
            gameData.jackpotFound = false;
            loadLayer(layerId);
            renderLayerList();
        }

        // 加载层级
        function loadLayer(layerId) {
            const layer = gameData.layers[layerId-1];
            
            // 更新UI
            layerNumberEl.textContent = layerId;
            
            // 重置翻牌计数
            gameData.flippedCards = 0;
            gameData.jackpotFound = false;
            
            // 隐藏大奖选择界面
            jackpotMessageEl.style.display = 'none';
            jackpotChoiceEl.style.display = 'none';
            
            // 恢复按钮状态
            flipOneBtn.disabled = false;
            flipFiveBtn.disabled = false;
            nextLayerBtn.disabled = true;
            
            // 生成卡牌
            generateCards(layer);
            
            // 更新进度
            updateProgress();
        }

        // 生成36个格子（6×6）- 确保大奖只有一个
        function generateCards(layer) {
            cardsContainerEl.innerHTML = '';
            gameData.currentLayerCards = [];
            
            // 复制奖励数组并随机打乱
            const rewardsPool = [...layer.rewards];
            shuffleArray(rewardsPool);
            
            // 记录大奖位置
            gameData.jackpotIndex = -1;
            rewardsPool.forEach((reward, index) => {
                if (reward.type === "jackpot") {
                    gameData.jackpotIndex = index;
                }
            });
            
            // 创建36个格子
            for (let i = 0; i < gameData.cardCount; i++) {
                const card = document.createElement('div');
                card.className = 'card';
                card.dataset.index = i;
                
                let reward = null;
                if (i < rewardsPool.length) {
                    reward = rewardsPool[i];
                } else {
                    // 如果奖励池不够，生成默认常规奖励
                    const randomIndex = Math.floor(Math.random() * layer.normalRewards.length);
                    reward = {
                        type: "normal",
                        value: layer.normalRewards[randomIndex]
                    };
                }
                
                gameData.currentLayerCards[i] = {
                    flipped: false,
                    reward: reward
                };
                
                let cardBackClass = 'card-back ';
                if (reward.type === 'normal') {
                    cardBackClass += 'normal';
                } else if (reward.type === 'special') {
                    cardBackClass += 'special';
                } else if (reward.type === 'jackpot') {
                    cardBackClass += 'jackpot';
                }
                
                // 处理显示文本
                let displayValue = reward.value;
                let displayText = "";
                
                if (reward.type === 'normal') {
                    displayText = "常规奖励";
                } else if (reward.type === 'special') {
                    displayText = "特殊奖励";
                } else if (reward.type === 'jackpot') {
                    displayText = "终极大奖";
                }
                
                // 如果文本太长，进行截断
                if (displayValue.length > 8) {
                    displayValue = displayValue.substring(0, 6) + '...';
                }
                
                card.innerHTML = `
                    <div class="card-front">
                        <i class="fas fa-question"></i>
                    </div>
                    <div class="${cardBackClass}">
                        <div class="card-value">${displayValue}</div>
                        <div class="card-text">${displayText}</div>
                    </div>
                `;
                
                card.addEventListener('click', () => flipCard(i));
                
                cardsContainerEl.appendChild(card);
            }
        }

        // 翻牌
        function flipCard(cardIndex) {
            const card = document.querySelector(`.card[data-index="${cardIndex}"]`);
            const layer = gameData.layers[gameData.currentLayer-1];
            
            if (!card || gameData.currentLayerCards[cardIndex].flipped || layer.completed) {
                return;
            }
            
            // 检查是否有足够火花币
            if (gameData.sparkCoin < 10) {
                alert('火花币不足！');
                return;
            }
            
            // 扣除火花币并记录花费
            gameData.sparkCoin -= 10;
            gameData.totalSpent += 10;
            
            updateCurrencyDisplay();
            updateStatsDisplay();
            
            // 翻牌动画
            card.classList.add('flipped');
            gameData.currentLayerCards[cardIndex].flipped = true;
            
            // 增加翻牌计数
            gameData.flippedCards++;
            
            // 发放奖励
            const reward = gameData.currentLayerCards[cardIndex].reward;
            let rewardMessage = '';
            let isJackpot = false;
            
            if (reward.type === 'normal') {
                rewardMessage = reward.value;
            } else if (reward.type === 'special') {
                rewardMessage = reward.value;
                // 如果是特殊奖励（探险币），添加到账户
                const match = reward.value.match(/探险币 x(\d+)/);
                if (match) {
                    const coinAmount = parseInt(match[1]);
                    gameData.explorationCoin += coinAmount;
                    updateCurrencyDisplay();
                }
            } else if (reward.type === 'jackpot') {
                rewardMessage = layer.jackpotReward;
                isJackpot = true;
                gameData.jackpotFound = true;
                
                // 显示大奖信息和选择
                jackpotMessageEl.textContent = `🎉 恭喜您抽到大奖: ${layer.jackpotReward}！`;
                jackpotMessageEl.style.display = 'block';
                jackpotChoiceEl.style.display = 'flex';
                
                // 禁用常规翻牌按钮
                flipOneBtn.disabled = true;
                flipFiveBtn.disabled = true;
            }
            
            // 更新进度
            updateProgress();
            
            // 添加奖励记录
            addRecentReward(rewardMessage, isJackpot);
            
            // 如果没有抽到大奖，检查是否完成当前层级
            if (!isJackpot && gameData.flippedCards >= layer.requiredFlips) {
                layer.completed = true;
                nextLayerBtn.disabled = false;
                flipOneBtn.disabled = true;
                flipFiveBtn.disabled = true;
                
                // 解锁下一层
                if (gameData.currentLayer < gameData.maxLayer) {
                    gameData.layers[gameData.currentLayer].unlocked = true;
                }
                
                renderLayerList();
                
                setTimeout(() => {
                    alert(`恭喜！您已完成${layer.name}！`);
                }, 500);
            }
        }

        // 翻五张牌
        function flipFiveCards() {
            const layer = gameData.layers[gameData.currentLayer-1];
            
            if (layer.completed || gameData.jackpotFound) {
                return;
            }
            
            // 检查是否有足够火花币
            if (gameData.sparkCoin < 50) {
                alert('火花币不足！');
                return;
            }
            
            // 检查是否还有未翻的牌
            const unflippedCards = gameData.currentLayerCards.filter(card => !card.flipped);
            if (unflippedCards.length === 0) {
                alert('所有格子都已翻开！');
                return;
            }
            
            // 计算实际要翻的牌数
            const cardsToFlip = Math.min(5, unflippedCards.length);
            
            // 扣除火花币并记录花费
            gameData.sparkCoin -= 50;
            gameData.totalSpent += 50;
            
            updateCurrencyDisplay();
            updateStatsDisplay();
            
            // 随机选择未翻的牌
            const unflippedIndices = [];
            gameData.currentLayerCards.forEach((card, index) => {
                if (!card.flipped) {
                    unflippedIndices.push(index);
                }
            });
            
            shuffleArray(unflippedIndices);
            const selectedIndices = unflippedIndices.slice(0, cardsToFlip);
            
            // 翻选中的牌
            let hasJackpot = false;
            let jackpotReward = '';
            
            selectedIndices.forEach((cardIndex, i) => {
                setTimeout(() => {
                    const card = document.querySelector(`.card[data-index="${cardIndex}"]`);
                    if (card) {
                        card.classList.add('flipped');
                        gameData.currentLayerCards[cardIndex].flipped = true;
                        
                        // 记录奖励
                        const reward = gameData.currentLayerCards[cardIndex].reward;
                        
                        // 检查是否是大奖
                        if (reward.type === 'jackpot') {
                            hasJackpot = true;
                            jackpotReward = reward.value;
                            gameData.jackpotFound = true;
                        }
                        
                        // 特殊奖励处理
                        if (reward.type === 'special') {
                            const match = reward.value.match(/探险币 x(\d+)/);
                            if (match) {
                                const coinAmount = parseInt(match[1]);
                                gameData.explorationCoin += coinAmount;
                            }
                        }
                        
                        // 增加翻牌计数
                        gameData.flippedCards++;
                        
                        // 更新进度
                        updateProgress();
                        
                        // 添加奖励记录
                        if (reward.type !== 'special') {
                            addRecentReward(reward.value, reward.type === 'jackpot');
                        }
                        
                        // 如果是最后一张
                        if (i === selectedIndices.length - 1) {
                            updateCurrencyDisplay();
                            
                            // 如果抽到了大奖
                            if (hasJackpot) {
                                // 显示大奖信息和选择
                                jackpotMessageEl.textContent = `🎉 恭喜您抽到大奖: ${jackpotReward}！`;
                                jackpotMessageEl.style.display = 'block';
                                jackpotChoiceEl.style.display = 'flex';
                                
                                // 禁用常规翻牌按钮
                                flipOneBtn.disabled = true;
                                flipFiveBtn.disabled = true;
                            }
                            
                            // 如果没有抽到大奖，检查是否完成当前层级
                            if (!hasJackpot && gameData.flippedCards >= layer.requiredFlips) {
                                layer.completed = true;
                                nextLayerBtn.disabled = false;
                                flipOneBtn.disabled = true;
                                flipFiveBtn.disabled = true;
                                
                                // 解锁下一层
                                if (gameData.currentLayer < gameData.maxLayer) {
                                    gameData.layers[gameData.currentLayer].unlocked = true;
                                }
                                
                                renderLayerList();
                                
                                setTimeout(() => {
                                    alert(`恭喜！您已完成${layer.name}！`);
                                }, 500);
                            }
                        }
                    }
                }, i * 200);
            });
        }

        // 继续抽奖（抽到大奖后选择）
        continueBtn.addEventListener('click', function() {
            // 隐藏大奖选择界面
            jackpotMessageEl.style.display = 'none';
            jackpotChoiceEl.style.display = 'none';
            
            // 恢复翻牌按钮
            flipOneBtn.disabled = false;
            flipFiveBtn.disabled = false;
            
            // 标记大奖已被找到，但可以继续抽
            gameData.jackpotFound = true;
        });

        // 进入下一层（抽到大奖后选择）
        nextLayerBtn2.addEventListener('click', function() {
            const layer = gameData.layers[gameData.currentLayer-1];
            
            // 标记层级完成
            layer.completed = true;
            
            // 解锁下一层
            if (gameData.currentLayer < gameData.maxLayer) {
                gameData.layers[gameData.currentLayer].unlocked = true;
            }
            
            // 隐藏大奖选择界面
            jackpotMessageEl.style.display = 'none';
            jackpotChoiceEl.style.display = 'none';
            
            // 启用下一层按钮
            nextLayerBtn.disabled = false;
            
            // 更新层级列表
            renderLayerList();
            
            // 提示用户
            alert(`您选择了进入下一层。${layer.name}已标记为完成！`);
        });

        // 更新进度
        function updateProgress() {
            const layer = gameData.layers[gameData.currentLayer-1];
            const progress = Math.min(gameData.flippedCards, layer.requiredFlips);
            const percentage = (progress / layer.requiredFlips) * 100;
            
            progressTextEl.textContent = `${progress}/${layer.requiredFlips}`;
            progressFillEl.style.width = `${percentage}%`;
        }

        // 添加最近奖励
        function addRecentReward(rewardText, isJackpot = false) {
            const rewardItem = document.createElement('div');
            rewardItem.className = 'reward-item';
            if (isJackpot) rewardItem.classList.add('jackpot');
            rewardItem.textContent = `「${getRandomName()}」${rewardText}`;
            
            recentRewardsEl.prepend(rewardItem);
            
            // 限制显示数量
            if (recentRewardsEl.children.length > 5) {
                recentRewardsEl.removeChild(recentRewardsEl.lastChild);
            }
        }

        // 获取随机名字
        function getRandomName() {
            const surnames = ['残', '风', '龙', '影', '星', '月', '炎', '冰', '雷', '光', '云', '雨', '雪', '夜', '日'];
            const name = surnames[Math.floor(Math.random() * surnames.length)] + '**';
            return name;
        }

        // 数组随机打乱
        function shuffleArray(array) {
            for (let i = array.length - 1; i > 0; i--) {
                const j = Math.floor(Math.random() * (i + 1));
                [array[i], array[j]] = [array[j], array[i]];
            }
            return array;
        }

        // 进入下一层（常规按钮）
        nextLayerBtn.addEventListener('click', function() {
            const currentLayer = gameData.layers[gameData.currentLayer-1];
            
            if (!currentLayer.completed) {
                alert('请先完成当前层级！');
                return;
            }
            
            if (gameData.currentLayer >= gameData.maxLayer) {
                alert('恭喜！您已完成所有层级！');
                return;
            }
            
            gameData.currentLayer++;
            gameData.jackpotFound = false;
            loadLayer(gameData.currentLayer);
            renderLayerList();
        });

        // 事件监听
        flipOneBtn.addEventListener('click', () => {
            // 如果已经抽到大奖但未选择
            if (gameData.jackpotFound) {
                alert('您已经抽到大奖，请先选择继续抽奖或进入下一层！');
                return;
            }
            
            // 随机翻一张未翻的牌
            const unflippedCards = gameData.currentLayerCards.filter(card => !card.flipped);
            if (unflippedCards.length === 0) {
                alert('所有格子都已翻开！');
                return;
            }
            
            const randomIndex = Math.floor(Math.random() * unflippedCards.length);
            let cardIndex = -1;
            
            // 找到对应的卡片索引
            gameData.currentLayerCards.forEach((card, idx) => {
                if (!card.flipped && cardIndex === -1) {
                    randomIndex--;
                    if (randomIndex < 0) {
                        cardIndex = idx;
                    }
                }
            });
            
            if (cardIndex !== -1) {
                flipCard(cardIndex);
            }
        });

        flipFiveBtn.addEventListener('click', flipFiveCards);

        // 添加火花币按钮事件
        addSparkBtn.addEventListener('click', function() {
            addSparkCoins(100);
        });

        // 重置游戏按钮事件
        resetBtn.addEventListener('click', resetGame);

        // 初始化游戏
        initGame();
    </script>
</body>
</html>
