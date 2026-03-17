---
title: "Home"
date: 2026-03-07T21:00:20Z
math: true
---

<style>
  /* Justify all paragraphs */
  .post-content p {
    text-align: justify;
  }

  /* Tighten ONLY the Contact → bullet gap */
  .post-content p:has(strong) {
    margin-bottom: 0 !important;   /* remove space under "Contact" */
  }

  .post-content p:has(strong) + ul {
    margin-top: 0 !important;      /* remove space above the bullet list */
  }
</style>


<div style="text-align:center; margin-bottom:2rem;">
  <img src="/profile.jpg" alt="Charlotte Clare-Hunt" style="width:180px; height:180px; border-radius:50%;">
  <h1>Charlotte Clare-Hunt</h1>
  <h3>DPhil student in Mathematics, University of Oxford</h3>
</div>

I am a DPhil student in Mathematics at the [University of Oxford](https://www.maths.ox.ac.uk/), focusing on algebraic number theory. My research interests lie in the Langlands programme, particularly \(p\)-adic aspects, automorphic forms, Galois representations, and eigenvarieties. I am also interested in arithmetic algebraic geometry and the study of elliptic and higher‑genus curves.

My primary supervisor is [James Newton](https://www.maths.ox.ac.uk/people/james.newton), and my secondary supervisor is [Victor Flynn](https://www.maths.ox.ac.uk/people/victor.flynn).

I am one of the organisers of the [Oxford Junior Number Theory Seminar](https://www.maths.ox.ac.uk/groups/number-theory/junior-number-theory-seminar).

**Contact**

- **Email:** <span id="email"></span>

    <script>
      // Obfuscated pieces
      const u = ["charlotte", "clare-hunt"].join("&#46;");
      const d = ["maths", "ox", "ac", "uk"].join("&#46;");

      // Decode entities into real characters
      const decode = s => s.replace(/&#46;/g, ".");

      const user = decode(u);
      const domain = decode(d);

      // Human‑readable obfuscated display
      const display =
        user
          .replace(/\./g, " [dot] ")
          .replace(/-/g, " [hyphen] ") +
        " [at] " +
        domain.replace(/\./g, " [dot] ");

      document.getElementById("email").innerHTML =
        `<a href="mailto:${user}@${domain}">${display}</a>`;
    </script>

- **Oxford webpage:** https://www.maths.ox.ac.uk/people/charlotte.clare-hunt