<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Historical Places in India</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: #f9f9f9;
    }

    header {
      background-color: #3f51b5;
      color: white;
      padding: 20px 0;
      text-align: center;
    }

    .container {
      padding: 20px;
    }

    .place {
      background-color: white;
      border-radius: 10px;
      margin-bottom: 20px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: transform 0.3s;
    }

    .place:hover {
      transform: scale(1.02);
    }

    .place img {
      width: 100%;
      height: auto;
    }

    .place-content {
      padding: 15px;
    }

    .place h2 {
      margin: 0 0 10px;
      color: #333;
    }

    .place p {
      color: #555;
    }

    footer {
      background-color: #3f51b5;
      color: white;
      text-align: center;
      padding: 10px;
    }

    button {
      margin-top: 10px;
      background-color: #3f51b5;
      color: white;
      padding: 10px 15px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background-color: #303f9f;
    }
  </style>
</head>
<body>

  <header>
    <h1>Historical Places in India</h1>
  </header>

  <div class="container">

    <div class="place">
      <img src="https://tirupatibalajitravels.co.in/vip-break-darshan-in-tirupati-is-it-worth-the-cost/" alt="Tirupati">
      <div class="place-content">
        <h2>Tirupati</h2>
        <p>The Venkateswara Temple of Tirumala or Sri Venkateswara Swami Temple is a Hindu temple situated in the hills of Tirumala, Tirupati Urban Mandal in the Tirupati district of Andhra Pradesh, India.</p>
        <button onclick="alert('Tirupati - One of the most beautiful monuments in the world!')">Know More</button>
      </div>
    </div>

    <div class="place">
      <img src="https://www.istockphoto.com/photo/majestic-mysore-palace-over-a-background-of-a-beautiful-sky-colored-by-the-sunset-gm1445347882-483780978" alt="Mysore Palace">
      <div class="place-content">
        <h2>mysore</h2>
        <p>Mysore Palace, also known as Amba Vilas Palace, is a historical palace and a royal residence. It is located in Mysore, Karnataka, India. It used to be the official residence of the Wadiyar dynasty and the seat of the Kingdom of Mysore. The palace is in the centre of Mysore, and faces the Chamundi Hills eastward.</p>
        <button onclick="alert('Mysore palce - A true beaty of Architecture!')">Know More</button>
      </div>
    </div>

    <div class="place">
      <img src="https://www.pexels.com/photo/the-qutub-minar-tower-in-new-delhi-india-14105979/" alt="Qutubminar">
      <div class="place-content">
        <h2>Qutubminar</h2>
        <p>The Qutb Minar, also spelled Qutub Minar and Qutab Minar, is a minaret and victory tower comprising the Qutb complex, which lies at the site of Delhi's oldest .</p>
        <button onclick="alert('Qutubminar - A glimpse into the glorious past of north India!')">Know More</button>
      </div>
    </div>

    <div class="place">
      <img src="http://tripoto.com/aurangabad/places-to-visit/ellora-caves" alt="Ellora Caves">
      <div class="place-content">
        <h2>caves</h2>
        <p> you should definitely visit the Ellora Caves, one of the most remarkable examples of rock-cut architecture and religious diversity in the world.
</p>
        <button onclick="alert('Ellora Caves - An architectural marvel!')">Know More</button>
      </div>
    </div>

  </div>

  <footer>
    <p>&copy; 2025 Historical India Web</p>
  </footer>

</body>
</html>
