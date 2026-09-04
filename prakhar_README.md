# Prakhar Pratap Singh — Portfolio

Frontend-developer style dark portfolio, built from resume content. Plain HTML/CSS/JS, single file (`index.html`), no build step.

## Content already filled in

Resume se saara data (skills, projects, education, certificates, publication, contact) already daala hua hai. Bas double-check kar lena:

- `#contact` section — email, phone, GitHub, LinkedIn sab resume se match karte hain
- Agar LinkedIn ka exact URL alag hai (resume mein space tha `prakhar-pratap-singh` ke pehle), toh `index.html` mein LinkedIn links (2 jagah hain — hero aur contact) update kar dena

## GitHub pe push karna

```bash
cd prakhar-portfolio
git init
git add .
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
```

## Vercel pe deploy karna

1. https://vercel.com pe GitHub account se login karo
2. **"Add New..." → "Project"** click karo
3. GitHub repo import karo
4. Framework preset auto "Other"/static aa jayega — koi build command nahi chahiye, seedha **Deploy** click karo
5. Live URL mil jayega (e.g. `your-repo.vercel.app`)

Future mein `main` branch pe push karne pe Vercel automatically redeploy kar dega.
