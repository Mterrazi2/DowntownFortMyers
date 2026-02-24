<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Downtown Fort Myers | Combat & AI Systems</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', sans-serif;
    background-color: #0a0a0f;
    color: #e6e6e6;
    line-height: 1.7;
}

.container {
    max-width: 1000px;
    margin: auto;
    padding: 60px 20px;
}

a {
    color: #F5C542;
    text-decoration: none;
}

a:hover {
    color: white;
}

.back {
    margin-bottom: 40px;
    display: inline-block;
}

.hero h1 {
    font-size: 40px;
    margin-bottom: 10px;
}

.subtitle {
    color: #9aa0a6;
    margin-bottom: 20px;
}

.video-container {
    margin-top: 30px;
    position: relative;
    padding-bottom: 56.25%;
    height: 0;
}

.video-container iframe {
    position: absolute;
    width: 100%;
    height: 100%;
}

section {
    margin-top: 60px;
}

h2 {
    border-left: 4px solid #F5C542;
    padding-left: 10px;
    margin-bottom: 20px;
}

ul {
    margin-left: 20px;
    margin-top: 10px;
}

.tech {
    margin-top: 20px;
}

.tech span {
    display: inline-block;
    background-color: #1f2230;
    padding: 6px 10px;
    margin: 5px 5px 0 0;
    border-radius: 4px;
    font-size: 13px;
}

.footer {
    margin-top: 100px;
    text-align: center;
    color: #777;
    font-size: 14px;
}
</style>
</head>

<body>

<div class="container">

<a class="back" href="https://mterrazi2.github.io/">← Back to Portfolio</a>

<div class="hero">
<h1>Downtown Fort Myers</h1>
<div class="subtitle">
First-Person Survival Shooter | Unreal Engine | C++
</div>

<p>
A systems-focused survival FPS prototype inspired by wave-based combat design.
This project emphasized combat responsiveness, enemy AI architecture, and scalable
encounter balancing.
</p>

<div class="video-container">
<iframe width="560" height="315" src="https://www.youtube.com/embed/h6VBicVe1e4?si=z8tMkNKgm4hZkL2A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

<div class="tech">
<span>Unreal Engine</span>
<span>C++</span>
<span>Combat Systems</span>
<span>Behavior Trees</span>
<span>AI Architecture</span>
<span>Game Balancing</span>
</div>
</div>

<section>
<h2>Project Overview</h2>
<p>
Downtown Fort Myers is a first-person survival shooter centered around
wave-based enemy encounters. The core objective was to push my gameplay
engineering skills by building modular combat systems, scalable AI behaviors,
and responsive weapon mechanics.
</p>

<p>
This project marked a major technical growth milestone, demonstrating rapid
improvement in gameplay system architecture following my previous stealth project.
</p>
</section>

<section>
<h2>Core Gameplay Systems Implemented</h2>
<ul>
<li>Modular weapon firing system (hitscan logic + damage calculation)</li>
<li>Health & damage processing framework</li>
<li>Enemy AI behavior trees with chase and attack states</li>
<li>Wave spawning and encounter escalation system</li>
<li>Player feedback systems (hit reactions, damage indicators)</li>
<li>Performance-conscious AI update logic</li>
</ul>
</section>

<section>
<h2>Combat System Architecture</h2>
<p>
Weapons were built using modular C++ components allowing reuse across
future weapon types. Damage calculations were abstracted into a
centralized processing system to maintain scalability and reduce redundancy.
</p>

<p>
Enemy behaviors were structured using Unreal’s Behavior Tree system,
ensuring clear separation between decision logic and execution logic.
This improved debugging clarity and system maintainability.
</p>
</section>

<section>
<h2>Technical Challenges</h2>
<p>
One of the primary challenges involved balancing AI aggression with
player survivability. Iterative tuning was required to ensure encounters
felt intense but fair.
</p>

<p>
Another key challenge was managing multiple AI actors simultaneously
while maintaining stable performance. Optimized update cycles and
controlled perception checks helped reduce unnecessary processing overhead.
</p>
</section>

<section>
<h2>Future Improvements</h2>
<ul>
<li>Advanced enemy archetypes with unique attack patterns</li>
<li>Dynamic difficulty scaling based on player performance</li>
<li>Weapon upgrade system with stat modifications</li>
<li>Network-ready architecture for multiplayer scalability</li>
</ul>
</section>

<div class="footer">
© 2026 Michael Terrazi
</div>

</div>

</body>
</html>
