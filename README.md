## Date: 11.05.2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE

```
map.html
<html>
<head>
<title>MyCity</title>
</head>
<body>
<h1 align="center">
<font color="blue"><b>Chennai</b></font>
</h1>
<h3 align="center">
<font color="Red">Pragatheeshraaj D (212224230199)</font>
</h3>
<center>
<img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Forum Vijaya Mall" title="Forum Vijaya Mall" href="forum.html" coords="1454,895,1676,979" shape="rect">
    <area target="" alt="Curtain Park" title="Curtain Park" href="curtainpark.html" coords="900,525,1085,579" shape="rect">
    <area target="" alt="Agasthiyar park" title="Agasthiyar park" href="park.html" coords="1334,300,1544,383" shape="rect">
</map>
</map>
</center>
</body>
</html>

park.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Agathiyar Nagar Children's Park</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e7f5ff;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #0077b6;
            color: white;
            padding: 20px;
            text-align: center;
        }
        main {
            padding: 20px;
        }
        .section {
            margin-bottom: 20px;
        }
        footer {
            background-color: #023e8a;
            color: white;
            text-align: center;
            padding: 10px;
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }
    </style>
</head>
<body>

<header>
    <h1>Agathiyar Nagar Children's Park</h1>
    <p>A fun and safe place for children in the heart of the community</p>
</header>

<main>
    <div class="section">
        <h2>About the Park</h2>
        <p>Agathiyar Nagar Children's Park is a local community park offering a safe and vibrant environment for kids to play and families to relax. The park features a playground, walking paths, benches, and greenery.</p>
    </div>

    <div class="section">
        <h2>Facilities</h2>
        <ul>
            <li>Slides and Swings</li>
            <li>Walking Track</li>
            <li>Seating Benches</li>
            <li>Gardens and Trees</li>
            <li>Open Space for Activities</li>
        </ul>
    </div>

    <div class="section">
        <h2>Gallery</h2>
        <img src="park-image1.jpg.png" alt="Children playing in the park">
    </div>
</main>

<footer>
    <p>&copy; 2025 Agathiyar Nagar Community. All rights reserved.</p>
</footer>

</body>
</html>

curtain.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>The Curtain Park</title>
    <style>
        body {
            font-family: 'Segoe UI', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
        }
        header {
            background-color: #2a9d8f;
            color: white;
            padding: 30px;
            text-align: center;
        }
        main {
            padding: 20px;
        }
        .section {
            margin-bottom: 30px;
        }
        ul {
            line-height: 1.8;
        }
        img {
            max-width: 100%;
            height: auto;
            margin-top: 10px;
            border-radius: 12px;
        }
        footer {
            background-color: #264653;
            color: white;
            text-align: center;
            padding: 15px;
        }
    </style>
</head>
<body>

<header>
    <h1>The Curtain Park</h1>
    <p>An Urban Retreat of Calm, Play, and Nature</p>
</header>

<main>
    <div class="section">
        <h2>Welcome to The Curtain Park</h2>
        <p>The Curtain Park is a beautiful green space nestled in the city, offering visitors a peaceful place to relax, play, and connect with nature. Whether you're out for a walk, bringing kids to play, or just unwinding, the park has something for everyone.</p>
    </div>

    <div class="section">
        <h2>Highlights & Features</h2>
        <ul>
            <li>Scenic walking and jogging trails</li>
            <li>Children's play area</li>
            <li>Open-air performance space (The Curtain Stage)</li>
            <li>Beautiful landscaped gardens</li>
            <li>Picnic lawns and shaded seating</li>
        </ul>
    </div>

    <div class="section">
        <h2>Gallery</h2>
        <img src="curtain-park1.jpg.png" alt="Park trail and trees">
    </div>
</main>

<footer>
    <p>&copy; 2025 The Curtain Park. All rights reserved.</p>
</footer>

</body>
</html>

forum.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Forum Vijaya Mall</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fdfdfd;
    }
    header {
      background-color: #333;
      color: white;
      padding: 30px;
      text-align: center;
    }
    main {
      padding: 20px;
    }
    .section {
      margin-bottom: 30px;
    }
    ul {
      padding-left: 20px;
    }
    img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
      margin-top: 10px;
    }
    footer {
      background-color: #222;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

<header>
  <h1>Forum Vijaya Mall</h1>
  <p>Your Favorite Shopping, Dining & Entertainment Destination in Chennai</p>
</header>

<main>
  <section class="section">
    <h2>About the Mall</h2>
    <p>Forum Vijaya Mall, located in Vadapalani, Chennai, is one of the city's premium shopping and entertainment destinations. With a wide range of national and international brands, food courts, cinemas, and family fun zones, it offers an immersive experience for all age groups.</p>
  </section>

  <section class="section">
    <h2>Key Attractions</h2>
    <ul>
      <li>150+ Retail Stores</li>
      <li>SPI Palazzo Multiplex (Luxury Cinema Experience)</li>
      <li>Food Court with 20+ Eateries</li>
      <li>Gaming & Kids Play Zone</li>
      <li>Ample Parking Space</li>
    </ul>
  </section>

  <section class="section">
    <h2>Gallery</h2>
    <img src="forum-vijaya-1.jpg.png" alt="Forum Vijaya Mall Exterior" />
  </section>
</main>

<footer>
  <p>&copy; 2025 Forum Vijaya Mall. All rights reserved.</p>
</footer>

</body>
</html>
```

## OUTPUT


![Screenshot 2025-05-11 210517](https://github.com/user-attachments/assets/cb9a5bc8-486c-41aa-8c57-c1b7c026f4fc)
![Screenshot 2025-05-11 210500](https://github.com/user-attachments/assets/77b759ff-1505-48ad-ae57-b0cae7307c69)
![Screenshot 2025-05-11 210434](https://github.com/user-attachments/assets/4eeb6983-e80a-4c9c-a7ef-f3e8d043cf82)
![Screenshot 2025-05-11 210414](https://github.com/user-attachments/assets/30487674-6f5b-4d21-a239-cacdae457cd4)






## RESULT
The program for implementing image maps using HTML is executed successfully.
