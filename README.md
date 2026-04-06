<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
</head>

<body>

<header>
  <h1>📚 School Clubs Management System</h1>
  <p>Manage clubs, events, members, and reservations</p>
</header>

<main>

  <section>
    <h2>📌 Overview</h2>
    <p>
      The <strong>School Clubs Management System</strong> is a full-stack application
      designed to manage and streamline all procedures inside school clubs.
    </p>
    <ul>
      <li>👥 Club members management</li>
      <li>📅 Events organization</li>
      <li>🏫 Room reservations</li>
      <li>🧰 Material reservations</li>
      <li>📩 Reservation requests workflow</li>
    </ul>
  </section>

  <section>
    <h2>🧱 Tech Stack</h2>

    <h3>🔙 Backend</h3>
    <p>Java, Spring Boot, REST APIs, Maven</p>

    <h3>🌐 Frontend</h3>
    <p>Angular, TypeScript, HTML, CSS</p>

    <h3>📱 Mobile</h3>
    <p>Android Studio, Java/Kotlin</p>
  </section>

  <section>
    <h2>🚀 Features</h2>
    <ul>
      <li><strong>Member Management:</strong> Add, update, delete members</li>
      <li><strong>Event Management:</strong> Create and manage events</li>
      <li><strong>Room Reservation:</strong> Request and manage rooms</li>
      <li><strong>Material Reservation:</strong> Manage equipment usage</li>
      <li><strong>Request Workflow:</strong> Approval/rejection system</li>
    </ul>
  </section>

  <section>
    <h2>⚙️ Project Structure</h2>
    <pre>
schools-club/
├── backend/
├── frontend/
├── mobile/
    </pre>
  </section>

  <section>
    <h2>🔧 Backend Setup</h2>
    <pre>
cd backend
mvn clean install
mvn spring-boot:run
    </pre>
    <p>Runs on: <strong>http://localhost:8080</strong></p>
  </section>

  <section>
    <h2>🌐 Frontend Setup</h2>
    <pre>
cd frontend
npm install
ng serve
    </pre>
    <p>Runs on: <strong>http://localhost:4200</strong></p>
  </section>

  <section>
    <h2>📱 Android Setup</h2>
    <ol>
      <li>Open Android Studio</li>
      <li>Select <strong>Open Project</strong></li>
      <li>Choose <code>mobile/</code></li>
      <li>Run on emulator or device</li>
    </ol>
  </section>

  <section>
    <h2>🔗 API Configuration</h2>
    <pre>
Web: http://localhost:8080/api
Android Emulator: http://10.0.2.2:8080/api
    </pre>
  </section>

  <section>
    <h2>🧪 Future Improvements</h2>
    <ul>
      <li>Authentication (JWT)</li>
      <li>Notifications system</li>
      <li>Analytics dashboard</li>
      <li>Role-based access</li>
    </ul>
  </section>

</main>

<footer>
  <p>© 2026 Yassine Oubenmoh — Educational Project</p>
</footer>

</body>
</html>
