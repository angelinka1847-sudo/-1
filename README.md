# -11800) — мини / легкая текстура -->
      <div class="product-card">
        <div class="product-icon">
          <i class="fas fa-tint"></i>
        </div>
        <div class="product-title">Жидкие румяна</div>
        <div class="product-desc">Легкая вуаль, мини-формат, натуральный румянец</div>
        <div class="product-price">1 800 ₽</div>
      </div>

      <!-- Жидкий хайлайтер -->
      <div class="product-card">
        <div class="product-icon">
          <i class="fas fa-sun"></i>
        </div>
        <div class="product-title">Жидкий хайлайтер</div>
        <div class="product-desc">Мерцание без видимых частиц, soft-focus эффект</div>
        <div class="product-price">от 3 800 ₽</div>
      </div>
    </div>

    <!-- Подписка по email (чтобы знать новинки) -->
    <div class="newsletter-section">
      <div class="newsletter-title">✨ Будьте в курсе новинок</div>
      <div class="newsletter-text">Подпишитесь на рассылку — получайте первыми анонсы, эксклюзивные предложения и beauty-советы.</div>
      <form id="subscribeForm" class="newsletter-form">
        <input type="email" id="emailInput" placeholder="Введите свой email чтобы знать новинки" required>
        <button type="submit" class="btn-subscribe"><i class="fas fa-paper-plane"></i> Подписаться</button>
      </form>
    </div>
  </div>
</main>

<footer class="site-footer">
  <div class="container">
    <div class="footer-grid">
      <!-- Блок НАВИГАЦИЯ -->
      <div class="footer-col">
        <h4>НАВИГАЦИЯ</h4>
        <ul class="footer-nav">
          <li><a href="#">О нас</a></li>
          <li><a href="#">Акции</a></li>
          <li><a href="#">Каталог</a></li>
          <li><a href="#">Блог</a></li>
          <li><a href="#">Бренды</a></li>
          <li><a href="#">Оплата и доставка</a></li>
        </ul>
      </div>

      <!-- Блок ПОМОЩЬ + соцсети -->
      <div class="footer-col">
        <h4>ПОМОЩЬ</h4>
        <div class="social-links">
          <a href="#" aria-label="VK"><i class="fab fa-vk"></i></a>
          <a href="#" aria-label="Telegram"><i class="fab fa-telegram-plane"></i></a>
          <a href="#" aria-label="Instagram"><i class="fab fa-instagram"></i></a>
        </div>
        <p style="margin-top: 24px; font-size: 0.85rem; color: #b29e8d;">ВК · TELEGRAM · INSTAGRAM
Служба заботы: support@lorax.ru</p>
      </div>

      <!-- Дополнительный блок с короткой информацией -->
      <div class="footer-col">
        <h4>LORAX</h4>
        <p style="line-height: 1.5; margin-bottom: 12px;">Натуральная космецевтика, вдохновлённая природой. Любовь к деталям и инновационные формулы.</p>
        <div style="display: flex; gap: 12px; font-size: 0.85rem;">
          <span><i class="far fa-clock"></i>  Пн–Пт: 10–20</span>
        </div>
      </div>
    </div>
    <div class="copyright">
      © 2025 LORAX — все права защищены. С любовью к красоте.
    </div>
  </div>
</footer>

<script>
  // Простая обработка подписки (демонстрация)
  const form = document.getElementById('subscribeForm');
  if (form) {
    form.addEventListener('submit', function(e) {
      e.preventDefault();
      const emailInput = document.getElementById('emailInput');
      const email = emailInput.value.trim();
      if (email === '' || !email.includes('@')) {
        alert('Пожалуйста, укажите корректный email');
        return;
      }
      // Имитация успешной подписки
      alert(`Спасибо за подписку, ${email}! Вы первыми узнаете о новинках LORAX ✨`);
      emailInput.value = '';
    });
  }
</script>
</body>
</html>
```
