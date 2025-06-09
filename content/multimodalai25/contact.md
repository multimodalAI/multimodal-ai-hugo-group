---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 80

title: Contact Us
subtitle:

content:
  # Contact (edit or remove options as required)
  email: 
  #directions:
  #appointment_url: 'https://calendly.com'
  contact_links:
  # Automatically link email and phone or display as text?
  autolink:

design:
  columns: '1'

---
<style>
  .sticky-buttons {
    position: fixed;
    top: 1px !important; /* Reduce distance from the top */
    left: 50%;
    transform: translateX(-50%);
    background: rgba(255, 255, 255, 0.9);
    padding: 5px 8px; /* Reduce padding to make it more compact */
    border-radius: 8px;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
    z-index: 9999;
  }

  .sticky-buttons button {
    font-family: 'Open Sans', Arial, sans-serif;
    font-size: 14px;
    font-weight: bold; /* This makes the text bold */
    padding: 6px 12px;
    border: none;
    border-radius: 4px;
    background-color: #154c79;
    color: #abdbe3;
    cursor: pointer;
    margin-right: 8px;
    flex: 0 0 auto;
    min-width: 120px;
  }
</style>

<div class="sticky-buttons">
  <a href="#speaker" style="text-decoration: none;">
    <button>Speakers</button>
  </a>
  <a href="/call-for-sponsorship/" style="text-decoration: none;">
    <button>Sponsor Us</button>
  </a>
  <a href="#key_dates" style="text-decoration: none;">
    <button>Key Dates</button>
  </a>
  <a href="#about" style="text-decoration: none;">
    <button>About</button>
  </a>
  <a href="#contact" style="text-decoration: none;">
    <button>Contact Us</button>
  </a>

</div>

<i class="fas fa-envelope"></i> Email the organisers: <a href="mailto:ukomain-mmai25@googlegroups.com">ukomain-mmai25@googlegroups.com</a>

