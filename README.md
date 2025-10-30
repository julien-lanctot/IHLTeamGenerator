# IHL Team Generator

A simple web app for generating randomized hockey teams for beer league hockey.

## Features

- Display teams in White and Black columns
- Randomize team assignments (goalies stay separate)
- Reset to default team configuration
- Edit player and goalie names inline
- Copy screenshot of teams to clipboard for sharing

## Deployment to Netlify

### Option 1: Drag and Drop
1. Go to [Netlify](https://www.netlify.com/)
2. Sign up or log in
3. Drag and drop this entire folder onto the Netlify dashboard
4. Your site will be live!

### Option 2: Git Repository
1. Initialize a git repository in this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```
2. Push to GitHub/GitLab/Bitbucket
3. Go to Netlify and connect your repository
4. Deploy!

### Option 3: Netlify CLI
1. Install Netlify CLI:
   ```bash
   npm install -g netlify-cli
   ```
2. Deploy:
   ```bash
   netlify deploy --prod
   ```

## Usage

1. **Randomize Teams**: Click to shuffle all players (except goalies) into random teams
2. **Reset to Default**: Restore the original team configuration
3. **Edit Names**: Click on any player or goalie name to edit it
4. **Copy Screenshot**: Click to copy a screenshot of the teams to your clipboard for sharing on WhatsApp

## Default Teams

**White Team:**
- Tom, Derek, Al, Robert, Joe, LP
- G: Chris

**Black Team:**
- Peter, Yero, Emile, Jon, Rolland, Stephan
- G: Julien
