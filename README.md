position: absolute;
    top: 60px;
    right: 0;
    background: var(--primary);
    width: 200px;
    display: none;
    box-shadow: -2px 2px 8px rgba(0,0,0,.3);
  }
  .nav.open {
    display: block;
  }
  .nav ul {
    flex-direction: column;
    padding: 1rem;
  }
  .menu-toggle {
    display: block;
  }
}
тот телефон!»</p>
          <footer>— Джон Д.</footer>
        </blockquote>
      </div>
    </div>
  </section>

  <!-- Контакты -->
  <section id="contact" class="section">
    <div class="container">
      <h2>Свяжитесь с нами</h2>
      <form class="contact-form" action="#" method="POST">
        <label for="name">Имя</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Сообщение</label>
        <textarea id="message" name="message" rows="5" required></textarea>

        <button type="submit" class="btn">Отправить</button>
      </form>
    </div>
  </section>

  <!-- Футер -->
  <footer class="site-footer">
    <div class="container">
      <p>© 2025 CosmoPhone. Все права защищены.</p>
      <div class="social">
        <a href="#" aria-label="Instagram">IG</a>
        <a href="#" aria-label="Twitter">TW</a>
        <a href="#" aria-label="Facebook">FB</a>
      </div>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
