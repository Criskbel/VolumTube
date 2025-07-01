<h1>VOLUMTUBE</h1>

<h2>Mathematical and Methodological Approach</h2>
<p>VOLUMTUBE calculates volumes of prefabricated elements (poles, pipes, cones) modeled as solids of revolution using definite integrals:</p>
<p><em>V = π ∫[R<sub>ext</sub>(x)<sup>2</sup> - R<sub>int</sub>(x)<sup>2</sup>] dx</em></p>
<p>The <strong>Monte Carlo method</strong> is implemented for numerical integration, ensuring precision and convergence by increasing sample size.</p>

<h2>Visualization</h2>
<p><strong>Matplotlib</strong> and <strong>Plotly</strong> are used to generate 3D plots of revolution surfaces and vector fields, aiding geometric interpretation.</p>

<h2>Technologies Used</h2>
<ul>
  <li><strong>Python:</strong> Core language for computation and visualization.</li>
  <li><strong>NumPy:</strong> Array manipulation and random sampling.</li>
  <li><strong>SymPy:</strong> Symbolic mathematics and function definition.</li>
  <li><strong>Pandas:</strong> Data handling and analysis.</li>
  <li><strong>Matplotlib & Plotly:</strong> 3D graphical visualization.</li>
</ul>

<h2>Results</h2>
<ul>
  <li>Pole volume: 0.653775 m³</li>
  <li>Pipe volume: 0.009633 m³</li>
  <li>Cone volume: 0.9904 m³</li>
</ul>
