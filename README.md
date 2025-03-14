<h1> Platform-for-Gym-Management (Esis Ekaterina 353505)</h1>
<p>Platform for the control of the gym with a system of roles</p>

<h2>Functional requirments</h2>
<ol>
<h3><li>Show general information:</li></h3>
  <ul>
    <li>prices</li>
    <li>schedule</li>
    <li>coach</li>
    <li>gallery</li>
  </ul>
<h3><li>Admin side:</li></h3>
  <ul>
    <li>client database</li>
    <li>write and delete clients</li>
    <li>extension, add, overwrite subscription</li>
  </ul>
<h3><li>Client side:</li></h3>
  <ul>
    <li>note to coach</li>
    <li>subscription renewal</li>
    <li>balance sheet view</li>
  </ul>
</ol>
<h2>Data models</h2>
<p>The database maintains a list of customers with individual information</p>
<h3>Client:</h3>
<ul>
  <li>mail (include @gmail.com or something like that) and password(consist at least 7 simbols) matching</li>
  <li>subscription information(price, client's balance)</li>
</ul>
<h3>Admin:</h3>
<ul>
  <li><mark>mail</mark></li>
  <li>password</li>
  <li>subscription information</li>
</ul>
<h2>Class diagram</h2>
<img src="https://github.com/user-attachments/assets/606642ac-19e1-42a1-b8b0-673b42f1ed4d">
