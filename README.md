RCC Slab Design Web Application

A professional Flask-based structural engineering web app for the design of one-way and two-way reinforced concrete slabs as per IS 456:2000.
The app performs complete load, bending moment, reinforcement, shear and deflection checks with an interactive web interface.

🚀 Features

One-way and Two-way slab classification (based on Ly/Lx)

Self-weight, dead load and live load calculation

Factored load calculation

IS 456 moment coefficient based bending moments

Main and distribution reinforcement design

Bar spacing calculation

Shear stress (τᵥ) vs permissible shear (τc) check

Deflection control using span-to-depth ratio

Final reinforcement detailing

Excel-based slab data display

📐 Design Code

IS 456:2000 – Limit State Method

Uses:

IS 456 Table-26 for moment coefficients

IS 456 Table-19 for shear stress (τc)

Minimum steel and spacing rules

Deflection modification factors

🛠 Tech Stack
| Layer              | Technology                        |
| ------------------ | --------------------------------- |
| Backend            | Python, Flask                     |
| Engineering Engine | IS 456 formulas                   |
| Data Handling      | Pandas, OpenPyXL                  |
| Frontend           | HTML5, CSS3 (Flexbox), JavaScript |
| Database           | Excel (.xlsx)                     |

📂 Project Structure
slab-design-app/
│
├── app.py
├── requirements.txt
│
├── data/
│   └── swet slab.xlsx
│
├── static/
│   └── css/
│       └── style.css
│
└── templates/
    ├── index.html
    ├── about.html
    ├── contact.html
    └── calculator.html


⚙️ How to Run
1️⃣ Clone the repository
git clone https://github.com/yourusername/slab-design-app.git
cd slab-design-app

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run the server
python app.py

4️⃣ Open in browser
http://127.0.0.1:5000

🧮 How It Works

The user enters:

Slab spans (Lx, Ly)

Thickness

Cover

Dead load & live load

Concrete and steel grades

The app computes:

Slab type (One-way or Two-way)

Loads and factored load

Bending moments (Mx, My)

Required steel (Ast)

Bar spacing

Shear stress and τc

Deflection check

Final reinforcement layout

All results are displayed instantly in the browser.

📊 Example Output

For a two-way slab:

Main reinforcement: 8 mm bars @ spacing in X-direction

Distribution steel: 8 mm bars @ spacing in Y-direction

Shear and deflection safety checks

Final design recommendation

👨‍💻 Author

Swet Raj
B.Tech Civil Engineering – NIT Goa
Structural Design | Python | RCC
