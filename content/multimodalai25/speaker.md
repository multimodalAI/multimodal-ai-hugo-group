---
# An instance of the People widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: people

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: Keynote Speakers

content:
  # Choose which groups/teams of users to display.
  #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
  user_groups:
    - mmai_25_keynote
#    - Principal Investigators
#    - Researchers
#    - Grad Students
#    - Administration
#    - Visitors
#   - Alumni
     #- multimodalai24
design:
  show_interests: false
  show_organizations: false
  show_role: true
  show_social: false
---
<style>
  .sticky-buttons {
    position: fixed;
    top: 1px !important;
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
    padding: 6px 12px;
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
  <a href="/call-for-sponsorship/" style="text-decoration: none;">
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

