<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Plantilla Informativa — DatoCuriosoX</title>
  <meta name="description" content="Página informativa limpia y responsive" />
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #0f172a;
      color: #e6eef6;
      padding: 32px 20px;
    }
    .wrap {max-width: 1100px; margin: auto;}
    header {display: flex; justify-content: space-between; align-items: center; margin-bottom: 28px;}
    .logo {width: 54px; height: 54px; border-radius: 12px; background: #ff5c5c; display: grid; place-items: center; font-weight: 700; color: #071022;}
    nav a {color: #9aa4b2; text-decoration: none; padding: 8px 12px; border-radius: 10px;}
    nav a:hover {color: #fff; background: rgba(255,255,255,0.03);}
    details {background: rgba(255,255,255,0.02); padding: 28px; border-radius: 14px; margin-bottom: 20px;}
    summary {cursor: pointer; font-size: 20px; font-weight: 700;}
    h3 {margin-top: 20px;}
    .muted {color: #9aa4b2;}
    .chart-row {display: flex; gap: 20px; flex-wrap: wrap;}
    .chart-col {width: 48%;}
    svg {border-radius: 6px;}
    .line-chart {width: 100%; height: 80px;}
    .candlestick {width: 100%; height: 120px;}
    .separator {height: 2px; background-color: rgba(255,255,255,0.1); margin: 12px 0;}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="logo">DC</div>
      <nav>
        <a href="#principiantes">Principiantes</a>
        <a href="#actualidad">Actualidad</a>
        <a href="#historica">Histórica</a>
        <a href="#patrones">Patrones</a>
      </nav>
    </header>

    <main>
      <details id="principiantes">
        <summary>Inversión para principiantes</summary>
        <p>Invertir consiste en poner el dinero a trabajar para obtener beneficios futuros.</p>
        <ul class="muted">
          <li><b>Para qué sirve:</b> protegerse de la inflación, crear patrimonio y generar crecimiento.</li>
          <li><b>Beneficios:</b> rendimiento potencial, diversificación e interés compuesto.</li>
        </ul>
      </details>

      <details id="actualidad">
        <summary>Datos financieros de actualidad</summary>
        <ul class="muted">
          <li>Índices estadounidenses muestran fuertes subidas tras recortes de tipos.</li>
          <li>Fondos de renta variable en India registran fuertes entradas de capital.</li>
          <li>Empresas del FTSE 100 británico planean recompras de acciones por £56 mil millones.</li>
          <li>Ibex 35 alcanza máximos históricos >16 700 puntos.</li>
          <li>Inversión pública en España muestra señales de ralentización.</li>
          <li>Fintech europeas amplían financiación para pymes.</li>
        </ul>
      </details>

      <details id="historica">
        <summary>Información histórica</summary>
        <p class="muted">El S&P 500 refleja la evolución de 500 grandes empresas. Periodos recientes incluyen fuertes bajadas y recuperaciones tras el colapso bursátil de 2025.</p>
      </details>

      <details id="patrones">
        <summary>Patrones de mercado</summary>
        <p class="muted">Los mercados muestran ciclos de tendencia alcista, bajista y correcciones.</p>
        <h3>Patrones de subida y bajada</h3>
        <ul class="muted">
          <li><b>Tendencia alcista:</b> máximos y mínimos crecientes.</li>
          <li><b>Tendencia bajista:</b> máximos y mínimos decrecientes.</li>
          <li><b>Correcciones:</b> movimientos temporales contra la tendencia.</li>
        </ul>

        <h3>Representaciones gráficas</h3>
        <div class="chart-row">
          <!-- Alcista -->
          <div class="chart-col">
            <h4 style="color:#1a7f37;">Alcista</h4>
            <div class="separator"></div>
            <svg class="candlestick" viewBox="0 0 200 120">
              <!-- Velas verdes con mechas simulando subida -->
              <line x1="20" y1="40" x2="20" y2="80" stroke="#1a7f37" stroke-width="2"/>
              <rect x="17" y="60" width="6" height="20" fill="#1a7f37"/>
              <line x1="50" y1="30" x2="50" y2="70" stroke="#1a7f37" stroke-width="2"/>
              <rect x="47" y="50" width="6" height="20" fill="#1a7f37"/>
              <line x1="80" y1="20" x2="80" y2="60" stroke="#1a7f37" stroke-width="2"/>
              <rect x="77" y="40" width="6" height="20" fill="#1a7f37"/>
              <line x1="110" y1="10" x2="110" y2="50" stroke="#1a7f37" stroke-width="2"/>
              <rect x="107" y="30" width="6" height="20" fill="#1a7f37"/>
            </svg>
          </div>

          <!-- Bajista -->
          <div class="chart-col">
            <h4 style="color:#c0392b;">Bajista</h4>
            <div class="separator"></div>
            <svg class="candlestick" viewBox="0 0 200 120">
              <!-- Velas rojas con mechas simulando bajada -->
              <line x1="20" y1="30" x2="20" y2="70" stroke="#c0392b" stroke-width="2"/>
              <rect x="17" y="40" width="6" height="30" fill="#c0392b"/>
              <line x1="50" y1="40" x2="50" y2="80" stroke="#c0392b" stroke-width="2"/>
              <rect x="47" y="50" width="6" height="30" fill="#c0392b"/>
              <line x1="80" y1="50" x2="80" y2="90" stroke="#c0392b" stroke-width="2"/>
              <rect x="77" y="60" width="6" height="30" fill="#c0392b"/>
              <line x1="110" y1="60" x2="110" y2="100" stroke="#c0392b" stroke-width="2"/>
              <rect x="107" y="70" width="6" height="30" fill="#c0392b"/>
            </svg>
          </div>
        </div>
      </details>
    </main>

    <footer class="muted" style="margin-top:28px; text-align:center;">© <span id="year"></span> DatoCuriosoX — Plantilla informativa</footer>
  </div>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
    document.querySelectorAll('a[href^="#"]').forEach(a => {
      a.addEventListener('click', e => {
        const id = a.getAttribute('href').slice(1);
        const el = document.getElementById(id);
        if (el) { e.preventDefault(); el.scrollIntoView({behavior:'smooth', block:'start'}); }
      });
    });
  </script>
</body>
</html>
