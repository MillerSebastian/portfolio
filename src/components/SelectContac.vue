<template>
  <section id="contacto" class="contacto">
    <div class="contenido-seccion">
      <h2>CONTACTO</h2>
      <div class="fila">
        <!-- Formulario -->
        <div class="col">
          <input type="text" placeholder="Tú Nombre" />
          <input type="text" placeholder="Número telefónico" />
          <input type="text" placeholder="Dirección de correo" />
          <input type="text" placeholder="Tema" />
          <textarea
            name=""
            id=""
            cols="30"
            rows="10"
            placeholder="Mensaje"
          ></textarea>
          <button>
            Enviar Mensaje<i class="fa-solid fa-paper-plane"></i>
            <span class="overlay"></span>
          </button>
        </div>
        <!-- Mapa -->
        <div class="col">
          <img
            src="/public/img/Captura de Pantalla 2024-03-26 a la(s) 7.02.19 p. m..png"
            alt=""
          />
          <div class="col">
            <div class="info">
              <ul>
                <li>
                  <i class="fa-solid fa-location-dot"></i>
                  Barranquilla , buenos aires
                </li>
                <li>
                  <i class="fa-solid fa-mobile-screen"></i>
                  Llamame: 3106727671
                </li>
                <li>
                  <i class="fa-solid fa-envelope"></i>
                  Email: seebastianrodelog@gmial.com
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
