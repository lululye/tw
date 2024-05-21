<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ideal Classrooms</title>
  <link rel="stylesheet" href="styles.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      background-color: #f0f0f0;
    }
    header {
      background-color: #007bff;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    h1 {
      margin: 0;
    }
    main {
      padding: 20px;
    }
    section {
      margin-bottom: 40px;
    }
    h2 {
      color: #007bff;
    }
    h3 {
      color: #0056b3;
    }
    p {
      line-height: 1.6;
    }
    .image-container {
      margin-bottom: 20px;
    }
    img {
      max-width: 100%;
      height: auto;
    }
    footer {
      background-color: #007bff;
      color: #fff;
      padding: 10px;
      text-align: center;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <h1>Ideal Classrooms</h1>
  </header>
  <main>
    <section id="content">
      <h2>Ideal Classrooms</h2>
      <p>There are various types of classrooms, but their design significantly impacts learning outcomes.</p>
      
      <h3>Dream Classroom</h3>
      <p>An open environment where students can move freely and interact, fostering collaboration and teamwork.</p>
      <p>Equipped with the latest technology such as tablets, computers, or VR glasses.</p>
      <p>A flexible space that can be arranged according to different teaching needs.</p>
      <p>This classroom might be filled with elements that inspire creativity, such as subject-related posters or professional vocabulary.</p>
      
      <h3>Impact on Learning</h3>
      <p>A positive, supportive classroom atmosphere can stimulate students' interest and motivation, thereby improving their academic performance.</p>
      <p>The design of the classroom can encourage active participation, such as through group discussions, gamified learning, etc., deepening their understanding and mastery of knowledge.</p>
      <p>Modern classroom facilities and resources can provide students with richer learning experiences, such as interactive learning using technology devices, expanded reading resources, etc., helping to improve their academic performance.</p>
      
      <h3>Future Classrooms May Include More Elements</h3>
      <ul>
        <li>With the advancement of AI technology and big data analysis, future classrooms may be more personalized, providing customized teaching content and activities based on students' learning styles and levels.</li>
        <li>Future classrooms may break down disciplinary boundaries, adopting interdisciplinary integrated teaching methods to help students better understand the connections and applications of knowledge.</li>
        <li>With the development of technology and globalization, future classrooms may focus more on a global perspective and cross-cultural communication, expanding students' horizons through international cooperation projects and online platforms.</li>
      </ul>
    </section>

    <section id="classroom-images">
      <h2>Classroom Images</h2>
      <div class="image-container">
        <img src="https://embed.widencdn.net/img/ki/t1wnesljtd/1500px@1x/Chattahoochee_Technical_College_Strive_Connection_Toggle_Computer_Lab.jpg?q=90&x.template=y" alt="Open Space Classroom">
        <p>This classroom has face-to-face seating arrangements, allowing all students to better discuss issues and learn from teachers outside of school, regardless of geographic location, at any time.</p>
      </div>
      <div class="image-container">
        <img src="https://embed.widencdn.net/img/ki/a9ieypc5ib/1500px@1x/BellinSSC_Zoetry_Bench_Lobby.jpg?q=90&x.template=y" alt="Natural Classroom">
        <p>This type of classroom can be placed in the library, allowing students to accompany nature, study while enjoying the scenery, which helps improve students' mood and learning efficiency.</p>
      </div>
      <div class="image-container">
        <img src="https://embed.widencdn.net/img/ki/eqx3f86og4/1500px@1x/Tributaire_Post_Leg_Tributarie_Monitor_Stand_LL_Task_Media_Center_2.jpg?q=90&x.template=y" alt="Interactive Classroom">
        <p>It allows students to better prepare for interactive classrooms and facilitates group discussions.</p>
      </div>
    </section>
  </main>
  <footer>
    <p>&copy; Changhui Hu</p>
  </footer>
</body>
</html>


<script>
document.getElementById("classroom-form").addEventListener("submit", function(event) {
    event.preventDefault(); // Prevent default form submission behavior
    var classroomText = document.getElementById("classroom").value; // Get the user input for classroom description
    alert("Your ideal classroom is: " + classroomText); // Display the user input in an alert dialog
    document.getElementById("classroom-form").reset(); // Reset the form
    document.getElementById("thank-you").style.display = "block"; // Display "Thank you" message
});
</script>
</body>
</html>
