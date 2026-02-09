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
  address:
    street: UCL East Campus, One Pool Street
    city: London
    region:
    postcode: 'E20 2AF'
    country: United Kingdom
    country_code: UK
  coordinates:
    latitude: '51.537163'
    longitude: '-0.012019'
  #directions:
  #appointment_url: 'https://calendly.com'
  # Automatically link email and phone or display as text?
  autolink:

design:
  columns: '1'

---
<style>
  .sticky-buttons {
    position: fixed;
    top: 6px !important;
    left: 50%;
    transform: translateX(-50%);
    background: rgba(255, 255, 255, 0.9);
    padding: 5px 8px;
    border-radius: 8px;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
    z-index: 9999;

    display: flex;            /* Enable flex layout */
    flex-direction: row;      /* Keep items in a row */
    flex-wrap: nowrap;        /* Prevent wrapping */
    overflow-x: auto;         /* Allow scrolling on very small screens */
    max-width: 100vw;         /* Avoid overflowing viewport width */
  }

  .sticky-buttons button {
    font-family: 'Open Sans', Arial, sans-serif;
    font-size: 14px;
    font-weight: bold;
    padding: 4px 12px;
    border: none;
    border-radius: 4px;
    background-color: #154c79;
    color: #abdbe3;
    cursor: pointer;
    margin-right: 8px;
    flex: 0 0 auto;           /* Prevent flex shrink/grow */
    min-width: 120px;
    white-space: nowrap;     /* Prevent button text from wrapping */
  }
</style>

<div class="sticky-buttons">
  <a href="#speaker" style="text-decoration: none;">
    <button>Speakers</button>
  </a>
  <a href="/multimodalai26-sponsorship/" style="text-decoration: none;">
    <button>Sponsor Us</button>
  </a>
  <a href="#programme" style="text-decoration: none;">
    <button>Programme</button>
  </a>
  <a href="#about" style="text-decoration: none;">
    <button>About</button>
  </a>
  <a href="#contact" style="text-decoration: none;">
    <button>Contact Us</button>
  </a>

</div>

<i class="fas fa-envelope fa-2x" style="margin-right:20px;"></i> Email the organisers: <a href="mailto:ukomain-mmai25@googlegroups.com">ukomain-mmai26@googlegroups.com</a>
