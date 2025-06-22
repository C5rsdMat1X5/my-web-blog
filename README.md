

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