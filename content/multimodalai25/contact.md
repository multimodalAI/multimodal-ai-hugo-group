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
    - icon: envelope
      icon_pack: fas
      name: Email the organisers
      link: 'mailto:multimodal-ai-enquiry-group@shef.ac.uk'
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
    padding: 6px 12px; /* Reduce button size */
    font-size: 14px; /* Decrease font size */
    border: none;
    background-color: #007BFF;
    color: white;
    border-radius: 4px;
    cursor: pointer;
    margin-right: 10px !important; /* Reduce spacing between buttons */
  }
</style>

<div class="sticky-buttons">
  <a href="#partners" style="text-decoration: none;">
    <button>About</button>
  </a>
  <a href="#about" style="text-decoration: none;">
    <button>Keynote Speakers</button>
  </a>
</div>


To be updated.

