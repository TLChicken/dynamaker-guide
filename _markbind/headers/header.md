<header>
<!--   <style>
    .logo {
      height: 5%;
      max-width: 20%;
    }
  </style> -->

  <navbar type="dark">
    <a slot="brand" href="{{baseUrl}}/index.html" title="Dynamaker Guide" class="navbar-brand"><img src="{{ baseUrl }}/Contents/Images/Dynamaker%20Guide%20Logo.png" class="logo"></a>
    <li><a href="{{baseUrl}}/mainPg.html" class="nav-link DynamixTxtContainer">Contents</a></li>
    <li slot="right">
      <form class="navbar-form">
        <searchbar :data="searchData" placeholder="Search" :on-hit="searchCallback" menu-align-right></searchbar>
      </form>
    </li>
  </navbar>
</header>
