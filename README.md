
<p align="center">
  <img src="/public/favicon.svg" width="50" alt="Logo" />
</p>
<h1 align="center">Personal Portfolio</h1>

[![Site preview](/public/site-preview.png)](https://your-deployed-site.com)

This is my personal portfolio to showcase selected projects. Built with [Remix](https://remix.run/), [Three.js](https://threejs.org/), and [Framer Motion](https://www.framer.com/motion/).  
➡️ [Live site](https://your-deployed-site.com)  
➡️ [Storybook preview](https://your-storybook-link.com)

---

## 🛠️ Install & Run

Make sure you have Node.js `19.9.0` or higher and npm `9.6.3` or higher installed.

Install dependencies:

```bash
npm install
```

Start the local development server:

```bash
npm run dev
```

To view the components in Storybook:

```bash
npm run dev:storybook
```

---

## 🚀 Deployment

This site is set up to deploy using Cloudflare Pages.

To deploy:

```bash
npm run deploy
```

---

## 📄 Permissions

This project is open source — feel free to use parts of the code to learn or build your own projects.

If you're using the site's design with minimal changes, a credit to **Adwait Mahadar** would be appreciated.  
Please do **not** present any of my actual portfolio projects as your own — these represent real work I’ve done.

---

## ❓ FAQs

<details>
  <summary>How do I change the color on the <code>DisplacementSphere</code> (the animated blobby background)?</summary>

  You'll need to edit the fragment shader. You can tweak the color values inside the shader file that powers the sphere.
</details>

<details>
  <summary>How do I get the contact form to work?</summary>

  Set up [AWS SES](https://aws.amazon.com/ses/) for sending emails, and configure the `.dev.vars` file with your credentials.  
  Alternatively, you can use [nodemailer](https://nodemailer.com/) with a Gmail account.  
  For production, remember to add these as environment variables in the Cloudflare dashboard.
</details>

---

## 👨‍💻 Maintained by

**Adwait Mahadar**  
[LinkedIn](https://www.linkedin.com/in/adwaitmahadar/) • [GitHub](https://github.com/adwaitmahadar) • [Portfolio](https://www.adwaitmahadar.tech/)
