<!-- Navbar -->
 <header>
   <h1 id="nav-title"><a href="#">DEV.TO</a></h1>
   <nav>
      <ul>
          <li><a href="#">About</a></li>
          <li><a href="#">Services</a></li>
          <li><a href="#">Contact</a></li>
      </ul>
   </nav>          
</header>****


/* Global */
* {
    margin: 0;
    padding: 0;
    font-family: Arial, Helvetica;
}

/* Header */
header {
    display: flex;
    justify-content: flex-end;
    align-items: center;
    padding: 20px 50px;
    box-shadow: 0 1px 8px #ddd;
}

#nav-title {
    margin-right: auto;
    font-size: 1.5em;
}

header li {
    list-style: none;
    display: inline-block;
    padding: 0 20px;
}

header a {
    text-decoration: none;
    color: #555;
    transition: all 0.3s ease 0s;
}

header a:hover {
    color: #b2dfdb;
}

