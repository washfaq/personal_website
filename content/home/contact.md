<form name="contact"
      method="POST"
      data-netlify="true"
      netlify-honeypot="bot-field">

  <input type="hidden" name="form-name" value="contact">

  <p hidden>
    <label>Don’t fill this out: <input name="bot-field"></label>
  </p>

  <p>
    <label>Name<br>
      <input type="text" name="name" required>
    </label>
  </p>

  <p>
    <label>Email<br>
      <input type="email" name="email" required>
    </label>
  </p>

  <p>
    <label>Message<br>
      <textarea name="message" required></textarea>
    </label>
  </p>

  <p>
    <button type="submit">Send</button>
  </p>

</form>
