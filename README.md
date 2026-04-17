**Thesis:** _A Survey of Methods in Song Detection and Music Information Retrieval_

**Author:** Nicky Zarick

**Completed:** 2026

In this repository, you'll find my full thesis and related notebooks containing code for the algorithms discussed within.


The main content of this thesis answers the following question: _How can we identify a piece of music without access to its metadata?_ A popular song identification application, called Shazam, serves as the basis of our discussion, and we build beyond that to explore ideas in cover/alternative version detection - a much more difficult and ill-defined problem. The thesis also includes a discussion of the Non-negative Matrix Factorization, which is useful beyond its music information retrieval use-cases.

Below I've included a few interesting visualizations present in the thesis, mainly to pique your curiostiy.

---

On the left, we compute the spectrogram of a song with added noise. On the right, we visualize a constellation map which serves as an important low-density identifier.
<img width="1390" height="590" alt="download" src="https://github.com/user-attachments/assets/0ccc3fa5-4760-4242-8ef4-890c2177a036" />

---

A similar pair of visualizations, this time in the context of cover identification. Frequency has been replaced with pitch class.
<img width="1382" height="485" alt="image" src="https://github.com/user-attachments/assets/dd69d0f9-01f9-41bc-9afd-89f5d0d829cd" />

---

A single song's spectrogram can be factored into "note" and "activation matrices". The first image is the original song, the second image determines which notes are found within that song, and the last determines when each of those notes gets played.
<img width="765" height="590" alt="download" src="https://github.com/user-attachments/assets/ff0b121a-4fa3-47e8-9e07-d481c15205ee" />

<img width="754" height="590" alt="download" src="https://github.com/user-attachments/assets/9b1c341b-3f04-4fb4-9304-3bdbac02860a" />

<img width="904" height="390" alt="download" src="https://github.com/user-attachments/assets/15785be4-bc1a-4a18-bb2b-4a2f8cd2fbd9" />
