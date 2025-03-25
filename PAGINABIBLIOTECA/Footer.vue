<template>
    <div class="footer">
      <p>&copy; 2025 Biblioteca Online. Todos los derechos reservados.</p>
      <nav>
        <ul class="footer-links">
          <li><a href="/acerca-de">Acerca de</a></li>
          <li><a href="/servicios">Servicios</a></li>
          <li><a href="/contacto">Contacto</a></li>
        </ul>
      </nav>
    </div>
  </template>
  
  <script setup></script>
  
  <style scoped>
  .footer {
    background-color: #007bff;
    color: white;
    padding: 20px;
    text-align: center;
  }
  
  .footer-links {
    list-style: none;
    padding: 0;
    margin: 10px 0 0;
    display: flex;
    justify-content: center;
    gap: 15px;
  }
  
  .footer-links a {
    color: white;
    text-decoration: none;
    font-size: 14px;
  }
  
  .footer-links a:hover {
    text-decoration: underline;
  }
  </style>
