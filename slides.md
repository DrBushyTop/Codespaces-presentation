---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
background: 'https://images.unsplash.com/photo-1564934304050-e9bb87a29c13?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80'
# apply any windi css classes to the current slide
class: 'text-center'
---

# Make Dev onboarding a breeze

with GitHub Codespaces!

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
- <logos-twitter style="display:inline"/> [@DrBushyTop](https://twitter.com/DrBushyTop)

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

### "Your instant dev environment"

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

# So what's my angle?

## I believe codespaces will become a common tool for teams for

<v-clicks>

- Setting up environments as config, allowing everyone to have a similar development setup
  - Pretty much like containers do, without you actually having to containerize your application
  - Bugfixes to older projects no longer require (as much) arcane knowledge

- Arranging trainings

- Sharing cool VS code modules, of course

</v-clicks>

---
---

# Configuration

<v-clicks>

- Config isn't just a feature of codespaces, it's built in to VS code too
  - The base is the `.devcontainer` folder in the root of your repo

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

- Whenever a file with a certain name, in my case "Setup.sh" is found in the dotfiles repository, it will be fun before `devcontainer` customizations

- If no setup file is found, files and directories starting with . will get symlinked to your home folder in codespaces

- You might want to consider using some tooling for this, but I've just written some spaghetti code

</v-clicks>

---
layout: image-right
image: https://source.unsplash.com/collection/94734566/1920x1080
---
# Useful Links
- [devcontainer.json reference](https://code.visualstudio.com/docs/remote/devcontainerjson-reference)
- [Remote - Containers VS Code extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
- [Personalization of Codespaces](https://docs.github.com/en/codespaces/setting-up-your-codespace/personalizing-codespaces-for-your-account)
- [Dotfiles In-depth](https://dotfiles.github.io/) 
- [My Blog](https://www.huuhka.net)


---
layout: image-right
image: https://source.unsplash.com/collection/94734566/1920x1080
---

# Code

Use code snippets and get the highlighting directly!

```ts {all|2|1-6|9|all}
interface User {
  id: number
  firstName: string
  lastName: string
  role: string
}

function updateUser(id: number, update: Partial<User>) {
  const user = getUser(id)
  const newUser = {...user, ...update}  
  saveUser(id, newUser)
}
```

---

# Components

<div grid="~ cols-2 gap-4">
<div>

You can use Vue components directly inside your slides.

We have provided a few built-in components like `<Tweet/>` and `<Youtube/>` that you can use directly use. And add your custom components are also super easy.

```md
<Counter :count="10" />
```

<!-- ./components/Counter.vue -->
<Counter :count="10" m="t-4" />

Check out [the guides](https://sli.dev/custom/#components) for more.

</div>
<div>

```html
<Tweet id="1385774635015307265" />
```

<Tweet id="1385774635015307265" scale="0.65" />

</div>
</div>

---

# LaTeX

LaTeX is supported out-of-box powered by [KaTeX](https://katex.org/).

<br>

Inline $\sqrt{3x-1}+(1+x)^2$

Block
$$
\begin{array}{c}

\nabla \times \vec{\mathbf{B}} -\, \frac1c\, \frac{\partial\vec{\mathbf{E}}}{\partial t} &
= \frac{4\pi}{c}\vec{\mathbf{j}}    \nabla \cdot \vec{\mathbf{E}} & = 4 \pi \rho \\

\nabla \times \vec{\mathbf{E}}\, +\, \frac1c\, \frac{\partial\vec{\mathbf{B}}}{\partial t} & = \vec{\mathbf{0}} \\

\nabla \cdot \vec{\mathbf{B}} & = 0

\end{array}
$$

<br>

[Learn more](https://sli.dev/guide/syntax#latex)

---
class: px-20
---

# Themes

Slidev comes with powerful theming support. Themes are able to provide styles, layouts, components, or even configurations for tools. Switching between themes by just **one edit** in your frontmatter:

<div grid="~ cols-2 gap-2" m="-t-2">

```yaml
---
theme: default
---
```

```yaml
---
theme: seriph
---
```

<img border="rounded" src="https://sli.dev/themes/default.png">

<img border="rounded" src="https://sli.dev/themes/seriph.png">

</div>

Read more about [How to use a theme](https://sli.dev/themes/use.html) and
check out the [Awesome Themes Gallery](https://sli.dev/themes/gallery.html).


---
layout: center
class: text-center
---

# Learn More

[Documentations](https://sli.dev) / [GitHub Repo](https://github.com/slidevjs/slidev)
