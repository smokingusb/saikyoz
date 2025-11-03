<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>Saikyo VPN - Личный кабинет</title>
  <script src="https://telegram.org/js/telegram-web-app.js"></script>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
      background: #000000;
      color: #FFFFFF;
      padding: 20px;
      min-height: 100vh;
      overflow-x: hidden;
    }

    .container {
      max-width: 500px;
      margin: 0 auto;
    }

    /* Animated Spiral Logo */
    .logo-container {
      display: flex;
      justify-content: center;
      align-items: center;
      margin: 30px 0 40px;
    }

    .spiral-logo {
      width: 150px;
      height: 150px;
      animation: rotate 3s linear infinite;
    }

    @keyframes rotate {
      from { transform: rotate(0deg); }
      to { transform: rotate(360deg); }
    }

    .spiral-path {
      stroke: #06D6A0;
      stroke-width: 3;
      fill: none;
      stroke-linecap: round;
      filter: drop-shadow(0 0 8px rgba(6, 214, 160, 0.6));
    }

    /* Header */
    .header {
      text-align: center;
      margin-bottom: 30px;
    }

    .app-name {
      font-size: 32px;
      font-weight: 700;
      letter-spacing: 4px;
      color: #FFFFFF;
      margin-bottom: 10px;
    }

    .subtitle {
      font-size: 14px;
      color: #94A3B8;
      letter-spacing: 1px;
    }

    /* User Info Card */
    .user-card {
      background: rgba(255, 255, 255, 0.05);
      border: 1px solid rgba(255, 255, 255, 0.1);
      border-radius: 12px;
      padding: 20px;
      margin-bottom: 25px;
    }

    .user-row {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px 0;
      border-bottom: 1px solid rgba(255, 255, 255, 0.05);
    }

    .user-row:last-child {
      border-bottom: none;
    }

    .user-label {
      font-size: 14px;
      color: #94A3B8;
    }

    .user-value {
      font-size: 14px;
      color: #FFFFFF;
      font-weight: 600;
    }

    .status-badge {
      display: inline-block;
      padding: 4px 12px;
      border-radius: 20px;
      font-size: 12px;
      font-weight: 600;
    }

    .status-active {
      background: rgba(6, 214, 160, 0.2);
      color: #06D6A0;
    }

    .status-expired {
      background: rgba(239, 68, 68, 0.2);
      color: #EF4444;
    }

    .status-free {
      background: rgba(245, 158, 11, 0.2);
      color: #F59E0B;
    }

    /* Pricing Section */
    .section-title {
      font-size: 18px;
      font-weight: 600;
      letter-spacing: 1px;
      margin: 30px 0 20px;
      color: #FFFFFF;
    }

    .pricing-grid {
      display: grid;
      grid-template-columns: 1fr;
      gap: 12px;
      margin-bottom: 25px;
    }

    .price-card {
      background: rgba(255, 255, 255, 0.05);
      border: 1px solid rgba(255, 255, 255, 0.1);
      border-radius: 12px;
      padding: 16px;
      cursor: pointer;
      transition: all 0.2s;
      position: relative;
    }

    .price-card:hover {
      background: rgba(255, 255, 255, 0.08);
      border-color: #06D6A0;
    }

    .price-card.selected {
      background: rgba(6, 214, 160, 0.1);
      border: 2px solid #06D6A0;
    }

    .price-card.popular::before {
      content: 'ПОПУЛЯРНО';
      position: absolute;
      top: -10px;
      right: 15px;
      background: #06D6A0;
      color: #000000;
      padding: 4px 12px;
      border-radius: 12px;
      font-size: 10px;
      font-weight: 700;
      letter-spacing: 0.5px;
    }

    .price-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 8px;
    }

    .price-duration {
      font-size: 16px;
      font-weight: 600;
      color: #FFFFFF;
    }

    .price-amount {
      font-size: 20px;
      font-weight: 700;
      color: #06D6A0;
    }

    .price-per-month {
      font-size: 12px;
      color: #94A3B8;
      margin-top: 4px;
    }

    .price-savings {
      font-size: 12px;
      color: #06D6A0;
      font-weight: 600;
      margin-top: 4px;
    }

    /* Device Info */
    .device-card {
      background: rgba(255, 255, 255, 0.05);
      border: 1px solid rgba(255, 255, 255, 0.1);
      border-radius: 12px;
      padding: 16px;
      margin-bottom: 20px;
    }

    .device-name {
      font-size: 14px;
      color: #FFFFFF;
      margin-bottom: 8px;
    }

    .device-id {
      font-size: 12px;
      color: #94A3B8;
      font-family: 'Courier New', monospace;
    }

    /* Buttons */
    .btn {
      width: 100%;
      padding: 16px;
      border: none;
      border-radius: 12px;
      font-size: 16px;
      font-weight: 700;
      letter-spacing: 1px;
      cursor: pointer;
      transition: all 0.2s;
      margin-bottom: 12px;
    }

    .btn-primary {
      background: #06D6A0;
      color: #000000;
    }

    .btn-primary:hover {
      background: #05BF8E;
      transform: translateY(-2px);
    }

    .btn-primary:disabled {
      background: rgba(6, 214, 160, 0.3);
      cursor: not-allowed;
      transform: none;
    }

    .btn-secondary {
      background: rgba(255, 255, 255, 0.05);
      color: #FFFFFF;
      border: 1px solid rgba(255, 255, 255, 0.1);
    }

    .btn-secondary:hover {
      background: rgba(255, 255, 255, 0.1);
    }

    /* Loading */
    .loading {
      text-align: center;
      padding: 40px;
      color: #94A3B8;
    }

    .spinner {
      width: 40px;
      height: 40px;
      border: 3px solid rgba(255, 255, 255, 0.1);
      border-top-color: #06D6A0;
      border-radius: 50%;
      animation: spin 1s linear infinite;
      margin: 0 auto 16px;
    }

    @keyframes spin {
      to { transform: rotate(360deg); }
    }

    /* Alert */
    .alert {
      padding: 12px 16px;
      border-radius: 8px;
      margin-bottom: 20px;
      font-size: 14px;
    }

    .alert-info {
      background: rgba(6, 214, 160, 0.1);
      color: #06D6A0;
      border: 1px solid rgba(6, 214, 160, 0.3);
    }

    .alert-warning {
      background: rgba(245, 158, 11, 0.1);
      color: #F59E0B;
      border: 1px solid rgba(245, 158, 11, 0.3);
    }

    .hidden {
      display: none;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Logo -->
    <div class="logo-container">
      <svg class="spiral-logo" viewBox="0 0 150 150">
        <path class="spiral-path" id="spiralPath" d=""/>
      </svg>
    </div>

    <!-- Header -->
    <div class="header">
      <div class="app-name">SAIKYO</div>
      <div class="subtitle">ЛИЧНЫЙ КАБИНЕТ</div>
    </div>

    <!-- Loading State -->
    <div id="loading" class="loading">
      <div class="spinner"></div>
      <div>Загрузка данных...</div>
    </div>

    <!-- Main Content -->
    <div id="content" class="hidden">
      <!-- User Info Card -->
      <div class="user-card">
        <div class="user-row">
          <span class="user-label">Пользователь</span>
          <span class="user-value" id="userName">—</span>
        </div>
        <div class="user-row">
          <span class="user-label">Статус подписки</span>
          <span class="status-badge" id="statusBadge">—</span>
        </div>
        <div class="user-row">
          <span class="user-label">Дней осталось</span>
          <span class="user-value" id="daysLeft">—</span>
        </div>
        <div class="user-row">
          <span class="user-label">Устройств подключено</span>
          <span class="user-value" id="deviceCount">—</span>
        </div>
      </div>

      <!-- Device Info -->
      <div id="deviceInfo" class="device-card hidden">
        <div class="device-name">📱 Текущее устройство</div>
        <div class="device-id" id="deviceId">—</div>
      </div>

      <!-- Free Trial Alert -->
      <div id="freeTrialAlert" class="alert alert-warning hidden">
        ⚠️ У вас бесплатный пробный период. Подключите подписку для постоянного доступа.
      </div>

      <!-- Pricing Section -->
      <div class="section-title">💳 ТАРИФЫ</div>
      <div class="pricing-grid" id="pricingGrid">
        <!-- Pricing cards will be inserted here -->
      </div>

      <!-- Payment Button -->
      <button class="btn btn-primary" id="payBtn" disabled>
        ОПЛАТИТЬ
      </button>

      <!-- Get Free Key Button -->
      <button class="btn btn-secondary" id="getFreeKeyBtn">
        🎁 ПОЛУЧИТЬ БЕСПЛАТНЫЙ КЛЮЧ
      </button>
    </div>
  </div>

  <script>
    // Initialize Telegram WebApp
    const tg = window.Telegram.WebApp;
    tg.expand();
    tg.ready();

    // User data
    const user = tg.initDataUnsafe?.user;
    const userId = user?.id;

    // Pricing plans (rubles per month for 1 device)
    const pricingPlans = [
      { months: 1, price: 100, perMonth: 100 },
      { months: 2, price: 150, perMonth: 75, savings: 25 },
      { months: 3, price: 250, perMonth: 83, savings: 50, popular: true },
      { months: 6, price: 450, perMonth: 75, savings: 150 },
      { months: 12, price: 800, perMonth: 67, savings: 400 },
      { months: 24, price: 1400, perMonth: 58, savings: 1000 },
    ];

    let selectedPlan = null;
    let userData = null;

    // Generate spiral path for logo
    function generateSpiralPath() {
      const centerX = 75;
      const centerY = 75;
      const maxRadius = 65;
      const turns = 3;
      const points = 48;
      
      let path = `M ${centerX} ${centerY}`;
      
      for (let i = 0; i <= points; i++) {
        const angle = (i / points) * turns * 2 * Math.PI;
        const radius = (i / points) * maxRadius;
        const x = centerX + radius * Math.cos(angle);
        const y = centerY + radius * Math.sin(angle);
        
        if (i === 0) {
          path += ` L ${x} ${y}`;
        } else {
          const prevAngle = ((i - 1) / points) * turns * 2 * Math.PI;
          const prevRadius = ((i - 1) / points) * maxRadius;
          const prevX = centerX + prevRadius * Math.cos(prevAngle);
          const prevY = centerY + prevRadius * Math.sin(prevAngle);
          const cpX = (prevX + x) / 2;
          const cpY = (prevY + y) / 2;
          path += ` Q ${cpX} ${cpY} ${x} ${y}`;
        }
      }
      
      return path;
    }

    // Set spiral path
    document.getElementById('spiralPath').setAttribute('d', generateSpiralPath());

    // Load user data
    async function loadUserData() {
      try {
        // Send request to bot backend
        const response = await fetch(`/api/user/${userId}`, {
          method: 'GET',
          headers: {
            'Content-Type': 'application/json',
          },
        });

        if (!response.ok) {
          throw new Error('Failed to load user data');
        }

        userData = await response.json();
        updateUI();
      } catch (error) {
        console.error('Error loading user data:', error);
        tg.showAlert('Ошибка загрузки данных. Попробуйте позже.');
      } finally {
        document.getElementById('loading').classList.add('hidden');
        document.getElementById('content').classList.remove('hidden');
      }
    }

    // Update UI with user data
    function updateUI() {
      if (!userData) {
        // Default state for new users
        document.getElementById('userName').textContent = user?.first_name || 'Пользователь';
        document.getElementById('statusBadge').textContent = 'Новый';
        document.getElementById('statusBadge').className = 'status-badge status-free';
        document.getElementById('daysLeft').textContent = '0';
        document.getElementById('deviceCount').textContent = '0/1';
        return;
      }

      // Update user info
      document.getElementById('userName').textContent = userData.username || user?.first_name || 'Пользователь';
      
      // Calculate days left
      const now = new Date();
      const expiresAt = userData.expiresAt ? new Date(userData.expiresAt) : null;
      const daysLeft = expiresAt ? Math.max(0, Math.ceil((expiresAt - now) / (1000 * 60 * 60 * 24))) : 0;
      
      document.getElementById('daysLeft').textContent = daysLeft > 0 ? daysLeft : '0';
      
      // Update status badge
      const statusBadge = document.getElementById('statusBadge');
      if (daysLeft > 0) {
        if (userData.isFree) {
          statusBadge.textContent = 'Пробный период';
          statusBadge.className = 'status-badge status-free';
          document.getElementById('freeTrialAlert').classList.remove('hidden');
        } else {
          statusBadge.textContent = 'Активна';
          statusBadge.className = 'status-badge status-active';
        }
      } else {
        statusBadge.textContent = 'Истекла';
        statusBadge.className = 'status-badge status-expired';
      }
      
      // Update device info
      const deviceCount = userData.devices ? userData.devices.length : 0;
      document.getElementById('deviceCount').textContent = `${deviceCount}/1`;
      
      if (deviceCount > 0 && userData.devices[0]) {
        document.getElementById('deviceInfo').classList.remove('hidden');
        document.getElementById('deviceId').textContent = userData.devices[0].deviceId || 'Неизвестно';
      }
    }

    // Render pricing cards
    function renderPricingCards() {
      const grid = document.getElementById('pricingGrid');
      
      pricingPlans.forEach((plan, index) => {
        const card = document.createElement('div');
        card.className = 'price-card' + (plan.popular ? ' popular' : '');
        card.dataset.index = index;
        
        const monthsText = plan.months === 1 ? '1 месяц' : 
                          plan.months < 5 ? `${plan.months} месяца` : 
                          `${plan.months} месяцев`;
        
        card.innerHTML = `
          <div class="price-header">
            <div class="price-duration">${monthsText}</div>
            <div class="price-amount">${plan.price} ₽</div>
          </div>
          <div class="price-per-month">≈ ${plan.perMonth} ₽/мес</div>
          ${plan.savings ? `<div class="price-savings">Экономия ${plan.savings} ₽</div>` : ''}
        `;
        
        card.addEventListener('click', () => selectPlan(index));
        grid.appendChild(card);
      });
    }

    // Select pricing plan
    function selectPlan(index) {
      // Remove previous selection
      document.querySelectorAll('.price-card').forEach(card => {
        card.classList.remove('selected');
      });
      
      // Select new plan
      const card = document.querySelector(`[data-index="${index}"]`);
      card.classList.add('selected');
      
      selectedPlan = pricingPlans[index];
      document.getElementById('payBtn').disabled = false;
    }

    // Handle payment
    document.getElementById('payBtn').addEventListener('click', async () => {
      if (!selectedPlan) {
        tg.showAlert('Выберите тариф');
        return;
      }

      // Create payment invoice
      const invoice = {
        title: `Saikyo VPN - ${selectedPlan.months} мес`,
        description: `Подписка на ${selectedPlan.months} месяцев (1 устройство)`,
        payload: JSON.stringify({
          userId: userId,
          months: selectedPlan.months,
          deviceId: userData?.devices?.[0]?.deviceId || null,
        }),
        currency: 'RUB',
        prices: [{
          label: `Saikyo VPN - ${selectedPlan.months} мес`,
          amount: selectedPlan.price * 100, // Amount in kopeks
        }],
      };

      // Send invoice via Telegram
      tg.sendData(JSON.stringify({
        action: 'create_invoice',
        invoice: invoice,
      }));
    });

    // Handle free key button
    document.getElementById('getFreeKeyBtn').addEventListener('click', () => {
      tg.sendData(JSON.stringify({
        action: 'get_free_key',
        userId: userId,
      }));
      tg.close();
    });

    // Initialize
    renderPricingCards();
    loadUserData();
  </script>
</body>
</html>
