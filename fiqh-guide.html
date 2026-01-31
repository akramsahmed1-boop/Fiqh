<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <meta name="apple-mobile-web-app-capable" content="yes">
  <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
  <meta name="apple-mobile-web-app-title" content="Fiqh Guide">
  <meta name="theme-color" content="#1B4332">
  <title>Fiqh Guide - Islamic Q&A</title>
  <link rel="apple-touch-icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><rect fill='%231B4332' width='100' height='100' rx='20'/><text x='50' y='62' font-size='40' text-anchor='middle' fill='white'>☪</text></svg>">
  <link href="https://fonts.googleapis.com/css2?family=Amiri:wght@400;700&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; -webkit-tap-highlight-color: transparent; }
    
    :root {
      --primary: #1B4332;
      --primary-light: #2D6A4F;
      --primary-lighter: #40916C;
      --accent: #D4A574;
      --accent-light: #E8D5B7;
      --bg: #FDFBF7;
      --bg-card: #FFFFFF;
      --text: #1A1A1A;
      --text-secondary: #5C5C5C;
      --text-light: #8A8A8A;
      --border: #E5E5E5;
      --success: #52B788;
      --warning: #F4A261;
      --shadow: 0 2px 12px rgba(27, 67, 50, 0.08);
      --shadow-lg: 0 8px 32px rgba(27, 67, 50, 0.12);
    }
    
    body {
      font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
      background: var(--bg);
      color: var(--text);
      min-height: 100vh;
      min-height: -webkit-fill-available;
      overflow-x: hidden;
    }
    
    .app {
      max-width: 100%;
      min-height: 100vh;
      min-height: -webkit-fill-available;
      display: flex;
      flex-direction: column;
    }
    
    /* Header */
    .header {
      background: linear-gradient(135deg, var(--primary) 0%, var(--primary-light) 100%);
      padding: max(env(safe-area-inset-top), 16px) 20px 20px;
      position: sticky;
      top: 0;
      z-index: 100;
    }
    
    .header-content {
      max-width: 600px;
      margin: 0 auto;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    
    .logo {
      display: flex;
      align-items: center;
      gap: 12px;
    }
    
    .logo-icon {
      width: 40px;
      height: 40px;
      background: rgba(255,255,255,0.15);
      border-radius: 10px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 22px;
    }
    
    .logo-text {
      color: white;
      font-family: 'Amiri', serif;
      font-size: 24px;
      font-weight: 700;
      letter-spacing: 0.5px;
    }
    
    .settings-btn {
      background: rgba(255,255,255,0.15);
      border: none;
      width: 40px;
      height: 40px;
      border-radius: 10px;
      color: white;
      font-size: 20px;
      cursor: pointer;
      transition: background 0.2s;
    }
    
    .settings-btn:hover { background: rgba(255,255,255,0.25); }
    
    /* Main Content */
    .main {
      flex: 1;
      padding: 20px;
      max-width: 600px;
      margin: 0 auto;
      width: 100%;
    }
    
    /* Madhhab Selector */
    .madhhab-section {
      margin-bottom: 24px;
    }
    
    .section-label {
      font-size: 12px;
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 0.5px;
      color: var(--text-light);
      margin-bottom: 10px;
    }
    
    .madhhab-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 10px;
    }
    
    .madhhab-btn {
      background: var(--bg-card);
      border: 2px solid var(--border);
      border-radius: 12px;
      padding: 14px 12px;
      font-size: 14px;
      font-weight: 500;
      color: var(--text);
      cursor: pointer;
      transition: all 0.2s;
      text-align: center;
    }
    
    .madhhab-btn:hover {
      border-color: var(--primary-lighter);
      background: #F8FAF9;
    }
    
    .madhhab-btn.active {
      border-color: var(--primary);
      background: linear-gradient(135deg, rgba(27,67,50,0.08) 0%, rgba(45,106,79,0.05) 100%);
      color: var(--primary);
    }
    
    .madhhab-btn .arabic {
      font-family: 'Amiri', serif;
      font-size: 13px;
      color: var(--text-secondary);
      margin-top: 4px;
      display: block;
    }
    
    .madhhab-btn.active .arabic {
      color: var(--primary-light);
    }
    
    /* Question Input */
    .question-section {
      background: var(--bg-card);
      border-radius: 16px;
      padding: 20px;
      box-shadow: var(--shadow);
      margin-bottom: 24px;
    }
    
    .question-input {
      width: 100%;
      min-height: 120px;
      border: none;
      font-size: 16px;
      line-height: 1.6;
      resize: none;
      font-family: inherit;
      color: var(--text);
      background: transparent;
    }
    
    .question-input::placeholder {
      color: var(--text-light);
    }
    
    .question-input:focus {
      outline: none;
    }
    
    .question-footer {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-top: 16px;
      padding-top: 16px;
      border-top: 1px solid var(--border);
    }
    
    .mode-toggle {
      display: flex;
      gap: 8px;
    }
    
    .mode-btn {
      background: var(--bg);
      border: 1px solid var(--border);
      border-radius: 8px;
      padding: 8px 14px;
      font-size: 13px;
      font-weight: 500;
      color: var(--text-secondary);
      cursor: pointer;
      transition: all 0.2s;
    }
    
    .mode-btn.active {
      background: var(--primary);
      border-color: var(--primary);
      color: white;
    }
    
    .ask-btn {
      background: linear-gradient(135deg, var(--primary) 0%, var(--primary-light) 100%);
      border: none;
      border-radius: 12px;
      padding: 12px 28px;
      font-size: 15px;
      font-weight: 600;
      color: white;
      cursor: pointer;
      transition: all 0.2s;
      box-shadow: 0 4px 12px rgba(27, 67, 50, 0.3);
    }
    
    .ask-btn:hover {
      transform: translateY(-1px);
      box-shadow: 0 6px 16px rgba(27, 67, 50, 0.4);
    }
    
    .ask-btn:disabled {
      opacity: 0.6;
      cursor: not-allowed;
      transform: none;
    }
    
    /* Answer Display */
    .answer-container {
      background: var(--bg-card);
      border-radius: 16px;
      box-shadow: var(--shadow-lg);
      overflow: hidden;
      animation: slideUp 0.4s ease;
    }
    
    @keyframes slideUp {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    
    .answer-header {
      background: linear-gradient(135deg, var(--primary) 0%, var(--primary-light) 100%);
      padding: 20px;
      color: white;
    }
    
    .answer-madhhab {
      font-size: 12px;
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 1px;
      opacity: 0.9;
      margin-bottom: 8px;
    }
    
    .answer-question {
      font-family: 'Amiri', serif;
      font-size: 18px;
      line-height: 1.5;
    }
    
    .confidence-badge {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      background: rgba(255,255,255,0.2);
      padding: 6px 12px;
      border-radius: 20px;
      font-size: 12px;
      font-weight: 600;
      margin-top: 12px;
    }
    
    .confidence-dot {
      width: 8px;
      height: 8px;
      border-radius: 50%;
    }
    
    .confidence-high .confidence-dot { background: #52B788; }
    .confidence-medium .confidence-dot { background: #F4A261; }
    .confidence-low .confidence-dot { background: #E76F51; }
    
    .answer-body {
      padding: 24px 20px;
    }
    
    .answer-section {
      margin-bottom: 24px;
    }
    
    .answer-section:last-child {
      margin-bottom: 0;
    }
    
    .answer-section-title {
      font-size: 11px;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 1px;
      color: var(--primary);
      margin-bottom: 12px;
      display: flex;
      align-items: center;
      gap: 8px;
    }
    
    .answer-section-title::before {
      content: '';
      width: 4px;
      height: 16px;
      background: var(--primary);
      border-radius: 2px;
    }
    
    .answer-text {
      font-size: 15px;
      line-height: 1.75;
      color: var(--text);
    }
    
    .answer-text p {
      margin-bottom: 12px;
    }
    
    .answer-text p:last-child {
      margin-bottom: 0;
    }
    
    /* Quick Answer Highlight */
    .quick-answer {
      background: linear-gradient(135deg, rgba(27,67,50,0.06) 0%, rgba(45,106,79,0.03) 100%);
      border-left: 4px solid var(--primary);
      padding: 16px 20px;
      border-radius: 0 12px 12px 0;
      margin-bottom: 24px;
    }
    
    .quick-answer .answer-text {
      font-size: 16px;
      font-weight: 500;
      color: var(--primary);
    }
    
    /* Evidence Section */
    .evidence-item {
      background: var(--bg);
      border-radius: 12px;
      padding: 16px;
      margin-bottom: 12px;
    }
    
    .evidence-item:last-child {
      margin-bottom: 0;
    }
    
    .evidence-type {
      font-size: 10px;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 0.5px;
      color: var(--accent);
      margin-bottom: 6px;
    }
    
    .evidence-ref {
      font-weight: 600;
      color: var(--text);
      margin-bottom: 6px;
    }
    
    .evidence-text {
      font-size: 14px;
      color: var(--text-secondary);
      font-style: italic;
    }
    
    .arabic-text {
      font-family: 'Amiri', serif;
      font-size: 18px;
      direction: rtl;
      text-align: right;
      color: var(--primary);
      margin-bottom: 8px;
    }
    
    /* Practical Steps */
    .steps-list {
      list-style: none;
    }
    
    .step-item {
      display: flex;
      gap: 12px;
      margin-bottom: 12px;
      align-items: flex-start;
    }
    
    .step-number {
      width: 24px;
      height: 24px;
      background: var(--primary);
      color: white;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 12px;
      font-weight: 600;
      flex-shrink: 0;
    }
    
    .step-text {
      font-size: 15px;
      line-height: 1.6;
      color: var(--text);
      padding-top: 2px;
    }
    
    /* Actions */
    .answer-actions {
      display: flex;
      gap: 12px;
      padding: 20px;
      border-top: 1px solid var(--border);
      background: var(--bg);
    }
    
    .action-btn {
      flex: 1;
      background: var(--bg-card);
      border: 1px solid var(--border);
      border-radius: 10px;
      padding: 12px;
      font-size: 13px;
      font-weight: 500;
      color: var(--text-secondary);
      cursor: pointer;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 6px;
      transition: all 0.2s;
    }
    
    .action-btn:hover {
      border-color: var(--primary-lighter);
      color: var(--primary);
    }
    
    .action-btn.bookmarked {
      background: var(--primary);
      border-color: var(--primary);
      color: white;
    }
    
    /* Loading State */
    .loading {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 60px 20px;
      background: var(--bg-card);
      border-radius: 16px;
      box-shadow: var(--shadow);
    }
    
    .loading-spinner {
      width: 48px;
      height: 48px;
      border: 3px solid var(--border);
      border-top-color: var(--primary);
      border-radius: 50%;
      animation: spin 1s linear infinite;
    }
    
    @keyframes spin {
      to { transform: rotate(360deg); }
    }
    
    .loading-text {
      margin-top: 16px;
      font-size: 15px;
      color: var(--text-secondary);
    }
    
    .loading-subtext {
      margin-top: 8px;
      font-size: 13px;
      color: var(--text-light);
      font-family: 'Amiri', serif;
    }
    
    /* Disclaimer */
    .disclaimer {
      background: rgba(212, 165, 116, 0.15);
      border: 1px solid var(--accent-light);
      border-radius: 12px;
      padding: 16px;
      margin-top: 24px;
    }
    
    .disclaimer-title {
      font-size: 12px;
      font-weight: 600;
      color: var(--accent);
      margin-bottom: 6px;
      display: flex;
      align-items: center;
      gap: 6px;
    }
    
    .disclaimer-text {
      font-size: 13px;
      line-height: 1.6;
      color: var(--text-secondary);
    }
    
    /* Settings Modal */
    .modal-overlay {
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: rgba(0,0,0,0.5);
      z-index: 1000;
      display: flex;
      align-items: flex-end;
      justify-content: center;
      animation: fadeIn 0.2s ease;
    }
    
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    
    .modal {
      background: var(--bg-card);
      width: 100%;
      max-width: 600px;
      border-radius: 24px 24px 0 0;
      padding: 24px;
      padding-bottom: max(env(safe-area-inset-bottom), 24px);
      animation: slideUp 0.3s ease;
    }
    
    .modal-handle {
      width: 40px;
      height: 4px;
      background: var(--border);
      border-radius: 2px;
      margin: 0 auto 20px;
    }
    
    .modal-title {
      font-family: 'Amiri', serif;
      font-size: 24px;
      font-weight: 700;
      color: var(--primary);
      margin-bottom: 24px;
    }
    
    .setting-group {
      margin-bottom: 24px;
    }
    
    .setting-label {
      font-size: 12px;
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 0.5px;
      color: var(--text-light);
      margin-bottom: 12px;
    }
    
    .setting-options {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
    }
    
    .setting-option {
      background: var(--bg);
      border: 2px solid var(--border);
      border-radius: 10px;
      padding: 12px 18px;
      font-size: 14px;
      font-weight: 500;
      color: var(--text-secondary);
      cursor: pointer;
      transition: all 0.2s;
    }
    
    .setting-option.active {
      border-color: var(--primary);
      background: rgba(27,67,50,0.08);
      color: var(--primary);
    }
    
    .modal-close {
      width: 100%;
      background: var(--primary);
      border: none;
      border-radius: 12px;
      padding: 16px;
      font-size: 16px;
      font-weight: 600;
      color: white;
      cursor: pointer;
      margin-top: 16px;
    }
    
    /* Sample Questions */
    .samples {
      margin-top: 20px;
    }
    
    .samples-title {
      font-size: 12px;
      font-weight: 600;
      text-transform: uppercase;
      letter-spacing: 0.5px;
      color: var(--text-light);
      margin-bottom: 12px;
    }
    
    .sample-chips {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
    }
    
    .sample-chip {
      background: var(--bg-card);
      border: 1px solid var(--border);
      border-radius: 20px;
      padding: 10px 16px;
      font-size: 13px;
      color: var(--text-secondary);
      cursor: pointer;
      transition: all 0.2s;
    }
    
    .sample-chip:hover {
      border-color: var(--primary-lighter);
      color: var(--primary);
    }
    
    /* Responsive */
    @media (min-width: 640px) {
      .madhhab-grid {
        grid-template-columns: repeat(3, 1fr);
      }
      
      .modal {
        border-radius: 24px;
        margin-bottom: 40px;
      }
    }
    
    /* New Question Button */
    .new-question-btn {
      position: fixed;
      bottom: max(env(safe-area-inset-bottom), 20px);
      right: 20px;
      width: 56px;
      height: 56px;
      background: linear-gradient(135deg, var(--primary) 0%, var(--primary-light) 100%);
      border: none;
      border-radius: 50%;
      color: white;
      font-size: 28px;
      cursor: pointer;
      box-shadow: 0 4px 20px rgba(27, 67, 50, 0.4);
      z-index: 50;
      transition: all 0.2s;
    }
    
    .new-question-btn:hover {
      transform: scale(1.05);
    }
    
    /* Hidden */
    .hidden { display: none !important; }
  </style>
</head>
<body>
  <div class="app" id="app"></div>
  
  <script>
    // App State
    const state = {
      madhhab: localStorage.getItem('madhhab') || 'hanafi',
      region: localStorage.getItem('region') || 'general',
      answerMode: 'detailed',
      currentQuestion: '',
      currentAnswer: null,
      isLoading: false,
      showSettings: false,
      bookmarks: JSON.parse(localStorage.getItem('bookmarks') || '[]')
    };
    
    // Madhahib data
    const madhahib = [
      { id: 'hanafi', name: 'Hanafi', arabic: 'الحنفي' },
      { id: 'maliki', name: 'Maliki', arabic: 'المالكي' },
      { id: 'shafii', name: "Shafi'i", arabic: 'الشافعي' },
      { id: 'hanbali', name: 'Hanbali', arabic: 'الحنبلي' },
      { id: 'general', name: 'General Sunni', arabic: 'عام' },
      { id: 'comparative', name: 'Comparative', arabic: 'مقارن' },
    ];
    
    const regions = [
      { id: 'general', name: 'General' },
      { id: 'uk', name: 'UK' },
      { id: 'us', name: 'USA' },
      { id: 'gcc', name: 'GCC' },
      { id: 'southasia', name: 'South Asia' },
      { id: 'sea', name: 'Southeast Asia' },
    ];
    
    const sampleQuestions = [
      "Does bleeding break wudu?",
      "Can I combine prayers while traveling?",
      "Is gelatin halal?",
      "Do I recite Fatihah behind the imam?",
      "How do I calculate zakat on savings?",
    ];
    
    // Mock answer generator (in real app, this calls your API)
    function generateAnswer(question, madhhab, mode) {
      // This is a simplified mock - in production, call your LLM API
      const answers = {
        'bleeding': {
          quickAnswer: `According to the ${getMadhhabName(madhhab)} madhhab, ${madhhab === 'shafii' || madhhab === 'hanbali' ? 'bleeding from a cut does NOT break your wudu. Your wudu remains valid and you may pray.' : madhhab === 'hanafi' ? 'if blood flows from a wound to a place that requires washing, it DOES break your wudu.' : 'there is detail based on the amount of blood.'}`,
          explanation: madhhab === 'shafii' ? 
            `The Shafi'i school takes a strict approach to what invalidates wudu, limited to what is clearly established in the Quran and authentic Sunnah. The nullifiers of wudu in the Shafi'i madhhab are: anything exiting from the front or back passages, sleep that is not in a firmly seated position, loss of consciousness, touching one's private parts with the palm, and skin-to-skin contact with a marriageable member of the opposite gender.\n\nBlood is not included in this list. The Shafi'i reasoning is that the hadith about blood breaking wudu are either weak or interpreted as recommendations rather than obligations.` :
            madhhab === 'hanafi' ?
            `The Hanafi school holds that blood or pus that flows from a wound to a place that requires washing in wudu or ghusl breaks the wudu. This is based on several narrations and the principle of analogical reasoning (qiyas).\n\nThe key criterion is "flowing" (sayalan) - if blood merely appears at the wound but does not flow, it does not break wudu. If it flows to an area that would be washed in wudu, the wudu is invalidated.` :
            `The scholars have differed on this matter. The relied-upon position considers the amount and flow of blood in determining whether wudu is broken.`,
          evidence: [
            {
              type: 'hadith',
              reference: 'Sahih al-Bukhari, Hadith 206',
              text: 'The Prophet (ﷺ) performed wudu and continued praying after cupping (hijama), only washing the blood.',
              arabic: 'أَنَّ النَّبِيَّ صلى الله عليه وسلم احْتَجَمَ وَصَلَّى وَلَمْ يَتَوَضَّأْ'
            },
            {
              type: 'fiqh',
              reference: madhhab === 'shafii' ? 'Minhaj al-Talibin, Imam al-Nawawi' : madhhab === 'hanafi' ? 'Radd al-Muhtar, Ibn Abidin' : 'Al-Fiqh al-Islami, Dr. Wahba al-Zuhayli',
              text: madhhab === 'shafii' ? 'The nullifiers of wudu are five: anything exiting from one of the two passages...' : 'Flowing blood from other than the two passages breaks wudu if it flows to a place of purification.'
            }
          ],
          madhhabNotes: madhhab === 'shafii' ? 
            'The Shafi\'i position is clear and unified: blood does not break wudu. It is recommended (mustahabb) to wash the blood for cleanliness.' :
            madhhab === 'hanafi' ?
            'The Hanafi position distinguishes between flowing and non-flowing blood. Blood from the mouth mixed with saliva breaks wudu if the blood is equal to or more than the saliva.' :
            'Different schools have varying criteria. The Shafi\'i and Hanbali schools generally hold that blood does not invalidate wudu.',
          practicalSteps: [
            madhhab === 'shafii' || madhhab === 'hanbali' ? 'Your wudu remains valid - you may pray' : 'If blood flowed, renew your wudu before praying',
            'Clean the wound and wash away visible blood',
            'If blood gets on clothing, wash it if possible before prayer',
            'A small amount of blood (dirham-sized) on clothing is excused'
          ],
          confidence: 'high'
        },
        'combining': {
          quickAnswer: `According to the ${getMadhhabName(madhhab)} madhhab, ${madhhab === 'hanafi' ? 'combining prayers (jam\') is generally NOT permitted while traveling, except at Arafah and Muzdalifah during Hajj.' : 'combining prayers IS permitted while traveling the distance of approximately 80-85km or more.'}`,
          explanation: madhhab === 'hanafi' ?
            `The Hanafi position is that combining prayers is not permitted for travelers in the way other schools allow. The Hanafi scholars interpreted the hadith about the Prophet combining prayers during travel as "apparent combining" (jam' suri) - praying one at the end of its time and the next at the beginning of its time.\n\nThe exception is at Arafah (combining Zuhr and Asr) and Muzdalifah (combining Maghrib and Isha) during Hajj, where combining is established by the Prophet's explicit practice.` :
            `The majority of scholars (Maliki, Shafi'i, Hanbali) permit combining Zuhr with Asr, and Maghrib with Isha, while traveling. This is based on authentic hadith showing the Prophet (ﷺ) combined prayers during his journeys.\n\nThe traveler may combine by advancing the later prayer (jam' taqdim) or delaying the earlier prayer (jam' ta'khir). Fajr is never combined with any other prayer.`,
          evidence: [
            {
              type: 'hadith',
              reference: 'Sahih Muslim, Hadith 705',
              text: 'The Prophet (ﷺ) combined Zuhr and Asr, and Maghrib and Isha at Tabuk.',
              arabic: 'جَمَعَ رَسُولُ اللَّهِ صلى الله عليه وسلم بَيْنَ الظُّهْرِ وَالْعَصْرِ وَبَيْنَ الْمَغْرِبِ وَالْعِشَاءِ بِالْمَدِينَةِ'
            },
            {
              type: 'fiqh',
              reference: madhhab === 'hanafi' ? 'Al-Hidayah, al-Marghinani' : 'Al-Mughni, Ibn Qudama',
              text: madhhab === 'hanafi' ? 'Combining is not permitted except at Arafah and Muzdalifah.' : 'The traveler may combine prayers, advancing or delaying, according to what is easier.'
            }
          ],
          madhhabNotes: madhhab === 'hanafi' ?
            'The Hanafi school is unique in restricting combining prayers. A traveler should pray each prayer in its time, though they may shorten the four-rak\'ah prayers to two.' :
            'The traveler has the choice between combining and not combining. Many scholars recommend not combining unless there is a genuine need or difficulty.',
          practicalSteps: madhhab === 'hanafi' ? [
            'Pray each prayer in its own time while traveling',
            'Shorten 4-rak\'ah prayers to 2 rak\'ahs (qasr)',
            'The travel distance is approximately 48 miles (77 km)',
            'Continue shortening for up to 15 days at your destination'
          ] : [
            'You may combine Zuhr+Asr or Maghrib+Isha',
            'Pray them together at either time (jam\' taqdim or ta\'khir)',
            'The travel distance is approximately 48-50 miles (80 km)',
            'Also shorten 4-rak\'ah prayers to 2 rak\'ahs'
          ],
          confidence: 'high'
        },
        'fatihah': {
          quickAnswer: `According to the ${getMadhhabName(madhhab)} madhhab, ${madhhab === 'hanafi' ? 'you should remain SILENT behind the imam and not recite al-Fatihah. The imam\'s recitation suffices for you.' : madhhab === 'maliki' ? 'you remain silent in audible prayers (Fajr, Maghrib, Isha) but recite quietly in silent prayers (Zuhr, Asr).' : 'you MUST recite al-Fatihah even behind the imam, in both audible and silent prayers.'}`,
          explanation: `This is a classic area of legitimate scholarly difference (ikhtilaf) with strong evidence supporting each position.\n\nThe evidence for reciting includes the hadith: "There is no prayer for the one who does not recite the Opening of the Book," which appears to make al-Fatihah obligatory for every person in every rak'ah.\n\nThe evidence for remaining silent includes the hadith: "When the imam recites, listen attentively," along with the Quranic verse: "When the Quran is recited, listen to it and remain silent."\n\nScholars differed in reconciling these texts, leading to the various madhhab positions.`,
          evidence: [
            {
              type: 'quran',
              reference: 'Surah al-A\'raf (7:204)',
              text: 'When the Quran is recited, listen to it and remain silent, that you may receive mercy.',
              arabic: 'وَإِذَا قُرِئَ الْقُرْآنُ فَاسْتَمِعُوا لَهُ وَأَنصِتُوا لَعَلَّكُمْ تُرْحَمُونَ'
            },
            {
              type: 'hadith',
              reference: 'Sahih al-Bukhari 756, Sahih Muslim 394',
              text: 'There is no prayer for the one who does not recite the Opening of the Book (al-Fatihah).',
              arabic: 'لَا صَلَاةَ لِمَنْ لَمْ يَقْرَأْ بِفَاتِحَةِ الْكِتَابِ'
            }
          ],
          madhhabNotes: madhhab === 'hanafi' ?
            'The Hanafi school gives precedence to the command to listen. The imam\'s recitation is considered recitation for the follower based on the hadith: "Whoever has an imam, the imam\'s recitation is recitation for him."' :
            madhhab === 'shafii' ?
            'The Shafi\'i school holds that al-Fatihah is a pillar (rukn) for every praying person. Recite during the imam\'s pauses or quietly during his recitation.' :
            'This is a legitimate area of difference. All positions are valid, and a person\'s prayer is correct according to their madhhab.',
          practicalSteps: madhhab === 'hanafi' ? [
            'Stand silently and listen during the imam\'s recitation',
            'Engage your heart in contemplation during silent prayers',
            'Your prayer is valid without reciting al-Fatihah',
            'Do not argue with those who follow other positions'
          ] : madhhab === 'shafii' || madhhab === 'hanbali' ? [
            'Recite al-Fatihah quietly during the imam\'s pause after his Fatihah',
            'If no pause, recite during his surah recitation',
            'Complete your Fatihah before the imam goes to ruku\'',
            'If you miss it, your prayer is still valid according to some scholars'
          ] : [
            'In audible prayers: remain silent and listen',
            'In silent prayers: recite al-Fatihah quietly',
            'Follow your madhhab\'s guidance consistently'
          ],
          confidence: 'high'
        },
        'gelatin': {
          quickAnswer: `The ruling on gelatin depends on its source. Porcine (pig) gelatin is unanimously haram. Bovine gelatin from animals not slaughtered Islamically is disputed - the ${getMadhhabName(madhhab)} position ${madhhab === 'hanafi' ? 'has some scholars permitting it based on the principle of transformation (istihalah), though caution is advised.' : 'generally requires the animal to be slaughtered properly.'} Fish and plant gelatin are halal.`,
          explanation: `Gelatin is derived from animal collagen, typically from bones and hides. The key questions are: (1) What animal is it from? (2) If from a halal animal, was it slaughtered properly? (3) Does the transformation process (istihalah) purify it?\n\nPorcine gelatin: Unanimously prohibited as pig products are haram regardless of transformation.\n\nBovine gelatin from non-halal slaughter: Scholars differ. Some argue that the extensive chemical transformation changes the substance entirely (istihalah), making it permissible. Others hold that the impure origin remains problematic.\n\nFish gelatin: Permissible as fish does not require slaughter.\n\nPlant-based gelatin (like agar): Permissible.`,
          evidence: [
            {
              type: 'quran',
              reference: 'Surah al-Ma\'idah (5:3)',
              text: 'Prohibited to you are dead animals, blood, the flesh of swine...',
              arabic: 'حُرِّمَتْ عَلَيْكُمُ الْمَيْتَةُ وَالدَّمُ وَلَحْمُ الْخِنزِيرِ'
            },
            {
              type: 'fiqh',
              reference: 'Contemporary fatwa bodies (AMJA, European Council for Fatwa)',
              text: 'There is scholarly difference on whether chemical transformation (istihalah) purifies impure substances. Caution recommends avoiding doubtful matters.'
            }
          ],
          madhhabNotes: 'Classical scholars discussed transformation in contexts like wine turning to vinegar. Modern applications to industrial processes like gelatin production involve contemporary ijtihad. Many fatwa councils recommend seeking halal-certified alternatives where available.',
          practicalSteps: [
            'Check ingredients for gelatin source (porcine, bovine, fish)',
            'Porcine gelatin: always avoid',
            'Look for "halal gelatin" or "fish gelatin" products',
            'Plant-based alternatives (agar, pectin) are safe options',
            'When in doubt, choose an alternative product'
          ],
          confidence: 'medium'
        },
        'zakat': {
          quickAnswer: `Zakat on savings is 2.5% of your total wealth that has been above the nisab threshold for one lunar year. The nisab is approximately the value of 85 grams of gold or 595 grams of silver. Calculate your zakatable assets, subtract debts, and pay 2.5% of the remainder.`,
          explanation: `Zakat on wealth (zakat al-mal) becomes obligatory when:\n\n1. Your wealth exceeds the nisab (minimum threshold)\n2. One lunar year (hawl) has passed while above nisab\n3. The wealth is in your full ownership\n\nThe nisab can be calculated using gold (85g ≈ $5,500-6,500 depending on gold prices) or silver (595g ≈ $400-500). Most scholars today recommend using the silver standard as it benefits more poor people.\n\nZakatable assets include: cash, bank balances, gold/silver, stocks (trading value), business inventory, and money owed to you that is expected to be repaid.`,
          evidence: [
            {
              type: 'quran',
              reference: 'Surah al-Tawbah (9:103)',
              text: 'Take from their wealth a charity by which you purify them and cause them increase.',
              arabic: 'خُذْ مِنْ أَمْوَالِهِمْ صَدَقَةً تُطَهِّرُهُمْ وَتُزَكِّيهِم بِهَا'
            },
            {
              type: 'hadith',
              reference: 'Sahih al-Bukhari 1454',
              text: 'There is no zakat on wealth until a year has passed over it.',
              arabic: 'لَا زَكَاةَ فِي مَالٍ حَتَّى يَحُولَ عَلَيْهِ الْحَوْلُ'
            }
          ],
          madhhabNotes: 'The four madhhabs agree on the basic calculation. Minor differences exist on debt deduction, business assets, and specific categories. The 2.5% rate on cash and gold/silver is agreed upon.',
          practicalSteps: [
            'Choose a consistent date each year (e.g., 1st Ramadan)',
            'List all zakatable assets (cash, gold, investments)',
            'Subtract immediate debts (by madhhab rules)',
            'Check if total exceeds nisab',
            'Pay 2.5% to eligible recipients',
            'Keep records for your reference'
          ],
          confidence: 'high'
        }
      };
      
      // Simple keyword matching for demo
      const q = question.toLowerCase();
      if (q.includes('blood') || q.includes('bleed') || q.includes('cut')) {
        return answers.bleeding;
      } else if (q.includes('combin') || q.includes('travel') || q.includes('journey')) {
        return answers.combining;
      } else if (q.includes('fatihah') || q.includes('fatiha') || q.includes('behind imam') || q.includes('recite')) {
        return answers.fatihah;
      } else if (q.includes('gelatin') || q.includes('halal') || q.includes('food')) {
        return answers.gelatin;
      } else if (q.includes('zakat') || q.includes('savings') || q.includes('wealth')) {
        return answers.zakat;
      }
      
      // Default fallback
      return {
        quickAnswer: `Based on the ${getMadhhabName(madhhab)} madhhab, this question requires careful consideration of the specific circumstances. The general principles of Islamic jurisprudence guide us to seek what is most beneficial while avoiding harm.`,
        explanation: `This is a topic that would benefit from consulting the classical sources of the ${getMadhhabName(madhhab)} school. The scholars have addressed similar questions with careful attention to both the primary sources (Quran and Sunnah) and the established principles of the madhhab.\n\nFor a complete answer with proper citations, please try one of our sample questions, or in the full version of this app, your question will be processed through our retrieval system to find relevant scholarly sources.`,
        evidence: [
          {
            type: 'note',
            reference: 'System Note',
            text: 'This demo has limited pre-loaded answers. The full app will use AI-powered retrieval from authentic Islamic sources.'
          }
        ],
        madhhabNotes: `The ${getMadhhabName(madhhab)} school would approach this question according to its established methodology and relied-upon texts.`,
        practicalSteps: [
          'Consider consulting a local scholar for personalized guidance',
          'Try asking about common topics: wudu, prayer, fasting, zakat',
          'Ensure your question is clear and specific'
        ],
        confidence: 'low'
      };
    }
    
    function getMadhhabName(id) {
      const m = madhahib.find(m => m.id === id);
      return m ? m.name : 'Selected';
    }
    
    function saveMadhhab(id) {
      state.madhhab = id;
      localStorage.setItem('madhhab', id);
      render();
    }
    
    function saveRegion(id) {
      state.region = id;
      localStorage.setItem('region', id);
      render();
    }
    
    function setAnswerMode(mode) {
      state.answerMode = mode;
      render();
    }
    
    function askQuestion() {
      const input = document.getElementById('questionInput');
      const question = input.value.trim();
      if (!question) return;
      
      state.currentQuestion = question;
      state.isLoading = true;
      state.currentAnswer = null;
      render();
      
      // Simulate API call
      setTimeout(() => {
        state.currentAnswer = generateAnswer(question, state.madhhab, state.answerMode);
        state.isLoading = false;
        render();
        
        // Scroll to answer
        setTimeout(() => {
          document.querySelector('.answer-container')?.scrollIntoView({ behavior: 'smooth', block: 'start' });
        }, 100);
      }, 1500);
    }
    
    function newQuestion() {
      state.currentQuestion = '';
      state.currentAnswer = null;
      state.isLoading = false;
      render();
      setTimeout(() => {
        document.getElementById('questionInput')?.focus();
      }, 100);
    }
    
    function toggleSettings() {
      state.showSettings = !state.showSettings;
      render();
    }
    
    function setSampleQuestion(q) {
      document.getElementById('questionInput').value = q;
      state.currentQuestion = q;
      render();
    }
    
    function toggleBookmark() {
      if (!state.currentAnswer) return;
      const id = state.currentQuestion;
      const idx = state.bookmarks.indexOf(id);
      if (idx > -1) {
        state.bookmarks.splice(idx, 1);
      } else {
        state.bookmarks.push(id);
      }
      localStorage.setItem('bookmarks', JSON.stringify(state.bookmarks));
      render();
    }
    
    function shareAnswer() {
      if (navigator.share) {
        navigator.share({
          title: 'Fiqh Guide Answer',
          text: `Q: ${state.currentQuestion}\n\nA: ${state.currentAnswer.quickAnswer}`,
        });
      } else {
        // Fallback: copy to clipboard
        navigator.clipboard.writeText(`Q: ${state.currentQuestion}\n\nA: ${state.currentAnswer.quickAnswer}`);
        alert('Answer copied to clipboard!');
      }
    }
    
    function render() {
      const app = document.getElementById('app');
      const isBookmarked = state.bookmarks.includes(state.currentQuestion);
      
      app.innerHTML = `
        <header class="header">
          <div class="header-content">
            <div class="logo">
              <div class="logo-icon">☪</div>
              <span class="logo-text">Fiqh Guide</span>
            </div>
            <button class="settings-btn" onclick="toggleSettings()">⚙</button>
          </div>
        </header>
        
        <main class="main">
          ${!state.currentAnswer && !state.isLoading ? `
            <div class="madhhab-section">
              <div class="section-label">Your Madhhab</div>
              <div class="madhhab-grid">
                ${madhahib.map(m => `
                  <button class="madhhab-btn ${state.madhhab === m.id ? 'active' : ''}" onclick="saveMadhhab('${m.id}')">
                    ${m.name}
                    <span class="arabic">${m.arabic}</span>
                  </button>
                `).join('')}
              </div>
            </div>
            
            <div class="question-section">
              <textarea 
                id="questionInput" 
                class="question-input" 
                placeholder="Ask your question about Islamic practice...

Example: Does bleeding break my wudu?"
                onkeydown="if(event.key === 'Enter' && !event.shiftKey) { event.preventDefault(); askQuestion(); }"
              >${state.currentQuestion}</textarea>
              
              <div class="question-footer">
                <div class="mode-toggle">
                  <button class="mode-btn ${state.answerMode === 'short' ? 'active' : ''}" onclick="setAnswerMode('short')">Short</button>
                  <button class="mode-btn ${state.answerMode === 'detailed' ? 'active' : ''}" onclick="setAnswerMode('detailed')">Detailed</button>
                </div>
                <button class="ask-btn" onclick="askQuestion()">Ask</button>
              </div>
            </div>
            
            <div class="samples">
              <div class="samples-title">Try asking about</div>
              <div class="sample-chips">
                ${sampleQuestions.map(q => `
                  <button class="sample-chip" onclick="setSampleQuestion('${q}')">${q}</button>
                `).join('')}
              </div>
            </div>
          ` : ''}
          
          ${state.isLoading ? `
            <div class="loading">
              <div class="loading-spinner"></div>
              <div class="loading-text">Finding authentic sources...</div>
              <div class="loading-subtext">بِسْمِ اللَّهِ الرَّحْمَٰنِ الرَّحِيمِ</div>
            </div>
          ` : ''}
          
          ${state.currentAnswer ? `
            <div class="answer-container">
              <div class="answer-header">
                <div class="answer-madhhab">${getMadhhabName(state.madhhab)} Position</div>
                <div class="answer-question">${state.currentQuestion}</div>
                <div class="confidence-badge confidence-${state.currentAnswer.confidence}">
                  <span class="confidence-dot"></span>
                  ${state.currentAnswer.confidence.charAt(0).toUpperCase() + state.currentAnswer.confidence.slice(1)} Confidence
                </div>
              </div>
              
              <div class="answer-body">
                <div class="quick-answer">
                  <div class="answer-text">${state.currentAnswer.quickAnswer}</div>
                </div>
                
                ${state.answerMode === 'detailed' ? `
                  <div class="answer-section">
                    <div class="answer-section-title">Detailed Explanation</div>
                    <div class="answer-text">
                      ${state.currentAnswer.explanation.split('\n\n').map(p => `<p>${p}</p>`).join('')}
                    </div>
                  </div>
                  
                  <div class="answer-section">
                    <div class="answer-section-title">Evidence & References</div>
                    ${state.currentAnswer.evidence.map(e => `
                      <div class="evidence-item">
                        <div class="evidence-type">${e.type}</div>
                        <div class="evidence-ref">${e.reference}</div>
                        ${e.arabic ? `<div class="arabic-text">${e.arabic}</div>` : ''}
                        <div class="evidence-text">${e.text}</div>
                      </div>
                    `).join('')}
                  </div>
                  
                  <div class="answer-section">
                    <div class="answer-section-title">Madhhab-Specific Notes</div>
                    <div class="answer-text">
                      <p>${state.currentAnswer.madhhabNotes}</p>
                    </div>
                  </div>
                ` : ''}
                
                <div class="answer-section">
                  <div class="answer-section-title">Practical Steps</div>
                  <ol class="steps-list">
                    ${state.currentAnswer.practicalSteps.map((step, i) => `
                      <li class="step-item">
                        <span class="step-number">${i + 1}</span>
                        <span class="step-text">${step}</span>
                      </li>
                    `).join('')}
                  </ol>
                </div>
              </div>
              
              <div class="answer-actions">
                <button class="action-btn ${isBookmarked ? 'bookmarked' : ''}" onclick="toggleBookmark()">
                  ${isBookmarked ? '★' : '☆'} ${isBookmarked ? 'Saved' : 'Save'}
                </button>
                <button class="action-btn" onclick="shareAnswer()">
                  ↗ Share
                </button>
              </div>
            </div>
            
            <div class="disclaimer">
              <div class="disclaimer-title">⚠ Important Note</div>
              <div class="disclaimer-text">
                This answer is for educational purposes. For personal matters involving marriage, divorce, inheritance, or unique circumstances, please consult a qualified local scholar.
              </div>
            </div>
            
            <button class="new-question-btn" onclick="newQuestion()">+</button>
          ` : ''}
        </main>
        
        ${state.showSettings ? `
          <div class="modal-overlay" onclick="if(event.target === this) toggleSettings()">
            <div class="modal">
              <div class="modal-handle"></div>
              <h2 class="modal-title">Settings</h2>
              
              <div class="setting-group">
                <div class="setting-label">Default Madhhab</div>
                <div class="setting-options">
                  ${madhahib.map(m => `
                    <button class="setting-option ${state.madhhab === m.id ? 'active' : ''}" onclick="saveMadhhab('${m.id}')">${m.name}</button>
                  `).join('')}
                </div>
              </div>
              
              <div class="setting-group">
                <div class="setting-label">Region (for relevance)</div>
                <div class="setting-options">
                  ${regions.map(r => `
                    <button class="setting-option ${state.region === r.id ? 'active' : ''}" onclick="saveRegion('${r.id}')">${r.name}</button>
                  `).join('')}
                </div>
              </div>
              
              <button class="modal-close" onclick="toggleSettings()">Done</button>
            </div>
          </div>
        ` : ''}
      `;
    }
    
    // Initial render
    render();
  </script>
</body>
</html>
