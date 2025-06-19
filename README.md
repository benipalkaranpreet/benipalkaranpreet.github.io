<style>
.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); /* 2 columns */
  gap: 20px; /* <-- Gutter: adjust this */
  max-width: 1000px; /* <-- Container width: adjust as needed */
  margin: 0 auto;
  padding: 20px;
}

.project-card {
  background: #ffffff;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.08); /* Subtle shadow */
  border-radius: 8px;
  overflow: hidden;
  text-decoration: none;
  color: inherit;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  display: flex;
  flex-direction: column;
}

.project-card:hover {
  transform: scale(1.02);
  box-shadow: 0 4px 16px rgba(0, 0, 0, 0.15);
}

.project-image {
  width: 100%;
  height: auto;
  object-fit: cover;
}

.project-content {
  padding: 15px;
}

.project-title {
  font-size: 1.25em;
  font-weight: bold;
  margin: 0 0 10px;
}

.project-description {
  font-size: 0.95em;
  line-height: 1.4;
}
</style>

<div class="project-grid">
  <a href="project1.html" class="project-card">
    <img src="project1.png" alt="Project 1 screenshot" class="project-image">
    <div class="project-content">
      <h3 class="project-title">Project One</h3>
      <p class="project-description">A brief description of Project One goes here. It can span up to a few lines.</p>
    </div>
  </a>

  <a href="project2.html" class="project-card">
    <img src="project2.png" alt="Project 2 screenshot" class="project-image">
    <div class="project-content">
      <h3 class="project-title">Project Two</h3>
      <p class="project-description">A quick overview of what this project is about. Summarize the key idea or result.</p>
    </div>
  </a>

  <!-- Add more cards below as needed -->
</div>
