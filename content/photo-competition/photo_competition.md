---
# An instance of the People widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: people

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 60

title: Photo Competition
subtitle: Third Workshop on Multimodal AI · 16–17 September 2025 · London, UK

content:
  # Choose which groups/teams of users to display.
  #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
#  user_groups:
#    - Principal Investigators
#    - Researchers
#    - Grad Students
#    - Administration
#    - Visitors
#   - Alumni
design:
  show_interests: false
  show_role: true
  show_social: true
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
