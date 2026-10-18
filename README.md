# Libadwaita Web

Libadwaita Web is an CSS + Astro Theme for WebSites, based on Libadwaita and Adwaita.

## Tailwind

In your Astro project, you need first download the `tailwind`:

```Bash
npx astro add tailwind
```

## Download

**1 -** Download from URL

**With Nexo:**

You can download Libadwaita Web with Nexo:

```Bash
nexo download https://github.com/HexaWorksOfficial/Libadwaita-Web/archive/refs/heads/main.zip -o ~/Downloads/main.zip
```

**With curl:**

Or with curl:

```Bash
curl -o https://github.com/HexaWorksOfficial/Libadwaita-Web/archive/refs/heads/main.zip ~/Downloads/main.zip
```

**2 -** unstract the `.zip`:

```Bash
unzip ~/Downloads/main.zip
```


## Install

**1 -** Go in project directory (replace 'project directory' with your actual project path):

```Bash
cd 'project directory'
```

**2 -** Remove the default `global.css` and `index.astro`:

```Bash
rm src/styles/global.css src/pages/index.astro
```

**3 -** Copy the new `global.css` and `index.astro` from the downloaded Libadwaita Web folder:

```Bash
cp ~/Downloads/main/CSS/global.css src/styles/global.css && cp ~/Downloads/main/Astro/index.astro src/pages/index.astro
```

**4 -** *(Optional but recommended)* Copy the `Adwaita.svg` from the downloaded Libadwaita Web folder to your `public` directory:

```bash
cp ~/Downloads/main/Adwaita.svg public/Adwaita.svg
```
