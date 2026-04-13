---
title: "Wearable"
---

<style>
* { box-sizing: border-box; }

.hero-tag {
  display: inline-block;
  background: #EEEDFE;
  color: #3C3489;
  font-size: 12px;
  font-weight: 500;
  padding: 4px 14px;
  border-radius: 999px;
  margin-bottom: 16px;
  letter-spacing: 0.04em;
}

.hero-desc {
  font-size: 15px;
  color: #666;
  max-width: 520px;
  margin: 0 auto 40px;
  line-height: 1.7;
  text-align: center;
}

.cards {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 20px;
  max-width: 860px;
  margin: 0 auto 48px;
}

.card {
  background: #fff;
  border: 0.5px solid #e0e0e0;
  border-radius: 12px;
  padding: 28px 24px 24px;
  display: flex;
  flex-direction: column;
  gap: 12px;
  text-decoration: none;
  color: inherit;
  transition: border-color 0.15s;
}

.card:hover { border-color: #999; text-decoration: none; }

.card.featured {
  border: 2px solid #AFA9EC;
  position: relative;
}

.badge {
  position: absolute;
  top: -13px;
  left: 20px;
  background: #EEEDFE;
  color: #3C3489;
  font-size: 11px;
  font-weight: 500;
  padding: 3px 12px;
  border-radius: 999px;
  border: 0.5px solid #AFA9EC;
}

.card-icon {
  width: 44px;
  height: 44px;
  border-radius: 8px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 22px;
}

.icon-purple { background: #EEEDFE; }
.icon-teal   { background: #E1F5EE; }
.icon-coral  { background: #FAECE7; }

.card h3 {
  font-size: 15px;
  font-weight: 500;
  margin: 0;
}

.card p {
  font-size: 13px;
  color: #777;
  line-height: 1.6;
  margin: 0;
}

.card-arrow {
  margin-top: auto;
  font-size: 13px;
  color: #aaa;
}
</style>

<div style="text-align:center; padding: 32px 0 16px;">
  <div class="hero-tag">Proyecto universitario · IBERO 2026</div>
  <p class="hero-desc">Documentación de mini proyectos electrónicos: desde la pulsera con LEDs hasta el desarrollo semanal del proyecto wearable.</p>
</div>

<div class="cards">

  <a href="pulsera.html" class="card">
    <div class="card-icon icon-purple">💡</div>
    <h3>Práctica de pulsera</h3>
    <p>Construcción de una pulsera con LEDs programables. Primer acercamiento al hardware wearable.</p>
    <div class="card-arrow">Ver proyecto →</div>
  </a>

  <a href="tira-led.html" class="card">
    <div class="card-icon icon-teal">🔆</div>
    <h3>Tira LED</h3>
    <p>Control de tiras LED mediante microcontrolador. Efectos de luz y animaciones personalizadas.</p>
    <div class="card-arrow">Ver proyecto →</div>
  </a>

  <a href="proyecto-final.html" class="card featured">
    <div class="badge">⭐ Proyecto principal</div>
    <div class="card-icon icon-coral">🏆</div>
    <h3>Proyecto final</h3>
    <p>Desarrollo completo del wearable. Documentación semanal del avance del proyecto integrador.</p>
    <div class="card-arrow">Ver proyecto →</div>
  </a>

</div>
