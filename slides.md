---
# try also 'default' to start simple
theme: seriph
background: 'https://db3pap002files.storage.live.com/y4m3ZzJqxbSgWCyOnNIpyiIXt5E-k3YzlmJXd_MXh0fGLb-kbB_zCLVLpGUvxP8DUOtQg1Dh4dRZdm9xbzz5QX3hXHg46kI0nB1u6vz2R8hP8dk1pBgYrX0KHbHn2xYab6ngYnGzjFMcGNz528NPcLCeD9rJ2SCdUUJcQsMC1yThR34LY9qM9igynAL5-2HpJdZ?width=2560&height=1440&cropmode=none'
# apply any windi css classes to the current slide
class: 'text-center'
---


---
layout: 'image' 
image: 'https://db3pap002files.storage.live.com/y4mawuzPnpoVkNySnMQne3_lwiz0fUpOo2y3mKJ0iU_BD8t8G67WMQa0mondCxYzPUaAfF_czJUNZiuAhvJSff3D89cThbSbpFZWCfNnTnN559Qxx3Vs4gI1VyrPFAXY1LM9LsaohyS2PaM_8rYk0k1lq5ALoRjQEgG8ThDGC2b7B47kEe-QHfTohRH4k3ua6hY?width=2560&height=1440&cropmode=none'
---

<a href="https://github.com/DrBushyTop" target="_blank" alt="GitHub"
  class="abs-br m-6 text-xl icon-btn opacity-50 !border-none !hover:text-white">
  <carbon-logo-github />
</a>

---
layout: image-right
image: https://db3pap002files.storage.live.com/y4mvftauMZYLJRnW3dSfXaWuToPelsTgKrk-NHrv2YWz_1pFlkpgGVzw4EjNsqj-VvIVw3mlp1rkJ3o1U0KqViIPAg1x1_sG6ndZrPkAGdtg2qYHa1Ro7Gj2GgbQf7cl2fxNU28NTDk6yzOYMwaUaDN07Rr3EdtYf621Q3mKOO8GcW9YzV_-aIKsYlExmBbDw0Q?width=2000&height=2000&cropmode=none

---
# Pasi Huuhka

<v-clicks>

