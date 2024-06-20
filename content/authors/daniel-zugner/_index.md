---
# Display name
title: Daniel Zügner

# Is this the primary user of the site?
superuser: false

# Order that this section appears on the page.
weight: 1

# Role/position
role: Senior Researcher, Microsoft Research AI4Science

# Organizations/Affiliations
organizations:
  - name:
    url: ''

interests:

# Social/Academic Networking
# For available icons, see: https://wowchemy.com/docs/getting-started/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
#  - icon: envelope
#    icon_pack: fas
#    link: 'mailto:test@example.org'
  - icon: google-scholar
    icon_pack: ai
    link: https://scholar.google.de/citations?user=zLYI3MwAAAAJ&hl=de
  - icon: linkedin
    icon_pack: fab
    link: https://www.linkedin.com/in/danielzuegner/
# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.
# - icon: cv
#   icon_pack: ai
#   link: files/cv.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: ''


# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
user_groups:
  - multimodalai24
---
Daniel Zügner is a Senior Researcher at Microsoft Research AI for Science. He is part of a team of researchers and engineers to develop the next generation machine learning models for materials discovery. His research interest includes generative models and graph neural networks. Before joining Microsoft, he obtained his PhD from the Technical University of Munich in 2022, advised by Stephan Günnemann. His experience also includes research internships at Amazon AWS and Spotify.

**MultimodalAI'24 Keynote Title:** MatterGen: a generative model for inorganic materials design

**MultimodalAI'24 Keynote Abstract:** The design of functional materials with desired properties is essential in driving technological advances in areas like energy storage, catalysis, and carbon capture. Traditionally, materials design is achieved by screening a large database of known materials and filtering down candidates based on the application. Generative models provide a new paradigm for materials design by directly generating entirely novel materials given desired property constraints. In this talk, we present MatterGen, a generative model that generates stable, diverse inorganic materials across the periodic table and can further be fine-tuned to steer the generation towards a broad range of property constraints. To enable this, we introduce a new diffusion-based generative process that produces crystalline structures by gradually refining atom types, coordinates, and the periodic lattice. We further introduce adapter modules to enable fine-tuning towards any given property constraints with a labeled dataset. Compared to prior generative models, structures produced by MatterGen are more than twice as likely to be novel and stable, and more than 15 times closer to the local energy minimum. After fine-tuning, MatterGen successfully generates stable, novel materials with desired chemistry, symmetry, as well as mechanical, electronic and magnetic properties. Finally, we demonstrate multi-property materials design capabilities by proposing structures that have both high magnetic density and a chemical composition with low supply-chain risk. We believe that the quality of generated materials and the breadth of MatterGen’s capabilities represent a major advancement towards creating a universal generative model for materials design.
