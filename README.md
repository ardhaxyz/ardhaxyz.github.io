# Minimal Jekyll homepage — Ardha clone (Substack & social links)

Drop these files into your Jekyll repository (ardhaxyz/ardhaxyz.github.io):

- _layouts/default.html
- index.md
- assets/styles.css
- _includes/social-icons.html
- _data/social.yml

Steps:
1. Add files above to your repository (or merge with your theme).
2. Update _data/social.yml with your real URLs.
3. Put your avatar at the path you set in _config.yml as `avatar:` or change the path in index.md.
4. Update site metadata in _config.yml (optional):
   - title, author, bio, substack, avatar, tagline
   Example:
   ```
   title: Ardha
   author: Ardha Xyz
   bio: "Researcher, builder, and writer. I write at my Substack."
   substack: https://your-substack.substack.com
   avatar: /assets/avatar.jpg
   tagline: Minimal writing and projects
   ```
5. Commit & push. GitHub Pages will build your Jekyll site and publish it.

Notes:
- If you use a remote theme, this layout will override the theme's layout. If you'd rather keep the theme header/footer and only replace the content, tell me which theme you're using and I will adapt the markup to work as an override (or provide only a page include).
- If you want the avatar strictly on the right even on narrow screens, I can change the responsive rules — currently the avatar stacks above the text on small screens for better legibility.
- If you want me to precisely match the design of your Next.js site (colors, spacing, fonts), share the URL (ardha.xyz) or a screenshot and I’ll adapt the CSS.

Would you like me to:
- adapt this to your existing Jekyll theme (tell me the theme name), or
- update the social links and avatar for you now? Please provide avatar file if you want me to add it.
