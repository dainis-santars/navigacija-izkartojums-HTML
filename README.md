# Navigācija un izkārtojums HTML

1. Sagatavo programmēšanas vidi. Instalē paplašinājumu **Preview** un iestati vārdu aplaušanu rindiņā (`Alt+Z`)
2. Pievieno navigācijas bloku pirms teksta. Kods:
```
<header class="navbar">
  <section class="navbar-section">
    
  </section>
  </section>
</header>
```
3. Pārveido teksta rindas Dzīve, Bērni un Izteicieni par 2. līmeņa virsrakstiem. Kods: `<h2 id="dzive">Dzīve</h2>`
4. Veido saites uz šiem virsrakstiem, veidojot lapas navigāciju tam sagatavotajā vietā. Paraugs:
```
<a href="#dzive">Dzīve</a>
```
5. Sadali lapu tā, lai teksts ir pa labi un ⅔ platumā. Domā un seko šim paraugam:
```
<!-- flexbox grid example -->
<div class="container">
  <div class="columns">
    <div class="column col-4">Te var ielikt attēlu</div>
    <div class="column col-8">Lapas teksts</div>
  </div>
</div>
```
