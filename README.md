# Projects
Small and Big Projects for learning

------------------------------------SOKA Jobs+Fair Website------------------------------------------ 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Soka JOBS+ Fair</title>
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












































































































































































