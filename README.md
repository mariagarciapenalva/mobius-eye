<p align="center">
  <img src="banner.svg" alt="The Möbius Eye — a single pixel-art eye watching in the dark, a drop of water falling" width="100%">
</p>

<h3 align="center"><i>A pixel-art horror mini-game about matrix powers.<br>One eye is watching. Some loops never end... Can you escape?</i></h3>

<p align="center"><b><a href="https://mariagarciapenalva.github.io/mobius-eye/">▶ ENTER IF YOU DARE</a></b></p>

<p align="center"><sub>Runs in any browser, on phone or desktop. No install, no sign-up.</sub></p>

---

## 🩸 What is this?

> *Drip.*
>
> You wake up in a cold room. Across the table, a single eye opens and stares at you.
>
> *Drip.*
>
> Between you lies a matrix, **Θ**. The keeper gives it to you again. And again. And again.
>
> *Drip.*
>
> Like water falling on the same spot, it never stops. Unless you see what it's doing.
>
> **Can you outsmart the keeper?**

Each mistake costs you. Run out, and you start over.
Solve everything until the last seal opens… it shows you what the keeper has been hiding.



---------------------------------------
* Breaking character *

Actual description of the repo itself and instructions. Hope you enjoy!
mobius-eye is the MVP of a small Halloween project, but every puzzle is real **Mathematics II** (Spanish *Bachillerato* / PAU level):
- matrix multiplication
- powers of a matrix
- determinants and their properties
- the inverse matrix

If you're preparing the PAU, it's practice. If you're not, it's a puzzle. Either way: don't look up the answer, find it.

## 🕯️ How to play

1. Press **Enter** and listen to the keeper (tap the dialogue box to continue).
2. Pick a card. Each one changes your run.
3. Answer each room: fill in the matrix, the determinants, or choose the right card.
4. Use hints if you must. Beware, they're limited.
5. Reach the final seal. How will this end?

> Tip: paper and pen help. So does noticing patterns.

## 🦴 Built with

- Plain **HTML, CSS and JavaScript** — a single file, no libraries, no build step.
- Pixel art drawn on a `<canvas>`, pyxel, aseprite, blenpy.
- A tiny hand-written 3D renderer for the final surface (projection, depth sorting, flat shading).
- Hosted on **GitHub Pages**.

## 🕸️ Roadmap

Forcing myself to "make it exist first, then make it perfect". Current version is a realistic,
scoped down version that saved me some sanity.
The sky is the limit, though, so some ideas I'd like to add:

- [ ] Difficulty levels
- [ ] New rooms: rank with parameters, systems of equations (Rouché–Frobenius), etc.
- [ ] A **Python** problem generator, so every run gets new matrices
- [ ] A **C / CUDA** experiment exploring which integer matrices behave like the keeper's
- [ ] A 3D-printable version of the final surface

## ⚰️ Run it locally

```bash
git clone https://github.com/mariagarciapenalva/mobius-eye.git
cd mobius-eye
# open index.html in your browser, or use any static server:
python3 -m http.server
```

## 👁️ About me

I'm **María García Penalva**, a physics student who likes GPUs, maths and making stuff.
I also tutor maths and STEM subjects.
Speak now or forever hold your peace, you can ``cd reach-out`` here:

- Instagram: [@bitsandphysics](https://instagram.com/bitsandphysics)
- GitHub: [@mariagarciapenalva](https://github.com/mariagarciapenalva)
- LinkedIn: [https://www.linkedin.com/in/maría-garcía-penalva-064084281/](https://www.linkedin.com/in/maría-garcía-penalva-064084281/)

## 📜 License

- **Code:** [MIT](LICENSE)
- **Pixel art, characters and logo:** © María García Penalva, all rights reserved.

---

<p align="center"><i>If you escape, don't tell the others how. The eye remembers.</i> 👁️</p>
