+++
title = "Contact"
+++

## Get in Touch

I'm actively seeking full-time work and am also open to contract and freelance projects. If you think we'd work well together, I'd love to hear from you.

<div data-fs-success style="display:none; color: green;">
  <p>Thanks for reaching out! I'll get back to you soon.</p>
</div>
<div data-fs-error style="display:none; color: red;">
  <p>Something went wrong. Please try again or email me directly.</p>
</div>

<form id="contact-form">
  <div>
    <label for="name">Name</label>
    <input type="text" id="name" name="name" data-fs-field required>
    <span data-fs-error="name" style="color: red; font-size: 0.9em;"></span>
  </div>
  
  <div>
    <label for="email">Email</label>
    <input type="email" id="email" name="email" data-fs-field required>
    <span data-fs-error="email" style="color: red; font-size: 0.9em;"></span>
  </div>
  
  <div>
    <label for="message">Message</label>
    <textarea id="message" name="message" rows="5" data-fs-field required></textarea>
    <span data-fs-error="message" style="color: red; font-size: 0.9em;"></span>
  </div>
  
  <div class="buttons centered">
    <button type="submit" class="colored big" data-fs-submit-btn>Send</button>
  </div>
</form>

<script>
  window.formspree = window.formspree || function () { (formspree.q = formspree.q || []).push(arguments); };
  formspree('initForm', { formElement: '#contact-form', formId: 'mwvwklgz' });
</script>
<script src="https://unpkg.com/@formspree/ajax@1" defer></script>
