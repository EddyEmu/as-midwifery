🌸 Mum's Website
A lightweight, custom-built website hosted on GitHub Pages.

🛠 Tech Stack
Editor: VS Code

    Hosting: GitHub Pages (Free Tier)

    Domain: Squarespace (Configured via Custom DNS)

    Language: HTML5, CSS3, and a sprinkle of JavaScript.

🚀 Deployment Workflow

Since this is a private repo, ensure your GitHub Pages settings are set to build from the main branch.

1. Make changes in your local environment or Project IDX.

2. Commit and Push:
   Bash
   git add .
   git commit -m "Updated the [Section Name]"
   git push origin main

3. Live Site: The site will automatically update at https://your-username.github.io/repo-name (and your custom domain).

🌐 Domain Configuration (Squarespace)
If the site ever goes down, check these DNS settings in the Squarespace dashboard:

Record Type | Host | Value
CNAME |www |yourusername.github.io
A |@ |185.199.108.153
A |@ |185.199.109.153
A |@ |185.199.110.153
A |@ |185.199.111.153

Note: Ensure Enforce HTTPS is checked in the GitHub repository settings under Settings > Pages.

🎨 Style Guide (Quick Reference)
Keep your design consistent by tracking your choices here:

    Primary Color: #99a38b

    Secondary Color: #f4dacb

    Fonts: 'Lora', Lato.

    Image Assets: Stored in /assets/images/.

📝 To-Do List
[ ] Finalize "About" section copy.

[ ] Optimize images for faster loading.

[ ] Connect custom domain via Squarespace DNS.

[ ] Test mobile responsiveness.
