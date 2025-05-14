<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mood Swing</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to right, #667eea, #764ba2);
      color: white;
      margin: 0;
      padding: 20px;
      text-align: center;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }

    p {
      font-size: 1.1rem;
    }

    .mood-options {
      margin: 20px 0;
      font-size: 2rem;
    }

    .mood-options span {
      cursor: pointer;
      margin: 0 10px;
      transition: transform 0.2s;
    }

    .mood-options span:hover {
      transform: scale(1.3);
    }

    textarea {
      width: 90%;
      max-width: 400px;
      height: 100px;
      border-radius: 10px;
      border: none;
      padding: 10px;
      margin-top: 10px;
      font-size: 1rem;
      resize: none;
    }

    button {
      margin-top: 15px;
      background: white;
      color: #764ba2;
      padding: 12px 24px;
      border-radius: 8px;
      border: none;
      font-size: 1rem;
      cursor: pointer;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }

    button:hover {
      transform: scale(1.03);
      box-shadow: 0 6px 16px rgba(0,0,0,0.3);
    }

    .entry {
      background: rgba(255,255,255,0.1);
      margin: 10px auto;
      padding: 10px;
      border-radius: 10px;
      max-width: 400px;
      text-align: left;
    }
  </style>
</head>
<body>
  <h1>Mood Swing 🌙</h1>
  <p>How are you feeling today?</p>

  <div class="mood-options" id="moodOptions">
    <span>😊</span><span>😐</span><span>😢</span><span>😡</span><span>😴</span>
  </div>

  <textarea id="moodNote" placeholder="Write something about your day..."></textarea><br>
  <button onclick="saveMood()">Save Mood</button>

  <h2 style="margin-top: 30px;">Your Mood History</h2>
  <div id="moodHistory"></div>

  <script>
    let selectedMood = '';

    document.querySelectorAll('#moodOptions span').forEach(el => {
      el.onclick = () => {
        selectedMood = el.textContent;
        document.querySelectorAll('#moodOptions span').forEach(s => s.style.border = '');
        el.style.border = '2px solid white';
        el.style.borderRadius = '50%';
      };
    });

    function saveMood() {
      if (!selectedMood) {
        alert("Please select a mood.");
        return;
      }
      const note = document.getElementById('moodNote').value;
      const entry = {
        mood: selectedMood,
        note: note,
        date: new Date().toLocaleString()
      };

      let history = JSON.parse(localStorage.getItem('moodHistory')) || [];
      history.unshift(entry);
      localStorage.setItem('moodHistory', JSON.stringify(history));

      document.getElementById('moodNote').value = '';
      selectedMood = '';
      document.querySelectorAll('#moodOptions span').forEach(s => s.style.border = '');
      renderHistory();
    }

    function renderHistory() {
      const history = JSON.parse(localStorage.getItem('moodHistory')) || [];
      const container = document.getElementById('moodHistory');
      container.innerHTML = '';

      history.forEach(entry => {
        const div = document.createElement('div');
        div.className = 'entry';
        div.innerHTML = `<strong>${entry.mood}</strong> <em>(${entry.date})</em><br>${entry.note}`;
        container.appendChild(div);
      });
    }

    renderHistory();
  </script>
</body>
</html>
