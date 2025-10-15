# Projects
Small and Big Projects for learning

------------------------------------SOKA Jobs+Fair Website------------------------------------------ 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Soka JOBS+ Fair</title>
<style>
/*General Rest */
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }
  
  body {
    background: linear-gradient(135deg, #004aad, #00bfff);
    color: #fff;
    line-height: 1.6;
    overflow-x: hidden;
  }
  
  header {
    text-align: center;
    padding: 2rem;
    background: #003580; 
    box-shadow: 0 4px 10px rgba(0,0,0,0.3)
  }
  
  header h1{
      font-size: 2.8rem;
      color: #ffdd00;
      text-transform: uppercase;
      letter-spacing: 3px;
      animation: glow 2s infinite alternate;
  }
  
  @keyframes glow {
      from { text-shadow: 0 0 5px #fff, 0 0 10px #ffdd00; }
      to { text-shadow: 0 0 20px #fff, 0 0 30px #ffdd00; }
  }
  
  header p {
      margin-top: 0.5rem;
      font-size: 1.2rem;
  }
  
  .event-info {
      display: flex; 
      justify-content: space-around;
      padding: 2rem 1rem;
      backgroud: #0057b7;
      flex-wrap: warp;
  }
  .event-info {
      margin: 1rem;
      font-size: 1.2rem;
  }
  
  .employers {
      padding: 2rem;
      background: #ffff:
      color: #333;
      text-align: center;
  }
  
  .employers h2 {
      font-size: 2rem;
      margin-bottom: 1.5rem;
      color: #004aad;
  }
  
  employers ul {
      list-style: none;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
  }
  
  employers li {
      background: #f5f5f5; 
      padding: 1rem;
      border-radius: 10px;
      transition: transform 0.3, background 0.3;
  }
  
  .employers li:hover {
      transform: scale(1.05);
      background: #ffdd00;
      color: #000;
  }
  
  .cta {
      padding: 2rem;
      background: #ffdd00;
      color: #000;
      text-align: center;
      font-size: 1.3rem;
  }
  
  .cta strong {
      display: block;
      font-size: 1.6rem;
      margin-bottom: 1rem;
  }
  
  .prep {
      background: #fb7b25;
      padding: 2rem;
      text-align: center;
  }
  
  .prep h3 {
      color: #ffdd00;
      margin-bottom: 1rem;
  }
  
  .prep p {
      margin: 0.5 rem 0;
  }
  
  footer {
      padding: 1.5rem;
      text-align: center;
      background: #2a4876;
      font-size: 0.9rem;
  }
  
  footer a {
      color: #ffdd00;
      text-decoration: none;
      transition: color 0.3s;
  }
  
  footer a:hover {
      color: #fff;
  }
  
  /*Countdown Styling*/
  #countdown {
    font-size: 1.5rem;
    font-weight: bold;
    margin-top: 1rem;
    color: #ffffff;
  }
</style>
</head>
<body>
  <header>
    <h1> 🚀 Soka JOBS+ Fair 🚀 </h1>
    <p>✨ Paid On-Campus Work Experience + Career Growth ✨</p>
  </header>
  
  <section>
    <div>📅 <strong>Friday, Oct 3, 2025</strong></div>
    <div>📍 <strong>Bistro Patio</strong></div>
    <div>⏰ <strong>11:30 am – 1:30 pm</strong></div>
  </section>

  <section class="employers">
    <h2>👀 Featuring On-Campus Employers:</h2>
    <ul>
      <li>Admissions</li>
      <li>Alumni Relations</li>
      <li>Athletics</li>
      <li>Bon Appetit</li>
      <li>Career Development Office</li>
      <li>DEI</li>
      <li>English Language Program Help Center</li>
      <li>IT</li>
      <li>Library</li>
      <li>Performing Arts Center</li>
      <li>Residential Life</li>
      <li>Marketing & Communications</li>
      <li>Student Activities</li>
      <li>Leadership & Service Engagement</li>
      <li>SUA Faculty / CAP</li>
    </ul>
  </section>

<section class="cta">
  <strong>💡 Your Great First Impression Can Get You HIRED!</strong>
  👉 Meet employers, build connections, explore jobs!
  <div id="countdown">Countdown loading...</div> 
</section>

<section>
  <h3>🔥 PREP Session: Thursday, Oct 2 @ 5 pm 🔥</h3>
  <p>✅ Be ready. Be confident. Be YOU.</p>
    <p>📩 Register here: <a href="https://sokannect.soka.edu/web/rsvp_boot?id=378575" target="_blank">[Prep Link]</a></p>
    <p>📩 Jobs+ Fair info: <a href="https://sokannect.soka.edu/cdo/rsvp_boot?id=378567" target="_blank">[Fair Link]</a></p>
</section>

<footer>
  Brought to you by SUA Career Development Office <br />
  Questions? <a href="mailto:ychoiplass@soka.edu">ychoiplass@soka.edu</a>
</footer>

<script>
  //Simple countdown to event date
  const countdown = document.getElementById("countdown");
  const eventDate = new Date("Oct 3, 2025 11:30:00").getTime();

  setInterval(() => {
    const now = new Date().getTime();
    const distance = eventDate - now;

    if (distance > 0) {
      const days = Math.floor(distance/(1000*60*60*24));
      const hours = Math.floor((distance % (1000*60*60*24)/(1000*60*60));
      const minutes = Math.floor((distance % (1000*60*60*24)/(1000*60));
      countdown.innerHTML = `⏳ ${days}d ${hours}h ${minutes}m until the Fair!`;
    } else {
      countdown.innerHTML = "🎉 The JOBS+ Fair is happening NOW!";
    } 
  
  }, 1000;)
</script>
</body>
</html>

------------------------------🧩 Project: Maze Solver (with Python)--------------------------------------








































































































































































