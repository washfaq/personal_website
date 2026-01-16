<form name="contact" method="POST" data-netlify="true" netlify-honeypot="bot-field">
  
  <!-- required hidden input -->
  <input type="hidden" name="form-name" value="contact">

  <!-- spam protection -->
  <p hidden>
    <label>Don’t fill this out: <input name="bot-field"></label>
  </p>

  <p>
    <label>Your Name<br>
      <input type="text" name="name" required>
    </label>
  </p>

  <p>
    <label>Your Email<br>
      <input type="email" name="email" required>
    </label>
  </p>

  <p>
    <label>Message<br>
      <textarea name="message" rows="6" required></textarea>
    </label>
  </p>

  <p>
    <button type="submit">Send</button>
  </p>

</form>
