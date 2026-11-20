# Online Bus Ticket Booking System

A simple static HTML webpage showing available buses, routes, journey dates, ticket prices and available seats.

## Project files
- `index.html` – Main webpage.
- `README.md` – Project description and instructions.
- `.gitignore` – Files to ignore in Git.

## Run locally
1. Open this folder in Visual Studio Code.
2. Open `index.html` in a browser, or use the VS Code Live Server extension.
3. The page displays the sample available-bus table.

## Upload to GitHub
Open a terminal in this folder and run:

```bash
git init
git add .
git commit -m "Initial bus booking website"
git branch -M main
```

Create a **public** repository on GitHub named `BusTicketBooking`, then connect it:

```bash
git remote add origin https://github.com/USERNAME/BusTicketBooking.git
git push -u origin main
```

Replace `USERNAME` with your GitHub username.

## Publish with GitHub Pages
1. Open the repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`.
5. Click **Save**.

The published address will be:
`https://USERNAME.github.io/BusTicketBooking/`

## Note
This is a static front-end demonstration only. It does not process actual bookings, logins, cancellations or payments.
