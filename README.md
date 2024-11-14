# Terminal Zero - Because Homelabs Should Look Cool Too

Hey y'all! This is my take on making homelab dashboards look like old-school terminals. If you're into retro computing aesthetic (like I am), grab the theme set I made for Dashy and Uptime Kuma.

## What's Inside

### Dashy Dashboard Theme

I started with Dashy's default look and gave it that classic terminal feel - complete with a CRT scan effect (some of this works...I'm not a web dev). It's got everything organized into clean sections for infra, monitoring, dev stuff, etc.

### Uptime Kuma Status Page

Made a matching terminal theme for Uptime Kuma status pages. Keeps things compact and clean with some nice glowing status indicators. Pretty much everything you need at a glance. Works great on mobile too!

## Getting Started

### Setting Up Dashy

1. Grab the `dashy_conf.yml` from the repo
2. Drop it in your Dashy config folder
3. Add your own services and URLs
4. Restart Dashy and you're good to go

### Setting Up Uptime Kuma

1. Copy the CSS from `uptimekuma-retro-compact-theme.css`
2. Head to Settings → Status Page in Uptime Kuma
3. Paste it into Custom CSS
4. Hit save and enjoy!

## How It Looks

### Dashy

![Dashy Dashboard](dashy/screenshots/dashy-dashboard.png)

### Uptime Kuma

![Uptime Kuma Status Page](uptime-kuma/screenshots/uptimekuma-status-page.png)
![Uptime Kuma Dashboard](uptime-kuma/screenshots/uptimekuma-dashboard.png)

## Make It Your Own

Want to tweak the colors or layout? Everything's controlled by CSS variables, so it's pretty easy to customize:

```css
:root {
  --terminal-green: #33ff00;  // Change this for different terminal colors
  --terminal-bg: #0a0a0a;     // Background darkness level
  // ... more variables available in the CSS files
}
```

## Project Structure

```zsh
terminal-zero/
├── dashy/
│   ├── config/
│   │   └── dashy_conf.yml     # The main Dashy config
│   └── screenshots/           
├── uptime-kuma/
│   ├── css/
│   │   └── uptimekuma-retro-compact-theme.css
│   └── screenshots/
└── LICENSE
```

## Want to Contribute?

Found a bug? Got an idea for an improvement? PRs are always welcome! Feel free to open an issue too if you want to discuss something.

## Thanks To

Big shoutout to the folks behind [Dashy](https://github.com/Lissy93/dashy) and [Uptime Kuma](https://github.com/louislam/uptime-kuma) - these tools are awesome!

## License

MIT Licensed - do whatever you want with it!

Let me know if you'd like me to adjust anything else!
