# OtaimFlux

**The 1st generator and editing tool for variable-sequence films (random without repetition + extensive settings), with its player.**
**A 100% free, open-source tool for experimental filmmaking.**

<img width="778" height="218" alt="LOGO-entete" src="https://github.com/user-attachments/assets/2cc98c86-aa51-4862-8b58-c8b73335411e" />


## Because it didn't exist

OtaimFlux was born from a simple observation: there was no simple, free, and accessible tool on the internet to create truly variable-sequence films — what we call "infinite films from shifting sequences."

We searched. We found brilliant artistic experiments (like Janos Xantus's *Got me* in 2001) and technical concepts like "uniform shuffle" or "database cinema." But no ready-to-use, web-native tool that any filmmaker, artist, or student could use to build their own.

So we built it. And we're sharing it.

## What is a variable-sequence film?

Forget simple "random videos." In an OtaimFlux film, each sequence has multiple variants. Each time the film plays, the player picks a **different random variant for every sequence**, never repeating one until all the others have played (a "uniform shuffle without replacement"). Once every variant has been shown, it reshuffles and starts again.

The film loops forever. But **each viewing is unique.**

<img width="1440" height="900" alt="DIAGRAMME OtaimFlux " src="https://github.com/user-attachments/assets/4b148b6a-eef0-4fcf-b3ea-c30f53a7f5fb" />

## Key features (and why they matter)

### 1. The Thread of Exclusion Rules
This is where OtaimFlux becomes a true editing tool. You can create rules like: *"When variant 3 of sequence 2 is played (2/3), never play variant 4/1, 5/11, 6/4, or 10/9 afterwards."*
These rules follow the entire thread of the film, not just the next sequence. It allows you to build complex narrative logic into the randomness, ensuring that certain combinations never happen.

### 2. Soundtracks on Specific Sequences
You can add a sound file that starts at the beginning of one sequence and fades out at the end of another (e.g., from sequence 2 to sequence 5). Add as many as you need. This lets you create evolving soundscapes that react to the random structure of the film.

### 3. The "Embed" Button (iframe)
Every film generated with OtaimFlux comes with a built-in "Embed" button. This provides an iframe code that anyone can copy and paste to display your film on their own website — exactly as we do in our collection.

## See it in action

*   **Try the generator:** [https://otaim.net/inserer-un-film-aleatoire/](https://otaim.net/inserer-un-film-aleatoire/)
*   **Explore our collection of films:** [https://otaim.net/videos-a-sequences-aleatoires/](https://otaim.net/videos-a-sequences-aleatoires/)

<img width="738" height="704" alt="Capture d’écran 2026-10-31 à 16 53 33" src="https://github.com/user-attachments/assets/6f99b103-b4ef-461b-85f6-138a2a1e1391" />

## We want to host your creations

OtaimFlux is not just a tool; it's a community. If you create a variable-sequence film with our player, we would be honored to feature it in our collection.

Send us the iframe code and a short description through our [Contact page](https://otaim.net/contact/). We'll review it and, if it fits, add it to our showcase.

Our own examples, like *Rêveries de Kafka* (an animated film based on Kafka's drawings) and *Got me* (a rediscovered Hungarian experimental film), are just the beginning.

## How to use it

The tool is designed to be simple:
1.  **Prepare your videos:** Export each variant as MP4 (H.264) with "Web Optimized" or "Fast Start" switched on. Upload them to your own server.
2.  **Fill in the generator:** Enter your film's title, number of sequences, and paste the URLs of your video variants.
3.  **Generate the codes:** The tool gives you two pieces of code — one for your website (e.g., WordPress Custom HTML block) and one for an iframe page (HTML file).
4.  **Publish:** Paste the code on your site and upload the .html file to your hosting.

That's it. Your infinite film is live.

## License

OtaimFlux is released under the **GNU General Public License v3.0 or later**, with an **additional exception** for embedding.

This means:
*   You can use, study, copy, modify, and redistribute the code, even commercially.
*   If you distribute a modified version, you must release it under the same license.
*   **The exception:** Using the player in your own web page or software with your own content does **not** force you to release your entire project under the GPL. The exception was created specifically to protect creators who embed OtaimFlux.

For the full legal texts, see the `LICENSE` and `LICENSE-EXCEPTION` files in this repository.

---

*OtaimFlux – Copyright (C) 2025 Cie O t'aim, Jean-Daniel Magnin.*
