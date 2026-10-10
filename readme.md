Portfolio Site - Assignment 1
# Overview
- Using HTML5 and CSS3, I created a professional portfolio to help introduce who i am to others. It highlights some projects i have done so far and, provides a way for visitors to contact me.

# Pages
- Home: Welcome message, profile image and navigation to the other pages. 
- About me: short intorduction, potrait, embedded video with controls and poster, and a skills list. A javascript toggles the video playback.
- Projects: project cards describing networking projectsm a financial literacy game and an event management system.
- Contact me: visitor inquiry form with name email, phone, comments, reset and submit controls.

# Responsive desing and viewports
The HTMLS are linked to all spereate viewports using media queries:
- Phone:'max-width:480px'. The CSS is designged to use a single-column on narrow creens with full width content and form fields.
- Tablet:'min-width: 481px`and`max-width: 960px'. This CSS uses two columns and project cards sized for medium-width displays.
- Desktop: 'min-width: 961px'. This CSS feautres wider columns and smaller project card widths to take advantage of the available screen space.

# CSS gradients
- Angled linear gradient: '.pagepr' uses a diagonal gradient with gold ('#d4af37'), burgundy ('#6b1d2f'), and navy ('#0a192f') for the projects-page background.

- Vertical linear gradient: 'form' uses a 180-degree gradient from brown ('#8c4a28') to burgundy ('#6b1d2f') to distinguish the contact form.


# Color scheme
The supplied design uses a coordinated, custom palette:
- Navy '#0A192F': header, footer, and primary text; creates a strong, professional base.
- Warm white '#FDFBF7': page background and text on dark areas; supports contrast and readability.
- Gold '#D4AF37':  navigation links, image borders, and highlights.
- Burgundy '#6B1D2F': buttons, hover states, and gradient accents.
- Forest green '#1B3B2B': project cards and video border.
- Brown '#8C4A28: used for section borders and form accents.

# Semantic HTML and accessibility
The markup uses semantic elements including header, nav, article, section, footer, and address to organize page content. Images include alt text, form labels use for attributes intended to associate with field IDs, and the video includes native playback controls and a poster image.


# Contact form behaviour and limitations
The form uses 'required' fields and an email input type, which allows for basic browser side required field and email-format checks. type="tel" does not by itself validate a specific number of digits.

# Project cards
The Projects page describes 
1. A Cisco Packet Tracer network using IP addressing, switches, routers, and ping tests.
2. A multi-branch network connected through routing.
3. A Python financial-literacy game.
4. A Python event management system using object-oriented programming.

[Janice Nanteza], [October 9th 2026]