---
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.
widget: blank
headless: true # This file represents a page section.

weight: 10 # Order that this section will appear.
title: Third Workshop on Multimodal AI
hero_media: 
design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: '1'
  # Add custom styles
  css_style:
  css_class:
---
<style>
  /* Sticky container for the navigation buttons */
  .sticky-buttons {
    position: fixed;
    top: 0;
    left: 50%;
    transform: translateX(-50%);
    width: 100%;
    background: rgba(255, 255, 255, 0.9);
    z-index: 9999;
    
    display: flex;
    align-items: center;
    justify-content: center;  /* Center buttons on larger screens */
    white-space: nowrap;
    overflow-x: auto;         /* Allow horizontal scrolling */
    margin: 0;
    padding: 5px 8px;
    box-shadow: 0px 4px 6px rgba(0,0,0,0.1);
  }
  
  /* On mobile devices, align buttons to the left */
  @media (max-width: 768px) {
    .sticky-buttons {
      justify-content: flex-start;
    }
  }

  /* Individual buttons styling */
  .sticky-buttons button {
    font-family: 'Open Sans', Arial, sans-serif;
    font-size: 14px;
    padding: 6px 12px;
    border: none;
    border-radius: 4px;
    background-color: #007BFF;
    color: #fff;
    cursor: pointer;
    margin-right: 8px;
    flex: 0 0 auto;   /* Prevent shrinking */
    min-width: 120px; /* Ensure buttons are wide enough to fit more text */
  }

  /* Show the scrollbar (custom styling for WebKit browsers) */
  .sticky-buttons::-webkit-scrollbar {
    height: 8px;         /* horizontal scrollbar height */
  }
  .sticky-buttons::-webkit-scrollbar-track {
    background: #f1f1f1;
  }
  .sticky-buttons::-webkit-scrollbar-thumb {
    background: #888;    /* scrollbar “thumb” color */
  }
  .sticky-buttons::-webkit-scrollbar-thumb:hover {
    background: #555;
  }

  /* Optional: smaller buttons on very narrow screens */
  @media (max-width: 480px) {
    .sticky-buttons button {
      font-size: 13px;
      padding: 4px 8px;
      min-width: 100px;
    }
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
  <a href="#contact" style="text-decoration: none;">
    <button>Contact Us</button>
  </a>

  <a href="/call-for-sponsorship/" style="text-decoration: none;">
    <button>Call for Sponsorship</button>
  </a>

</div>

This page is currently under construction. Please check back soon for updates.
