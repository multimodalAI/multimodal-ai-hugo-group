---
# An instance of the People widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: people

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 60

title: Administrative and Technical Support

content:
  # Choose which groups/teams of users to display.
  #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
  user_groups:
    - Tech 25 Workshop

design:
  show_interests: false
  show_role: true
  show_social: false
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
  <a href="#about" style="text-decoration: none;">
    <button>About</button>
  </a>
  <a href="#speaker" style="text-decoration: none;">
    <button>Keynote Speakers</button>
  </a>
  <a href="#organiser" style="text-decoration: none;">
    <button>Organisers</button>
  </a>
  <a href="#partners" style="text-decoration: none;">
    <button>Partners</button>
  </a>
  <a href="#sponsors" style="text-decoration: none;">
    <button>Key Sponsors</button>
  </a>
  <a href="#contact" style="text-decoration: none;">
    <button>Contact Us</button>
  </a>

  <a href="/call-for-sponsorship/" style="text-decoration: none;">
    <button>Call for Sponsorship</button>
  </a>

</div>




