---
title: Lab Members
---

<style>
.lab-section {
  max-width: 1200px;
  margin: 3rem auto;
  padding: 0 1rem;
}

.lab-section h2 {
  text-align: center;
  margin-bottom: 2rem;
  border-bottom: 2px solid #eee;
  padding-bottom: 0.5rem;
}

.lab-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 2rem;
}

.lab-member {
  text-align: center;
}

.lab-member img {
  width: 200px;
  height: 250px;
  object-fit: cover;
  object-position: center;
  border-radius: 8px;
  display: block;
  margin: 0 auto 0.75rem;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.lab-member img:hover {
  transform: translateY(-3px);
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
}

.lab-member p {
  margin: 0;
  line-height: 1.4;
}

.lab-member strong {
  display: block;
  margin-bottom: 0.25rem;
}

@media (max-width: 600px) {
  .lab-member img {
    width: 180px;
    height: 225px;
  }
}
</style>

<!-- Faculty / Leadership -->
<div class="lab-section">
  <h2>Faculty & Leadership</h2>

  <div class="lab-grid">

    <div class="lab-member">
      {% include figure.html image="/images/MikeOchs.jpg" width="200" %}
      <p>
        <strong>Michael Ochs, PhD</strong>
        Associate Professor / Lab Manager
      </p>
    </div>

  </div>
</div>

<!-- Postdoctoral Fellows -->
<div class="lab-section">
  <h2>Postdoctoral Fellows</h2>

  <div class="lab-grid">

    <div class="lab-member">
      {% include figure.html image="/images/ArunDas.jpg" width="200" %}
      <p><strong>Arun Das, PhD</strong>Postdoctoral Fellow</p>
    </div>

    <div class="lab-member">
      {% include figure.html image="/images/EmilyLasseOpsahl.jpeg" width="200" %}
      <p><strong>Emily Lasse-Opsahl, PhD</strong>Postdoctoral Fellow</p>
    </div>

    <div class="lab-member">
      {% include figure.html image="/images/KatleenNoller.jpg" width="200" %}
      <p><strong>Kathleen Noller, PhD</strong>Postdoctoral Fellow</p>
    </div>

    <div class="lab-member">
      {% include figure.html image="/images/DonghyunYim.jpeg" width="200" %}
      <p><strong>Donghyun Yim, PhD</strong>Postdoctoral Fellow</p>
    </div>

    <div class="lab-member">
      {% include figure.html image="/images/Jiaqi_avatar.jpg.jpeg" width="200" %}
      <p><strong>Jiaqi Zhang, PhD</strong>Postdoctoral Fellow</p>
    </div>

  </div>
</div>

<!-- Research Staff -->
<div class="lab-section">
  <h2>Research Staff</h2>

  <div class="lab-grid">

    <div class="lab-member">
      {% include figure.html image="/images/yangsong.jpg.jpeg" width="200" %}
      <p>
        <strong>Yang Song, PhD</strong>
        Sr. Bioinformatics Software Engineer
      </p>
    </div>

    <div class="lab-member">
      {% include figure.html image="/images/dima-lvovs.jpg" width="200" %}
      <p>
        <strong>Dima Lvovs, PhD</strong>
        Research Associate
      </p>
    </div>

  </div>
</div>

<!-- Graduate Students -->
<div class="lab-section">
  <h2>Graduate Students</h2>

  <div class="lab-grid">

    <div class="lab-member">
      {% include figure.html image="/images/Junhan_Kim.png" width="200" %}
      <p>
        <strong>Junhan Kim</strong>
        Graduate Student
      </p>
    </div>

  </div>
</div>