- 🔨 **DevOps Architect @ [Zure](https://www.zure.com)**
- 🐱‍💻 **[Azure MVP](https://mvp.microsoft.com/en-us/PublicProfile/5003781?fullName=Pasi%20%20Huuhka)** 
- 🚀 **[User Group](https://www.meetup.com/Finland-Azure-User-Group/) Organizer** 
- <logos-azure-icon style="display:inline"/> **Focus on anything Azure**
- 📝 **Blog @ [huuhka.net](https://www.huuhka.net)**
- <logos-twitter style="display:inline"/> [**@DrBushyTop**](https://twitter.com/DrBushyTop)

</v-clicks>

<br>
<br>

<v-clicks>

### Currently working on:
- Kubernetes with GitOps
- Championing GitHub
- Mentoring Projects
- Driving ARM -> Bicep transition for all our teams

</v-clicks>

---
layout: 'image'
image: 'https://db3pap002files.storage.live.com/y4mol_wbajK_VkyWRrjy5cvIR17JMwSVt4-lY7FQs_XFVHHpkVKlyyvPk8z_e-x5cOetxNc45LWAy3YU2k0pbH0kHICy42nga3Ur_ZJm-1zQDOrGFKUksu6fQOEzHsCatGQdG0WWFlDzqx7CGEfK5GCIxQ6jiMn-gtY5Msre-Tb81u9NEvKnc1iP-ZH0_uKiZ5F?width=2560&height=1440&cropmode=none'
---
---

# Session Agenda

<v-clicks>

- You'll learn what Github Codespaces are and why you should think about using them
- We'll take a look at how you can customize your projects for everyone, dev environments as code
- And of course how you can get all your nifty personal configurations on top of it all

</v-clicks>

<style>
li {
  font-size: x-large;
}
</style>

---
layout: image-right
image: https://db3pap002files.storage.live.com/y4mGcZXCfu03vieQQ3b0JkpOOpyffg18oxx_rt5iM_0YhIKpYgP4wEbGnnzHC1ueYbiYFNtoKcVi7LAeRMtyBSHjA4UGqdVQv36aDibqLcrCPYrMl6eSNBrnLNM8sS2oir79kf5idAVg1yENCJue7vV9WgyrpuykS9LtPVRk-GlqEAaPwDry0c33JJhu6WfJK8K?width=525&height=842&cropmode=none
---

# Codespaces!

### "Your instant dev environment" (BETA)

The marketing team inside my head would explain codespaces as...

<v-clicks>

- Visual Studio or Visual Studio Code on your browser
- Available from any location, from any device
- Customizable for almost any need
- With your own tools
- ... and great GitHub integration

</v-clicks>

<v-clicks>

DISCLAIMER: I'm not very good at marketing

</v-clicks>

---
layout: center
class: text-center
---

# Setting up your first codespace

---
---
# Some details

<v-clicks>

- 👩‍💻 Can connect from your local VS Code instance too
- 💸 Free during the beta, [will be billed by use later](https://github.blog/changelog/2020-09-15-about-codespaces-pricing/)
- 💻 Multiple VM sizes available even during the beta, though specifics are still unclear
- 🐛 Still in beta, so some of the bugs we might spot are most likely still being polished out
- 🚀 GA in Q3-2021 according to [the GitHub public roadmap](https://github.com/github/roadmap/issues/55)
- <logos-visual-studio style="display:inline"/> Works with full Visual Studio too!

</v-clicks>

---
---

# So what's my angle?

## I believe codespaces will become a common tool for teams for

<v-clicks>

- Setting up environments as code, allowing everyone to have a similar development setup
  - Pretty much like containers do, without you actually having to containerize your application
  - Bugfixes to older projects no longer require (as much) arcane knowledge

- Arranging trainings

- Sharing cool VS code modules, of course

</v-clicks>

---
---

# Configuration

<v-clicks>

- Config isn't just a feature of codespaces, it's built in to VS code
  - The base is the `.devcontainer` folder in the root of your repo
  - You can actually use these for local development inside a container just as well, and reap a subset of the benefits

- You can use a default container, select from ready made ones, or just customize your own from scratch

- There are decent community made lists of devcontainers too, like [this set](https://github.com/benc-uk/devcontainers) by [Ben Coleman](https://github.com/benc-uk)

</v-clicks>

---
layout: center
class: text-center
---

# Let's create a configuration for our project

---
---

# But what about my cool toys?

<v-clicks>

### Don't worry, you can have those too

</v-clicks>

<v-clicks>

- Enter dotfiles and VS code settings sync

- `yourGitHubUser/dotfiles` repository will get synced to every codespace you create

- Whenever a file with a certain name, in my case "Setup.sh" is found in the dotfiles repository, it will be fun after(?) `devcontainer` customizations
  - Documentation does say "before" but this doesn't seem to be the case

- If no setup file is found, files and directories starting with . will get symlinked to your home folder in codespaces

- You might want to consider using some tooling for this, but I've just written some spaghetti code

</v-clicks>

---
---

# Settings Sync

<v-clicks>

- Built in to VS Code (so NOT the extension in the marketplace)

- Allows you to log in to your GitHub or Microsoft account to sync all settings from keybindings to extensions and themes

- Sync is almost instant from one device to another

- Can ignore certain settings easily

</v-clicks>

---
layout: center
class: text-center
---

# Dotfiles & Settings Sync demo

---
layout: image-right
image: https://docs.github.com/assets/images/help/settings/codespaces-audit-log-org.png
---
# Management & Security

<v-clicks>

- [Security logs](https://docs.github.com/en/codespaces/managing-your-codespaces/reviewing-your-security-logs-for-codespaces) are available for you personally
- [Audit logs](https://docs.github.com/en/codespaces/managing-codespaces-for-your-organization/reviewing-your-organizations-audit-logs-for-codespaces) are available for your organization
- [Personal & Organizational Secrets](https://docs.github.com/en/codespaces/managing-your-codespaces/managing-encrypted-secrets-for-your-codespaces) can be set on a repository level for Codespaces
- [Private Container Registry](https://docs.github.com/en/codespaces/codespaces-reference/allowing-your-codespace-to-access-a-private-image-registry)

</v-clicks>

---
layout: image-right
image: https://source.unsplash.com/collection/94734566/1920x1080
---
# Useful Links
- [Devcontainer development](https://docs.github.com/en/codespaces/setting-up-your-codespace/configuring-codespaces-for-your-project)
- [devcontainer.json reference](https://code.visualstudio.com/docs/remote/devcontainerjson-reference)
- [Remote - Containers VS Code extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
- [Personalization of Codespaces](https://docs.github.com/en/codespaces/setting-up-your-codespace/personalizing-codespaces-for-your-account)
- [Dotfiles In-depth](https://dotfiles.github.io/) 
- [My Blog](https://www.huuhka.net)

---
layout: center
class: text-center
---

# Slides: [zure.ly/pasi/techorama](http://zure.ly/pasi/techorama)