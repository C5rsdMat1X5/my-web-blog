

# Personal Portfolio Website

This is a personal portfolio website built with Flask to showcase projects, skills, and blog posts. The design is clean, responsive, and accessible.

## Features

- Responsive layout with CSS custom properties (variables) for easy theming.
- About section with personal info and fun facts.
- Skills section with icons and hover effects.
- Projects and blog posts showcased with cards and animations.
- Accessibility features like skip links.
- Uses Google Fonts (Montserrat).
- Simple, clean, and modern design.

## Tech Stack

- Python 3.x
- Flask
- HTML5 & CSS3 (with CSS variables and flexbox/grid)
- Google Fonts (Montserrat)

## Setup and Installation

1. **Clone the repository**

```bash
git clone https://github.com/C5rsdMat1X5/your-repo-name.git
cd your-repo-name
```

2. **Create and activate a virtual environment (recommended)**

```bash
python3 -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install Flask
```

4. **Run the Flask app**

```bash
export FLASK_APP=app.py        # On Windows: set FLASK_APP=app.py
export FLASK_ENV=development   # Enables debug mode
flask run
```

5. **Open your browser**

Go to [http://127.0.0.1:5000](http://127.0.0.1:5000) to see your portfolio in action.

## Project Structure

```
/your-project
│
├── app.py             # Main Flask app
├── static/
│   ├── style.css      # CSS styles
│   ├── pfp.png        # Profile picture
│   └── favicon.ico    # Favicon
├── templates/
│   └── index.html     # Main HTML template
└── README.md
```

## Customization

- Update the `app.py` or Flask route to serve your content dynamically if desired.
- Replace images inside `/static` folder with your own.
- Modify `style.css` to tweak colors, fonts, and layout.
- Add or remove social links in the header.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
# Matías Henríquez — Personal Portfolio

> My online playground, interactive résumé, and humble brag all rolled into one.

![Hero Screenshot](./static/demo-screenshot.png)<!-- Swap for a real capture later -->

---

## 🧐 What’s This All About?

This project is **not** a tutorial repo.  
It’s my personal corner of the internet—built with Flask and a pinch of vanilla CSS—to show the world (and future employers 👀) what I can do.

Think of it as:

- **Digital résumé** —  _Who I am, what I know, where I’ve been._
- **Project showroom** —  _Latest code experiments, side‑quests, and half‑baked ideas._
- **Blog outlet** —  _Occasional rants about tech, life, and why tabs beat spaces._
- **Playground** —  _A safe space to break things, then ship them anyway._

---

## ✨ Highlights

| Section      | Why You Should Care                                    |
|--------------|--------------------------------------------------------|
| **Hero**     | Quick intro, cheeky waving‑hand emoji, and socials     |
| **About**    | Bullet‑proof facts (winter > summer, fight me)         |
| **Skills**   | Python, web dev, basketball dunks—you know, essentials |
| **Projects** | Card grid with subtle hover sauce                      |
| **Blog**     | Mini‑essays on coding adventures & bad coffee reviews  |
| **Accessibility** | Skip links, semantic HTML, and readable contrast  |

---

## ⚙️ Under the Hood (Brief)

- **Flask** handles the routing magic.  
- **HTML5 + CSS custom properties** give it that sleek, theme‑able vibe.  
- **Google Fonts – Montserrat** for that clean typographic drip.  
- Zero JS frameworks—because sometimes less _is_ more.

---

## 🛣️ Roadmap

- Dark mode toggle 🌚
- Multilingual switch (¡obvio!)
- Auto‑deploy with GitHub Actions
- More animated easter eggs

---

## 🤝 Credits & License

Made with ♥ and _way_ too much coffee by **Matías Henríquez**.  
Feel free to peek at the code, steal ideas for inspiration, or open issues—but remember: this repo’s main job is to _show off_, not teach you how to clone & run it.

Licensed under MIT because why not.